# Major Project
Structural health monitoring has undergone a massive transformation in the last few
years, which is only accelerating with the advent of new technologies and methods of
testing. Traditional methods such as manual inspection and destructive testing often require
extensive time and energy and are not so efficient. New and powerful methods such as
non-destructive testing reduce the time and effort required and are preferred over the older
methods. Recently, image processing and machine learning methods have been gaining
popularity owing to their excellent speed in getting the results of any analysis. The
accuracy obtained from these methods is often comparable, if not better, than that of
traditional methods.
In this project, we aim to explore the possibility of using image processing and machine
learning (ML) algorithms to determine cracks in concrete. In particular, we used Convolutional neural
networks such as VGG16, ResNet50, Xception, and MobileNet, to name a few.
We have used the datasets to detect the presence of cracks in concrete which  were taken from the Kaggle website. 
This dataset consists of 40000 images, 20000 with and 20000 without cracks. The second
dataset had pictures of cracked and uncracked decks on a bridge from a dataset called
SDNET2018 (2018). VGG16 Architecture based artificial neural network performed the best while MobileNet performed the worst.
As the scope for the project expanded, we also tried to determine crack properties, specifically crack width as we felt that an automated system for the same would be much
more useful than a manual one. It was done using morphological transformations and concepts of Euclidean distance.
Keywords : Structural Health Monitoring, VGG16, ResNet50, Xception, MobileNet,
ML, Crack width
