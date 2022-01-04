# 运行说明

## 1.解压程序文件


把程序代码压缩包解压到E盘任一新建文件夹内

说明: 解压到D盘也可以;文件夹命名用英文命名,例如:D:\Final



## 2.打开终端


## 3.切换到程序所在盘内


在cmd里切换路径到D:\Final\recognition_Sys\recognition_Sys\dropzone-env\Scripts

例如:cd D:\Final\recognition_Sys\recognition_Sys\dropzone-env\Scripts

## 4. 激活环境
**.\activate**


例如: D:\Final\recognition_Sys\recognition_Sys\dropzone-env \Scripts> **.\activate**
## 5.  切换目录到recognition_Sys目录
## 6. 开始运行: **flask run**
例如:D:\Final\recognition_Sys\recognition_Sys>flask run
## 7. 在浏览器输入网址:http://127.0.0.1:5000/



运行过程如下图所示:
![](README_md_files%5Cimage.png?v=1&type=image)


## 说明

如果没有成功运行,

在根目录里面有导出的 requirements.txt文件,这里是所有环境的版本

先激活虚拟环境,然后

输入命令 **pip install -r requirements.txt**
根据文件的环境版本安装所对应的环境

再重新按照以上方法进行操作.
