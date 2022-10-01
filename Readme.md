# Idea
Simple Abnormal Detection code using yolo v5(For Hackathon)

### Used 
1. yolo v5 : Object Detection Model.
2. colab pro : Dev environment based on cloud service
3. roboflow : Before training by using roboflow, we can label images and preprocessing them(ex. data argumentation or resize image..)
4. weight and bias(wnb) : by using wnb, visualize training process and result, also can find optimal hyperparameter

### Process
1. Create image data
2. Create class or multi-class(Roboflow)
3. Train custum dataset(yolo v5)
4. Adapt customized model(example.pt) to your own detection project 


### Referenct
1. Yolo V5
https://github.com/ultralytics/yolov5

2.Weight and bias tutorial
https://docs.wandb.ai/?_gl=1*1ltitp9*_ga*OTA1NTMyMDgzLjE2NjQ2MzQ2NzA.*_ga_JH1SJHJQXJ*MTY2NDYzNDY3MC4xLjAuMTY2NDYzNDY3MC42MC4wLjA.

3. Roboflow tutorial
https://docs.roboflow.com/


### Acc
![image](https://user-images.githubusercontent.com/50313997/193414514-fe9cff34-8e14-425e-bef3-eea1f2bdb8fc.png)

