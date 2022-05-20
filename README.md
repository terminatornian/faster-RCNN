# faster-RCNN

The paper addresses the problem of traffic sign detection analysing the state-of-the-art of several object-detection systems (Faster R-CNN,SSD) combined with various feature extractors (Resnet V1 50, Resnet V1 101, Inception Resnet V2, Mobilenet V1). We aim to explore the properties of these object-detection models which are modified and specifically adapted to the traffic sign detection problem domain by means of transfer learning. In particular, various publicly available object-detection models that were pre-trained on the Microsoft COCO dataset are fine-tuned on the German Traffic Sign Detection Benchmark dataset. The evaluation and comparison of these models include key metrics, such as the mean average precision (mAP), memory allocation, running time.

Pretrained model

You can use pre-trained models from Google Drive.
faster_rcnn_inception_resnet_v2_atrous
faster_rcnn_resnet_101
faster_rcnn_resnet_50
ssd_inception_v2
ssd_mobilenet_v1

Training
After you pretrain these models, you can train the new picture. For example, you can use the new test image to detect.

![image](https://user-images.githubusercontent.com/90360834/169600503-1a887681-378a-433f-ae16-c1d495a02fdd.png)



