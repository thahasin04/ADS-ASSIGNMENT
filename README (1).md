***Named Entity Recognition (NER) Script***

**Overview**

Named Entity Recognition (NER) is a fundamental Natural Language Processing (NLP) technique used to identify and categorize named entities within text. These entities can include names of people, places, organizations, dates, and more. The NER script provided here utilizes the spaCy library to recognize named entities in a text document.

**Usage**

1.Ensure that spaCy is installed by running pip install spacy.

2.Download the English language model "en_core_web_sm" by running python -m spacy download en_core_web_sm.

3.Modify the input and output file paths in the provided Python script to match your setup.

4.Execute the script, providing a text document containing 200-300 words as input.

5.The recognized named entities along with their labels will be written to the specified output file.



***Karate Club Network Analysis Script***

**Overview**

This Python script analyzes Zachary's karate club network, which is represented as a graph in the "karate.gml" file, using the NetworkX library. The script performs various analyses on the network, including calculating centrality measures, identifying communities, and more.

**Usage**

1.Ensure that NetworkX is installed by running pip install networkx.

2.Download the "karate.gml" file from the repository and update the file path accordingly in the script.

3.Execute the script to perform the following tasks:

    *Create a graph from the "karate.gml" file and display basic information about the network.

    *Store metadata of actors in the network.

    *Calculate centrality measures (degree, betweenness, closeness, eigenvector, and pagerank centrality) and provide an       analysis based on the centrality values.

    *Find possible k-components of the network and compute the clustering coefficient.

    *Identify communities using the Girvan-Newman algorithm and Louvain method.
