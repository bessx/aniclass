# Performance Comparison of Convolutional neural networks for animal classification on disproportionate datasets 

**by [Adam Bess](https://github.com/bessx/), Blessing Ajibero, Cheng Yan, Jacques Comeaux, Jesse Dai, Josh Duke, Mahfuza Khatun, Sweta Ghimire**

&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;In this study, we use ImageNet and other image datasets to train an animal identification network. The method can be divided into two parts: encoding and identification. First, the basic characteristics of the different animal images are extracted and the corresponding embeddings are encoded into vectors by using a convolutional neural network. The important information from the images can be encoded into vectors. Furthermore, the similarity between the new image and the image in the database can be calculated by comparing the new vectors and the stored vectors. Finally, the animal can be identified by finding the vector with the highest similarity in the graph pool. 

&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;We retrain the final few layers of the ImageNet model with different datasets of varying proportions of animal and non-animal imagery. For example, comparing three datasets containing: 1) only animal images, 2) a proportional amount of animal and non-animal images, and 3) an oversampled non-animal classification group. With these datasets of varying proportions of classifications, we compare the training time, loss, and accuracy of the networks tested on similar animal datasets such as OpenImages, CIFAR, Visual Genome, and COCO.


---

[(•̀ᴗ•́)و ̑̑](https://glitch.com/@bess)
