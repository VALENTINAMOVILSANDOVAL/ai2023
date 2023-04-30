# AI Mindset: Insights from EAFIT's Course on Artificial Intelligence

Hey there! 

Welcome to my AI hub! I've got a whole bunch of cool AI stuff for you to check out. The idea behind this is to share what I've been learning and get some feedback on my work. So let's dive in and see what we can discover together!

-Valentina

# Content

- Neural Nuggets: Bite-sized Brainy Bits

# Neural Nuggets: Bite-sized Brainy Bits

## Meet the Perceptron

The perceptron is like a computer's version of a real brain cell. It's a super important model in AI because it was the first neural network that we could actually use for computing. So, it's like the OG neural network, you know? It's kind of like a baby step towards making machines that can think and learn like us.

## How Your Brain Actually Works: A Peek into Neural Networks

The brain's neural network is basically a cluster of nerve cells called neurons. These neurons receive electrical signals from their neighboring neurons through dendrites. Once the sum of these signals reaches a certain level, the neuron shoots out its own electrical signal via axons, which are connected to other neurons' dendrites. The connection point between two neurons is called a synapse, and usually, each neuron connects to around 7,000 of them. When we learn new things, the synaptic strength between the neurons representing those things becomes stronger, in accordance with Hebb's rule (1949), which states that "Cells that fire together wire together".

## Math for Nerds: Basic Fundamentals of Neural Networks

(This section is still a work in progress)

The Perceptron Model is a simpler artificial version of a biological neuron. It's got $m$ binary inputs, labeled as $x_1, ..., x_m$, which basically means signals coming from neighboring neurons. The perceptron processes these signals by doing some math magic, where each input is multiplied by a weight $w_i$ that represents the connection strength. This eventually leads to a single binary output, labeled as $o$, which tells us if the perceptron is "firing" or not.

But wait, there's more! To make sure our inputs $x_1, ..., x_m$ (which are basically the features in our data) match up with the output $y$ (which is the label), we need a special input neuron called the bias neuron. Its connection weight is either shown as $b$ or $w_0$, and it always gives an output value of 1 (if the net input goes beyond a specific threshold value $\theta$).

So basically, we have the inputs, the weights, the net input ($z$), the activation function $f(z)$, and the output ($o$). A picture that shows all of this is given below:








## References






