As a data analyst or scientist, your first task before manipulating a dataset must **always** be to understand your dataset. This involves identifying the type of data *(structured or unstructured)* and determining the type of modeling needed *(supervised or unsupervised)*.

This is very important because knowing the type of model you need allows you to infer which features should be used in your model *(see Note 1)*. Additionally, every data type requires a different preprocessing approach, as the information you can extract from each is vastly different, and it is impossible to apply the same preprocessing style to all types of data.

> [!note]
> **Note 1:** Some models, like embedding models, are not designed to work well with categorical data. You must carefully consider what steps to take in these situations. This is why determining whether the data is structured or unstructured is crucial for deciding on the appropriate preprocessing approach.


## Structured data

This is the most common data type and the style that you must dominate if you wish be a good data scientis, beacuse is the base about the technincns of data mining environment, here is where you can use the mentioned in the first charper. Here the posibilities hare infinity and basically the limit is how many time you have *(and want)* available to do this *(data mining)*.

The most essencial is know the size and dimensions about your dataset, here use `Pandas` and `readr` like a library example to **Python** and **R** lenguage respecty. To read csv file in python the code is the next:

```python
import pandas as pd # import library

data = pd.read_csv(<path>)
```

Or in R:

```r
library(readr) # import library

data <- read_csv(<path>)
```

> [!note]
> **Note 2:** Where $\text{<path>}$ is the location of yor csv file, remember that it's must be writen into quotes, for expample `"Downloads/data_heatlh.csv"`.

To know what are the size and dimension *(number of features)* that contain your file is need execute the next code.

```python
data.shape
```

Or in R:

```r
dim(data)
```

In the same cases, they will give you two numbers. The first is the number of records or the sample population contained in the dataset, and the second is the number of features that describe this population.

Then, you should have a clear understanding of the data features in the dataset. Again, this is relevant because you will communicate your insights, and this is only possible by understanding your data. Otherwise, you will just communicate nonsense. The next image shows 4 of the most relevant feature types commonly used in data science. However, there are many more feature types that you will likely use, such as geographic information like geospatial references.

![features types](https://lh3.googleusercontent.com/ouaZ3rY3a2NL356W3kDyYr5HTBFFMzSVK2QSQmptX4oMWmH5rmiBix3RIu-aZ9ptEZZUcKkDhN2A7BmPKgs_bCN6raFf5Car4CxHKsPqu_rmB5f-engm9BsHnTyR2rgLmxCSgq9s)

Finally you should apply technics about data cleaning that involucre **NaN** and **outladiers** detection that we will see in the other chapter.

> [!note]
> **Note 3:** Geographic data can be considered both structured and unstructured, depending on the file format of the data. For example, satellite photos are unstructured, but points or polygons are structured data.

## Unstructured data

The process of understanding your unstructured data depends on the type of data you are dealing with: videos, pictures, audio, text, etc. The process for each type is different, and I think it's better to consult resources that specifically address each. For that reason, I recommend these lectures on this data type.

#### Brief difference about structured-unstructured data types

I think this video explain in a brief time what's the diferents about this and which is this importance to make the modeling stage.

<div style="text-align: center;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/5M2okstYF3A" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

#### Most complete unstructured data definition

I considered that this video explain a good definition about unstructured data definition, it format types, and the implication in our society in the sense about the quantity about it like social media and business data recolegtion.

<div style="text-align: center;">
    <iframe width="560" height="315" 
            src="https://www.youtube.com/embed/Av4BsJmqUQ8?start=224" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
    </iframe>
</div>

Obviously, there are more videos that could explain this, but I am confident that this will help you understand the basic concepts of the distinction between structured and unstructured data and their use in data mining.

