- [R interface to Keras](https://keras.rstudio.com/)  
- GPU 메모리가 적은 경우(GTX 1050, 2GB) 오류해결  
~~~
library(keras)
library(tensorflow)

gpu_options <- tf$GPUOptions(per_process_gpu_memory_fraction = 0.2)
config <- tf$ConfigProto(gpu_options = gpu_options)
k_set_session(tf$Session(config = config))
~~~
참고 : [깃허브(2018.3.29), 'limit ressource usage by tensorflow backend in rstudio', https://github.com/rstudio/keras/issues/338, 검색일:2019.7.17](https://github.com/rstudio/keras/issues/338)  
~~~
config = tf.ConfigProto()
config.gpu_options.allow_growth = True
session = tf.Session(config=config, ...)
~~~
~~~
import tensorflow as tf
from keras.backend.tensorflow_backend import set_session

config = tf.ConfigProto(
    gpu_options = tf.GPUOptions(per_process_gpu_memory_fraction=0.8)
    # device_count = {'GPU': 1}
)
config.gpu_options.allow_growth = True
session = tf.Session(config=config)
set_session(session)
~~~
참고 : [1] [스택오버플로우(2016.12.13), 'Tensorflow crashes with CUBLAS_STATUS_ALLOC_FAILED', https://stackoverflow.com/questions/41117740/tensorflow-crashes-with-cublas-status-alloc-failed, 검색일:2019.7.17](https://stackoverflow.com/questions/41117740/tensorflow-crashes-with-cublas-status-alloc-failed)  
[2] [깃허브(2016.3.10), 'GPU sync failed', https://github.com/tensorflow/tensorflow/issues/1450, 검색일:2019.7.17](https://github.com/tensorflow/tensorflow/issues/1450)  
