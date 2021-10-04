# Multi-Label-Medical-text-Classification

With the continuous increase in available data, there is a pressing need to organize it and modern classification problems often involve the prediction of multiple labels simultaneously associated with a single instance. Known as Multi-Label Classification, it is one such task that is omnipresent in many real-world problems.

In this project,i have experimented with various deep learning models
and evaluated them for the task of Multi-label text classification. 
To form a comprehensive representation of the texts i have investigate a powerful
and intelligent feature extraction technique based on deep representation,
which is GloVe. To improve the classification system, LSTM is the most natural
sequence processing model capable of learning long-term dependencies
and remembering past data. As a result, i have presented a comparative
analysis of several recent architectures model based LSTM.

The use of fusing the prediction of all classifiers or selected classifiers in
this work was suggested in anticipation of better performance, regardless of
the base used and to better generalize our contribution.

The Ohsumed collection is a subset of the MEDLINE database, which is a
bibliographic database of important peer-reviewed medical literature maintained
by the National Library of Medicine. This dataset is multi-label text
related problem type. The subset we consider is the collection consisting
of the first 20,000 documents from the 50,216 medical abstracts of the year
1991. The classification scheme consists of the 23 Medical Subject Headings
(MeSH) categories of cardiovascular diseases. After selecting such
category subset, the document number is 13,929. The main task was to classify
those categories where the documents can belong to several classes, for example, an abstract can belong to four types of diseases (Classes: C17, C1,
C3, C23). This data collection is available at http://disi.unitn.it/moschitti/corpora.htm.

Dataprepar.ipynb This file is for preparing and converting the dataset from Files to csv forma. if you want the test and train in the same file just merge it.

## The following diagram illustrates the main steps of the approach.

![SHEMAVERSIONFINAL](https://user-images.githubusercontent.com/51234043/135873673-c14bb276-5609-4794-8518-1f34f5b40464.png)
