---
layout: post
title:  "Mixing addition and multiplication"
date:   2025-11-14 22:52:00 +0100
categories: main content
---

{% include math.html %}

So far we've only dealt with equations that contained only addition or only multiplication.
Fortunately, using both in the same equation is quite simple, actually.

There is an established convention on the order of operations that you've surely heard about in school.
It states that whenever both operations are present in the same equation, 
multiplication should always be performed first, unless the order is overriden by parentheses.

Here's what I mean:
\\[4 \cdot 2 + 3 = 8 + 3 = 11\\]
Here, I first evaluated the multiplication to get 8, and then performed the addition after that.

If I wrap the addition part with parentheses, the order changes:
\\[4 \cdot (2 + 3) = 4 \cdot 5 = 20\\]
The parentheses indicate that I should first evaluate the addition to get 5, and only then do I
perform the multiplication. The resulting value is different. The order of operations is not monkey business.

There's one important thing to be cognizant of: **the order of operations is not a mathematical rule**. It's a convention to help us
standardize the use of mathematical operations.

## Multiplying parentheses

Remember that multiplication is a shorthand for repeated addition. Always has been.
For example:
\\[6 \cdot 5 = 5 + 5 + 5 + 5 + 5 + 5\\]
Six times five means adding five six times. Easy.

Let's apply this same logic in the case where the multiplicand is in parentheses. E.g. $$4 \cdot (2 + 3)$$.
Technically, I can perform the addition inside the parentheses and proceed as in the example in the introduction, but let's instead break up the multiplication
into repeated addition, since that's what multiplication means anyway. The expression above means that I have to add (2 + 3) four times.
Like so:
\\[4 \cdot (2 + 3) = (2 + 3) + (2 + 3) + (2 + 3) + (2 + 3)\\]

There is no magic involved. Nothing special is happening.
Even though the addition part is in parentheses, indicating that it should be evaluated first, this does not in fact violate
the order of operations, since I haven't performed any operation yet 😉.
I simply chose to *rewrite* multiplication as repeated addition.

Notice that after breaking up the multiplication, we are left with addition only. We've already talked about
the fact that when only addition is involved in an expression or equation, I can freely reorder or regroup the terms.

I can reorder the above expression like so:
\\[2 + 2 + 2 + 2 + 3 + 3 + 3 + 3\\]
All I did was break up all the parentheses and group equal terms together. Twos on the left, threes on the right.

Notice the repeated addition of twos and threes! This is multiplication! So let's write it as such!
It might seem stupid to introduce multiplication again, since we literally started by breaking it up, but let's do that anyway.
We replace repeated addition with multiplication to get:
\\[4 \cdot 2 + 4 \cdot 3\\]

Evaluating this, I get:
\\[4 \cdot 2 + 4 \cdot 3 = 8 + 12 = 20\\]

This is the same result that we got in the case where we performed the addition inside the parentheses first, like a sane person.

Now why the hell did we do all this? Why can't we just go the simpler route and actually perform the addition inside the parentheses?
Why do we break up multiplication and reintroduce it again?
Well, to answer your question, let's compare the expression that we started with, $$4 \cdot (2 + 3)$$, and the expression
we ended up with, $$4 \cdot 2 + 4 \cdot 3$$. These two are equal, since they both evaluate to 20. So I can write:
\\[4 \cdot (2 + 3) = 4 \cdot 2 + 4 \cdot 3\\]

If you take a look at the shape of this equation, you might notice something. Instead of multiplying the entire addition inside the parentheses by four,
we transformed the expression into a form where we multiply the *individual terms* by four, and only then do we add them up.

Believe it or not, this is another general property. If you feel like it, perform the same process that I did to see why
these examples are also valid:
\\[9 \cdot (1 + 5) = 9 \cdot 1 + 9 \cdot 5\\]
\\[3 \cdot (10 + 2) = 3 \cdot 10 + 3 \cdot 2\\]
\\[1 \cdot (6 + 20) = 1 \cdot 6 + 1 \cdot 20\\]

Using letters, I can write the general form as:
\\[a(b + c) = ab + ac\\]

Remember that when using letters, we usually do not use the multiplication sign.

This property has a name. It's called **distributivity**. We say that **multiplication distributes over addition**.
It's quite a revealing name, don't you think 😉?.

You might not yet see why this is useful. After all, it seems like we are overcomplicating a simple problem.
No worries, let's get pragmatic and see where we could apply this property.

## Factoring

Let's say you're faced with the following math problem. You have to evaluate $$50 \cdot 25 + 50 \cdot 75$$.
Oh, and you don't have a calculator.

It's not a particulary hard problem, but if you're shit at mental math like me, it's sometimes a bother. Is there a way
to make our lives easier?

Notice that the problem we have is similar to the right side of the examples for distributivity. We have some terms multiplied by the same number, namely 50, added together.
I introducted distributivity as going from left to right. That is, if we have an expression of the form $$a(b+c)$$,
I can break up the multiplication and transform it into $$ab + ac$$.

But **equality is a two-way street**. There's nothing stopping me from going from right to left.
If I have an expression of the form $$ab + ac$$, I can apply distributivity *backwards* to get $$a(b + c)$$.

In our case, I can write
\\[50 \cdot 25 + 50 \cdot 75 = 50 \cdot (25 + 75)\\]

This is just the distributive property, like we've talked about. Equality has no direction. It works both ways.

Using the distributive property to "pull out" multipliers in an expression like this is called **factoring**.

The factored form of this expression is a lot easier to compute in your head. It involves "easy" numbers. Look:
\\[50 \cdot (25 + 75) = 50 \cdot 100 = 5000\\]

It's much easier to do in your head than the original $$50 \cdot 25 + 50 \cdot 75$$ form.

## A hard addition problem

I want you to compute the following sum:
\\[1 + 2 + 3 + 4 + \dots + 97 + 98 + 99 + 100\\]
That is, add all the numbers from 1 to 100 without using a calculator.
This is going to be our capstone project for addition and multiplication.

This problem isn't especially hard, just very tedious. A good mathematician is very lazy, always looking for shortcuts.
It's not a bad thing, it's very good quality to have actually. I'm too sleepy to work hard. Why not work *efficiently* instead?

The above problem involves only addition, so we can reorder it and add in parentheses to our liking. Is there a reordering that
makes the problem easier 🤔? Consider this one:
\\[(1 + 100) + (2 + 99) + (3 + 97) + ... + (49 + 52) + (50 + 51)\\]
What I did was group the first and last term together, the second and second to last together, and so on.
This is a simple reordering and regrouping.

Notice now, that each group wrapped in parentheses evaluates to 101. Really, I'm not joking, see for yourself. Replacing the parentheses with their value,
the above sum is equal to:
\\[101 + 101 + 101 + 101 + \dots + 101 + 101 + 101\\]

This is amazing for us, since this is repeated addition, i.e., multiplication! The question remains: multiplication by what?
How many times is 101 added?

Well, if you look at the sum above, each pair of parentheses in the reordering contains 2 terms. How many such groups of two can we make from 100 elements?
Obviously, the answer is 50. There are 50 such groups.

This means that 101 is added 50 times, i.e., it's multiplied by 50. And we have our answer:
\\[50 \cdot 101 = 5050\\]

This is the sum of numbers from 1 to 100.

# Takeaway

We talked a lot about addition and multiplication separately, but only now have we tried to combine them.
It's always important to experiment with how two distinct mathematical objects behave when put together.
This way of experimentation might lead to new discoveries that increase our knowledge or efficiency (e.g. factoring).

The last problem demonstrates how hard and tedious problems can be solved much quicker if we make good use
of our mathematical inventory.