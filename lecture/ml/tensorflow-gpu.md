[1] 솔라리스의 인공지능 연구실(2017.5.30), '1-2. 텐서플로우(TensorFlow) GPU버전(Tensorflow-Gpu) 설치하기', [http://solarisailab.com/archives/1581](http://solarisailab.com/archives/1581),검색일: 2019.7.17  

~~~
(kdata_ml) C:\Users\KDATA31>conda install tensorflow-gpu
WARNING: The conda.compat module is deprecated and will be removed in a future release.
Collecting package metadata: done
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 4.6.11
  latest version: 4.7.5

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: C:\Users\KDATA31\Anaconda3\envs\kdata_ml

  added / updated specs:
    - tensorflow-gpu


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    _tflow_select-2.1.0        |              gpu           3 KB
    absl-py-0.7.1              |           py36_0         158 KB
    astor-0.7.1                |           py36_0          44 KB
    cudatoolkit-10.0.130       |                0       371.0 MB
    cudnn-7.6.0                |       cuda10.0_0       215.3 MB
    gast-0.2.2                 |           py36_0         138 KB
    grpcio-1.14.1              |   py36h5c4b210_0         927 KB
    h5py-2.9.0                 |   py36h5e291fa_0         969 KB
    keras-applications-1.0.8   |             py_0          33 KB
    keras-preprocessing-1.1.0  |             py_1          36 KB
    libprotobuf-3.8.0          |       h7bd577a_0         2.2 MB
    markdown-3.1.1             |           py36_0         132 KB
    mkl_fft-1.0.12             |   py36h14836fe_0         136 KB
    mkl_random-1.0.2           |   py36h343c172_0         318 KB
    mock-3.0.5                 |           py36_0          47 KB
    numpy-1.16.4               |   py36h19fb1c0_0          49 KB
    numpy-base-1.16.4          |   py36hc3f5095_0         4.1 MB
    protobuf-3.8.0             |   py36h33f27b4_0         582 KB
    pyreadline-2.1             |           py36_1         141 KB
    scipy-1.2.1                |   py36h29ff71c_0        14.0 MB
    tensorboard-1.13.1         |   py36h33f27b4_0         3.3 MB
    tensorflow-1.13.1          |gpu_py36h9006a92_0           4 KB
    tensorflow-base-1.13.1     |gpu_py36h871c8ca_0       217.6 MB
    tensorflow-estimator-1.13.0|             py_0         205 KB
    tensorflow-gpu-1.13.1      |       h0d30ee6_0           2 KB
    termcolor-1.1.0            |           py36_1           8 KB
    werkzeug-0.15.4            |             py_0         262 KB
    ------------------------------------------------------------
                                           Total:       831.7 MB

The following NEW packages will be INSTALLED:

  _tflow_select      pkgs/main/win-64::_tflow_select-2.1.0-gpu
  absl-py            pkgs/main/win-64::absl-py-0.7.1-py36_0
  astor              pkgs/main/win-64::astor-0.7.1-py36_0
  blas               pkgs/main/win-64::blas-1.0-mkl
  cudatoolkit        pkgs/main/win-64::cudatoolkit-10.0.130-0
  cudnn              pkgs/main/win-64::cudnn-7.6.0-cuda10.0_0
  gast               pkgs/main/win-64::gast-0.2.2-py36_0
  grpcio             pkgs/main/win-64::grpcio-1.14.1-py36h5c4b210_0
  h5py               pkgs/main/win-64::h5py-2.9.0-py36h5e291fa_0
  hdf5               pkgs/main/win-64::hdf5-1.10.4-h7ebc959_0
  icc_rt             pkgs/main/win-64::icc_rt-2019.0.0-h0cc432a_1
  intel-openmp       pkgs/main/win-64::intel-openmp-2019.4-245
  keras-applications pkgs/main/noarch::keras-applications-1.0.8-py_0
  keras-preprocessi~ pkgs/main/noarch::keras-preprocessing-1.1.0-py_1
  libprotobuf        pkgs/main/win-64::libprotobuf-3.8.0-h7bd577a_0
  markdown           pkgs/main/win-64::markdown-3.1.1-py36_0
  mkl                pkgs/main/win-64::mkl-2019.4-245
  mkl_fft            pkgs/main/win-64::mkl_fft-1.0.12-py36h14836fe_0
  mkl_random         pkgs/main/win-64::mkl_random-1.0.2-py36h343c172_0
  mock               pkgs/main/win-64::mock-3.0.5-py36_0
  numpy              pkgs/main/win-64::numpy-1.16.4-py36h19fb1c0_0
  numpy-base         pkgs/main/win-64::numpy-base-1.16.4-py36hc3f5095_0
  protobuf           pkgs/main/win-64::protobuf-3.8.0-py36h33f27b4_0
  pyreadline         pkgs/main/win-64::pyreadline-2.1-py36_1
  scipy              pkgs/main/win-64::scipy-1.2.1-py36h29ff71c_0
  tensorboard        pkgs/main/win-64::tensorboard-1.13.1-py36h33f27b4_0
  tensorflow         pkgs/main/win-64::tensorflow-1.13.1-gpu_py36h9006a92_0
  tensorflow-base    pkgs/main/win-64::tensorflow-base-1.13.1-gpu_py36h871c8ca_0
  tensorflow-estima~ pkgs/main/noarch::tensorflow-estimator-1.13.0-py_0
  tensorflow-gpu     pkgs/main/win-64::tensorflow-gpu-1.13.1-h0d30ee6_0
  termcolor          pkgs/main/win-64::termcolor-1.1.0-py36_1
  werkzeug           pkgs/main/noarch::werkzeug-0.15.4-py_0


Proceed ([y]/n)? y


Downloading and Extracting Packages
mock-3.0.5           | 47 KB     | ############################################################################ | 100%
numpy-1.16.4         | 49 KB     | ############################################################################ | 100%
gast-0.2.2           | 138 KB    | ############################################################################ | 100%
h5py-2.9.0           | 969 KB    | ############################################################################ | 100%
scipy-1.2.1          | 14.0 MB   | ############################################################################ | 100%
astor-0.7.1          | 44 KB     | ############################################################################ | 100%
mkl_fft-1.0.12       | 136 KB    | ############################################################################ | 100%
tensorflow-gpu-1.13. | 2 KB      | ############################################################################ | 100%
keras-applications-1 | 33 KB     | ############################################################################ | 100%
libprotobuf-3.8.0    | 2.2 MB    | ############################################################################ | 100%
werkzeug-0.15.4      | 262 KB    | ############################################################################ | 100%
grpcio-1.14.1        | 927 KB    | ############################################################################ | 100%
cudnn-7.6.0          | 215.3 MB  | ############################################################################ | 100%
numpy-base-1.16.4    | 4.1 MB    | ############################################################################ | 100%
_tflow_select-2.1.0  | 3 KB      | ############################################################################ | 100%
pyreadline-2.1       | 141 KB    | ############################################################################ | 100%
protobuf-3.8.0       | 582 KB    | ############################################################################ | 100%
tensorboard-1.13.1   | 3.3 MB    | ############################################################################ | 100%
mkl_random-1.0.2     | 318 KB    | ############################################################################ | 100%
cudatoolkit-10.0.130 | 371.0 MB  | ############################################################################ | 100%
tensorflow-estimator | 205 KB    | ############################################################################ | 100%
tensorflow-base-1.13 | 217.6 MB  | ###########################################################################9 | 100%

~~~
~~~
(base) C:\Windows\system32>conda -V
conda 4.7.5

(base) C:\Windows\system32>conda info

     active environment : base
    active env location : C:\Users\KDATA31\Anaconda3
            shell level : 1
       user config file : C:\Users\KDATA31\.condarc
 populated config files : C:\Users\KDATA31\.condarc
          conda version : 4.7.5
    conda-build version : 3.17.8
         python version : 3.7.3.final.0
       virtual packages : __cuda=10.1
       base environment : C:\Users\KDATA31\Anaconda3  (writable)
           channel URLs : https://repo.anaconda.com/pkgs/main/win-64
                          https://repo.anaconda.com/pkgs/main/noarch
                          https://repo.anaconda.com/pkgs/r/win-64
                          https://repo.anaconda.com/pkgs/r/noarch
                          https://repo.anaconda.com/pkgs/msys2/win-64
                          https://repo.anaconda.com/pkgs/msys2/noarch
          package cache : C:\Users\KDATA31\Anaconda3\pkgs
                          C:\Users\KDATA31\.conda\pkgs
                          C:\Users\KDATA31\AppData\Local\conda\conda\pkgs
       envs directories : C:\Users\KDATA31\Anaconda3\envs
                          C:\Users\KDATA31\.conda\envs
                          C:\Users\KDATA31\AppData\Local\conda\conda\envs
               platform : win-64
             user-agent : conda/4.7.5 requests/2.21.0 CPython/3.7.3 Windows/10 Windows/10.0.17134
          administrator : True
             netrc file : None
           offline mode : False


(base) C:\Windows\system32>conda activate kdata_ml

C:\Windows\system32>set "JAVA_HOME_CONDA_BACKUP="

C:\Windows\system32>set "JAVA_HOME=C:\Users\KDATA31\Anaconda3\envs\kdata_ml\Library"

(kdata_ml) C:\Windows\system32>conda install tensorflow-gpu
WARNING conda.base.context:use_only_tar_bz2(632): Conda is constrained to only using the old .tar.bz2 file format because you have conda-build installed, and it is <3.18.3.  Update or remove conda-build to get smaller downloads and faster extractions.
Collecting package metadata (repodata.json): done
Solving environment: /
Solving environment: done

# All requested packages already installed.


C:\Windows\system32>set "JAVA_HOME="

C:\Windows\system32>set "JAVA_HOME_CONDA_BACKUP="

C:\Windows\system32>set "JAVA_HOME=C:\Users\KDATA31\Anaconda3\envs\kdata_ml\Library"

(kdata_ml) C:\Windows\system32>
~~~
