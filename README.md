# Quiz8
## Section 1：Image style transfer
&emsp;Image style transfer is a technique that transfer the style of a image to another style meanwhile hold the content of the original image.

&emsp;I got inspired by this video.
[youtube:style-transfer](https://www.youtube.com/watch?v=Cqh8804Mq7g)

![image](https://github.com/IAPEY/czhu0121_9103_tut2/assets/129077906/12c9c307-599d-4dc7-bdfe-b2f19a31995e)
![image](https://github.com/IAPEY/czhu0121_9103_tut2/assets/129077906/3f181757-e06b-40d8-a043-48a9b24ec51c)

&emsp;I believed that this must be beneficial cause we can transfer our work to the style of a masterpiece such as "starry night" and so on.In our work, we can generate some patterns by p5.js and transfer the style of our code to one of the master piece,to create some amazing effects. The users as well are able to control the process of style transfer to interact with our work.

## Section 2：fast-style-transfer
Link of code reference:
[fast-stytle-transfer](https://github.com/lengstrom/fast-style-transfer)
![image](https://github.com/IAPEY/czhu0121_9103_tut2/assets/129077906/150fc666-2b0c-46a8-9264-656eba9ae5fa)
![image](https://github.com/IAPEY/czhu0121_9103_tut2/assets/129077906/ddf20d34-75f1-4250-a94e-bfe67badd4a0)

#### Language :
&emsp;Python
#### Framwork :
&emsp;Tensorflow
#### Details :
&emsp;Based on the work of Gatys (Gatys,2016),[Gatys_Image_Style_Transfer_CVPR_2016](https://openaccess.thecvf.com/content_cvpr_2016/html/Gatys_Image_Style_Transfer_CVPR_2016_paper.html) Using CNN:VGG-19 to pre-train some of the style-transfer network and save the .ckpt files, by using these pretrained parameters and style-transfer network, we can transfer many images as well as videos in a short time.And finally we can get an image or a video with the original content and the style of a masterpiece.







