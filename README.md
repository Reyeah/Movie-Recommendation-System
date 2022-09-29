
## Movie Recommendation System

To build a recommendation system using Cosine Similarity

* Recommendation Systems work based on the similarity between either the content or the users who access the content.

* There are several ways to measure the similarity between two items. The recommendation systems use this similarity matrix to recommend the next most similar product to the user.
### Code Requirements
You can install Conda for python which resolves all the dependencies for machine learning.

**Here are some important libraries:**


```python import pandas as pd

import numpy as np

from sklearn.feature_extraction.text import CountVectorizer

from sklearn.metrics.pairwise import cosine_similarity
```


### DataSet

[TMDB 5000 Movie Dataset](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa1dSU2V0d1YwT3R4NzhtU2JETXVnMUdVOVhBd3xBQ3Jtc0ttLWYwdTE5VmJEenpGcEFDODBnSzhydVMtdG9LaVFZNlJLLWZqSG9iMDkyd01SRWVscVVSdTJWWVRsUTdPZzYtSVRPR1k2Z2w4S3NYaXl3TEYzcE1SdldpYnlpS2plN0FhUWwtWEZYZVdjUUhyZFBrVQ&q=https%3A%2F%2Fwww.kaggle.com%2Ftmdb%2Ftmdb-movie-metadata%3Fselect%3Dtmdb_5000_movies.csv&v=1xtrIEwY_zY)


### License

[MIT](https://choosealicense.com/licenses/mit/)


### Cosine Similarity

* Cosine similarity is a metric used to measure how similar two items are. Mathematically it calculates the cosine of the angle between two vectors projected in a multidimensional space. 

* Cosine similarity is advantageous when two similar documents are far apart by Euclidean distance(size of documents) chances are they may be oriented closed together. The smaller the angle, higher the cosine similarity.

![image](https://www.oreilly.com/library/view/statistics-for-machine/9781788295758/assets/2b4a7a82-ad4c-4b2a-b808-e423a334de6f.png)
