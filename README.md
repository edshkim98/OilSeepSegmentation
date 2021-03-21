# OilSeepsSegmentation
![Oil seep sample](oil_seep.png)

I used a pre-trained deeplabv3-resnet101 model and then fine tuned it.<br/>
Loss functions = Weighted cross entropy + soft dice loss + mean iou loss<br/>
0.73 IOU for segmentation of 2 classes 
