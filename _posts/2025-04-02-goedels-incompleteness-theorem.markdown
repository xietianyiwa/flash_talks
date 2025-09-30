---
layout: post
title:  "Gödel's Incompleteness Theorem"
date:   2025-04-02 14:50:50 +0000
categories: flash_talks
---
<h3>Axioms</h3>
You might think that maths is all about numbers and equations, but a lot of the work of a pure mathe- matician is formalizing problems and proving them.

What exactly is a proof? Some examples look like this:

• If p ⇒ q and p are true statements, then q is a true statement. 

• If p is true, and q is true,then p and q is true.

Granted, these examples are a bit idiotic, but all the proofs in the maths world are proved in this way: from known result A, deduce new result B.

A devoted follower of the socratic method or a five year old might then ask “why is A true?”
We’ll have to prove A as well, let’s say from other known result C. But then you can ask “why is C true?”.

The reminds me of the myth of the World Turtle. A conversation with a firm believer might look like this: what’s below our feet? The Earth. What’s beneath the Earth? Four elephants. What’s beneath the four elephants? A turtle. What’s beneath the turtle? Stop asking stupid questions.

With every proof in maths, you can peel back the layers of assumptions and discover a turtle, which is a statement which is so fundamental, so “obvious”, that it’s impossible to prove. It’s things like “1 + 1 = 2”. We have to agree about this to have a conversation, otherwise we will never get anywhere.

These fundamental statements are the turtles of the mathematical universe. Everything depends upon them. These statements are called Axioms.

Different people have can believe in different sets of axioms, just like different people can have different core beliefs. Different sets of axioms can lead to different results.

That being said, some sets of axioms are... broken, like if it includes the axiom “1 + 1 = 3”. In such a system, a contradiction can be reached, and weird things happen (in fact in this world, every single statement is true). So for this talk we will assume all set of axioms are reasonable and not broken.

There are certain things mathematicians agree on, but there are actually a few statements which are disputed. Interesting results can be proven in both cases where the statement is true or false, and people are doing active research under the assumption of either.

<h3>Hilbert's Dream</h3>
David Hilbert was one of the greatest mathematicians of all times. He believed that all the true statements in mathematics can be proven.

Obviously, if something can be proven, it must be true. But the converse is not so clear. Is a true statement impossible to prove? Or is it just so hard that no one has found a solution yet?

Hilbert believed that all true statements in maths will one day be proved. During his retirement speech (9 years before WW2), he said the words “we must know, we shall know”. He believed in this so firmly that this quote is engraved on his tombstone.

Sadly, what Hilbert didn’t know is that by the time he is making his speech, his vision has already been proven false, by a bright young mathematician named Gödel.

<h3>Enter Gödel</h3>
Gödel was an amazing mathematician, but also an interesting man. Later in life Gödel became paranoid of being poisoned, and ate only food prepared by his wife. He died of malnutrition[^1].

The result Gödel proved, which shook the entire maths community, is this: in a axiom system which supports the existence of natural numbers, there is always a true statement which cannot be proven.

[^1]In a set theory class at university, we learned about a thing called Gödel functions. There are a series of proofs involving them which are extremely annoying and tedious. Looking at blackboards full of derivations, someone joked “no wonder Gödel went crazy.”
 
This means that as long as in our mathematical world, there is such a thing as natural numbers, there is always a true statement that we can never proof. Not that we haven’t found the proof yet, no matter how long you try, even if you have an infinite amount of time, you can never find a proof – because the proof does not exist.

Fine, you might say, a thing as obscure as that is probably not important. Let’s just assume it’s true, and add that statement to our axioms.

But then in this new system, a new statement will appear that you cannot prove. There is always going to be a hole in maths, which is unknown to us.

<h3>Sidenote: Proof by Contradiction</h3>

We will discuss the proof next and for that we use proof by contradiction. If you are unfamiliar with this technique, the idea is this:

• Suppose we wish to prove a sentence S is true.

• First assume that S is not true, and try to reach a contradiction.

• Suppose that we managed to prove, under the assumption that S is not true, that the sky is green. Then something must have gone wrong, because the sky is not green!

• This tells us that something in our assumption is impossible. So S must be true.

<h3>The Puzzle</h3>
It is amazing that we can prove that something is unprovable. The proof depends on a logical puzzle. Have you heard of the sentence “I am telling a lie”? When someone says that, a paradox is created. A similar thing happens here. Consider the sentence S, which says “this sentence is unprovable.”

I claim: S is true but unprovable.

S is true: If it is not true, then it is provable. A provable statement is true, contradiction. So S must be true.

S is unprovable: if S is provable, then S is true, so S is unprovable, contradiction.

The tricky thing of course, is how would you write down “this sentence is unprovable”. It requires the sentence to know what is its own content. We met a similar problem in the Prisoner’s Dilemma talk, where a program was required to print out its own source code. We will talk about the solution to these in a future talk.

<h3>Maths Could be a Religion </h3>
I will leave you with this last thought, which a friend brought to my attention: Suppose you define religion as “a system of beliefs, which includes held beliefs which cannot be proven”, then Gödel just told us that maths is a religion! In fact, it is the only religion that can prove that it is one.

<a href="/PDF/Goedel_incompleteness.pdf"target="_blank">PDF</a>