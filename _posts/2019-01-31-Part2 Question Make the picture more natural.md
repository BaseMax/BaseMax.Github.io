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




Click [here](https://basemax.github.io/2019/02/02/Part3-Question-Make-the-picture-more-natural.html) to view further queries.

-------------


If you tried and thought ...

Click [here](https://basemax.github.io/2019/01/31/Part2-Answer-Make-the-picture-more-natural.html) to check the final answer.
