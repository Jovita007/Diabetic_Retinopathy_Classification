# Diabetic_Retinopathy_Classification

Diabetic Retinopathy (DR) is an ophthalmic disease in which the retinal blood vessels are damaged. If not detected early on, DR causes vision impairment and may even result in blindness.
The presence of microaneurysms, exudates, neovascularization, and haemorrhages determines the severity of diabetic retinopathy disease. Diabetic retinopathy was divided into
five stages: normal, mild, moderate, severe, nonproliferative (NPDR), and proliferative diabetic
retinopathy (PDR). 

This Project aims to classify the diabetic prediction stages using APTOS Datasets of fundus images. To encode the rich characteristics and improve classification for different stages of DR
using an ensemble of four deep Convolution Neural Network (CNN) models (Resnet50, Xception, Dense121, Vgg16). 

Image processing with Gaussian Blur and contrast limited adaptive histogram equalization techniques are used in this study's solution method (CLAHE). 
Transfer learning on pretrained Vgg16, ResNet50 and DenseNet121 models from ImageNet approach performs with kappa score for Diabetic Retinopathy classifications problems.
The best result of the experiment was achieved by DenseNet121 with 87.24 % kappa score. 


Keywords: Diabetic Retinopathy, Fundus Images, Convolution Neural Network(CNN), Contrast Limited Adaptive Histogram Equalization(CLAHE), Vgg16, Densenet121, ResNet50.
