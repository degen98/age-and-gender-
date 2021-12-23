Age and Gender Detection using OpenCV

Face verification has turn into an area of dynamic research and the applications are important in law enforcement because it can be done without involving the subject. Still, the influence of age estimation on face verification become a challenge to decide the similarity of
pair images from individual faces considering very limited of data base availability.
We focus on the development of image processing and face detection on face
verification system by improving the quality of image quality. The main objective of
the system is to compare the image with the reference images stored as templates in
the database and to determine the age and gender. A fast and efficient gender and age
estimation system based on facial images is developed. There are already many
methods proposed for gender and age detection. However, all of them still have
disadvantages such as complete reflection about face structure, texture. This
technique applies to both face alignment and recognition and significantly improves
these aspects.


![image](https://user-images.githubusercontent.com/61080527/147287433-a0d8b338-dd12-47cb-965f-7778b170c8d6.png)



Face Detection - For Face Detection we used Techniques like Image
segmentation and image filling to detect the faces. Initially the image is
segmented by subtracting the image with the RGB values of the skin tone
color. Then the image is turned to pure black where ever the color pixels are
found after the subtraction of the skin tone. Then we get the image of faces
alone. The noises in the image are filled with the white pixels by calculating
the surrounding spaces intensity. If the surrounding pixels are of white, then
the center pixels are changed to white again. This should
be done on a single loop alone. At the last remaining low space dimensional
areas of white pixels are removed used the image filling method. After the face
regions are separated, the faces are surrounded with a bounded box with the
face as a center and the image is cropped.
• Comparison of age stages - In this step we use comparison algorithm to
compare the test image with the reference image set available in the
dataset(Adience), and the matching score is given as output. For the
comparison, we need multiple images with their respective ages specified and
separated in the dataset already. Then the input image is compared with all the
images and the most common features available is selected and the age is
determined.
• Gender classification - After obtaining features, the features of the training
dataset will be compared with the features of input image to classify whether
the given input image is female or male gender.

![image](https://user-images.githubusercontent.com/61080527/147287505-76630343-b249-42d5-bfd9-c5f754cbc375.png)

**Conclusion **
In this work, techniques of PCA algorithm and KNN
classifier is used. Age synthesis is a developing concept, which needs more
developers and researchers on it. The basic concept is to predict the image model of
certain person on basis of age which does not even exist


```System.out.println("Hello") ```



