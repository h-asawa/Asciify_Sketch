# Asciify_Sketch

## Description
ASCII(American Standard Code for Information Interchange) is a common encoding format used for representing strings and text data in computers. ASCII Art is a graphic design technique which consists of pictures pierced together from the 95 printable ascii characters. In this project, we will use python and its libraries to convert images to beautiful ascii sketches.

## Theory and Additional Task
The project involves two main steps -> <br />
1. Converting image to pencil sketch : <br />
   It involves the following steps : <br />
      &emsp;a) Convert the image to grayscale and invert it. <br />
      &emsp;b) Blur the resultant image using gaussian blur. This step is done because for creating sketch, we need only &emsp;&emsp; prominent features from the image. Appropriate               kernal size can be selected by trial and error. <br />
      &emsp;c) Invert the blurred image. <br />
      &emsp;d) The final sketch can be obtained by performing bitwise division between grayscale image and inverted &emsp;&emsp; blurred image. <br />
      <br />
2. Converting sketch to ascii sketch : <br />
   It involves the following steps : <br />
      &emsp;a) Resizing the image to a smaller width so that we dont end up with too large text. <br />
      &emsp;b) Creating an ascii character list arranged from darkest to lightest. <br />
      &emsp;c) Converting to ascii sketch by getting pixel value for each pixel in image and mapping the respective ascii &emsp;&emsp; character together. 
      <br />
## Results 

Running the code for a sample image gave the following result: <br /> <br />
![sample](https://user-images.githubusercontent.com/83265838/174033985-373f39e4-ab95-44c6-9b20-259553c70ce8.jpg)
![final](https://user-images.githubusercontent.com/83265838/174034039-56157d25-05b2-4e7a-9492-c60124807550.png)

## Key Learnings 

1. Fundamentals of Image Processing. <br />
2. Usage of OpenCV and PIL Python libraries. <br />
3. Sampling, scaling and transforming images to map pixels to their desired characters. <br />

## Additional Task Performed 

Turned ascii art into pencil sketch. 

## Video Demo

https://user-images.githubusercontent.com/83265838/174428384-8ae87afb-1dc5-4d21-97b8-81b3fc3661bd.mp4

<br />

## Resources 

* [Wiki Article on ASCII Art](https://en.wikipedia.org/wiki/ASCII_art#Types_and_styles) 
* [Image to ASCII Art](https://www.youtube.com/watch?v=v_raWlX7tZY&t=224s)
* [How Image are stored in computer](https://alekya3.medium.com/how-images-are-stored-in-a-computer-f364d11b4e93)
* [Converting Image to Sketch](https://www.geeksforgeeks.org/convert-image-into-sketch/)
