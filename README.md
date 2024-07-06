# brain-tumor-classify

[Dataset used](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data)

- `model1.ipynb` is the code for the custom model implemention
- `vgg19.ipynb` is the code for feature extraction of VGG19 model for the task, **ImageNet** weights were used
- `resnet50_scratch_ipynb` is the code for resnet50 implementation from scratch in tensorflow
- `resnet_101_freeze.ipynb` is the code for feature extraction of resnet101 model. **ImageNet** weights were used
- `resnet_101_allTrain.ipynb` is the code for finetuning of resnet101 model. **ImageNet** weights were used

---

- `model1_shap.ipynb` is implementation of shaply explanable deep learning on custom implemention
- `layer_by_model1.ipynb` is implementation of layer-by-propagation for custom model
   - layer-by-propagation is a technique by which we extract the output of intermediate layers to explain the output of the model
