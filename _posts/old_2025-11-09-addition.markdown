---
layout: post
title:  "Addition"
date:   2025-11-09 17:39:00 +0100
categories: main content
---

{% include math.html %}

I have three copies of the hit video game Elden Ring on one shelf.
I have two copies of Alan Wake (2007) on another.
How many games do I have in total? Five.

Adding two things to three things looks like this in writing, using Hindu-Arabic numerals:
\\[3 + 2 = 5\\]
Three plus two is equal to five.

If you have managed to successfully graduate from primary school,
then you know what this means. Basic addition like this is so simple that 
I think it doesn't deserve further explanation.

But don't laugh. As with any other simple things, the devil is in the details.
Addition is no exception. Simple arithmetic can open up some pretty important ideas
that are crucial in high school and university level mathematics. So pay attention.

## The order of terms

Now listen up, because I'm going to put a little "twist" on the previous problem.
Suppose that now I have two HP DeskJet 2700 printers on one desk (terrible printer by the way) on the left,
and three more on another desk on the right.
How many do I have in total?

You might try adding the two on the right to the three on the left get the total, as before.
Writing this down, this is $$3 + 2 = 5$$. Simple.

But what if we try adding the three on the left *to* the two on the right?
Well, the total is still five, I just changed the order of terms. Like so: $$2 + 3 = 5$$.
This is pretty convenient. **I can add these two quantities in any order**. 
See:
\\[3 + 2 = 5\\]
\\[2 + 3 = 5\\]
Since 3 + 2 and 2 + 3 are both equal to 5, they are equal to each other.
This way, I can write
\\[3 + 2 = 2 + 3\\]
as a shortcut.
The quantity "three plus two" is equal to the quantity "two plus three".

Use your braincells for a second and verify that this is true for any two numbers.
For instance, in the following examples the left and right hand sides of the equations are equal:
\\[8 + 9 = 9 + 8\\]
\\[100 + 15 = 15 + 100\\]
\\[1 + 111 = 111 + 1\\]
This further reinforces that fact that this should work for all numbers.

In general, I can simply write
\\[\text{first number} + \text{second number} = \text{second number} + \text{first number}\\]
This pattern matches up with the examples above. Think of it as a template, or a fillable form.
I can plug in any two numbers in place of "first number" and "second number",
and the two sides would be equal.

For example, if I say "first number" is 78 and "second number" is 99, then the statement becomes
\\[78 + 99 = 99 + 78\\]

This is an example of a **general property**, something that holds for all numbers.
This is very important. Math is all about general properties, as you will see 😜.
Introducing you to the concept of a general property is the only reason I'm willing
to type all this stuff about about preschool addition, by the way.

## Addition with 0

You want more examples of such properties, you say? 
Then consider what happens when I add 0 to a number. For example, what is $$55 + 0$$? If you're older than 7,
then you know that nothing will happen, **the number doesn't change when I add 0 to it**.
This is also a general property, since this is true for any number I choose. I can write
\\[\text{the number I chose} + 0 = \text{the number I chose}\\]

For example, if "the number I chose" is 42, then plugging it into the statement above I get
\\[42 + 0 = 42\\]
which is a true statement, of course.
This is the power of general properties. **No matter what numbers I plug into them, it's always going to result in a true statement** (try it!).

## Abbreviation

You can see by now that whenever I state a general property in writing,
I have to kind of describe what the statement says in English.
I need to write things like "first number" and "the number I chose".
This is terrible, no one wants to type that much 💀.

The solution to this problem is quite simple, actually: abbreviation.
When I want to state some general property that is true for all numbers,
I'm just going to use single letters, instead of using lengthy phrases as above.
Yeah. This is common practice.

Like this:
\\[a + b = b + a\\]
This says that I can add two numbers in any order, like we've talked about.
In place of "first number" or "second number", I'm using "a" and "b".
Technically you can use any symbol, or phrase, or whatever you want,
but abbreviating using the letters of the ABC is the most straightforward and widely used.

Letters in math are only used for brevity. No magic and hat tricks involved 🪄🎩.

For the property concerning zero, I'm gonna write
\\[a + 0 = a\\]

Here, the letter "a" stands in place of "the number I chose".

If you think about, 0 is actually the only number that has this property. Adding anything else will
surely change the value of $$a$$.

## Parentheses

**Parentheses are used to specify the order of addition when you have three or more terms.**
Take a look at this:
\\[3 + (5 + 2)\\]
This means that you first have to perform 5 + 2, which gives 7, and only then do you add the 7 to the three.
Like so:
\\[3 + (5 + 2) = 3 + 7 = 10\\]
Notice that after the first equals sign, I replaced the parantheses with the value of the addition inside.

Let's now move the parantheses one position to the left to get
\\[(3 + 5) + 2\\]
If you evaluate this like before, you get
\\[(3 + 5) + 2 = 8 + 2 = 10\\]
which is the same number, namely 10.

If you try this with more examples, you will hopefully realize that this is another general property.
Here are some more examples. Evaluate both sides and you will see that they are equal.
\\[(100 + 1) + 10 = 100 + (1 + 10)\\]
\\[(7 + 6) + 33 = 7 + (6 + 33)\\]

In general, I can write
\\[\text{first number} + (\text{second number} + \text{third number}) = (\text{first number} + \text{second number}) + \text{third number}\\]

Using single letters to abbreviate, it's written like
\\[a + (b + c) = (a + b) + c\\]
Less of a pain to type 😌.

## Addition in any order

Let's evaluate this expression here: $$(472 + 62) + 9$$.
This is pretty simple:
\\[(472 + 62) + 9 = 534 + 9 = 543\\]

Let's evaluate another expression too! For example, $$(9 + 472) + 62$$.
The result of this one can be computed like this:
\\[(9 + 472) + 62 = 481 + 62 = 543\\]

This gives the exact same value as the previous one, which is not that surprising since they contain
the exact same terms. Can we use the general properties of addition to reason through why they are equal?
Here's what I mean.

Take the original expression, $$(472 + 62) + 9$$. Use the property concerning parentheses to move the parentheses
one position to the right. This results in $$472 + (62 + 9)$$. Let's swap the order of terms inside the parentheses.
According to the general property concerning the order of terms, it doesn't change its value. We get $$472 + (9 + 62)$$.
Let's move the parentheses back to its original position. We end up with $$(472 + 9) + 62$$. Finally, I can change the order of
terms inside the parentheses to get $$(9 + 472) + 62$$.

What this means, is that we can use the general properties of addition to transform the first expression into the second one
without changing its value (since none of these properties change the value of the expression, only the ordering and grouping).

Since $$(472 + 62) + 9 = 543$$ and $$(9 + 472) + 62 = 543$$, we can see that these two expressions are indeed equal, but
seeing is often not good enough. Using the properties of addition, we have actually *demonstrated* why they are equal.

In reality, you don't consciously think about the general properties of addition when evaluating expressions like the ones above.
You already know that addition can be performed in any order using any arrangement of parantheses using however many terms.
It's obvious.
For example, take the following addition problem:
\\[4 + (9 + 111 + 56 + (64 + 1) + 0) + 0 + 91 + 36 + 11\\]

This can be rearranged in whatever order you like. Really. For instance
\\[0 + 0 + 1 + 4 + 9 + 11 + 36 + 56 + 64 + 91 + 111\\]
or
\\[(4 + 56) + (9 + 1) + (64 + 36) + 111 + 91 + 11 + 0 + 0\\]
or
\\[11 + 36 + 91 + 0 + 0 + 1 + 64 + 56 + 111 + 9 + 4\\]

These three contain the exact same numbers as the original expression.
The order of terms and the positioning of parantheses doesn't matter, all of the above give the same result.

**You can technically use the properties introduced in this section to reason through why these rearrangements are correct**, like before,
but let's be real, no is going to do that 💀. Who has time for that?

From now on, let's just agree that doing addition can be done in any order and arrangement.
It's just common sense 👍. If you have successfully graduated school, you should already have a feel
for simple addition.

# Takeaway

Math is all about general properties which are true for a wide range of numbers.
Instead of providing a single example to these properties, we usually state them using letters or symbols,
so as to create a fillable form or pluggable template that works for all numbers.
An infinite amount of flies, with only a handful of stones 😼. 


