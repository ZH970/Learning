1.conda虚拟环境下就用conda install，venv虚拟环境下就用pip install。
2.创建venv虚拟环境时不要用annaconda的python解释器，虚拟环境会在打包等这类动态链接、导入dll等场景产生bug，创建conda虚拟环境同理
3.安装python最好用exe，或 源码构建，可以选路径