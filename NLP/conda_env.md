~~~
$ conda info --envs
WARNING: The conda.compat module is deprecated and will be removed in a future release.
# conda environments:
#
base                  *  /Users/b3nn9/anaconda3
~~~
~~~
$ conda create -n PM python=3.6
WARNING: The conda.compat module is deprecated and will be removed in a future release.
Collecting package metadata: done
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 4.6.11
  latest version: 4.7.11

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: /Users/b3nn9/anaconda3/envs/PM

  added / updated specs:
    - python=3.6


The following NEW packages will be INSTALLED:

  ca-certificates    pkgs/main/osx-64::ca-certificates-2019.5.15-1
  certifi            pkgs/main/osx-64::certifi-2019.6.16-py36_1
  libcxx             pkgs/main/osx-64::libcxx-4.0.1-hcfea43d_1
  libcxxabi          pkgs/main/osx-64::libcxxabi-4.0.1-hcfea43d_1
  libedit            pkgs/main/osx-64::libedit-3.1.20181209-hb402a30_0
  libffi             pkgs/main/osx-64::libffi-3.2.1-h475c297_4
  ncurses            pkgs/main/osx-64::ncurses-6.1-h0a44026_1
  openssl            pkgs/main/osx-64::openssl-1.1.1c-h1de35cc_1
  pip                pkgs/main/osx-64::pip-19.1.1-py36_0
  python             pkgs/main/osx-64::python-3.6.9-h359304d_0
  readline           pkgs/main/osx-64::readline-7.0-h1de35cc_5
  setuptools         pkgs/main/osx-64::setuptools-41.0.1-py36_0
  sqlite             pkgs/main/osx-64::sqlite-3.29.0-ha441bb4_0
  tk                 pkgs/main/osx-64::tk-8.6.8-ha441bb4_0
  wheel              pkgs/main/osx-64::wheel-0.33.4-py36_0
  xz                 pkgs/main/osx-64::xz-5.2.4-h1de35cc_4
  zlib               pkgs/main/osx-64::zlib-1.2.11-h1de35cc_3


Proceed ([y]/n)? y

Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate PM
#
# To deactivate an active environment, use
#
#     $ conda deactivate

~~~
