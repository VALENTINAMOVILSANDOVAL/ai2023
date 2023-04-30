# Artificial Intelligence EAFIT

Hey, welcome! This is my AI repository. I've got a bunch of AI algorithms lined up for ya. The whole point of this is to share the knowledge I've been gathering and get some feedback on my work.

Let's do it!

# Content

Supervised models:
- Neural networks

# Supervised models

## Neural Networks

### The Perceptron

The perceptron is a computational model that was developed based on the structure and function of a biological neuron. It is considered to be the first neural network model used for computation and served as a significant breakthrough in the field of artificial intelligence.

#### Biological Neural Works

A brain's neural network is basically a bunch of nerve cells called neurons. These neurons get electrical signals from their neighboring neurons through dendrites. When the sum of these signals gets high enough, the neuron shoots out its own electrical signal via axons, which are hooked up to other neurons' dendrites. The connection point between two neurons is called a synapse, and usually each neuron hooks up to around 7,000 of them. When we learn new things, the synaptic strength between the neurons representing those things gets stronger, following Hebb's rule (1949), which says "Cells that fire together wire together".


#### The Mathematical Model

The Perceptron Model is a simpler version of a biological neuron and was first introduced by Frank Rosenblatt way back in 1957. Take a look at the figure below, it gives you a side-by-side comparison of the structure of a biological neuron and an artificial neuron. Oh, and by the way, the perceptron has m binary inputs labeled as $x_1,..., x_m$. These inputs come from neighboring neurons and indicate the signals received. And finally, the perceptron produces a single binary output marked as $o$ which shows whether it's "firing" or not.


![image](https://user-images.githubusercontent.com/50112524/235356715-f329cd01-2b53-4e7d-bb7c-a3f993ae7acb.png)



### To consider:

The perceptron first computes the weighted sum of its incoming signals, by multiplying each input by its corresponding weight. This weighted sum is often called
net input and denoted by $z$, which is defined as:

$z=\sum_{i=1}^{m} \omega_i x_i$


## Referencias

[1] Niti Sharma. (2018, March 2). Perceptrons: The First Neural Network Model. Towards Data Science. https://towardsdatascience.com/perceptrons-the-first-neural-network-model-8b3ee4513757




