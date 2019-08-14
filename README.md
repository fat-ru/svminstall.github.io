# svminstall.github.io
安装SVM工具箱

1 下载对应版本的svm工具箱，我下载的是libsvm323
2 将下载的工具箱压缩包解压到matlab安装目录的toolbox文件夹
3 设置路径
4 用mex -setup指令检验是否安装编译器，如果已安装编译器，则用make.m进行编译，如没有安装编译，先安装编译器，我安装的是tdm64-gcc-5.1.0-2.exe。
5 安装编译器之后新建环境变量，变量名为MW_MINGW64_LOC，变量值为C:\TDM-GCC-64（指的是安装路径），然后重启matlab.
6 现在再用指令mex -setup，则不会报错
