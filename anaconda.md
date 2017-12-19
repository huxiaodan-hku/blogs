```
conda create -n tensorflow python=3.6
```
```
conda env remove -n tensorflow
```
```
source activate tensorflow
```
```
juypter notebook
```
```
jupyter notebook --ip=10.112.16.86 --port=8080 --allow-root
```

启动tensorboard
打开tensorflow环境
找到存储的event目录。执行
tensorboard --logdir "./graphs"
web：local
![image.png](http://upload-images.jianshu.io/upload_images/4037309-79dad217402c6c70.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
