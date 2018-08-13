# OSVOS_Changes
Changes from original OSVOS files for project, will hopefully have our parent and child models soon.

## Introduction
This project was dedicated to taking scaelles' [OSVOS TensorFlow based model](https://github.com/scaelles/OSVOS-TensorFlow) and reconfiguring it to work with images of people that we added in ourselves.

1. From scaelles, follow steps one through three under [Installation](https://github.com/scaelles/OSVOS-TensorFlow#installation).

2. Continuing, follow steps one and two under [Demo Online Training and Testing](https://github.com/scaelles/OSVOS-TensorFlow#demo-online-training-and-testing).

3. Follow steps one through five on [Training the Parent Network](https://github.com/scaelles/OSVOS-TensorFlow#training-the-parent-network-optional). This will be required to ensure that you can create your own unique parent model.

4. Place your desired pictures to train your new model with under 480p or 1080p (depending on resolution) in the folders JPEGImages and Annotations. The .jpg versions of the files should go in JPEGImages, and the .png files should go under Annotations.

5. Edit the train_parent file so that it only contains the directories of the pictures that you want to use to train the model. They should all be in the following format per line:

  JPEGImages/480p/imageFolder/imageName1.jpg Annotations/480p/imageFolder/imageName1.png

6. Run ```python osvos_parent_demo.py```.



## Credits

Special thanks goes out to scaelles, whose [OSVOS_Tensorflow respository](https://github.com/scaelles/OSVOS-TensorFlow) helped us get off the ground for this oneshot learning project.
