# Social network project

## Overview

The aim of the project is to provide descriptive analysis of a social network. Available options: 

- Your ego network. Nodes are your friends except you, edges are friendship. Edges are directed in a case of follower/following relationship. The network size is at least 100 nodes.
- Community network. Nodes are public communities such as VK groups or facebook pages, edges are references between communities. The network size is at least 300 nodes.
- Communication network. Nodes are users, edges are messages. Examples: edges are replies in a chat with many members, edges are conversation among users in the same post in a public community, edges are retweets or quoted tweets. The network size is at least 300 nodes.
- Co-occurrence network. Nodes are hashtag, edges are publications in which two hashtags co-occur. The network size is at least 1000 nodes.

Collect the data from an online social service such as VK, OK, facebook, instagram, twitter, youtube, tiktok, telegram, discord, slack, etc. The data can be collected by API or by auxiliary services or by web scrapers such as selenium. Then, provide code for analysis and prepare a presentation. Presentation should contain key interpretable results.

## Submission

Submit following files:

1. Presentation in pdf format. Presentation should be **10-15 slides**, with estimated duration of oral presentation **5-7 minutes**. Slides are in Russian or English. 
2. Source code with comments in ipynb format (py and other languages are also possible) 
3. Source code with comments in pdf format 
4. Additional data, if needed

Deadline for submission is **April 30, 23:59**. All the files should be send to **networksciencecourse@gmail.com** with the topic: [HSE NS 2022] Surname Name SN Project. For example:

> Topic: [HSE NS 2022] Ivan Petrov SN Project
> 

> Attached: Petrov_presentation.pdf, Petrov_source.ipynb, Petrov_source.pdf, additional data
> 

Do not use filenames without your surname. In a case of large files, upload the files to a cloud service (yandex.disk, dropbox, etc.) and send the link, the service should display uploading date and time.

## Content suggestions

Network summary

- Network source and the description of preprocessing steps.
- Type of the graph: directed/undirected, heterogeneous/homogeneous, weighted/unweighted, etc.
- Node/Edge attributes.
- Number of nodes and edges.
- Diameter, radius.
- Clustering coefficient (global, average local, histogram).
- Average path length (histogram).
- Degree distribution, fitted models by regression/MLE/KS-test.
- Gorgeous network layout. Try to show that your network has some structure, play with node sizes and colors, scaling parameters. Tools like Gephi may be useful here.

Structural Analysis

- The closest random graph model similar to your social network. Compare models from lectures, such as ER, BA, WS. Check real-world network properties on chosen random graph models and your network, compare the results.
- Degree/Closeness/Betweenness/Katz/Eigenvector centralities, top nodes description.
- Page-Rank/HITS in a case of directed network, top nodes description.
- Correlation comparison of centralities.
- Assortative mixing by node attributes and node degree.
- Node structural equivalence/similarity.

Community Detection

- Clique search, k-cores visualization.
- Best results of various community detection algorithms, both in terms of interpretation and some quality criterion (modularity, silhouette, ground truth partition).
- The results should be visible on the network layout.

## Shortcomings

Frequent shortcomings that can lead to a lower score:

Presentation

- No presentation in pdf format
- Font of the text or the labels is too small and unreadable
- Too many labels on the graph, they overlap and become unreadable
- Too many entries in the matrix/table, which makes them unreadable
- An important part of the visualization is missing, for example, highlighting the color or size of the nodes on the slide with centralities
- Absence of important labels where it is necessary, for example, axes on graphs are not signed
- Numerical data on the slides are presented in an unreadable form, for example, too many decimal places
- No key comments on the slides
- Too many comments on the slides, the main thing is not highlighted
- Comments are inappropriate, for example, fragments of biography, dry facts, definitions, network properties are not presented
- An important part of the analysis is missing, for example community detection
- Too much attention is paid to non-network properties, for example, distributions by cities/universities
- Careless visualization of the graph, for example, the nodes size is too large and overlap
- Low resolution or cropped pictures
- Allocation of communities by the “trembling hand”

Code

- No code in pdf format
- There is a code in pdf format, but the formatting is broken, for example, blocks of text did not fit on the page
- No explanatory comments, difficult to read
- A lot of garbage in the code, for example debugging messages

Interpretation

- No explanation why this or that random model works better/worse on your graph
- No explanation why these or other people got into the top of the centrality, instead of life stories
- No interpretation of the centrality correlation
- Incorrect interpretation of the assortative mixing, for example, “there are few girls in the graph, so the assortative mixing for girls turned out to be low”
- No explanation why the degree distribution of the network is similar or not similar to Power law
- Incorrect interpretation of centrality values, for example, “this person has a high page rank value because we often communicate”
- No explanation why one or another clustering algorithm works better/worse on your graph
