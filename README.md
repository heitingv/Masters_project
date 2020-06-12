# Masters_project
MEng Project: Mammogram Image Segmentation
4th year Bioengineering MEng Project: Image Segmentation of Breast Tumours in Mammograms through Neural Networks and Deep Learning

As part of my 4th year final project I looked at developing an efficient framework to train and test image segmentation networks on mammograms to detect breast cancer and overcoming the issues of having a smaller database. 
Three neural networks are used: U-Net, Nested U-Net and FC DenseNet. 
I explored two different ways of extracting patches from full mammogram images (1-connected patches and whole mass patches) to create a source database that is larger than the target database for the initial training. 
Transfer learning is then used either for weight initialization or fine-tuning on the target database.
