# IR-Project
IR Course projects - Building a Wikipedia Search Engine.
In this project we built a search engine on more than 6M wikipedia docs.
Institute: Ben Gurion University of the Negev.
Professor: Nir Grinberg
Students: Beni ifland, Itay Saig
This repository includes the following files:
1. Create_Indices.ipynb - A notebook we ran on GCP to build our indices.
2. IR final project 2022-2023.pdf - assignment given by the course staff.
3. IR project Presentation.pptx - small and funny presentation for peer evaluation.
4. Inverted_index_gcp.py - A python script given by the course staff with an implementation of an Inverted Index class.
5. new_train.json - an updated training set provided by the course staff, this is a json file with queries and top (most relevant) wiki pages excpected.
6. run_frontend_gcp.ipynb - a notebook to run tests on the whole corpus on a gcp cluster.
7. run_frontend_in_colab.ipynb - a notebook to run tests on a small corpus (1000 docs)
8. search_frontend.py - the backend python script for querying our search engine, containing 5 methods of querying: wiki doc body, wiki title, wiki anchor text, pagerank, # of page views and more helper functions which we united to a general search wuery function.
9. updated_inverted_index.py - an updated class of Inverted Index with some more functionalitis.
10. 10. run_queries.py - a notebook that contains a code provided by teh course staff that implements Map@40 score and an iterative process to run the queries in the training set, calculate scores and measure times.
