# What is machine learning?

Before we move to discussion about deep learning. Let's understand what is machine learning. Deep learning is a subfield of machine learning.

Here is how Herbert Alexander Simon \(Turning and Nobel Prize winner\) defined it:

> Learning is any process by which a system improves performance from experience.
>
> Machine Learning is concerned with computer programs that automatically improve their performance through experience.

Let's have a look at a simple machine learning problem to see what it all means:

#### Example task:

---

Given measurements of an unknown Iris flower's petal and sepal **identify the species of the plant**.

![](/assets/Iris flower sepal and petal.png)

#### Experience \(in the form of dataset with known answers\)

---

We have known information of lots of Iris flowers. This the experience that machine learning will use to improve its performance on the task of identifying species.

![](/assets/Iris table.png)

#### Performance

---

To see if machine learning improves on the performance we must define performance for our algorithm.

In this example a simple way to define performance would be accuracy of correct answers on a set of flowers that are not in the experience \(training dataset\) of machine learning algorithm.

