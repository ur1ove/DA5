~~~
library(keras)
library(tensorflow)

gpu_options <- tf$GPUOptions(per_process_gpu_memory_fraction = 0.2)
config <- tf$ConfigProto(gpu_options = gpu_options)
k_set_session(tf$Session(config = config))
~~~
참고 : [깃허브(2018.3.29), 'limit ressource usage by tensorflow backend in rstudio', https://github.com/rstudio/keras/issues/338, 검색일:2019.7.17](https://github.com/rstudio/keras/issues/338)  
