# OSVOS_Changes
Changes from original OSVOS files for project.

We utlized scaelles' [TensorFlow based model for our project](https://github.com/scaelles/OSVOS-TensorFlow).


1. From scaelles, follow steps one through three under installation.

2. Continuing, follow steps one and two under Demo Online Training and Testing.

3. Follow steps one through five on Training the Parent Network. This will be required to ensure that you can create your own unique parent directory.

4. Place your desired pictures to train your new model with under 480p or 1080p (depending on resolution) in the folders JPEGImages and Annotations. The .jpg versions of the files should go in JPEGImages, and the .png files should go under Annotations.

5. Edit the train_parent file so that it only contains the directories of the pictures that you want to use to train the model. They should all be in the following format per line:

  JPEGImages/480p/imageFolder/imageName1.jpg Annotations/480p/imageFolder/imageName1.png
