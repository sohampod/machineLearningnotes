Model Representation I

Let's examine how we will represent a hypothesis function using neural networks. At a very simple level, neurons are basically computational units that take inputs (dendrites) as electrical inputs (called "spikes") that are channeled to outputs (axons). In our model, our dendrites are like the input features x1⋯xnx_1\cdots x_nx1​⋯xn​, and the output is the result of our hypothesis function. In this model our x0x_0x0​ input node is sometimes called the "bias unit." It is always equal to 1. In neural networks, we use the same logistic function as in classification, 11+e−θTx\frac{1}{1 + e^{-\theta^Tx}}1+e−θTx1​, yet we sometimes call it a sigmoid (logistic) activation function. In this situation, our "theta" parameters are sometimes called "weights".

Visually, a simplistic representation looks like:
[x0x1x2]→[   ]→hθ(x)


If network has sj​ units in layer j and sj+1​ units in layer j+1, then Θ(j) will be of dimension sj+1​×(sj​+1). ***