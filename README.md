# ObjectDetection_Cat
Object detection using Tensorflow Object Detection API.

## References

This project is based in the [tutorial](https://gilberttanner.com/blog/object-detection-with-tensorflow-2/) provided by Gilbert Tanner.

The notebook was run using google colab in a custom Dataset created by myself.

## Dataset

The dataset is comprised of 107 images and 107 annotations. Part of the images was aquired via google images and the remaining are personal images of my pet cat or pictures I had saved from other cats. All the annotations were provided by me, using label-studio. In this repository, it will be archive.zip, which contains the image files, the annotations and two .csv files containing the labels in a format readable by tensorflow API.

## Model

The model used was EfficientDet D0 512x512, that was used in the tutorial. The model was already pretrained on the [COCO](https://cocodataset.org/#home) dataset and it is then downloaded and trained again on my own dataset. The link to the [model paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tan_EfficientDet_Scalable_and_Efficient_Object_Detection_CVPR_2020_paper.pdf).

[Code for the model](https://github.com/google/automl/tree/master/efficientdet).

The file will also be provided here.