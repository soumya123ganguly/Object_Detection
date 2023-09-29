# PA5
Object detection models' comparison.

This project provides a comprehensive analysis of deep learning techniques for object detection, with a particular emphasis on comparing the efficiency of CNN-based models and attention-based Transformer models. The study investigates various model architectures, like Resnet, VGG, and Visual Transformer, all of which utilize the Faster RCNN framework. The experimental evaluations are conducted on the widely used Pascal VOC dataset where some of the models were pre-trained on the COCO dataset. With untrained backbones, the best results obtained were from a `Faster R-CNN with ViT backbone and corners aligned', with 2.1 mAP, and with pre-trained backbones (on COCO dataset) the best results obtained were from 'Faster R-CNN with pre-trained ResNet backbone', with 24 mAP.


# Files 
1. vgg_rcnn.ipynb : Contains model with VGG backbone.
2. vite.ipynb : Contains model with ViT end to end.
3. vit_rcnn.ipynb : Contains model with ViT backbone.


