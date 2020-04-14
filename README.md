# face_recognization
## Face-Recognition：人脸识别算法在Keras当中的实现
---

### 目录
1. [所需环境 Environment](#所需环境)
2. [使用方法 Usage](#使用方法)
3. [文件描述 Description](#文件描述)

### 使用方法
1、先将整个仓库download下来。 
2、pip install -r requirements.txt #安装依赖
3、将自己想要识别的人脸放入到face_dataset中。  
4、运行face_recognize.py即可。  
5、align.py可以查看人脸对齐的效果。  
  

### 文件描述
1、face_recognize.py 识别单一人脸
2、faces_recognize.py  识别人脸库里的人脸
3、main.py 多线程识别人脸里的人脸，利用PnP算法实现人脸位姿解算
4、main_Pcontrol.py 多线程识别人脸里的人脸，利用像素差算法实现人脸位姿解算
5、thread_test.py 多线程结构
6、uart_cloud_platform.py 串口发送数据
