# Python-tutorial

## 1. Online preview (recommended)

Use this button to launch the tutorial in [Binder](https://mybinder.org/): [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hpc-nuist-ap/Python-tutorial.git/main?filepath=Python_Tutorial_2020.ipynb)

## 2. Local preview

1. Download the latest anaconda package from [TUNA](https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/?C=M&O=A)

2. Install anaconda by running the `.sh` or `.exe` file

3. Add Anaconda to the system environment following this [tutorial](https://www.pythonlikeyoumeanit.com/Module1_GettingStartedWithPython/Installing_Python.html) or any online tutorial

4. Check whether the Anaconda environment is set successfully

   ```
   which conda
   ```

5. Download this repository to your local directory

6. Create the new environment in the terminal or cmd window

   ```
   conda env create -f environment.yml
   ```

7. Activate the environment

   ```
   conda activate python_tutorial
   ```

8. Test the jupyter notebook

   ```
   jupyter-notebook.exe
   # or jupyter-notebook
   ```