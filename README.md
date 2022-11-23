This repository contains the common lists used in Class-Incremental Learning (CIL) works. It is there to provide a fair comparison between the different methods. The lists are available for the following datasets:
- [CIFAR-100](https://github.com/GregoirePetit/imagelistsCIL/blob/master/cifar100/): 100 classes
- [ImageNetSubset](https://github.com/GregoirePetit/imagelistsCIL/blob/master/imagenetsubset/): 100 classes
- [TinyImageNet](https://github.com/GregoirePetit/imagelistsCIL/blob/master/tinyimagenet/): 200 classes
- [ILSVRC](https://github.com/GregoirePetit/imagelistsCIL/blob/master/ilsvrc/): 1000 classes
- [GoogleLandmarks](https://github.com/GregoirePetit/imagelistsCIL/blob/master/google_landmarks/): 1000 classes
- [iNaturalist](https://github.com/GregoirePetit/imagelistsCIL/blob/master/inat/): 1000 classes


Each folder contains a README.md file that explains how to download the dataset. The lists are provided in the following format: a text file with the path to the images and their labels. The first line of the file indicates the path to the images. The following lines are of the form: `path/to/image label`. The labels are integers starting from 0.

[datasets_mean_std.txt](https://github.com/GregoirePetit/imagelistsCIL/blob/master/datasets_mean_std.txt) contains the mean and standard deviation of the datasets. The mean and standard deviation are computed on the training set.

A loader is provided in the repository [utilsCIL](https://github.com/GregoirePetit/utilsCIL) in [MyImageFolder.py](https://github.com/GregoirePetit/utilsCIL/blob/main/MyImageFolder.py#L34) to load the lists.