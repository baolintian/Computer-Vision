

This Computer Vision Course is originated from Cornell University, and the following demos just some assignments  I have finished for my Computer Vision homework.



# Homework1 Hybird Images

Extract the high frequency from one image and extract the low frequency from another image.

Then mix them together, you will find the high frequency has a significant effect on nearby version,

but the low frequency has a significant effect on the distant version.



Extract its low frequency:

![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rin5cdqzj20be0a1ac7.jpg)

Extract its high frequency:

![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rimeal47j20be0a1dhv.jpg)

The mixed image:

![](https://ws1.sinaimg.cn/large/a7ded905ly1g1riktjm1fj20be0a1tfy.jpg)



# Homework2 Feature Detection and Match

After taking a photograph from one angle, we move our camera horizontally without changing its direction and take another photograph.

Then we get two photographs. Our task is to design an algorithm to detect some similar points in the two pictures. We also need an algorithm to match them in pairs.

The detailed accomplished steps are included in the homework report.





Finish the assignment using random and simple algorithm:

![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rj0e1u6wj21h60spdrl.jpg)



Finish the assignment using MOPS algorithm:

![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rj07jexmj21hb0p3gx4.jpg)



# Homework3 Panorama

At first, we have a series of pictures and they have the same feature that they all have the same camera optic center. That's why we can make some coordinate transformations to them and form a panorama.

At first, we need an initial picture, then we need to do the feature detection and match which has been discussed in homework2. Then we calculate the transformation matrix, we multiple the image with the matrix, then we get a part of the panorama. We continuously go through this process and at last, we will get a panorama.

The following pictures are taken from my campus square center:

![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rjawe7q9j20go0ciq4u.jpg)



![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rjazn1ykj20go0cijtg.jpg)



![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rjb3hehuj20go0ciwh3.jpg)



![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rjb8whnwj20go0cidiy.jpg)



The result:

![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rjbj1oavj215c0kpe81.jpg)



# Homework4 Stereoscopic vision

The picture may show some information about the depth of the object. This assignment is designed to figure out this attribution.

The data set is specially processed.



The result:

![](https://ws1.sinaimg.cn/large/a7ded905ly1g1rji7jlxsg20x80q0npi.gif)