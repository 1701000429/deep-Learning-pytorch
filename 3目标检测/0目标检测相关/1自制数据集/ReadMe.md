# 制作自己的目标检测数据集

## 1.labelImg工具(pascal VOC和yolo格式)

labelImg的安装

```
pip install labelImg -i https://pypi.tuna.tsinghua.edu.cn/simple
```

labelImg的使用

```
1.新建文件夹annotation和image，并新建一个classify.txt类别文件
2.文件夹下shift+右键打开powerShell
3.执行命令   labelImg ./JPEGImages ./class_names.txt
4.change save dir --> Create RectBox  -->  Save
```



## 2.labelMe工具(pascal VOC 和COCO)

labelme的安装

```
pip install labelme -i https://pypi.tuna.tsinghua.edu.cn/simple
```

labelme的使用

```
1.新建文件夹data_annotated并新建一个labels.txt类别文件
2.文件夹下shift+右键打开powerShell
3.执行命令
labelme data_annotated --labels labels.txt --nodata --autosave
```

