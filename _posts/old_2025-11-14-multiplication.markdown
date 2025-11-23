---
layout: post
title:  "Multiplication"
date:   2025-11-14 19:49:00 +0100
categories: main content
---

{% include math.html %}

Turns out that in real life, having to add the same number many times comes up quite often.
Let's say I have eight PCs, each equipped with 16 GBs of RAM. How much RAM do I have in total
(always too little 😢)?
Well, to find out I have to repeatedly add 16 eight times in a row. That is, I need to compute 8 *times* 16.
Multiplication.

This is also kiddie math. You already know that multiplication is a shorthand for repeated addition.
That is
\\[16 + 16 + 16 + 16 + 16 + 16 + 16 + 16 = 8 \cdot 16\\]

The answer is 128, of course:
\\[8 \cdot 16 = 128\\]

## The order of terms

What happens in the case where I have 16 PCs with 8 GBs of RAM each?
To count the total amount of RAM I have now, I have to compute 16 times 8, which is also 128.
In writing, this is
\\[16 \cdot 8 = 128\\]

Similar to addition, swapping the two terms when doing multiplication doesn't change the result.
Here are some more examples:
\\[3 \cdot 5 = 5 \cdot 3\\]
\\[11 \cdot 10 = 10 \cdot 11\\]
\\[3459 \cdot 21356 = 21356 \cdot 3459\\]

You see now that this property holds for addition and multiplication too. It's special. So special in fact,
that it has a name. **Commutativity**. We say that **addition and multiplication are commutative operations**.
You will get to know other commutative operators in mathematics.

Writing this property down with letters is very similar to the addition case:
\\[a \cdot b = b \cdot a\\]

When using letters with multiplication, it is customary to drop the dot between the terms. Like this:
\\[ab = ba\\]
Whenever you see two letters next to each other, it should be interpreted as multiplication.

When $$a = 2$$ and $$b = 7$$, we can substitute into this template to get the statement
\\[2 \cdot 7 = 7 \cdot 2\\]
This is totally the same think as with addition.

## Templates

I want to make one thing clear. **You can substitue arbitrarily complex mathematical expression into
the templates of general properties like the one before**. I've been doing it with single numbers for simplicity,
but there's nothing stopping you from going crazy with it.

Recall the property of addition concerning 0: $$a + 0 = a$$.
We can substitute $$a$$ with simple numbers. We know that. We've seen that before.
For instance, if $$a = 65$$, then plugging it in we get
\\[65 + 0 = 65\\]
This is perfectly fine.

What if I say that $$a = 7 + 2$$? A perfectly reasonable decision would be to just perform the addition.
Essentially, $$a = 9$$, since $$7 + 2 = 9$$. So we plug in 9:
\\[9 + 0 = 0\\]

But what if I forcefully substitue $$a$$ with the addition problem itself without finding its exact value first? Does the
template break down? Take a look:
\\[(7 + 2) + 0 = 0\\]

I use parentheses to indicate that $$a$$ was replaced by an entire expression. The parentheses group the numbers together in the expression.

Is the equation invalid? It doesn't take a big brain to see that it's in fact a completely valid equation. Replacing the parentheses $$(7 + 2)$$
with it's value, 9, we get the same form as before:
\\[9 + 0 = 0\\]

All in all, **it doesn't matter whether we evaluate complicated expression before or after substituting**.

For another example, let's recall the commutative property for addition: $$a + b = b + a$$.
Suppose that $$a = 11 \cdot (3 + 5)$$ and $$b = 2 + 8$$.
Substituting in, I get
\\[(11 \cdot (3 + 5)) + (2 + 8) = (2 + 8) + (11 \cdot (3 + 5))\\]
This is also totally valid. I chose to just plug in the expressions as they are instead of evaluating first.

The fact that you can actually replace the letters in the templates for general properties with
*arbitrarily complex* expressions is one of the hardest things to get used to at this stage, so I'll
be providing plenty of examples.

## Parentheses

What about the parentheses property? As for addition, this was $$a + (b + c) = (a + b) + c$$.
It there a similar property for multiplication too? Well, let's investigate!

Take the following multiplication problem:
\\[3 \cdot (10 \cdot 6)\\]

As with addition, we evaluate the parentheses first, and then the rest.
\\[3 \cdot (10 \cdot 6) = 3 \cdot 60 = 180\\]
I first replaced the parentheses with it's value, 60, and then performed the remaining multiplication.

Let's now move the parentheses one position to the left. This gives us
\\[(3 \cdot 10) \cdot 6\\]
Evaluating this can be done as follows:
\\[(3 \cdot 10) \cdot 6 = 30 \cdot 6 = 180\\]

This confirms our suspicion that the parentheses property holds for multiplication as well.
Here are some more examples to convince yourself:
\\[25 \cdot (4 \cdot 6) = (25 \cdot 4) \cdot 6\\]
\\[3 \cdot (4 \cdot 100) = (3 \cdot 4) \cdot 100\\]

This property also holds for addition, as we've seen. This one is also pretty special, and it also has a name.
**Associativity**. **Addition and multiplication are associative operations**.

With letters, I can write this as
\\[a(bc) = (ab)c\\]

As an example, to create a concrete equation from this template, let's assume that $$a = 7$$,
$$b = 11 + 2$$ and $$c = 49$$.
Plugging these in, we obtain
\\[7 \cdot ((11 + 2) \cdot 49) = (7 \cdot (11 + 2)) \cdot 49\\]

Notice that there is an entire addition problem standing in place of $$b$$. This is completely fine.
Remember that you can substitute the letters in these templates with any complicated expression.

## Multiplication in any order

Just like addition, multiplication can be performed in any order with any number of terms.
For example, these are all equal
\\[2 \cdot (125 \cdot 51 \cdot (11 \cdot 3) \cdot 46) \cdot 5\\]
\\[125 \cdot 46 \cdot 5 \cdot (2 \cdot 11 \cdot 3) \cdot 51\\]
\\[5 \cdot 46 \cdot 3 \cdot (11 \cdot 55) \cdot (125 \cdot 2)\\]

You can change the order of terms, delete or add in parentheses, it doesn't matter. It's all the same.
**You can use commutativity and associativiy to reason through why this is a correct thing to do**,
but let's not waste our time with that.

## Multiplication by 1

Zero is a special number, since it doesn't really have a "value" with respect to addition.
It doesn't contribute to the total. I stated this general property as
\\[a + 0 = a\\]
Of course, since addition is commutative, I could have also said
\\[0 + a = a\\]
since the order doesn't matter 😉. We know that addition is commutative, so we can write it either way.

Is there a number with a similar property for multiplication? One that doesn't change the value of the multiplicand?
Yeah, there is one. And it's *one*.
Look:
\\[1 \cdot 472 = 472\\]
One times 472 is obviously still 472. And it's not hard to imagine that this works for any number.

Using letters to state this general property, I can say
\\[1 \cdot a = a\\]
Since multiplication is commutative, I could also write this as
\\[a \cdot 1 = a\\]

If you think about it, 1 is the only number that has this property. Multiplying by any other number will
surely change the value of $$a$$.

This phenomenon also has a name.
**Zero is the identity element of addition and one is the identity element of multiplication**.
**The identity element for addition and multiplication is unique**, there is no other number that satisfies this property.

As an example, if $$a = 11 + 17 + (6 \cdot 6)$$, then the template evaluates to
\\[(11 + 17 + (6 \cdot 6)) \cdot 1 = 11 + 17 + (6 \cdot 6)\\]

It might be a little hard to see, but this indeed comforms to the template above.

## Multiplication by 0

What should happen when I multiply some number with zero?
For instance
\\[0 \cdot 2 = ?\\]

Let's examine the multiplication table of 2 for a clue!
\\[
    \begin{align}
    6 \cdot 2 &= 12 \newline
    5 \cdot 2 &= 10 \newline
    4 \cdot 2 &= 8 \newline
    3 \cdot 2 &= 6 \newline
    2 \cdot 2 &= 4 \newline
    1 \cdot 2 &= 2 \newline 
    0 \cdot 2 &= ? \newline
    \end{align}
\\]

You can see that as we multiply 2 by smaller and smaller numbers, the result decreases. Specifically,
the result decreases by 2 at each step. This makes sense, since multiplication is technically repeated addition and
at each step, the number of twos we add together decreases by one, so the total decreases by two.

The last step is multiplication by zero. Continuing the pattern, the only thing that makes sense is to
say that the last multiplication is equal to zero.
That is
\\[0 \cdot 2 = 0\\]

This line of reasoning works with any number (try it!). This is another general property, that should be stated using letters
\\[0 \cdot a = 0\\]

Due to commutativity, it's also true that
\\[a \cdot 0 = 0\\]
since reversing the order of multiplication doesn't change the result.

Remember that I can plug in any number in place of $$a$$, even 0 itself. This means that
\\[0 \cdot 0 = 0\\]
which is not that surprising I guess 🤔.

This property also has a formal name.
**Zero is the annihilating element of multiplication.**
Yeah, that's the official name 😼.

# Takeaway

General properties are often so general, that they are true for multiple different types of objects.
A large part of mathematics is generalization. If we know that commutativity is true for addition,
why don't we examine how it behaves with other operations? If zero is the identity element for addition, why don't
we try to find an identity element for multiplication as well? Is there a property that multiplication has
but addition doesn't?

Seeing where a property holds and where it breaks down in different contexts allows us to describe
the property in the most general sense, which is useful and efficient.

