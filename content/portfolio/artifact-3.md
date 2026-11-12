+++
date = '2026-11-12T13:45:16-06:00'
draft = true
title = 'Artifact 3: Explaining Neural Networks'
+++

# Introduction and Description

In this assignment, I reviewed how neural networks function, composed an article to explain this concept, and discussed with my classmates about the quality and effectiveness of our articles. 

# Objective

The objective of this assignment is to create a explanation about neural networks in machine learning. It should be simple, yet effective at communicating the idea. 

# Value Proposition

This activity strengthens my understanding of the working principle of neural networks that lie in the center of machine learning concepts, and exercises my ability to communicate a complex idea in a simple, easy to follow manner. 

# Process

## Step 1: Research

Despite having some previous understanding of neural networks, I decided that the best thing to do was to refresh my knowledge and correct any misconceptions on my end. 

## Step 2: Composition

After watching some videos from 3Blue1Brown, I confirmed that my knowledge was mostly correct, and began writing the article. 

## Step 3: Revision

To ensure accuracy, I entered the article to Claude to check for errors. It pointed out some grammatical errors and knowledge inconsistencies. I then proceeded to revise the article based on its suggestions. 

## Step 4: Discussion

The last part of the assignment was to review articles written by my classmates, and comment on the effectiveness and quality of the communication for learning. I was glad to see that everybody had different approaches to explain the topic. 

# Result

Here's the explanation article I composed: 

The structure of a neural network is inspired by the structure of a biological brain. In a brain, countless neurons are wired together. Each neuron is a cell that takes the signal from many other neurons as its input, and generates one main output signal that is then sent to multiple other neurons. By having billions of neurons, complex behavior and thought can occur.
Translating this to a digital form, imagine you have a column of numbers, which represent the input. Then, add another column of numbers, the values of which are calculated based on the numbers in the previous column. This is a layer of the neural network. We can continue to add more columns of numbers (layers), each storing the calculation results based on the values from the previous column (layer). Finally, the values of the numbers in the last layer are what we want as the output of the neural network. We call the length of the columns the width of the network, and the number of columns the depth of the network. The width and depth can be chosen based on application. Each number in a column is a neuron. 
As for how the outputs of neurons are calculated, imagine you are a neuron in a layer, you can see all the values from the previous layer, and have a predetermined number (called weight) to multiply onto each of them. Then, you add all the multiplication results together, and pass the result through a function, called the activation function, so that the resulting value is not too off-the-chart. Of course, all other neurons in your layer do the same thing, but with their own unique weights. All neurons in the following layer can see your output as well, as they use yours, and the output of all other neurons in your layer to multiply, and sum, to get their outputs.
Now, how do you find good weights? To start, we choose random values, and the network’s output is complete garbage. Then, we show it examples from the training data, and measure the error by comparing the garbage output with the correct output. We then adjust every weight slightly in a way that will result in lower error. By repeating this process, the weights get gradually adjusted so that the result matches with the training data better and better. This is the “learning” part of machine learning. 

# Tools and Technologies Used

I used Claude from Anthropic to revise the article. 

# Recommended Resources

I highly recommend the following resources as related, additional reading: 

But what is a neural network? | Deep learning chapter 1 - 3Blue1Brown

https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi

{{< youtube aircAruvnKk >}}

Gradient descent, how neural networks learn | Deep Learning Chapter 2 - 3Blue1Brown

https://www.youtube.com/watch?v=IHZwWFHWa-w&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi

{{< youtube IHZwWFHWa-w >}}