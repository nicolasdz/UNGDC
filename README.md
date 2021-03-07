# UNGDC

The UN General Debate (UNGD) is the annual high-level event where each UN member state can address all the others.  The UNGD Corpus (UNGDC) provides the English-language text of speeches from 200 countries between 1970 and 2018: some 8,093 speeches in total.

The UNGDC dataset was created by Slava Jankin Mikhaylov, Alexander Baturo, and Niheer Dasandi in 2017.  See their [Github repository](https://github.com/sjankin/UnitedNations) for the latest version.  You can also find all of their replication materials on this [webpage](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0TJX8Y).
The 2017 article they published in the journal <i>Research & Politics</i> which draws upon the dataset can be found [here](https://journals.sagepub.com/doi/full/10.1177/2053168017712821) (pay-walled).

In this repository, I provide a simple Jupyter notebook demonstrating how the dataset can be used to analyze and visualize trends in global diplomacy. It employs the Pandas and SpaCy packages to do some simple NLP on the dataset, with three major applications: tracking topic mentions across countries; tracking topic mentions over time; and performing semantic similarity analysis.  At a later date, I hope to add a demonstration of how named entity recognition can be used to visualize the UNGDC as a network.
