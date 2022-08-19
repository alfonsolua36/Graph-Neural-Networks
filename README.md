# Graph Nueral Networks

## Introduction

Here you will find articles and slides that I have compiled and used for Graph Neural Networks. These research papers were used for research during my time at UCLA. In addition, there is CNN code that you can utilize. Make sure to install the dependencies before using it. 

## Graph

A graph in computer science is a way to structure data. It consists of nodes to represent entities, and edges that represent the relationship between these entities. Further, each node may also have a set of features that may describe that node. As for edges, they can either be undirected [two-way] or directed [one-way]. So to put this into picture graphs could be described as 

- Graph=(Node, Edge)

## Neural Networks

Neural Networks are able to learn a variety of desired outputs from several kind of inputs which can come in the form of numbers, stock prices, words, images, etc. This type of neural network works best for data that is structures, However, one downside is that neural networks struggle with graphs that don't have a fixed structure like the examples above. This is where we stepped in and did research on things of this nature. 

## 
ational Neural Networks

### Images

Convulutional Neural Network is a method used to analyze different inputs. For instance, it could extract information on an image by looking at each indiviudal pixel and the region around it and aggregating the information. The next layer will then extracts information about that region and the process continues until the network is able to reason over different parts of the whole image. After that, the Neural Network utilizes linear combinations to identify the object.

![Convulutional Neural Networks](images/cnn.jpeg)


### Graphs
 
You can view an image as a special type of graph. It is a grid graph that is structured and every node is a pixel connected to its 8 nieghboring pixels. We then could perform the same process in a normal image to this graph and obtain the desired output. One application of this could be a dating app where individuals, represented as a node, have certain features that describe the individual. We can then use a CNN to gather information and find a suitable match. 

## Final Thoughts

Feel free to leave a message regarding any of this or your thoughts on this. Till next time!
