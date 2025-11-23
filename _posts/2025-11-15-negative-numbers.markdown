---
layout: post
title:  "Negative numbers"
date:   2025-11-16 10:11:00 +0100
categories: main content
---

{% include math.html %}

The idea of a negative number was so outrageous that in only became widely accepted in Europe in the 19th century.
English mathematician Francis Maseres claimed "negative numbers darken the very whole doctrines of the equations".
Although mathematicians in ancient China already sort of used negative numbers to represent debt,
it took thousands of years for this idea to become a common notion.

To say that I own -5 dollars means that I owe you 5 dollars. This is debt, and it's actually quite a natural way
to think of negative numbers. You've surely learnt about negative numbers in school, since it's in the
K12 curriculum of pretty much every country, but a surprisingly high amount of people still do not fully
understand them. Do you understand why the product of two negative numbers is positive, for example?

Geometrically, negative numbers can be represented by extending the number line to the left. Like this:

![negative-line.svg]({{ site.baseurl }}/images/negative-line.svg)

How do I add two negative numbers together? Going with the debt analogy, this is equivalent to piling up debt
(something you should try to avoid in real life 💀). Thinking of it this way, the following equation makes perfect sense:
\\[-2 + (-7) = -9\\]
If I owe you two things, and I add a debt of seven more things, I'm going to owe you nine things. When the plus sign and the minus sign are next
to each other like above, it is customary to **wrap the negative number in parentheses, so that it's easier to see that the minus sign belongs
to the number**.

Let's take a look at another example!
\\[-6 + 10 = 4\\]
If I'm six dollars in debt, but I get ten dollars, I'm actually going to end up with four dollars.
Pretty straightforward.

## Negation

What *really* happens when I add a minus sign in front of a number?

Well, negating a positive number is easy. If you put a minus sign in front of say, 5, it ends up on the opposite side of
the number line with respect to zero, like so:

![negation.svg]({{ site.baseurl }}/images/negation.svg)

This number is called "minus five". Notice that the distance from zero to 5 and -5 is equal. They're equally far
apart from zero, but on different sides. This can be done with any number, of course. This process is called **negation**.

If you're on the right side of the number line, you're debt-free, you have credit 😎. If you're on the left, you have debt, which is pretty bad.
In effect, the negative part of the number line is like a mirror copy of the right side. Minus signs allow you to travel between
these mirror dimensions by transporting the number in question to the opposite side of the number line to its appropriate place.

What happens if I put a minus sign in front of a number that already has one, e.g. -(-5)? As I've said before,
a sensible way to think about minus signs is to think of it as transporting the number to the opposite side of the number line.
What's the appropriate place on the opposite side for -5? It's 5, of course. Take a look at this image:

![negation-negation.svg]({{ site.baseurl }}/images/negation-negation.svg)

This means that $$-(-5) = 5$$. The first minus sign jumps to the left, from 5 to -5, while the second one
jumps back to the right, from -5 to 5.

It's not that hard to see that this can indeed be done with any number. What do we have when we idenfity
some phenomenon that is true for every number? Let's say it together: this is a general property!
Written with letters, this is:
\\[-(-a) = a\\]

If we play around with addition of negative and positive numbers, we can identify another general property of numbers.
Take a look at these examples:
\\[4 + (-4) = 0\\]
\\[10 + (-10) = 0\\]
\\[7 + (-7) = 0\\]

Adding the negated copy of a number to itself always results in 0. That is,
\\[a + (-a) = 0\\]

As an example, if $$a = -11$$, then the template evaluates to
\\[-11 + (-(-11)) = 0\\]

This introduced a double negation. Thankfully, we've already learned about them.
Since $$-(-11) = 11$$, this really just says
\\[-11 + 11 = 0\\]
which is obvioulsy true. In fact, this is just the commutative reversing of
\\[11 + (-11) = 0\\]

The number $$-a$$ is called the **additive inverse** of $$a$$.
There's only *one* additive inverse for each number. That is, the additive inverse for some number $$a$$ is unique.
For example, the additive inverse of 8 is -8, while the additive inverse of -65 is 65 since
\\[8 + (-8) = 0\\]
\\[-65 + (-(-65)) = -65 + 65 = 0\\]
All other numbers either undershoot or overshoot zero.

## Multiplication

What should happen when multiplying a negative number? For example, what is $$4 \cdot (-3)$$?
Four times minus three. Well, by definition of multiplication, this is minus three, added together four times:
\\[4 \cdot (-3) = (-3) + (-3) + (-3) + (-3) = -12\\]
Not too hard.

What happens if I swap the order of terms. That is, what is the value of $$(-3) \cdot 4$$? Minus three times four?
How do I add four *minus three times*? The commutative property of multiplication tells us that the value shouldn't change,
and it should still be equal to -12. But what if commutativity only works for positive numbers? How do we know it doesn't actually
*break down* when we introduce negative numbers? I want to maintain commutativity, even with negative numbers, so my goal is to find
some convincing evidence that $$(-3) \cdot 4 = -12$$.

When faced with a difficult dilemma like this, it is always helpful to **investiage simple cases first**? For instance, instead
of trying to evaluate $$(-3) \cdot 4$$, let's actually swap that -3 with a -1. It's the simplest negative number after all.
Our goal is now to make sense of $$(-1) \cdot 4$$. Using commutativiy to reverse the order of terms, this would become
$$4 \cdot (-1)$$, which is equal to -4. But is there *evidence* that is is a sensible thing to do?

Take a look at the following expression:
\\[4 + (-1) \cdot 4\\]
Our target, $$(-1) \cdot 4$$, appears in it. Can we use this expression to somehow better understand it?

First, let's put 1 as a multiplier in front of 4, like this:
\\[1 \cdot 4 + (-1) \cdot 4\\]
This is equal to the original expression, since multiplying 4 by 1 is still 4, it doesn't influence its value.

Now let's use the commutative property of multiplication to swap the order of terms. Look:
\\[4 \cdot 1 + 4 \cdot (-1)\\]

Remember when we talked about factoring? If we have two terms added together, each multiplied by the same number, we
apply the distributive property backwards to pull it out. This can be done with the number 4 in this case:
\\[4 \cdot (1 + (-1))\\]

Thankfully, we've also learned about additive inverses, so we know that $$1 + (-1) = 0$$.

Therefore, the final value of the expression is
\\[4 \cdot 0 = 0\\]

We started with $$4 + (-1) \cdot 4$$ and by applying the already known properties of multiplication and addition, we found out that it's value is exactly zero.
Here are all the steps we took as an equation chain:

This is all pretty cool, but how does it help us understand $$(-1) \cdot 4$$, since that's our ultimate goal. Take a look at the expression we just evaluated:
\\[4 + (-1) \cdot 4 = 0\\]

This is suspiciously similar to the property concerning additive inverses. We add something to four to make it zero. We already know that -4 has this property. Compare these two:
\\[4 + (-1) \cdot 4 = 0\\] 
\\[4 + (-4) = 0\\]

I believe we have found the evidence that we were looking for.
Both $$(-1) \cdot 4$$ and $$-4$$ are additive inverses for 4. But since there must only be one additive inverse for a number, these two must be the same thing.
That is, they are equal:
\\[(-1) \cdot 4 = -4\\]

This phenomenon is another pretty cool general property:
\\[(-1) \cdot a = -a\\]

Knowing this will make evaluating $$(-3) \cdot 4$$ a lot simpler, which was our original goal. First, let's rewrite $$-3$$ as $$(-1) \cdot 3$$:
\\[((-1) \cdot 3) \cdot 4\\].

Then, I use the associative property to move the parentheses one position to the right to get
\\[(-1) \cdot (3 \cdot 4)\\]

This is now easy to evaluate:
\\[(-1) \cdot (3 \cdot 4) = (-1) \cdot 12 = -12\\]

This is the evidence that we were looking for. This whole argument works with any numbers
and we can safely declare that the commutative property of multiplication doesn't break down when negative numbers
are introduced.

There's still one gaping hole in the theory. What about the multiplication of two negative numbers?
For example, what is the value of $$(-3) \cdot (-4)$$? Finding a sensible definition might seem like a
daunting task, but this is where the power of mathematics comes in. Using what we already know about multiplication and
negative numbers, it is actually super simple to evaluate it.

First, rewrite $$-3$$ as $$(-1) \cdot 3$$. This gives us
\\[((-1) \cdot 3) \cdot (-4)\\]

I'm going to use the associative property to move the parentheses one position to the right to get
\\[(-1) \cdot (3 \cdot (-4))\\]

The value of the parentheses is -12. Let's write it in:
\\[(-1) \cdot (-12)\\]

We also know that $$(-1) \cdot a = -a$$ for every number $$a$$, so this is in turn equal to
\\[-(-12)\\]
which is equal to 12.

Through multiple steps and application of various properties, we have derived that
\\[(-3) \cdot (-4) = 12\\]

And this line of reasoning works for any two numbers. The product of two negative numbers is positive, and this can
be demonstrated using only a couple simple properties concerning the order terms and additive inverses. Pretty good 👍.

This can also be stated as a general property:
\\[(-a)(-b) = ab\\]

As an example, let $$a = 8$$ and $$b = 2$$. The template becomes
\\[(-8) \cdot (-2) = 8 \cdot 2\\]
which evaluates to 16.

For a different example, consider what happens when $$a = -2$$ and $$b = 1$$.
Then the template becomes
\\[(-(-2)) \cdot 1 = (-2) \cdot 1\\]

If you look at it and evaluate both sides, you can see that this is also true.

## Subtraction

Poor subtraction. You might have been wondering about him. How does he fit in?

This might be a little disappointing, but subtraction is literally just a different notation for adding negative numbers.
Like this
\\[3 + (-5) = 3 - 5\\]
\\[(-6) + (-8) = -6 - 8\\]
\\[12 + (-4) = 12 - 4\\]

There's literally nothing to it. It's just a notation. A shorthand. Sorry to dissapoint you.
From now on, we are going to accept that subtraction is the same thing as adding a negative number.
\\[a + (-b) = a - b\\]

# Takeaway

Introducing negative numbers is probably the first time where we had to go knee-deep into mathematics to
make sense of their properties. It might seem confusing at first, but this is actually a good thing.
Using only handful of simple properties concerning addition and multiplication, we can make sense
of the properties of more complicated objects, like negative numbers.

This hierarchical structure is very well known in mathematics. We build complicated rules and objects from simple rules and objects, and we
use the objects that we built to build even more complicated objects.
