---
layout: post
title:  "The Universe on a Stick"
date:   2025-02-22 14:50:50 +0000
categories: flash talks
---
<h3>The Story</h3>
When I was a child, my dad told me a story that he once heard. Once upon a time, an alien visited earth and was greeted by friendly humans, who invited him to stay with us and learn our culture. He stayed with us for a long time, and learned all there was to know about planet Earth. When it was time to leave, he said he wanted to record his experience so that he could tell all the other aliens. 

Well, what do you need? The earthlings asked. We have super computers and pen and paper. 

No need! The alien said. Looking around, he picked up a tree branch on the ground, and used a knife to carve a line on it. There! He said. This line represents an irrational number, which encodes all the information on this planet.

This is an exaggerated account, of course. I mean, the knife cut is not a perfect line with zero width, and it is impossible to know with accuracy where to cut. But I am here to tell you that theoretically this is possible, because numbers have incredible power to store information.

<h3>The Happiness Record</h3>
Let's start with a simple case. Look at every human being on the planet, and suppose each of them reports a number from  0 to  9, which represents how happy they are at this moment in time. 

Next, let’s number all the people on the planet, for instance, you can be number 1, I can be number 2, your favorite musician is number 3 etc.

Then, let’s build a number between 0 and 1. Suppose you are at a happiness level 6, I’m at 5, and let’s say your favorite musician is extremely happy, at a 9. So the number we write down is 0.659..., where after 0, the Nth digit stands for the happiness for the Nth person.

After this, we can regard the piece of stick as the number segment [0,1], where 0 is the left end of the stick and 1 is the right end. Now if you carve the number 0.659... on the stick, this cut represent the happiness level of all human beings on Earth.

<h3>More Information</h3>
Suppose that instead of a small integer with length 1, everyone on Earth is allowed a longer integer. For instance, if everyone is allowed an integer of 6 digits in length, we can record everyone's age and height. If you are 17 years old, and have a height of 170cm, your integer is 017170. We then join everyone's integers together into one big number, like we did with the happiness record. We number everyone on Earth and after zero, we write down their integers one by one. 

Indeed, instead of 6 digits, we can even allow everybody one hundred digits, one million digits, and record everything from their GPS coordinate at this moment to their bank details to their wifi password. 

If fact, we can even store am indefinitely large amount of information for each person. Instead of giving everyone a large integer, we can give them a number between 0 an 1, whose digit expansion is infinite in length. Then to combine everyone's number into one number, we can interleave them like cogs. With two people, it changes 0.123456789... and 0.000000000... to 0.102030405060708090...

The number of people on Earth is finite, so after giving each of them have a number between 0 and 1, we can interleave the numbers together to get one number. Then, using a cut on a stick, we can store all the information you could think of for everyone on Earth.

A warning: In order to decode the message, you need to first know the number of people on the planet, and the method of encryption. Otherwise the number is useless to you.

<h3>The Universe, Till the End of Time...</h3>
Why stop there? Let’s look at the entire observable universe and all the planets, all the suns, all the black holes, all the floating particles. There’s a finite number of those. Using the exact method as before, we can represent the position of all of them at this moment in time as a single cut on a stick.

But isn’t this rather a waste? There are infinitely many numbers on the stick, and we are only going to use one?

Instead of making one cut, we can make infinitely many cuts to record the information about the universe through time. Suppose that we take a measurement every second, and use a number in (0, 1) to record each state. Then what we can do is this:

At the first second, treat the entire stick as the interval [0, 1]. Make a cut.

At the second second, treat the portion of the stick to the right of the cut to be [0, 1]. Make the second cut.

At the third second, treat the portion of the stick to the right of the second cut to be [0, 1]. Make the third cut.

Notice how we are using a number in (0, 1) to represent the state of the universe, so we never repeat cuts, and we never reach the end. But if we never reach the end of the stick, it means there’s still room to the right of the last cut, to make another cut. In this way, we can use a stick to record the state of the universe, from now to infinity beyond.

(There is a slight possibility that you'll get 0.999999... as your number. To avoid this, you can for example, insist that all of your encodings start with 0.0. That is, make sure all of the numbers are of the form 0.01234... so that all of the numbers are less than or equal to 0.1)

And my favorite fact about this whole thing: after you finish making infinitely many cuts, there’s still a lot of space left over on the stick. If you want to do this all over again for another universe, you have enough space on that stick to do so.

<a href="https://github.com/xietianyiwa/flash_talks/blob/gh-pages/PDF/The_Universe_On_A_Stick.pdf" target="_blank">PDF</a>
