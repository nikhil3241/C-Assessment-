# C-Assessment-
Dictionary Assessment Programs

Bobble AI Assignment
Assignment project for campus-recruitement drive of Bobble.ai

About the assignment
The assignment had two problem statements, and both of the problems were related to trie data structure. The assignement solution had to be written in C++.

Parse a dictionary (in CSV format) which contains words along with their occurrence frequencies. This trie data structure's object instance should be serialized so that later search operations can be directly performed on this trie data structure rather than building it again and again from the original CSV file.

A dictionary of words is given, with all the words indexed from 0 to N (where N is the total number of words present in the dictionary). Store these words in a trie data structure so that a search operation can be performed on the index which will return the actual word itself.

How to compile & run the assignment?
Clone the repository and move to project's root directory:

git clone git@gitlab.com:saranshabd/bobble-ai-assignment.git
cd bobble-ai-assignment
Make sure you are using a Linux environment to run this project. In case you are using another operating system, use the following command to run an Ubuntu 18.04 image inside a Docker container:

docker run -it --rm -v $(pwd)/NodeTest:/usr/src/app ubuntu:18.04 bash
Run the following command to build binaries of the assignment project files:

make build
Once the binaries have been created, you can run the solution code of each of the assignments using the following commands:

Dictionary to Trie conversion
./dict_conversion.out $(word-to-search)
Reverse searching
./reverse_search.out $(index-to-search)
