# Lithium-Search
1.Run the first chunk of the notebook starts with "
from bs4 import BeautifulSoup
import requests
import numpy as np
import re
import pandas as pd

import csv
comp_relations = []
with open("/content/drive/MyDrive/FinTech/data/relationsUnique.txt") as f:
 lines = csv.reader(f,  delimiter=' ')
 count = 1
 for line in lines:
   c = "C" + str(count)
   comp_relations.append([c,line[2],line[5]])
   count = count + 1

#unique "P"s"

2.Jump to the Graph Build Section

3.Run the chunks one by one, remember replace the file location, for example, "
wiki_relations = loadRelationCSVFile('/content/complete_relations_list_10051.csv')"

4.Ignore the section of "Graph aggregation intro",  "Get Familiar with SGN, simple graph network task", and "GCN Application, wrap up on tf", 
and run chunks in "GNN on the homo graph of our data" and other remaining chunks in the following sections. Be sure to check the file path of "Lithium_futures_price_2017-2022.csv"
and "10051_homograph_LSTM_embeddings_2014-2021.csv"
