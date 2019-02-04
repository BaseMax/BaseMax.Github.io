---
layout: post
title: Part2 Questions about making the picture more natural.
---


Although this is a simple question and easy...
But it can be interesting for many people.

I saw this question at Stanford University.
And thanks to the professor.


# Question 1

The image below, golden-gate-red.jpg, shows the golden gate bridge, but all of the data is in the red values. 
golden gate bridge, shown in red

Write code that for each pixel copies the red value over to be the green and blue value. The result will be to change the image to grayscale which will look better.


![Make the picture more natural](https://basemax.github.io/assets/image/city3.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/city4.jpg)



# Question 2


![Make the picture more natural](https://basemax.github.io/assets/image/image3.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/image4.jpg)




# Question 3


### Converting Color To Grayscale

- How to covert a regular color image to grayscale?
- Problem: for each pixel, how dark/light is it (ignoring hue)
- Choose a few pixels out of flowers.jpg, each in a row below
- Q: which pixel is brightest? darkest?
- We compute average for each pixel
- Reminder: to average 3 numbers, add them up and divide by 3
- average = (red + green + blue)/3

- Average combines red/green/blue into one number
- The average measures how bright the pixel is 0..255
- Ignoring hue


write code to change the flowers.jpg image to grayscale, using the "average" strategy: for each pixel, compute the average of its red/green/blue values. This average number represents the brightness of the pixel 0..255. Then set the red, green, and blue values of the pixel to be that average number. The result is a grayscale version of the original color image. Once its working with flowers.jpg, try it with poppy.jpg or oranges.jpg. (Solution code available below)

![Make the picture more natural](https://basemax.github.io/assets/image/flower5.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/flower6.jpg)


# Question 4

Write code to change the banana.jpg image to be grayscale. Reminder: here is the line used in the loop to compute the average of the red/green/blue values and store that value in a variable named "avg".

```
avg = (pixel.getRed() + pixel.getGreen() + pixel.getBlue())/3;
```


![Make the picture more natural](https://basemax.github.io/assets/image/banana.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/banana2.jpg)



# Question 5

we have the baby.jpg image.

make it appear that the green parts of her little chair are sprouting leaves.

![Make the picture more natural](https://basemax.github.io/assets/image/baby.jpg)

### Final Answer


![Final Answer](https://basemax.github.io/assets/image/baby2.jpg)


# Question 6

Here is our monkey movie star:


![Make the picture more natural](https://basemax.github.io/assets/image/animal.jpg)


Here is our background, the famous Apollo 8 photo of the earth shown rising above the moon horizon.

![Make the picture more natural](https://basemax.github.io/assets/image/animal2.jpg)



Real technique
1. Two images: image, back
2. Loop over image, detect color area
3. Color area: copy over x,y pixel from back to image

### Final Answer

![Final Answer](https://basemax.github.io/assets/image/animal3.jpg)


# Question 6


![Make the picture more natural](https://basemax.github.io/assets/image/university4.jpg)

Suppose you are visiting Stanford and you park your car here, and get a parking ticket. Philosophically, they say that you are better off taking in events as they have actually happened. Nonetheless, here we'll try to fix history in code. 

Challenge: write code to detect the red curb, (a) change it to medium gray red=120 green=120 blue=120. (b) change just the red curb to be grayscale, which will look more realistic. Rather than changing the whole image to grayscale, we change just the red areas. Recall that the algorithm to change grayscale is to set red/green/blue values all to be the average value.


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/university5.jpg)



# Question 7


![Make the picture more natural](https://basemax.github.io/assets/image/university4.jpg)

Suppose you are visiting Stanford and you park your car here, and get a parking ticket. Philosophically, they say that you are better off taking in events as they have actually happened. Nonetheless, here we'll try to fix history in code. 

Challenge: write code to detect the red curb, (a) change it to medium gray red=120 green=120 blue=120. (b) change just the red curb to be grayscale, which will look more realistic. Rather than changing the whole image to grayscale, we change just the red areas. Recall that the algorithm to change grayscale is to set red/green/blue values all to be the average value.


Tune the * 1.5 to detect the red areas
Setting to solid gray (120, 120, 120) looks a little crude
Note that we put gray on the red plants to the right
Our strategy chooses exclusively on pixel color, so necessarily get the red plants too
(b) Rather than (120, 120, 120), change the red pixels to grayscale
This looks much better, as it reflects the dark/light of the real curb
Just draining out the red


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/university6.jpg)



# Question 8


![Make the picture more natural](https://basemax.github.io/assets/image/flower7.jpg)

Write code that picks out the pixels of the green leaves in the image (using the > avg * factor technique, as in lecture). For each green pixel identified, set its green value to 0. The result is that the green leaves are changed to a sort of weird purple color, since setting green to 0, we just have red and blue contributing.




### Final Answer

![Final Answer](https://basemax.github.io/assets/image/flower8.jpg)



-------------


If you tried and thought ...

Click [here](https://basemax.github.io/2019/01/31/Part2-Answer-Make-the-picture-more-natural.html) to check the final answer.
