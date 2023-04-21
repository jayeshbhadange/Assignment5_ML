Tensorboard Visualization
-----------------------
Scalars:
--------
1.VGG

![vgg1](https://user-images.githubusercontent.com/90170940/233562415-b164ed02-4d1d-4069-80a6-9cf0090168aa.png)



2. VGG3

![vgg3](https://user-images.githubusercontent.com/90170940/233555634-a1868541-4780-4319-9517-9f994a472813.png)


3. VGG3(data augmentation)

![VGG3D](https://user-images.githubusercontent.com/90170940/233555735-d0e7aebf-2da4-4a7e-a651-7d702e7c3b25.png)


4. VGG16

![VGG16](https://user-images.githubusercontent.com/90170940/233557967-80c99e9f-ead1-42f5-8cf2-5e39dc82ae0a.png)

Are the results as expected? Why or why not?
-----------------------
Yes, the results are as expected. Both the test and train accuracies increases in the order VGG (1 block) < VGG (3 blocks) < VGG (3 blocks) with data augmentation < Transfer learning using VGG16 or VGG19

Does data augmentation help? Why or why not?
-------------------------------------
Yes, the data augmentation is helpful because the accuracy of the model increases by using it. Since we are using a dataset with a limited data, the data augmentation plays a crucial in improving the accuracy by introducing some variability into the data.

Does it matter how many epochs you fine tune the model? Why or why not?
---------------------------------
Yes, the number of epochs that we use to tune a model have a significant impact on the performance. Suppose, if we use a higher number of epochs, then it may lead to overfit to the training data. In contrast, if we use lower number of epochs, then model may not learn the data well and lead to underfitting of the data.
