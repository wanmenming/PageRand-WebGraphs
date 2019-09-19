1.For task 1 to creat G1 and G2, here are two options:

In the webGraphs folder:
a. Run crawler_hw2.ipynb to get 1000 url documents first: 
   In the "set Threshold here for key word variation" cell: set folder name for documents. i.e. "G1" for G1 documents; "G2" for G2 documents; 
   After running "Entrance of create G1" cell and "Entrance of create G2" cell, we will see 1000 url documents in G1 folder and another 237 url documents in G2 folder

b. Use the url documents I prepared in the folder webGraphs: doc1 and doc2. 1000 urls are in G1Frontier.txt and 237 urls in G2Frontier.txt. docIdmap.txt is the map from Documented to full url (use for creating G1)

Then run webgraphs.ipynb to get G1.txt and G2.txt in graph folder. Additionaly, sub-folder task1 of folder pageRank include the simple statistics for G1 and G2

2.For task 2
In the pageRank folder, Run pageRank.ipynb to get pagerank.txt, G1statistics.txt, G2statistics.txt, pageRank.txt and L1_norm.txt. I put them into folder task2.

3.For task3
In the experiment folder, set “d=0.5" or “d=0.65" or “itera_count = 4” in the global setting cell (first part of my codes). Also remember switch filename and N there.
My result in different folder: task3.1, task3.2 and task3.3.