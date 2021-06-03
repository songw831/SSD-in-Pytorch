## 基于Pytorch实现的SSD目标检测模型在胃肠镜图像识别领域的应用


## 所需环境

torch == 1.2.0



## 训练步骤
1. 本文使用VOC格式进行训练。  
2. 训练前将标签文件放在VOCdevkit文件夹下的VOC2007文件夹下的Annotation中。  
3. 训练前将图片文件放在VOCdevkit文件夹下的VOC2007文件夹下的JPEGImages中。  
4. 在训练前利用voc2ssd.py文件生成对应的txt。  
5. 再运行根目录下的voc_annotation.py，此时会生成对应的2007_train.txt，每一行对应其**图片位置**及其**真实框的位置**。  

6. 运行train.py即可开始训练。

   

## 数据来源

本文所用图像均来源于真实肠镜图像。