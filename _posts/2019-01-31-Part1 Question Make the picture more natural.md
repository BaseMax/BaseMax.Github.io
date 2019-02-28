---
layout: post
title: Part1 Questions about making the picture more natural.
---

Although this is a simple question and easy...
But it can be interesting for many people.

I saw this question at Stanford University.
And thanks to the professor.


# Question 1

Write code to fix the poppy.png image which should show an orange California Poppy in the foreground (the California state flower!).

The background is mostly green with some in the upper-right.

![Make the picture more natural](https://basemax.github.io/assets/image/flower.jpg)


### Primary Pseudo Code Sample

```
image = new SimpleImage("poppy.png");
for (pixel: image)
{
   //Complate Here...
}
print(image);
```

### Description about functions

```
pixel.setBlue( <number> );
pixel.setGreen( <number> );
pixel.setRed( <number> );
```

```
pixel.getRed()
pixel.getGreen()
pixel.getBlue()
```


### How Solve

At the first, you need to know **Poppy California**.
And how it looks.

![Poppy California](https://basemax.github.io/assets/image/flower2.jpg)

![Poppy California](https://basemax.github.io/assets/image/flower3.jpg)

### Final Answer

![Final Answer](https://basemax.github.io/assets/image/flower4.jpg)


# Question 2

Write code to fix the oranges image which should show a box of oranges. The box itself is dull gray. The sign on the box is black, with "organic" written in light orange, and the rest of the letters in white.


![Orange](https://basemax.github.io/assets/image/orange.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/orange2.jpg)



# Question 3

- The green and blue values are all just random values in the range 0..255 ("snow")
- The data of the real image is exclusively in the red values
- In addition, the red values have all been divided by 10 (dark)
- The green/blue snow is obscuring the real image

Write code to recover the real image.

![City](https://basemax.github.io/assets/image/city.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/city2.jpg)


# Question 4

Write code to fix the stop-sky image which should show a red stop sign front with a background of a light blue sky and green tree leaves.

![Stop](https://basemax.github.io/assets/image/stop.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/stop2.jpg)


# Question 5

Write code to fix the puzzle-copper image. The red values in the image are random noise, so they should be set to 0.

The real image is in the blue and green values, which have been divide by 10.


![Stop](https://basemax.github.io/assets/image/paris.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/paris2.jpg)



# Question 6

Write code to fix the puzzle-iron image. The red and green values in the image are random noise, so they should be set to 0.

The real image is in the blue values, which have been divide by 10. The "solution" image will look blue, since it is exclusively in the blue values, so don't worry about that. We'll see a way to fix that blueness in a later section.



![Stop](https://basemax.github.io/assets/image/image.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/image2.jpg)


Click [here](https://basemax.github.io/2019/01/31/Part2-Question-Make-the-picture-more-natural.html) to view further queries.



-------------


If you tried and thought ...

Click [here](https://basemax.github.io/2019/01/31/Part1-Answer-Make-the-picture-more-natural.html) to check the final answer.

