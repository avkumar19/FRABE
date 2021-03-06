# FRABE
______________________________________________________________________________________________________________________________________________________________
## The thought behind the project.

Biological research journals are kept in specialized online repositories. Due to rapid research activities from the last two decades, the number of documents that resides in these repositories is too voluminous, that makes it impossible for the human being to extract knowledge from them. An intelligent automatic information system is thus needed, which can do the task effectively and efficiently. Most of the existed relation extraction systems extract binary relations in the vicinity of single sentence only, some of them use term-occurrence but fails to achieve high recall. There are also some other complicated relation extractors, but they offer an only specific type of relations such as protein-protein interactions, molecular pathways and other few.
Moreover, these relation extractors deal with many false positives due to working with the predefined rule set only. The proposed system “finds the relations among biological entities from Medline abstracts (FRABE)” taking ontology tagged text corpus as input and mine binary relations from the text at concept level rather than entity level. It combines text mining with natural language processing (NLP) to handle both binary and complex relations through natural language queries. Dependency parsing is used to take care of dependencies between entities that are distantly apart from one another. In this paper, an efficient complex relation extraction algorithm is proposed which takes binary relations from the database and plot those as binary tree forests to extract path between target entities which implies a complicated relationship between them. The experimental results on Genia corpus achieve both high precision and recall values.

## ScreenShots of the GUI
### Search Module API
![Search Module API](https://github.com/avkumar19/FRABE/blob/master/Screenshot%202020-11-07%20at%2012.22.12%20PM.png)
![Relation options](https://github.com/avkumar19/FRABE/blob/master/Screenshot%202020-11-07%20at%2012.39.05%20PM.png)
### Results along with Medline data ID and Title
![Search Module API](https://github.com/avkumar19/FRABE/blob/master/Screenshot%202020-11-07%20at%2012.22.45%20PM.png)
