# Classification-of-Malaria-Cell-Images
In this project my aim is using 3 different pretrained model to classify NIH dataset. They are  
* **Xception 
* **Resnet152V2
* **InceptionResNetV2


The reason of to chosing this pretrained models that they are top of the 3 models depend on keras applications page https://keras.io/api/applications/ (except the nasnet large because it's need large images). 

![pretrained_models](https://user-images.githubusercontent.com/35764362/122302618-02976c00-cf0b-11eb-86ec-487635aca508.png)

I used to transfer learning and fine tunining techinuques to retrain with NIH dataset. The top layer of that models are not includeded. Reason of that, they are trained 1000 objects, but I have only 2 object and they are parasitized and uninfected images. Finaly I evaluate the training results and I find which is the best model for this dataset.


![Screenshot from 2021-06-17 01-27-03](https://user-images.githubusercontent.com/35764362/122302776-3ffbf980-cf0b-11eb-8ef1-217e8c62596d.png)

![Screenshot from 2021-06-17 01-27-14](https://user-images.githubusercontent.com/35764362/122302780-41c5bd00-cf0b-11eb-9228-bca3f6f2aef1.png)

## Final Results

![Screenshot from 2021-06-17 01-27-35](https://user-images.githubusercontent.com/35764362/122302785-44281700-cf0b-11eb-98d9-49bbcba5fafb.png)
