---
layout: post
title:  "Hilbert's Infinite Hotel"
date:   2025-03-25 15:50:50 +0000
categories: flash_talks
---

<h3>Welcome to the Hotel...</h3>
It was a dark and stormy night. You traveled for the entire day, and you were tired and soaked through. In the distance, through the mist of rain you saw a neon sign which spelled “Hilbert Hotel”.

You walk up to the receptionist, and asked if there was any room. He replied that unfortunately, the entire hotel was full. Just when you turned to leave, the manager stopped you. “Wait! We can make room!”
See, this is no ordinary hotel. Hilbert hotel has infinitely many rooms: For every natural number, there is a room with that number on the door. How can the manager make room for you?

Well, he could ask all of the residents in the hotel to move. If a guest lived in room N, then he would move to room N + 1. For any number N , there is a natural number larger than it, so nobody was kicked out. You will put in room 1.

Just when you were settling in, a train arrived, bearing 1 million passengers who seeks shelter in the hotel. What now?

Simple! Everyone in room N moved to room N + 1, 000, 000. The rooms 1 to 1, 000, 000 were now empty to accommodate the new arrivals.

This phenomenon is similar to what happens when you put a drop of water in the ocean: you can’t notice anything because the ocean is enormous. Infinity is so large, that adding any finite number to it doesn’t affect it in the slightest. You can describe this phenomenon loosely[^1] as 1 + ∞ = ∞; 1,000,000 + ∞ = ∞.

Now, an infinite train arrived at the station. This train had all the residents from another identical In- finite Hotel which unfortunately collapsed. For every natural number, there is a corresponding passenger. What will happen now?

[^1]: Very loosely. We haven’t defined exactly what is ∞, and there are different types of infinity, as we’ll soon see.

The hotel manager wiped sweat off his brows and made a decision. He asked all the guests in the hotel to move from their room N to room 2N. So the original guests now occupied rooms 2,4,6,8..., freeing up all the odd-numbered rooms, which enabled him to accommodate the new guests. The only problem now is that he has several angry guests. One of them had to move from room 14, 589, 123, 067 to room 29, 178, 246, 134, climbing over ten billion flights of stairs.

<h3>How big is the Hotel?</h3>
Just how magical is the hotel? What can you fit in there?

If you have a train of people arriving, then as long as you can list them one by one in some way
and not miss out on anybody, then we can fit them into the hotel (even if the hotel is already full). We describe this phenomenon by saying “the amount of people on the train is countable’. Indeed, if you can fit a group of people into the hotel, then this group of people is countable.

Some examples of countable numbers include the global population, the number of humans that have ever lived, the number of people that will ever live. Indeed, compared to the sheer size of the hotel, these are very very small numbers because they are all finite! As we have observed, any finite number compared to the hotel, no matter how big that number is, is like a drop of water compared to the ocean.

Suppose that you are an omniscient creature who for every second from now until the end of time, records the state the universe, then in the end you would have many infinitely many records, but that number is still infinite. Why? Because we can still list them, second by second.

Do you see a connection between this and what we talked about during <a href="https://xietianyiwa.github.io/flash/talks/the-universe-on-a-stick/" target="_blank">the Universe on a Stick talk</a>? We’ll come back to this.

<h3>Different Sizes of Infinity</h3>
At this point you might ask “What’s the limit of the hotel? Can the hotel just keep taking in people?”. Turns out, the answer is no.

Suppose a new train arrived, where for every real number in the interval (0,1), the train bears a passenger in a seat with that number as its label. All of them needs shelter, can you house them?
Now the hotel manager was in serious trouble. Even if he were to kick out all of the existing guests, he still had no hope of housing all of the passengers from the train. Why?

Well, suppose he could, and in each room N slept a passenger R , where the real number R was this person’s seat number. The manager has a list of passengers and the rooms they were in, like so:

1 → passenger 0.1234567 . . . 

2 → passenger 0.5000000 . . . 

3 → passenger 0.3333333 . . .

...

Suddenly an angry passenger demands to speak with the manager. “I’ve not been given a room!” He shouted.
“Sir, please calm down,” said the manager, “I have here all the passengers and their room numbers. Give me your seat number, and I’ll check which room you are supposed to be in.”

This passenger sat at seat R = 0.2649.... This seat number R has the interesting property that every Nth digit after zero is different from the Nth digit of the passenger in the Nth room.

This number exists, because we can write down this number simply by going down the manager’s list diagonally. Every number on the diagonal is the Nth digit of the Nth passenger, and we just need to choose a number different from it.

This has the consequence that R is different from all the seat numbers on the manager’s list, so this passenger has not been housed!

This situation will arise no matter how you arrange the passengers in the Hilbert hotel. This is because although there are infinitely many natural numbers and real numbers, their sizes are different. The real numbers are not countable, and infinities have different sizes.

This is the hidden reason behind <a href="https://xietianyiwa.github.io/flash/talks/the-universe-on-a-stick/" target="_blank">the first talk</a>. There are uncountably many numbers on any stick, so we could comfortably put countable amount of information there.

<a href="https://github.com/xietianyiwa/flash_talks/blob/gh-pages/PDF/Hilbert_Hotel.pdf" target="_blank">PDF</a>
