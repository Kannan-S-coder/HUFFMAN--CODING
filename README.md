# Huffman-Coding

## Aim :
To implement Huffman coding to compress the data using Python.

## Software Required :
Anaconda - Python 3.7
## Algorithm :
Step 1 :
Count the frequency of each character in the input string and store in a dictionary.

Step 2 :
Create leaf nodes for each character with its frequency and store them in a list.

Step 3 :
Build the Huffman tree: repeatedly merge the two nodes with the lowest frequencies into a new node until only one tree remains.

Step 4 :
Generate Huffman codes recursively: assign '0' for left branches and '1' for right branches, storing codes for each leaf character.

Step 5 :
Display the Huffman codes for all characters in a tabular format.
