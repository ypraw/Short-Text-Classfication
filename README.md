# Implementation of K-Nearest Neighbor Algorithm Using Term Weighting TF-IDF to Categorize the Title of Bachelor Thesis at Department of Informatics of Dian Nuswantoro University

## Abstract
_The Dian Nuswantoro university library has very significant growth of electornic documents, especially the mini-thesis documents. This makes it difficult to categorize and organize the documents, especially the documents which can be used as a reference for further research.  In addition, these documents are text that has a large data ratio. Text mining is one of the solutions which can categorize all documents automatically, making it easier to divide the document based on its category. The implementation of digital computing in this research uses K Nearest Neighbor algorithm and word weighting method TF-IDF  to categorize the final assignment document based on its title. The word weighting method  TF-IDF and K Nearest Neighbor Classifier are able to classify the final assignment categories, evidenced by the accuracy value, precision value and recall value of 75% each._

# Data Source
**_This program based on my research for Bachelor program on my University. The data used is the original Title of Bachelor Thesis at Department of Informatics of Universitas Dian Nuswantoro that has been edited for some content for publication purposes._**

# Design of System
*  TEXT ANALYSIS

    * Having a peek at the Data
            - Total of Data
            - Total of Categories
            - Total Range of Graduation years

*  TEXT TRANSFORMATION

    * Data Cleaning (Removing unimportant data/ Stopwords/ Stemming)
            - Stopword term of Data
            - Stemming term of Data

    * Converting data into a model usable format
            - Convert to TFIDF vector

*  MODEL APPLICATION

        - Analyzing of K value for determine The Best K value
        - Classification KNN with Best value of K
        - Evaluation Overview Using Accuracy, Recall and Precision

# Implementation

- Please make sure you have installed python 3 on your devices, if not, you can download here [python.org](https://www.python.org/downloads/)
- if you using linux or mac, which is have installed python, make sure you create virtual env for better managing packages on your python system.
- install the `requirements.txt`
```bash
pip install -r requirements.txt
```
- open jupyter notebook on your terminal
```bash
jupyter notebook
```
- open MainAPP.ipynb on your browser.


## License
This program licensed under [MIT License](LICENSE.md)

And in the name of *SCIENCE*, you *MUST* reveal what you have *FOUND* or *THE TRUTH* will be *PERISHED*

_Semarang - Indonesia, March 2020_