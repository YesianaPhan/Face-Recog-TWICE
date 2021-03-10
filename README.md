# Face-Recog-TWICE
in this code, we want to recognize every twice member, first I want to explain the dataset : 
there are 2 folder which are train and test
![image](https://user-images.githubusercontent.com/76993601/110577330-0477c380-8195-11eb-8b55-0149f7a625ed.png)


the train folder contains the name of the members
![image](https://user-images.githubusercontent.com/76993601/110576699-c4fca780-8193-11eb-88b9-6d0a6b137af0.png)


as each folders have the face of the members (I only show one of the folders, because if I show them all it will be too many images)
![image](https://user-images.githubusercontent.com/76993601/110576799-f5dcdc80-8193-11eb-9ca0-b979e276845c.png)

as for the test folder, contains 6 images of the members 
![image](https://user-images.githubusercontent.com/76993601/110576840-0ab97000-8194-11eb-9372-127026db3251.png)


there are 8 functions that were used in this code :
1. get the directory path list
2. get the labels of the images 
3. detect the trains faces and filter it, using haarcascade_frontalface_default.xml
4. get the test images and convert it into a list
5. detect the test faces and filter, once again using haarcascade_frontalface_default.xml
6. predict the images
7. now draw the prediction result using cv2, also print the calculated accuracy and the rectangle around their detected faces
8. combine and show the result altogether
![image](https://user-images.githubusercontent.com/76993601/110576506-77803a80-8193-11eb-910a-8131d0ac00d8.png)
