This repository contains the common lists used in Class-Incremental Learning (CIL) works. It is there to provide a fair comparison between the different methods. The lists are available for the following datasets:
- [CIFAR-100](https://github.com/GregoirePetit/imagelistsCIL/blob/main/cifar100/)
- [ImageNetSubset](https://github.com/GregoirePetit/imagelistsCIL/blob/main/imagenetsubset/)
- [TinyImageNet](https://github.com/GregoirePetit/imagelistsCIL/blob/main/tinyimagenet/)
- [ILSVRC](https://github.com/GregoirePetit/imagelistsCIL/blob/main/ilsvrc/)
- [GoogleLandmarks](https://github.com/GregoirePetit/imagelistsCIL/blob/main/google_landmarks/)
- [iNaturalist](https://github.com/GregoirePetit/imagelistsCIL/blob/main/inat/)


Each folder contains a README.md file that explains how to download the dataset. The lists are provided in the following format: a text file with the path to the images and their labels. The first line of the file indicates the path to the images. The following lines are of the form: `path/to/image label`. The labels are integers starting from 0.

A loader is provided in the repository [utilsCIL](https://github.com/GregoirePetit/utilsCIL) in [MyImageFolder.py](https://github.com/GregoirePetit/utilsCIL/blob/main/MyImageFolder.py#L34) to load the lists.