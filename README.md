### 项目简介
此项目是用python的深度学习算法包去训练计算机模仿世界名画的风格.具体原理参考[大牛论文](https://arxiv.org/abs/1508.06576)

### 安装
#### 本项目基于python3,Ubuntu16.04
#### 1.命令行安装keras、h5py、tensorflow
1. pip3 install keras
2. pip3 install h5py
3. pip3 install tensorflow
#### 2.下载VGG16模型,[百度网盘](https://pan.baidu.com/s/1boIcxun)
把下载好的模型文件放入到/home/(用户)/.keras/modes目录下
#### 3.运行
```
python3 pic_transfer.py   你的待转化图片路径    模板图片路径   保存的生产图片路径加名称（注意不需要有.jpg等后缀）
python3 pic_transfer.py './stu.jpeg' './star.jpeg' './stu_t'

```
#### 4.要跑挺长时间的，吃顿饭回来估计差不过跑好了.
##### 结果
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_0.png)
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_1.png)
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_2.png)
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_3.png)
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_4.png)
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_5.png)
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_6.png)
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_7.png)
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_8.png)
![](https://github.com/starbt/deep_leaning_pic/raw/master/pics/stu_t_at_iteration_9.png)
