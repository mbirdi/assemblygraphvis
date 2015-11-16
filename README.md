Let's solve a visualization problem important to biology together. 

In Genomics we can assemble all the sequencing reads from a genome to try to reconstruct the full genome. When the genome includes large repeats that create ambiguities, we cannot produce the entire genome correctly as a single string of output text. Inside assembly software, a graph is produced, and then to output this into a format called FASTA with individual strings, the graph is chopped up at every site of ambiguity. 
The goal of this project is to work with the graph itself such that the connecting information between sequences is not lost. For biologists to be able to use the graph, one important aspect is simply to visualize it. 

Specifications for the graph:
Each node is a sequence of DNA (made up of A,T,C,G). It can have connections on either the start or end of the sequence, meaning it is useful to represent the graph with each node having two ports (start and end), and the edges can connect to either the start or end ports of a node. The edges themselves are undirected because DNA can be read in either the forward or reverse directions. 

Visualization goals:
Overview, zoom and filter, details on demand. 

 
Email maria.nattestad@gmail.com or tweet @marianattestad with questions or to chat about how you can contribute to this project. 
Pull requests very welcome. 

