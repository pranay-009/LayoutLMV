# LayoutLMV3_Fine_Tuning


<a name="1nstallation"></a>

## 1. Installation

<a name="11-install-paddlepaddle"></a>

### 1.1 Install PaddlePaddle

> If you do not have a Python environment, please refer to [Environment Preparation](./environment_en.md).

- If you have CUDA 9 or CUDA 10 installed on your machine, please run the following command to install

  ```bash
  python -m pip install paddlepaddle-gpu -i https://pypi.tuna.tsinghua.edu.cn/simple
  ```

- If you have no available GPU on your machine, please run the following command to install the CPU version

  ```bash
  python -m pip install paddlepaddle -i https://pypi.tuna.tsinghua.edu.cn/simple
  ```

For more software version requirements, please refer to the instructions in [Installation Document](https://www.paddlepaddle.org.cn/install/quick) for operation.

<a name="12-install-paddleocr-whl-package"></a>

```bash
pip install "paddleocr>=2.0.1" # Recommend to use version 2.0.1+
```

- **For windows users:** If you getting this error `OSError: [WinError 126] The specified module could not be found` when you install shapely on windows. Please try to download Shapely whl file [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#shapely).

  Reference: [Solve shapely installation on windows](https://stackoverflow.com/questions/44398265/install-shapely-oserror-winerror-126-the-specified-module-could-not-be-found)
