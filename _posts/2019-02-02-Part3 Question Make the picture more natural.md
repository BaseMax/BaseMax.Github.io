---
layout: post
title: Part3 Questions about making the picture more natural.
---

Although this is a simple question and easy...
But it can be interesting for many people.

I saw this question at Stanford University.
And thanks to the professor.


# Question 1

Goal: change the red sign to be blue



![Make the picture more natural](https://basemax.github.io/assets/image/stop5.jpg)



### Final Answer

![Final Answer](https://basemax.github.io/assets/image/stop6.jpg)




# Question 2


![Make the picture more natural](https://basemax.github.io/assets/image/stop7.jpg)


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/stop8.jpg)

# Question 3





Suppose you are visiting Stanford and you park your car here, and get a parking ticket. Philosophically, they say that you are better off taking in events as they have actually happened. Nonetheless, here we'll try to fix history in code. 

Challenge: write code to detect the red curb, (a) change it to medium gray red=120 green=120 blue=120. (b) change just the red curb to be grayscale, which will look more realistic. Rather than changing the whole image to grayscale, we change just the red areas. Recall that the algorithm to change grayscale is to set red/green/blue values all to be the average value.


![Make the picture more natural](https://basemax.github.io/assets/image/university4.jpg)

### Final Answer

![Make the picture more natural](https://basemax.github.io/assets/image/university5.jpg)


# Question 4

we have the baby.jpg image.

make it appear that the green parts of her little chair are sprouting leaves.

![Make the picture more natural](https://basemax.github.io/assets/image/baby.jpg)

### Final Answer


![Final Answer](https://basemax.github.io/assets/image/baby2.jpg)




# Question 5


![Make the picture more natural](https://basemax.github.io/assets/image/university4.jpg)


Tune the * 1.5 to detect the red areas
Setting to solid gray (120, 120, 120) looks a little crude
Note that we put gray on the red plants to the right
Our strategy chooses exclusively on pixel color, so necessarily get the red plants too
(b) Rather than (120, 120, 120), change the red pixels to grayscale
This looks much better, as it reflects the dark/light of the real curb
Just draining out the red
Conclusions:

### Final Answer

![Make the picture more natural](https://basemax.github.io/assets/image/university6.jpg)




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


# Question 7


![Make the picture more natural](https://basemax.github.io/assets/image/university4.jpg)

Suppose you are visiting Stanford and you park your car here, and get a parking ticket. Philosophically, they say that you are better off taking in events as they have actually happened. Nonetheless, here we'll try to fix history in code. 

Challenge: write code to detect the red curb, (a) change it to medium gray red=120 green=120 blue=120. (b) change just the red curb to be grayscale, which will look more realistic. Rather than changing the whole image to grayscale, we change just the red areas. Recall that the algorithm to change grayscale is to set red/green/blue values all to be the average value.


### Final Answer

![Final Answer](https://basemax.github.io/assets/image/university5.jpg)



# Question 8


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



# Question 9


![Make the picture more natural](https://basemax.github.io/assets/image/flower7.jpg)

Write code that picks out the pixels of the green leaves in the image (using the > avg * factor technique, as in lecture). For each green pixel identified, set its green value to 0. The result is that the green leaves are changed to a sort of weird purple color, since setting green to 0, we just have red and blue contributing.




### Final Answer

![Final Answer](https://basemax.github.io/assets/image/flower8.jpg)





# Question 10


![Make the picture more natural](https://basemax.github.io/assets/image/fish.jpg)

Write bluescreen code to place this fish in front of the yosemite.jpg background. The fish has bits of blue on it, but that's ok since we're using a green background in this case. Adjust the code so that all of the green towel below the fish disappears. Little flecks of white will appear in the blue middle section of the fish; we're stuck with those with our current technique.



### Final Answer


![Final Answer](https://basemax.github.io/assets/image/fish3.jpg)





# Question 11



For the next problem, we'll accomplish a sort of artistic effect, working with the tree.jpg image:


![Make the picture more natural](https://basemax.github.io/assets/image/tree.jpg)

![Make the picture more natural](https://basemax.github.io/assets/image/tree2.jpg)

Write bluescreen code to modify the tree.jpg image, replacing the trunk and some of the branches of the tree with pixels from pebbles.jpg. The result is a sort of fanciful looking stone-tree image. Adjust the code so the lower trunk is changed to pebbles, but not too much of the greenery next to the trunk.


### Final Answer


![Final Answer](https://basemax.github.io/assets/image/tree3.jpg)



# Question 12

The next problem, Fish Dreams of Paris, uses two images. paris.jpg:

![Make the picture more natural](https://basemax.github.io/assets/image/paris3.jpg)

And striped-fish-blue.jpg:

![Make the picture more natural](https://basemax.github.io/assets/image/fish.jpg)



The "Fish Dreams of Paris" problem.

The striped fish is facing right in front of a blue background. Parts of the fish are blue also — the eye and the vertical stripe in the middle. For this problem, we'll let the background image replace those two blue areas as well.

Write bluescreen code to place striped-fish-blue.jpg in front of paris.jpg. In particular, adjust the code so that the blue background, the blue middle stripe, and blue eye of the fish all show the paris.jpg pixels. Adjust the code so the blue towel below the fish is almost completely replaced.


### Final Answer


Not Defined!

-------------


If you tried and thought ...

Click [here](https://basemax.github.io/2019/02/04/Part3-Answer-Make-the-picture-more-natural.html) to check the final answer.

