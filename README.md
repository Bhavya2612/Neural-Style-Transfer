# Neural-Style-Transfer
As a part of Delta Mentorship Final Project, I have implemented a paper by Leon A Gatys, namely, A Neural Algorithm of Artistic Style.
This project aims on creating unique visual experiences through composing a complex interplay between the "content" and "style" of an image.

I've chosen this project as I'm intrigued by art and the implications that Deep learning on our daily lives and how more creatively we can use to our own needs.
I've used Keras framework, Eager Execution environment that evaluates operations immediately, without building graphs: operations return concrete values instead of constructing a computational graph to run later. It is also liked as it helps with the brevity of the code because it reduces boilerplate content. 
I've also used the feature space provided by 16 convolutional layers and 5 pooling layers from a pre-trained VGG-19 layered Neural Network. 

## About VGG Network : 
It is a Convolutional neural network that rivals human performance on a common visual object detection/ recognition benchmark task. 

## "Creativity of this Paper" 
The most interesting about this paper that distinguishes it from other papers aimed at "creating art" is that it doesn't deal with the exact pixel details, instead it makes use of difference between the "content" and "style" of an image which are reconstructed in the project.

a) CONTENT RECONSTRUCTION :-
       A given image is represented as a set of filtered images at each processing stage. While no of filters increase along th eprocessing hierarchy of the model, the size of the        image is reduced by max pooling(However, it is later found out in the project that average pooling gives slightly better results than max). 
       While reconstruction from lower layers is almost perfect, the higher layers lack the detailed pixel info, however, high level content is preserved. 
       
b) STYLE RECONSTRUCTION :-
       Style representation is a multi-scale representation that includes multiple layers of the neural network.. 


### OUTPUT IMAGES: 
https://github.com/Bhavya2612/Neural-Style-Transfer/blob/master/Outputs/1.png
