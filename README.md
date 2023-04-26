# 图片工具
本工程基于Qt开发，其软件用于日常对图片的处理，避免麻烦的代码处理过程。

## 开发环境

windows 10 (64 bit)

QT Creator 4.12

Opencv-4.6.0（使用cmake-3.26.0编译）

QT 工程文件(.pro) 加入 opencv 路径。就达到使用 opencv 的目的

## 工程介绍

imageshow 是源代码文件

output 是编译结果，其中的 Image_show.exe 已经做了跨设备适配，下载到本地直接运行。

功能随时更新，需要什么加什么。

## v2.0 

充分运用 C++ 类，结构体，对象等知识。

极大的改善了代码结构，工程结构。

现在非常易于开发。

界面如图：

<left><img src="./output/panel_show.png" 
       width = 60% ><left>

## v1.0现有开发功能
1. 二值以及灰度处理（包括各种阈值设置，阈值参数等）
2. 图片resize大小（包括利用最邻近插值法，双线性插值，4方，8方插值值，像素关系重采样）




