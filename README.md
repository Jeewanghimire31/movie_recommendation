## movie_recommendation

# Overview 
This is a project of Movie Recommendation using the tmdb datasets.<br>
This Project of recommendation is based on the Content Based Recommendation system.


# Steps used in this Project
### It is based on Content Based Filtering.
Content Based Filtering works in a way such that if you are looking for a product and in the description of the product certain params are mentioned like material it is made up, durable, water resistence or not etc...
The content based filtering will look for all the other products whose description matches with this product description(not all the word to word) But it will takes some params word of the Description.

### TF `*` IDF Algorithm 
TF = Term Frequency
It is the how many times the word is mentioned inside the document which is divided by the total number of term in the document.
i.e. Average Number of times a particular word occur inside the Document.

IDF = Inverse Documnet Frequency
It is the measure of how significant that term is in the whole overview/document.


### Vector Space Model
Then we will construct matrix of vector that contains the words. 
In this particular model, we store each items as a vector of its attribute which basically is another vector. It is n dimensional space.
The angle between the vector are calculated to determine the similarity between the vector.


### Calculating the Cosine Similarity.
For this process we can also use, other similarity algorithm as:
`Euclidean Distance.`
`Manhattan Distance.`
 
After creating a vector space for our words, we will look for the similarity of two words, if we have two words like women and queen instead of man and queen,
the word women and queen are more similar to each other.
like that: Cosine similarity is a metric, helpful in determining how similar the data objects are irrespective of their size.
We can measure the similarity between two sentence using cosine similarity in Python.
In cosine similarity, data objects in a dataset are treated as a vector. The formula to find the cosine similarity between two vectors is –<br>

Cos(x, y) = x . y / ||x|| * ||y||<br>
where,<br>
x . y = product (dot) of the vectors ‘x’ and ‘y’.<br>
||x|| and ||y|| = length of the two vectors ‘x’ and ‘y’.<br>
||x|| * ||y|| = cross product of the two vectors ‘x’ and ‘y’.<br>

These steps are all done step by step on the code above.


## Codes Content
For the Dataset it is done by using TMDB 5000 dataset from the kaggle and this project is also done in the kaggle notebook.

can also be viewed here: https://www.kaggle.com/jeewanghimire
