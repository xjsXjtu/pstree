# pstree
Personal Skill Tree, defined by DOT language and rendered by Graphviz.

0. Overview
----
This repo is used to track the high-level picture of my knowledge base. 

Basically it shows what I am/not good at.

    - [Green] What areas I have know deeply

    - [White] What areas I know broadly 
    
    - [Red]   What areas are considered to be important, and plan to do a project recently

1. How to update the graph
----
This graph is defined by DOT language and rendered by Graphviz. 

I am using Ubuntu. Steps are:
    
    - Install Graphviz. $ sudo apt-get install graphviz
    
    - Update graph.dot, according to DOT language specification
    
    - Generate png PS tree by graphviz. $ make
