- train.py 提取图片特征，训练svc，保存参数到svc.pickle.p 中

- test_train.py 测试保存的参数

- image_test.py 测试图像（封装参数，实现图片处理管道）

- video_test.py 视频处理管道

- standard-imp 别人更好的实现
   
  - train.py 训练
  - test.py 查看HSV的h通道的颜色直方图，ysv的hog特征
  - image_detect.py 检测图片
  - video_detect.py 检测视频