# artificial-intelligence-task1

Training image recognition model 

## Steps in Teachable Machine

1.   I opened Teachable Machine website then chose image project,I defined 2 classes (sun,moon).
2.   In sun class I uploaded several images of sun from my computer, I did the same thing with the moon class.
3.   I clicked on train model.
4.   after training I upladed  image of moon from my computer to test model and the result showed that it was indeed a moon 100%.
5.   I uploaded an image of sun to make sure that the model was able to differentiate between sun and moon and give 
correct result.
6.   I clicked export model then chose tensorflow then download keras format and copy python code 


### images for results 

![image alt](https://github.com/Sa12345678434/artificial-intelligence-task1/blob/main/moon.png?raw=true)
![image alt](https://github.com/Sa12345678434/artificial-intelligence-task1/blob/main/sun.png?raw=true)



## Steps in Google Colab

1- In google colab, I uploaded keras model files that I downloaded from Teachable Machine site and uploaded an image of moon
to predict its class

 ![image alt](https://github.com/Sa12345678434/artificial-intelligence-task1/blob/main/files2.png?raw=true)

 2- I wrote the copied Python code from Teachable Machine for this model
 
 3- I wrote this command to prevent error
 
 ![image alt](https://github.com/Sa12345678434/artificial-intelligence-task1/blob/main/pip.png?raw=true)


 4-In the line below, I put the path of the image in designated place,which I had previously uploaded to Google Colab
 
      image = Image.open("moon t.jpg").convert("RGB")

5- I run code then Python predict the class of the image is moon 


### output

![image alt](https://github.com/Sa12345678434/artificial-intelligence-task1/blob/main/output%20moon.png?raw=true)


