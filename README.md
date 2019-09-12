# Nested Data Structures to Insights

## Introduction

By now you've seen the power of nested data structures (NDS) to represent the
world around us. NDS' are giant collections of facts, like an encyclopedia. We
have to take the knowledge from an encyclopedia and do work with those facts to create
new _insights_.

For example, by researching Colombia, the history of soccer, and South
American history, we can write a report about "Soccer in South America." We can
_synthesize_ facts into _insight_.

We do the same with NDS'. By applying code to NDS', we can _synthesize_
insights from the raw facts contained in the NDS.

Here are some examples:

* "What's the average age of people in the NDS representing a class?"
* "How many pieces of candy are in this vending machine?"
* "In what year will most of my employees reach retirement age?"

But sometimes it can be downright scary to get started. You get a big old blob
of `Array` of `Hash` of `Array` of `Array` literals and you get stuck. Never
fear!  In this lesson, we're going to show you a process that will help you get
started whenever you have an NDS that you need to process for insights.

## NDS to Insight Strategy

1. Understand the NDS
  * Pretty-Print It with `pp`
  * Print Arrays
2. Use `[]` to verify your understanding from Step 1
  * Print values to verify your understanding
  * Leave code comments and documentation for yourself
3. Wrap uses of `[]` from Step 2 into new methods
  * Create simple methods with meaningful names ("First-Order Methods")
  * Ensure "First-Order Methods" use arguments to create flexibility
4. See-saw between bottom-up and top-down method writing
  * Write a method that provides an insight e.g. `oldest_student`
  * Evaluate your First Order Methods
  * Can you use your First-Order Methods to build the insight method's
    implementation?
    * **YES**: Great! Your method is done!
    * **NO**: Build a new method that combines _other_ methods to get closer to what the insight method needs. Repeat step 4
5. Insight method provides an insight! We're done!

We recommend printing this list out and keep it handy as you complete labs that
require you to transform NDS' into _insights_.

## Conclusion

In Renaissance Florence, a large block of marble sat for twenty-six years,
unfinished. Rain, sun, snow, it sat because no one was brave enough to face
such an enormous task.  It took a person of courage and conviction to make that
first chip in it. His name was Michaelangelo Buonarotti. "The Giant" became the
masterpiece, "David." Starting large programs can feel like facing "The Giant."
This process gives you the confidence to make the first chip.

At Flatiron School, we've seen that most students get the basics of programming
easily: variables, statements, loops, all that. But what stymies ***all***
developers &mdash; all _creators_ as the story of "The Giant" demonstrates
&mdash; is not being able to get started. This strategy is designed to help you
get over that initial activation energy and get on your way.

While it might feel silly to think this carefully about process, we can promise
you that students who have process don't get overwhelmed and give up before
they've even begun. Take this process seriously, and you'll find yourself
vaccinated against "getting started" anxiety! 

Let's learn to make masterpieces.
