# 系统：windows10
# conda版本：20.02
## 问题1：cmd下conda报错
错误信息：
Traceback (most recent call last):
  File "c:\Anaconda\Scripts\conda-script.py", line 16, in <module>
    from conda.cli import main
ModuleNotFoundError: No module named 'conda'

解决：
系统环境变量以及临时定义的环境变量中取消对PYTHONHOME的定义
参考：https://github.com/conda/conda/issues/9230
  
