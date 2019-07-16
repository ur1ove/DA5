### 참고사항
아나콘다를 이용하는 경우,   
아나콘다 내비게이터를 이용해 환경을 추가하고  
알스튜디오를 설치하자.  
  
~~~
> install_keras(tensorflow = "gpu")
WARNING: The conda.compat module is deprecated and will be removed in a future release.

Remove all packages in environment C:\Users\KDATA31\ANACON~1\envs\r-tensorflow:


## Package Plan ##

  environment location: C:\Users\KDATA31\ANACON~1\envs\r-tensorflow


The following packages will be REMOVED:

  _tflow_select-2.3.0-mkl
  absl-py-0.7.1-py37_0
  asn1crypto-0.24.0-py37_1003
  astor-0.7.1-py_0
  blas-1.0-mkl
  ca-certificates-2019.6.16-hecc5488_0
  certifi-2019.6.16-py37_0
  cffi-1.12.3-py37hb32ad35_0
  chardet-3.0.4-py37_1003
  cryptography-2.7-py37hb32ad35_0
  freetype-2.10.0-h5db478b_0
  gast-0.2.2-py_0
  grpcio-1.16.1-py37h351948d_1
  h5py-2.9.0-nompi_py37h3cb27cb_1102
  hdf5-1.10.4-nompi_hcc15c50_1106
  icc_rt-2019.0.0-h0cc432a_1
  idna-2.8-py37_1000
  intel-openmp-2019.4-245
  jpeg-9c-hfa6e2cd_1001
  keras-2.2.4-py37_1
  keras-applications-1.0.7-py_1
  keras-preprocessing-1.0.9-py_1
  libblas-3.8.0-8_mkl
  libcblas-3.8.0-8_mkl
  libgpuarray-0.7.6-hfa6e2cd_1003
  liblapack-3.8.0-8_mkl
  libmklml-2019.0.3-0
  libpng-1.6.37-h7602738_0
  libprotobuf-3.9.0-h1a1b453_0
  libtiff-4.0.10-h6512ee2_1003
  lz4-c-1.8.3-he025d50_1001
  mako-1.0.10-py_0
  markdown-3.1.1-py_0
  markupsafe-1.1.1-py37hfa6e2cd_0
  mkl-2019.4-245
  numpy-1.16.4-py37hc71023c_0
  olefile-0.46-py_0
  openssl-1.1.1c-hfa6e2cd_0
  pillow-6.1.0-py37h9a613e6_0
  pip-19.1.1-py37_0
  protobuf-3.9.0-py37he025d50_0
  pycparser-2.19-py37_1
  pygpu-0.7.6-py37h452e1ab_1000
  pyopenssl-19.0.0-py37_0
  pyreadline-2.1-py37_1000
  pysocks-1.7.0-py37_0
  python-3.7.3-h8c8aaf0_1
  pyyaml-5.1.1-py37hfa6e2cd_0
  requests-2.22.0-py37_1
  scipy-1.2.1-py37h29ff71c_0
  setuptools-41.0.1-py37_0
  six-1.12.0-py37_1000
  sqlite-3.28.0-he774522_0
  tensorboard-1.13.1-py37_0
  tensorflow-1.13.1-mkl_py37h9463c59_0
  tensorflow-base-1.13.1-mkl_py37hcaf7020_0
  tensorflow-estimator-1.13.0-py37h39e3cac_0
  tensorflow-hub-0.5.0-py_0
  tensorflow-probability-0.7-py_1
  termcolor-1.1.0-py_2
  theano-1.0.4-py37h6538335_1000
  tk-8.6.9-hfa6e2cd_1002
  urllib3-1.25.3-py37_0
  vc-14.1-h0510ff6_4
  vs2015_runtime-14.15.26706-h3a45250_4
  vs2015_win-64-14.0.25420-h55c1224_11
  werkzeug-0.15.4-py_0
  wheel-0.33.4-py37_0
  win_inet_pton-1.1.0-py37_0
  wincertstore-0.2-py37_0
  xz-5.2.4-h2fa13f4_1001
  yaml-0.1.7-hfa6e2cd_1001
  zlib-1.2.11-h2fa13f4_1005
  zstd-1.4.0-hd8a0e53_0


Preparing transaction: ...working... done
Verifying transaction: ...working... done
Executing transaction: ...working... done
Creating r-tensorflow conda environment for TensorFlow installation...
WARNING: The conda.compat module is deprecated and will be removed in a future release.
Collecting package metadata: ...working... done
Solving environment: ...working... done


==> WARNING: A newer version of conda exists. <==
  current version: 4.6.11
  latest version: 4.7.5

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: C:\Users\KDATA31\ANACON~1\envs\r-tensorflow

  added / updated specs:
    - python=3.7


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    certifi-2019.6.16          |           py37_0         155 KB
    ------------------------------------------------------------
                                           Total:         155 KB

The following NEW packages will be INSTALLED:

  ca-certificates    pkgs/main/win-64::ca-certificates-2019.5.15-0
  certifi            pkgs/main/win-64::certifi-2019.6.16-py37_0
  openssl            pkgs/main/win-64::openssl-1.1.1c-he774522_1
  pip                pkgs/main/win-64::pip-19.1.1-py37_0
  python             pkgs/main/win-64::python-3.7.3-h8c8aaf0_1
  setuptools         pkgs/main/win-64::setuptools-41.0.1-py37_0
  sqlite             pkgs/main/win-64::sqlite-3.28.0-he774522_0
  vc                 pkgs/main/win-64::vc-14.1-h0510ff6_4
  vs2015_runtime     pkgs/main/win-64::vs2015_runtime-14.15.26706-h3a45250_4
  wheel              pkgs/main/win-64::wheel-0.33.4-py37_0
  wincertstore       pkgs/main/win-64::wincertstore-0.2-py37_0



Downloading and Extracting Packages
certifi-2019.6.16    | 155 KB    | ########## | 100% 
Preparing transaction: ...working... done
Verifying transaction: ...working... done
Executing transaction: ...working... done
#
# To activate this environment, use
#
#     $ conda activate r-tensorflow
#
# To deactivate an active environment, use
#
#     $ conda deactivate

Installing TensorFlow...

C:\Users\KDATA31\Desktop\예제\2019_0716\7일차\0.Data\FASHION_MNIST>set "JAVA_HOME="  
Collecting tensorflow-gpu==1.13.1 from https://storage.googleapis.com/tensorflow/windows/gpu/tensorflow_gpu-1.13.1-cp37-cp37m-win_amd64.whl
  Downloading https://storage.googleapis.com/tensorflow/windows/gpu/tensorflow_gpu-1.13.1-cp37-cp37m-win_amd64.whl (259.7MB)
Collecting keras-preprocessing>=1.0.5 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/28/6a/8c1f62c37212d9fc441a7e26736df51ce6f0e38455816445471f10da4f0a/Keras_Preprocessing-1.1.0-py2.py3-none-any.whl (41kB)
Collecting termcolor>=1.1.0 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/8a/48/a76be51647d0eb9f10e2a4511bf3ffb8cc1e6b14e9e4fab46173aa79f981/termcolor-1.1.0.tar.gz
Collecting grpcio>=1.8.6 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/7a/f5/fe046577387a3589ab3092096ca423fcf9a8c7ac876f56c6f3b4c9b9e533/grpcio-1.22.0-cp37-cp37m-win_amd64.whl (1.6MB)
Collecting keras-applications>=1.0.6 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/71/e3/19762fdfc62877ae9102edf6342d71b28fbfd9dea3d2f96a882ce099b03f/Keras_Applications-1.0.8-py3-none-any.whl (50kB)
Collecting astor>=0.6.0 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/d1/4f/950dfae467b384fc96bc6469de25d832534f6b4441033c39f914efd13418/astor-0.8.0-py2.py3-none-any.whl
Collecting tensorflow-estimator<1.14.0rc0,>=1.13.0 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/bb/48/13f49fc3fa0fdf916aa1419013bb8f2ad09674c275b4046d5ee669a46873/tensorflow_estimator-1.13.0-py2.py3-none-any.whl (367kB)
Collecting gast>=0.2.0 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/4e/35/11749bf99b2d4e3cceb4d55ca22590b0d7c2c62b9de38ac4a4a7f4687421/gast-0.2.2.tar.gz
Collecting six>=1.10.0 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/73/fb/00a976f728d0d1fecfe898238ce23f502a721c0ac0ecfedb80e0d88c64e9/six-1.12.0-py2.py3-none-any.whl
Collecting absl-py>=0.1.6 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/da/3f/9b0355080b81b15ba6a9ffcf1f5ea39e307a2778b2f2dc8694724e8abd5b/absl-py-0.7.1.tar.gz (99kB)
Collecting protobuf>=3.6.1 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/5a/5b/2ffcea713a542179878d0f03e7c6e50d09ca470b36e730f94ed51e51b35d/protobuf-3.9.0-cp37-cp37m-win_amd64.whl (1.0MB)
Collecting numpy>=1.13.3 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/ce/61/be72eee50f042db3acf0b1fb86650ad36d6c0d9be9fc29f8505d3b9d6baa/numpy-1.16.4-cp37-cp37m-win_amd64.whl (11.9MB)
Collecting tensorboard<1.14.0,>=1.13.0 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/0f/39/bdd75b08a6fba41f098b6cb091b9e8c7a80e1b4d679a581a0ccd17b10373/tensorboard-1.13.1-py3-none-any.whl (3.2MB)
Collecting wheel>=0.26 (from tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/bb/10/44230dd6bf3563b8f227dbf344c908d412ad2ff48066476672f3a72e174e/wheel-0.33.4-py2.py3-none-any.whl
Collecting h5py (from keras-applications>=1.0.6->tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/4f/1e/89aa610afce8df6fd1f12647600a05e902238587ae6375442a3164b59d51/h5py-2.9.0-cp37-cp37m-win_amd64.whl (2.4MB)
Collecting mock>=2.0.0 (from tensorflow-estimator<1.14.0rc0,>=1.13.0->tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/05/d2/f94e68be6b17f46d2c353564da56e6fb89ef09faeeff3313a046cb810ca9/mock-3.0.5-py2.py3-none-any.whl
Collecting setuptools (from protobuf>=3.6.1->tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/ec/51/f45cea425fd5cb0b0380f5b0f048ebc1da5b417e48d304838c02d6288a1e/setuptools-41.0.1-py2.py3-none-any.whl (575kB)
Collecting werkzeug>=0.11.15 (from tensorboard<1.14.0,>=1.13.0->tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/9f/57/92a497e38161ce40606c27a86759c6b92dd34fcdb33f64171ec559257c02/Werkzeug-0.15.4-py2.py3-none-any.whl (327kB)
Collecting markdown>=2.6.8 (from tensorboard<1.14.0,>=1.13.0->tensorflow-gpu==1.13.1)
  Downloading https://files.pythonhosted.org/packages/c0/4e/fd492e91abdc2d2fcb70ef453064d980688762079397f779758e055f6575/Markdown-3.1.1-py2.py3-none-any.whl (87kB)
Building wheels for collected packages: termcolor, gast, absl-py
  Building wheel for termcolor (setup.py): started
  Building wheel for termcolor (setup.py): finished with status 'done'
  Stored in directory: C:\Users\KDATA31\AppData\Local\pip\Cache\wheels\7c\06\54\bc84598ba1daf8f970247f550b175aaaee85f68b4b0c5ab2c6
  Building wheel for gast (setup.py): started
  Building wheel for gast (setup.py): finished with status 'done'
  Stored in directory: C:\Users\KDATA31\AppData\Local\pip\Cache\wheels\5c\2e\7e\a1d4d4fcebe6c381f378ce7743a3ced3699feb89bcfbdadadd
  Building wheel for absl-py (setup.py): started
  Building wheel for absl-py (setup.py): finished with status 'done'
  Stored in directory: C:\Users\KDATA31\AppData\Local\pip\Cache\wheels\ee\98\38\46cbcc5a93cfea5492d19c38562691ddb23b940176c14f7b48
Successfully built termcolor gast absl-py
Installing collected packages: six, numpy, keras-preprocessing, termcolor, grpcio, h5py, keras-applications, astor, absl-py, mock, tensorflow-estimator, gast, setuptools, protobuf, werkzeug, wheel, markdown, tensorboard, tensorflow-gpu
Successfully installed absl-py-0.7.1 astor-0.8.0 gast-0.2.2 grpcio-1.22.0 h5py-2.9.0 keras-applications-1.0.8 keras-preprocessing-1.1.0 markdown-3.1.1 mock-3.0.5 numpy-1.16.4 protobuf-3.9.0 setuptools-41.0.1 six-1.12.0 tensorboard-1.13.1 tensorflow-estimator-1.13.0 tensorflow-gpu-1.13.1 termcolor-1.1.0 werkzeug-0.15.4 wheel-0.33.4
WARNING: The conda.compat module is deprecated and will be removed in a future release.
Collecting package metadata: ...working... done
Solving environment: ...working... done


==> WARNING: A newer version of conda exists. <==
  current version: 4.6.11
  latest version: 4.7.5

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: C:\Users\KDATA31\ANACON~1\envs\r-tensorflow

  added / updated specs:
    - h5py
    - pillow
    - pyyaml
    - requests
    - scipy


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    certifi-2019.6.16          |           py37_0         148 KB  conda-forge
    ------------------------------------------------------------
                                           Total:         148 KB

The following NEW packages will be INSTALLED:

  asn1crypto         conda-forge/win-64::asn1crypto-0.24.0-py37_1003
  blas               pkgs/main/win-64::blas-1.0-mkl
  cffi               conda-forge/win-64::cffi-1.12.3-py37hb32ad35_0
  chardet            conda-forge/win-64::chardet-3.0.4-py37_1003
  cryptography       conda-forge/win-64::cryptography-2.7-py37hb32ad35_0
  freetype           conda-forge/win-64::freetype-2.10.0-h5db478b_0
  h5py               conda-forge/win-64::h5py-2.9.0-nompi_py37h3cb27cb_1102
  hdf5               conda-forge/win-64::hdf5-1.10.4-nompi_hcc15c50_1106
  icc_rt             pkgs/main/win-64::icc_rt-2019.0.0-h0cc432a_1
  idna               conda-forge/win-64::idna-2.8-py37_1000
  intel-openmp       pkgs/main/win-64::intel-openmp-2019.4-245
  jpeg               conda-forge/win-64::jpeg-9c-hfa6e2cd_1001
  libblas            conda-forge/win-64::libblas-3.8.0-8_mkl
  libcblas           conda-forge/win-64::libcblas-3.8.0-8_mkl
  liblapack          conda-forge/win-64::liblapack-3.8.0-8_mkl
  libpng             conda-forge/win-64::libpng-1.6.37-h7602738_0
  libtiff            conda-forge/win-64::libtiff-4.0.10-h6512ee2_1003
  lz4-c              conda-forge/win-64::lz4-c-1.8.3-he025d50_1001
  mkl                pkgs/main/win-64::mkl-2019.4-245
  numpy              conda-forge/win-64::numpy-1.16.4-py37hc71023c_0
  olefile            conda-forge/noarch::olefile-0.46-py_0
  pillow             conda-forge/win-64::pillow-6.1.0-py37h9a613e6_0
  pycparser          conda-forge/win-64::pycparser-2.19-py37_1
  pyopenssl          conda-forge/win-64::pyopenssl-19.0.0-py37_0
  pyreadline         conda-forge/win-64::pyreadline-2.1-py37_1000
  pysocks            conda-forge/win-64::pysocks-1.7.0-py37_0
  pyyaml             conda-forge/win-64::pyyaml-5.1.1-py37hfa6e2cd_0
  requests           conda-forge/win-64::requests-2.22.0-py37_1
  scipy              pkgs/main/win-64::scipy-1.2.1-py37h29ff71c_0
  six                conda-forge/win-64::six-1.12.0-py37_1000
  tk                 conda-forge/win-64::tk-8.6.9-hfa6e2cd_1002
  urllib3            conda-forge/win-64::urllib3-1.25.3-py37_0
  win_inet_pton      conda-forge/win-64::win_inet_pton-1.1.0-py37_0
  xz                 conda-forge/win-64::xz-5.2.4-h2fa13f4_1001
  yaml               conda-forge/win-64::yaml-0.1.7-hfa6e2cd_1001
  zlib               conda-forge/win-64::zlib-1.2.11-h2fa13f4_1005
  zstd               conda-forge/win-64::zstd-1.4.0-hd8a0e53_0

The following packages will be UPDATED:

  ca-certificates    pkgs/main::ca-certificates-2019.5.15-0 --> conda-forge::ca-certificates-2019.6.16-hecc5488_0

The following packages will be SUPERSEDED by a higher-priority channel:

  certifi                                         pkgs/main --> conda-forge
  openssl              pkgs/main::openssl-1.1.1c-he774522_1 --> conda-forge::openssl-1.1.1c-hfa6e2cd_0



Downloading and Extracting Packages
certifi-2019.6.16    | 148 KB    | ########## | 100% 
Preparing transaction: ...working... done
Verifying transaction: ...working... done
Executing transaction: ...working... done

C:\Users\KDATA31\Desktop\예제\2019_0716\7일차\0.Data\FASHION_MNIST>set "JAVA_HOME="  
Collecting keras
  Downloading https://files.pythonhosted.org/packages/5e/10/aa32dad071ce52b5502266b5c659451cfd6ffcbf14e6c8c4f16c0ff5aaab/Keras-2.2.4-py2.py3-none-any.whl (312kB)
Collecting tensorflow-hub
  Downloading https://files.pythonhosted.org/packages/b5/be/f18c352d84382d9c795a0f37eaf16d42ace7d161fbb0ad20bdcd5e550015/tensorflow_hub-0.5.0-py2.py3-none-any.whl (78kB)
Collecting tensorflow-probability
  Downloading https://files.pythonhosted.org/packages/3e/3a/c10b6c22320531c774402ac7186d1b673374e2a9d12502cbc8d811e4601c/tensorflow_probability-0.7.0-py2.py3-none-any.whl (981kB)
Requirement already satisfied, skipping upgrade: keras-preprocessing>=1.0.5 in c:\users\kdata31\anacon~1\envs\r-tensorflow\lib\site-packages (from keras) (1.1.0)
Requirement already satisfied, skipping upgrade: numpy>=1.9.1 in c:\users\kdata31\anacon~1\envs\r-tensorflow\lib\site-packages (from keras) (1.16.4)
Requirement already satisfied, skipping upgrade: scipy>=0.14 in c:\users\kdata31\anacon~1\envs\r-tensorflow\lib\site-packages (from keras) (1.2.1)
Requirement already satisfied, skipping upgrade: pyyaml in c:\users\kdata31\anacon~1\envs\r-tensorflow\lib\site-packages (from keras) (5.1.1)
Requirement already satisfied, skipping upgrade: keras-applications>=1.0.6 in c:\users\kdata31\anacon~1\envs\r-tensorflow\lib\site-packages (from keras) (1.0.8)
Requirement already satisfied, skipping upgrade: six>=1.9.0 in c:\users\kdata31\anacon~1\envs\r-tensorflow\lib\site-packages (from keras) (1.12.0)
Requirement already satisfied, skipping upgrade: h5py in c:\users\kdata31\anacon~1\envs\r-tensorflow\lib\site-packages (from keras) (2.9.0)
Requirement already satisfied, skipping upgrade: protobuf>=3.4.0 in c:\users\kdata31\anacon~1\envs\r-tensorflow\lib\site-packages (from tensorflow-hub) (3.9.0)
Collecting cloudpickle>=0.6.1 (from tensorflow-probability)
  Downloading https://files.pythonhosted.org/packages/09/f4/4a080c349c1680a2086196fcf0286a65931708156f39568ed7051e42ff6a/cloudpickle-1.2.1-py2.py3-none-any.whl
Collecting decorator (from tensorflow-probability)
  Downloading https://files.pythonhosted.org/packages/5f/88/0075e461560a1e750a0dcbf77f1d9de775028c37a19a346a6c565a257399/decorator-4.4.0-py2.py3-none-any.whl
Requirement already satisfied, skipping upgrade: setuptools in c:\users\kdata31\anacon~1\envs\r-tensorflow\lib\site-packages (from protobuf>=3.4.0->tensorflow-hub) (41.0.1)
Installing collected packages: keras, tensorflow-hub, cloudpickle, decorator, tensorflow-probability
Successfully installed cloudpickle-1.2.1 decorator-4.4.0 keras-2.2.4 tensorflow-hub-0.5.0 tensorflow-probability-0.7.0

Installation complete.


Restarting R session...

> 
~~~
