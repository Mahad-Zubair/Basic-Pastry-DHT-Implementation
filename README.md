# Basic-Pastry-DHT-Implementation
The code shows a basic implementation of the DHT protocol, it consists of different functions, and classes.

The Implementation is based on the guidelines and notes taken from the Lecture, the internet and from the provided pastry.pdf.

The code follows Object-Oriented Principles with the main functions included in a class called Pastry. The functions include:

An __init__ function that helps initialize a node with an Id, it’s coordinates/position, the total number of nodes in the network, and allows the node to join the network by finding the closest node to itself.

The Add function helps the network to add elements into the node using the “. append” function.

A join function that handles the joining of the new node to the network, and updates the leaf sets, neighboring sets, and routing table respectively

A routing function that helps to find the closest node based on the given criteria

A function that helps update the values of the left and right leaf sets of the node

Similarly, a function that helps update the neighboring nodes and the routing table as the program proceeds.

A delete function to remove a node from the Pastry network and update the nodes affected accordingly.

A routing data function is used to stimulate the current node to a target node, updating the hop count and maintaining a list of all the nodes encountered.

The main function allows the user to interact and helps in creating and maintaining the Pastry network. 
#-------------------------------------------------------------------------------------------------------------------------------------------------------------#
When executed it allows the user to select from the five given options:

Press 1 to exit the program

Press 2 to delete nodes from the network

Press 3 to add elements to nodes

Press 4 to print the details of a specific node

Press 5 to perform lookup queries to find the number of hops required to reach the targeted nodes from the node user entered.

Most functions that deal with the functioning of the program are included in the Pastry Class.

Whereas some functions are defined on their own to help perform the Pastry DHT better.
