## Pyenv 国内镜像源

### 1. [pyenv-win](https://github.com/pyenv-win/pyenv-win)
  设置环境变量
  ```
  PYTHON_BUILD_MIRROR_URL=https://jedore.netlify.app/tools/python-mirrors/
  或
  PYTHON_BUILD_MIRROR_URL=https://jedore.vercel.app/tools/python-mirrors/
  ```
  生效后，
  刷新版本信息 `pyenv update`
  安装
  ```
  C:\Users\Jedore>pyenv install 3.10.3
  :: [Info] ::  Mirror: https://jedore.netlify.app/tools/python-mirrors/
  :: [Downloading] ::  3.10.3 ...
  :: [Downloading] ::  From https://registry.npmmirror.com/-/binary/python/3.10.3/python-3.10.3-amd64.exe
  :: [Downloading] ::  To   D:\pyenv\pyenv-win\install_cache\python-3.10.3-amd64.exe
  :: [Installing] ::  3.10.3 ...
  ```
  
### 2. [pyenv](https://github.com/pyenv/pyenv-virtualenv)
  设置环境变量
  ```
   export PYTHON_BUILD_MIRROR_URL="https://registry.npmmirror.com/-/binary/python"
  ```
  生效后，安装
  ```
  $ pyenv install 3.11.0
  Downloading Python-3.11.0.tar.xz...
  -> https://registry.npmmirror.com/-/binary/python/3.11.0/Python-3.11.0.tar.xz
  Installing Python-3.11.0...
  ```
