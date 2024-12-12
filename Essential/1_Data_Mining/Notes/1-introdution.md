# Introduction to data mining

Before explaining what data mining is, it is necessary to understand a few concepts about data and how it is implicated in this topic. These concepts are called "Levels of Knowledge".

- **Data:** This is a data unit, generally quantifiable, that doesn't have any context. For this reason, you can't make any inferences about this unit. For example, if I give you these numbers: 80, 87, 24, can you tell me what they represent? No, the data has no context; it is only a unit of "something".

- **Information:** Now suppose I tell you that the previously mentioned numbers represent people, cars, and months, respectively. This **data** has been converted into units of information individually. Each number now represents something with a defined meaning. Note that information level is the "something" that data doesn't have.

- **Knowledge:** At this stage, you can establish connections between this information. For example, you might say *(continuing with my example)* that in 24 months, 87 cars have been bought by 80 people. As you can see, it is possible to create relationships with the information you have.

- **Insights:** Here, you can make inferences about the future based on the past data collected and analyzed up to this point. This is where enterprises are interested in a typical data mining process.

- **Wisdom:** Up to the insights level, computers are capable of processing and analyzing data because we can implement various techniques at each level of this pyramid. However, at the wisdom level, computers lack the capacity to participate. This level requires a full understanding of the data and its business importance. It is at this stage that the analyst plays a critical role but always handler with the expert in the field where is de business data.

> [!note]
> Working as a data scientist or analyst consists of understanding the data to achieve the **Knowledge**, **Insights**, and **Wisdom** levels, but you must **always** collaborate with the business data expert.

![levels of knowledge](https://i.pinimg.com/736x/cd/ef/7b/cdef7b8ce51a1d3a728ca5357e97a8d5.jpg)

Said this, I will explain to you about data mining is, I will explain it with the **five w questions** concept.

### What

**Data Mining** is every proccess to extract information of data to generate knowledge and insights to according business interesting.

### Who

Mainly, data analyst and data scientist are focused in this part but is posible that data scientist are most focused in modeling stage.

### Why

As previously seen, this is important to the business due to allow their take decisions based on the undertaning data and creating value in the different industries where data scientis is applied... And the business had been paying very good for this roles.

### Where

There are mainly three programming lenguage to allow data manipulation, mathlab is common used in student environments, then R allow use powerfull the computation to make statistical proccess because this lenguage was created to focus this target in their implementation, and Python is the most common used lenguage due to their optimized libraries to Machine Learning and Deep Learning modeling such as [*scikit-learn*](https://scikit-learn.org/stable/), [*TensorFlow*](https://www.tensorflow.org/?hl=es-419) and [*PyTorch*](https://pytorch.org/).

### When

This topic involve kind of a structure proccess that consist in differents thecnique to extract information like thus:

1. **Description:** Is a basic understanding about the dataset that you are analizing, considering the population size sample and features that allows describe this sample. Here, there are diferent basic descriptors that you must use.

    1.1. **Dataset size:** Prevously to try find patterns in the dataset, you must know the population sample size and features that contains this dataset. This is important to determinate if the population size could be a representative sample and if the features of this population can be viable to the business objetive.

   1.2 **Statistic basic:** When you do a descriptive proccess, you would need know how implement descriptive thecnics such as measures of the central trend, variability, position measures. Thus allow to you describe diferents features of the population sample, and also allow explain the population behaior.

2. **Data cleaning:** This section abords diferent concepts to clean a dataset, the most common proccess are.

    2.1. **Null Values:** Consists in find a missing information in the dataset and if is posible determinate if this missing data is natural or artificial.

    2.2. **Outladiers detection:** Some times the dataset contains outladier data in their features, here you should analyst it wit your handler expert and determinate if this outladier values are real value or are and error induced.

3. **Univariate analysis:**

    3.1. **Normailty test:**

    3.2. **Features distribution:**
    
4. **Bivariate analysis:**

    4.1. **Independence test:**

5. **Multivariate analysis:** Here is most commonly see implementations about more than two predict features with the target feature and observate how this predict features could be stronger for a modeling stage to predict the target feature.

> [!important]
> In univariate, bivariate and multivariate analysis, you must use several and easy understanding visualizations because of this allow to you a major representation of your features patterns.
