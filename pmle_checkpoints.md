1. [1. Links](#1-links)
   1. [1.1. Offical](#11-offical)
2. [2. GCP Products](#2-gcp-products)
   1. [2.1. Document AI](#21-document-ai)
   2. [2.2. Dataproc (Hadoop cluster)](#22-dataproc-hadoop-cluster)
   3. [2.3. Dataprep (UI-Driven Data Prep)](#23-dataprep-ui-driven-data-prep)
   4. [2.4. Dataflow Flex](#24-dataflow-flex)
   5. [2.5. Dataflow (Apache Beam based jobs)](#25-dataflow-apache-beam-based-jobs)
   6. [2.6. Data/Cloud Fusion](#26-datacloud-fusion)
   7. [2.7. Cloud Pub/Sub](#27-cloud-pubsub)
   8. [2.8. Cloud Spanner](#28-cloud-spanner)
   9. [2.9. Cloud Composer](#29-cloud-composer)
   10. [2.10. Cloud Monitoring](#210-cloud-monitoring)
   11. [2.11. Cloud BigTable](#211-cloud-bigtable)
3. [3. Machine Learning](#3-machine-learning)
   1. [3.1. Problem Framing](#31-problem-framing)
   2. [3.2. Data Preparation and Feature Engineering](#32-data-preparation-and-feature-engineering)
      1. [3.2.1. Scaling](#321-scaling)
         1. [3.2.1.1. Linear scaling:](#3211-linear-scaling)
         2. [3.2.1.2. Non-linear transformantion](#3212-non-linear-transformantion)
         3. [3.2.1.3. Array of numbers](#3213-array-of-numbers)
         4. [3.2.1.4. Categorical inputs](#3214-categorical-inputs)
      2. [3.2.2. Hashed feature](#322-hashed-feature)
      3. [3.2.3. Embedding](#323-embedding)
   3. [3.3. Recommendation system](#33-recommendation-system)
      1. [3.3.1. Filtering the data](#331-filtering-the-data)
   4. [3.4. Clustering in machine learning](#34-clustering-in-machine-learning)
   5. [3.5. Testing and Debugging in machine learning](#35-testing-and-debugging-in-machine-learning)
      1. [3.5.1. Data debugging](#351-data-debugging)
      2. [3.5.2. Model debugging](#352-model-debugging)
   6. [3.6. Privacy in machine learning](#36-privacy-in-machine-learning)
4. [4. Metrics](#4-metrics)
   1. [4.1. Regularization](#41-regularization)
   2. [4.2. Neural Network](#42-neural-network)
5. [5. AI Explanations](#5-ai-explanations)
6. [6. Tensorflow](#6-tensorflow)
   1. [6.1. Tensorflow Enterprise](#61-tensorflow-enterprise)
   2. [6.2. Keras](#62-keras)
      1. [6.2.1. Functional vs Sequential API](#621-functional-vs-sequential-api)
      2. [6.2.2. Feature engineering](#622-feature-engineering)
         1. [6.2.2.1. Bucketing](#6221-bucketing)
         2. [6.2.2.2. Feature cross](#6222-feature-cross)
         3. [6.2.2.3. Softmax](#6223-softmax)
         4. [6.2.2.4. Faster input pipeline](#6224-faster-input-pipeline)
   3. [6.3. Model Monitoring](#63-model-monitoring)
   4. [6.4. Accelerators](#64-accelerators)
   5. [6.5. Distributor](#65-distributor)
   6. [6.6. LIT (Languge Interpretability Tool)](#66-lit-languge-interpretability-tool)
   7. [6.7. Tensorflow Probaility](#67-tensorflow-probaility)
7. [7. MLOps](#7-mlops)
   1. [7.1. CI/CD architecture](#71-cicd-architecture)
   2. [7.2. TFX](#72-tfx)
      1. [7.2.1. Tensorflow extend](#721-tensorflow-extend)
      2. [7.2.2. Tensorflow data validation (TFDV)](#722-tensorflow-data-validation-tfdv)
      3. [7.2.3. Tensorflow transform](#723-tensorflow-transform)
      4. [7.2.4. Tensorflow estimators and keras](#724-tensorflow-estimators-and-keras)
      5. [7.2.5. Tensorflow model analysis](#725-tensorflow-model-analysis)
      6. [7.2.6. Tensorflow serving](#726-tensorflow-serving)
      7. [7.2.7. Put them together](#727-put-them-together)
      8. [7.2.8. TFX on Cloud AI Platform Pipelines](#728-tfx-on-cloud-ai-platform-pipelines)
   3. [7.3. Kubernetes (K8)](#73-kubernetes-k8)
      1. [7.3.1. Google compute option](#731-google-compute-option)
      2. [7.3.2. K8 architecture](#732-k8-architecture)
   4. [7.4. Kubeflow](#74-kubeflow)
   5. [7.5. CI/CD](#75-cicd)
   6. [7.6. BigQuery ML](#76-bigquery-ml)
   7. [7.7. What all can you do with BigQuery ML? What are its limitations](#77-what-all-can-you-do-with-bigquery-ml-what-are-its-limitations)
   8. [7.8. AI Platform](#78-ai-platform)
      1. [7.8.1. Use automatic hyperparameter tuning](#781-use-automatic-hyperparameter-tuning)
      2. [7.8.2. Continuous evaluation overview](#782-continuous-evaluation-overview)
      3. [7.8.3. Vertex AI](#783-vertex-ai)
         1. [7.8.3.1. Prediction logging](#7831-prediction-logging)
         2. [7.8.3.2. Model monitoring](#7832-model-monitoring)
            1. [7.8.3.2.1. Data drift](#78321-data-drift)
            2. [7.8.3.2.2. Feature store](#78322-feature-store)
         3. [7.8.3.3. Model Deployment](#7833-model-deployment)
   9. [7.9. APIs](#79-apis)
      1. [7.9.1. Natural Language](#791-natural-language)
      2. [7.9.2. Translation](#792-translation)
      3. [7.9.3. Vision AI](#793-vision-ai)
      4. [7.9.4. Video AI](#794-video-ai)
      5. [7.9.5. Other Products](#795-other-products)

# 1. Links

* [GCP Machine Learning Engineer Certification Preparation Guide - 08 Jan 2022](https://dzlab.github.io/certification/2022/01/08/gcp-ml-engineer-prep/)

## 1.1. Offical
* [Cloud Architecture Center](https://cloud.google.com/architecture)
# 2. GCP Products

## 2.1. Document AI
Automate data capture at scale to reduce document processing costs. (OCR)

## 2.2. Dataproc (Hadoop cluster)
Use Dataproc for data lake modernization, ETL, and secure data science

* Fully managed and automated big data open source software
* Containerize Apache Spark jobs with Kubernetes
* Enterprise security integrated with Google Cloud
* The best of open source with the best of Google Cloud 

## 2.3. Dataprep (UI-Driven Data Prep)
An intelligent cloud data service to **visually explore**, clean, and prepare data for analysis and machine learning.

## 2.4. Dataflow Flex
Unified **stream** and **batch** data processing that's **serverless**, fast, and cost-effective.
* Autoscaling of resources and dynamic work rebalancing
* Flexible scheduling and pricing for batch processing
* Ready-to-use real-time AI patterns

Use case:
* Stream analytics
* Real-time AI
* Sensor and log data processing


## 2.5. Dataflow (Apache Beam based jobs)
[link](https://cloud.google.com/dataflow)
Unified stream and batch data processing that's serverless, fast, and cost-effective.
* Autoscalling of resource
* **Batch processing**
* Ready-to-use real-time AI patterns
* Work with **Apache Beam**

Use Beam with **dataflow** to write elastic data processing pipeline
* Serverless
* Support both batch (from cloud storage) and streaming (from pub/sub) process using the same pipeline code
* When you work with large datasets, Dataflow is more scalable and cost-effective than AI Platform Training. For example, see TensorFlow Model Analysis, which is implemented using Apache Beam, and which can run on Dataflow to evaluate TensorFlow SavedModels.

Some features:
*  *Interactive Apache Beam runner (beta)* lets you iteratively develop pipelines on a small dataset and cost-effectively validate the correctness of the pipeline
* *Dataflow Flexible Resource Scheduling (FlexRS)* reduces batch processing costs by using advanced scheduling techniques
* *Dataflow Shuffle operation enables faster execution*; more efficient consumption of CPU, memory and persistent disk resources; better autoscaling; and better fault tolerance

![comparing](https://cloud.google.com/architecture/images/data-lifecycle-4.svg)

## 2.6. Data/Cloud Fusion
Fully managed, cloud-native *data integration* at any scale.
* Visual point-and-click interface enabling **code-free** deployment of ETL/ELT data pipelines
    * Data Fusion’s intuitive drag-and-drop interface, pre-built connectors, and self-service model of code-free data integration remove technical expertise-based bottlenecks and accelerate time to insight.
* A **serverless** approach leveraging the scalability and reliability of Google services like Dataproc means Data Fusion offers the best of data integration capabilities with a lower total cost of ownership.

## 2.7. Cloud Pub/Sub
[link](https://cloud.google.com/pubsub/docs/overview)
* Pub/Sub allows services to communicate **asynchronously**, with latencies on the order of 100 milliseconds.
* Pub/Sub is used for **streaming** analytics and data integration pipelines to ingest and distribute data
* Pub/Sub enables you to create systems of event producers and consumers, called publishers and subscribers. Publishers communicate with subscribers asynchronously by broadcasting events, rather than by synchronous remote procedure calls (RPCs).

## 2.8. Cloud Spanner
Fully managed relational database with **unlimited scale**, strong consistency, and up to 99.999% availability.

Spanner is a row-based, transactional database. You want to use spanner to back transaction processing such as e-commerce, core banking, gaming ...; on the other hand, big query (bq) is columnar data warehouse, good for analytical work.

* Get all the benefits of relational semantics and **SQL** with unlimited scale
* Deliver high-performance **transactions** with strong consistency across regions and continents

## 2.9. Cloud Composer
A fully managed **workflow orchestration** service built on **Apache Airflow**.

## 2.10. Cloud Monitoring
[link](https://cloud.google.com/monitoring) Gain visibility into the performance, availability, and health of your applications and infrastructure.

## 2.11. Cloud BigTable
A fully managed, **scalable NoSQL database** service for large analytical and operational workloads with up to 99.999% availability.

# 3. Machine Learning
## 3.1. Problem Framing
[link](https://developers.google.com/machine-learning/problem-framing)

* Supervise
* Unsupervise
* Reinforecement Learning:  
  * Reinforcement learning differs from other types of machine learning. In RL **you don't collect examples with labels.**
  * The lack of a data requirement makes RL a tempting approach. However, designing a good reward function is difficult, and RL models are less stable and predictable than supervised approaches. 
  * Additionally, you need to provide a way for the agent to interact with the game to produce data, which means either building a physical agent that can interact with the real world or a virtual agent and a virtual world, either of which is a big challenge.

Types of ML problems:
* classification
* regression
* clusteirng
* association rule learning - infer likely association patterns in data - i.e, if you buy hamburger buns, you're likely to buy hamburgers (unsupervised)
* structured output
* ranking - identify position on a scale or status - i.e., search result ranking

## 3.2. Data Preparation and Feature Engineering
[link](https://developers.google.com/machine-learning/data-prep)

### 3.2.1. Scaling

#### 3.2.1.1. Linear scaling:
* linear scaling / min-max scaling: work best for uniformly distributed data
* clipping with (linear scaling)
* z-score: work best for distributed data
* winsorizing: use the empirical distribution in the training dataset to clip the dataset to bounds, i.e., 5th and 95 percentile tile
  ```python
  from scipy.stats.mstats import winsorize
  winsorize(
    [92, 19, 101, 58, 1053, 91, 26, 78, 10, 13, -40, 101, 86, 85, 15, 89, 89, 28, -5, 41], 
    limits=[0.05, 0.05]
  )
  ```
Don't simply discard outliers, instead, replace outliers with min/max after scaling; outliers can contain important information

#### 3.2.1.2. Non-linear transformantion
If data is skewed or neither uniformly/normally distributed, it is better to use non-linear transformation
* Bucketize
* Box-Cox transformation: choose its single paramter - lambda - to control "heteroscedasticity" so that the variance no longer depends on the magnitude.

#### 3.2.1.3. Array of numbers
The input data is an array of numbers of different length, i.e., to predict number of sales of a nonfiction book, we use previous sales as input, which will have different length because there are different numbers of books published on different topics; to process this kind of input:
* represent array by it's stats, i.e., mean, min, max, var ...
* represent the input arry by it's emperical distribution, i.e., 10th/20th/... percentile
* if ordered array, last 3 inputs/fixed number of items

#### 3.2.1.4. Categorical inputs
* dummy coding - preferred by statiscal model, which required inputs to be linearly independent
* one-hot - preferred by modern machine learning model, which doesnt required linear independent; ml model use l1/l2/other regularization to prune redundant inputs and thus many ml algo only supports one-hot
  * cons: 
    * incomplete vocabulary - require to know the vocabulary beforehand
    * high cardinality
    * cold-start - issue for categorical level unknown in production setting, need handle separately.
  * solution: hashed feature
* array of categorical variable, i.e., `[induced, induced, natural, cesarean]`
  * count: [2,1,1]
  * relative count: to avoid large number, [0.5, 0.25, 0.25]
  * ordered array
  
### 3.2.2. Hashed feature
The hashed feature represent categorical input by doing the following: [link](https://github.com/GoogleCloudPlatform/ml-design-patterns/blob/master/02_data_representation/hashed_feature.ipynb)
  1. converting the categorical input into a unique string
  2. invoking a deterministic (set seed) for hashing algo
  3. taking the remainder when the hash result is divided by the desired number of buckets

Why it works? Even if an airport (level) with a handful of flights is not part of the training dataset, it's hashed feature values will be in the range of [0-9]. Therefore, there is no resilience problem during serving.

If we have 347 airports, an average of 35 airports will get the same hash bucket code if we hash into 10 buckets. An airport that is missing from the training dataset will 'borrow' it characteristic from the other similar airports. Of course it won't be accurate but at least it will be in the right range.
* choose right number of bucket is important here; rule of thumb :arrow_right: at least five entries for each bucket
* lose information by bucketizing, can lead to drop in model accuracy - trade off: by chossing hashed feature, we are explicity compromising on the ability to accurate represent the data

### 3.2.3. Embedding
The embedding design pattern address the problem of representing high-cardinality data densely in a lower dimension by passing the input data through an embedding layer that has trainable weights

Autoencoder:
* train embedding layer via autoencoder - no labling data required
* use embededed layer in later task



## 3.3. Recommendation system
### 3.3.1. Filtering the data
* Content-based: A popular, recommended product has similar attributes to what the user views or likes.
* Cluster: Recommended products go well together, no matter what other users have done.
* Collaborative: Other users, who like the same products the user views or likes, also liked a recommended product.

## 3.4. Clustering in machine learning
[link](https://developers.google.com/machine-learning/clustering)

Type of clustering:
* Centroid-based, i.e., k-mean
* Density-based: connects areas of high example density into clusters; This allows for arbitrary-shaped distributions as long as dense areas can be connected. These algorithms have difficulty with data of varying densities and high dimensions. Further, by design, these algorithms do not assign outliers to clusters. ![density-based](https://developers.google.com/machine-learning/clustering/images/DensityClustering.svg)
* Distribution-based: assumes data is composed of distributions, such as Gaussian distributions. the distribution-based algorithm clusters data into three Gaussian distributions. As distance from the distribution's center increases, the probability that a point belongs to the distribution decreases. ![distribution-based](https://developers.google.com/machine-learning/clustering/images/DistributionClustering.svg)
* Hierarchical clustering: creates a tree of clusters. Hierarchical clustering, not surprisingly, is well suited to hierarchical data, such as taxonomies. In addition, another advantage is that any number of clusters can be chosen by cutting the tree at the right level.



## 3.5. Testing and Debugging in machine learning

### 3.5.1. Data debugging
1. Validate input data using a data schema
   * check range and distribution of numerical data; check set of possible values of categorical data
   * encode your understanding into schema
   * test your data against the data schema
     * anomalies
     * unexpected values of categorical variables
     * unexpected data distribution
2. Ensure splits are good quality
3. Test engineered data: While your raw data might be valid, your model only sees engineered feature data. Because engineered data looks very different from raw input data, you need to check engineered data separately. 
   * All numeric features are scaled, for example, between 0 and 1.
   * One-hot encoded vectors only contain a single 1 and N-1 zeroes.
   * Missing data is replaced by mean or default values.
   * Data distributions after transformation conform to expectations. For example, if you've normalized using z-scores, the mean of the z-scores is 0.
   * Outliers are handled, such as by scaling or clipping.

### 3.5.2. Model debugging
1. Check that the data can predict the labels.
2. Establish a baseline.
3. Write and run tests.
4. Adjust your hyperparameter values.
5. 
## 3.6. Privacy in machine learning


# 4. Metrics
## 4.1. Regularization
Regularization techniques
* L1 - A type of regularization that penalizes weights in proportion to the sum of the absolute values of the weights. In models relying on sparse features, **L1 regularization helps drive the weights of irrelevant or barely relevant features to exactly 0, which removes those features from the model.**
* L2 - A type of regularization that penalizes weights in proportion to the sum of the squares of the weights. L2 regularization helps drive outlier weights **(those with high positive or low negative values) closer to 0 but not quite to 0**. L2 regularization always improves generalization in linear models.
* Dropout
  * normal dropout range: 20% - 50%
* Other methods:
    * early stopping
    * max-norm regularization
    * data augmentation
    * noise robustness
    * sparse representation - zero out coefficient can help with the performance especially with large and sparse dataset in the way:
    	* fewer coefficient to store/load :arrow_right: reduce memory need
    	* fewer multiplication need :arrow_right: increase predict speed


## 4.2. Neural Network
* Vanishing Gardients - The gradients for the lower layers (closer to the input) can become very small. When the gradients vanish toward 0 for the lower layers, **these layers train very slowly, or not at all**. :arrow_right: The ReLU activation function can help prevent vanishing gradients.
* Exploding Gardients - If the weights in a network are very large, then the gradients for the lower layers involve products of many large terms. In this case you can have exploding gradients:  gradients that get too large to converge. :arrow_right: Batch normalization can help prevent exploding gradients, as can lowering the learning rate.
* Dead ReLU Units - Once the weighted sum for a ReLU unit falls below 0, the ReLU unit can get stuck. It outputs 0 activation, contributing nothing to the network’s output, and gradients can no longer flow through it during backpropagation. With a source of gradients cut off, the input to the ReLU may not ever change enough to bring the weighted sum back above 0.. Lowering the learning rate can help keep ReLU units from dying. :arrow_right:
  * Lower learning rate
  * Leaky-Relu can help to address this
  * As can choice of optimiser eg. ADAM!!

# 5. AI Explanations
* For structured data, Shapely is a popular technique to use
Integrated ingredients can be used for large feature spaces;
* For images data, use integrated gradients for pixel-level explanations or [XRAI](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kapishnikov_XRAI_Better_Attributions_Through_Regions_ICCV_2019_paper.pdf) for region-level explanations.

Also, an important tool to know about is [WhatIf Tool](https://pair-code.github.io/what-if-tool/) — when do you use it? How do you use it? How do you discover different outcomes? How do you conduct experiments?

# 6. Tensorflow
## 6.1. Tensorflow Enterprise
The TensorFlow Enterprise is a distribution of the open-source platform for ML, linked to specific versions of TensorFlow, tailored for enterprise customers.

It is free but only for big enterprises with a lot of services in GCP. It is prepackaged and optimized for usage with containers and VMs.

It works in Google Cloud, from VM images to managed services like GKE and Vertex AI.

## 6.2. Keras
### 6.2.1. Functional vs Sequential API
* **Functional API**  - is a way to create models that are more flexible than the tf.keras.Sequential API. The functional API can handle models with non-linear topology, shared layers, and even multiple inputs or outputs.
```python
dense = layers.Dense(64, activation="relu")
```
* Sequential API - A Sequential model is appropriate for a plain stack of layers where each layer has exactly one input tensor and one output tensor.
```python
# Define Sequential model with 3 layers
model = keras.Sequential(
    [
        layers.Dense(2, activation="relu", name="layer1"),
        layers.Dense(3, activation="relu", name="layer2"),
        layers.Dense(4, name="layer3"),
    ]
)
# Call model on a test input
x = tf.ones((3, 3))
y = model(x)
```

### 6.2.2. Feature engineering
#### 6.2.2.1. Bucketing
* if you know the keys beforehand, use `tf.feature_columns.categorical_column_with_vocabulary_list`
* if your data is already indexed, use `tf.feature_columns.categorical_column_with_identity`
* if you don't have index a vocabulary of all possible value, use `tf.feature_columns.categorical_column_with_hash_bucket`
```python
# if you know the keys beforehand
tf.feature_columns.categorical_column_with_vocabulary_list(
	'employee_id', ['1', '12312', '2345']
)
# if your data is already indexed
tf.feature_columns.categorical_column_with_identity(
	'employee_id',num_buckets=3
)
# if you don’t have index a vocabulary of all possible value
tf.feature_columns.categorical_column_with_hash_bucket(
	'employee_id',hash_bucket_size=500
)
```
#### 6.2.2.2. Feature cross
Problem is not always linear separable :arrow_right: need higher dimensional data to draw decision boundary: a feature cross memorize the input space
* If you dont have enough data, you risk in overfitting, memorization works well when you have large dataset.
* Memorization is the opposite to the generalization :arrow_right: the large the data, more powerful the memorization it is (and so does feature cross)
* Feature cross + massive data leads to good in learn highly complex spaces (color+taxi example)
* Linear model is a convex problem (optimizing convex problem is much easier than optimizing non-convex problem) :arrow_right: therefore sparse linear model is a very cost effective method to solve problem
* Feature cross leads to sparsity :arrow_right: however, tf can handle sparse matrix well
* Hash bucket for feature crossing:
	* Small # hash bucket :arrow_right: lots of collision :arrow_right: less amount of detailed information memorized, but also less memory used. Still trying to keep enough bucket
	* High # hash bucket :arrow_right: very sparse 
	* Rule of thumb: between 0.5*sqrt(n) and 2n (trade of memorization and sparsity) 
* Embeded feature cross :arrow_right: Let the model to learn how to represent the feature cross in lower dimensional space

#### 6.2.2.3. Softmax
* `softmax_cross_entropy_with_logits_v2` - general multi-calss classification
  * While the classes are mutually exclusive, their probabilities need not be. All that is required is that each row of labels is a valid probability distribution
    ```python
    logits = [[4.0, 2.0, 1.0], [0.0, 5.0, 1.0]]
    labels = [[1.0, 0.0, 0.0], [0.0, 0.8, 0.2]]
    tf.nn.softmax_cross_entropy_with_logits(labels=labels, logits=logits)
    ```
* `sparse_softmax_cross_entropy_with_logits` - more efficient multi-class classification with **hard labels**
  * For this operation, the probability of a given label is considered exclusive. That is, soft classes are not allowed, and the labels vector must provide a single specific index for the true class for each row of logits (each minibatch entry).
    ```python
    logits = tf.constant([[2., -5., .5, -.1],
                        [0., 0., 1.9, 1.4],
                        [-100., 100., -100., -100.]])
    labels = tf.constant([0, 3, 1])
    tf.nn.sparse_softmax_cross_entropy_with_logits(
        labels=labels, logits=logits).numpy()
    ```
* `sigmoid_cross_entropy_with_logits` - binary classification
    ```python
    logits = tf.constant([1., -1., 0., 1., -1., 0., 0.])
    labels = tf.constant([0., 0., 0., 1., 1., 1., 0.5])
    tf.nn.sigmoid_cross_entropy_with_logits(
        labels=labels, logits=logits).numpy()
    ```

#### 6.2.2.4. Faster input pipeline
`tf.data.Dataset` allows you to :arrow_right: consider this when reading data inputs has become an bottleneck to the training / scoring process

* create data pipeline from
  * in-memory dictionary and lists of tensor
  * **out-of-memory** sharded data files
* preprocess data in **parallel**
    ```python
    def preproc_func():
        # define data preprocessing
        pass

    dataset = dataset.map(preproc_func).cache()
    ````
* configure the way the datga is fed into a model with a number of chainning methods
    ```python
    dataset = dataset.shuffle(1000).repeat(epochs).batch(batch_size, drop_remainder=True)
    ```

`tf.TFRecordReader `: The TFRecord format is efficient for storing a sequence of binary and not-binary records using Protocol buffers for serialization of structured data.

`tf.Quantization`: Aimed to reduce CPU and TPU GCP latency, processing, and power.

## 6.3. Model Monitoring
* `tf.function`: a transformation tool used to make graphs out of your programs. It helps to create performant and portable models (change from eager mode to static graph)
* `tf.Profiler`: a tool for checking the performance of your TensorFlow models and helping you to obtain an optimized version.
* `tf.Trace`: lets you record TensorFlow Python operations in a graph.
* `tf.CheckPoint`: Checkpoints catch the value of all parameters in a serialized SavedModel format.

## 6.4. Accelerators
You need to know the differences between CPUs, TPUs and GPUs and when to use each one. The general answer is that GPU training is faster than CPU training, and GPU usually doesn’t require any additional setup. TPUs are faster than GPUs but they don’t support custom operations.

* Use CPUs for quick prototypes, simple/small models or if you have many C++ custom operations;
* Use GPU if you have some custom C++ operations and/or medium to large models;
* Use TPUs for big matrix computations, no custom TensorFlow operations and/or very large models that train for weeks or months

## 6.5. Distributor

[link](https://www.tensorflow.org/guide/distributed_training)

|          Strategy           | Synchronous / Asynchronous | Number of nodes | Number of GPUs/TPUs per node |                                                                                                                                                                                            How model parameters are stored                                                                                                                                                                                            |
| :-------------------------: | :------------------------: | :-------------: | :--------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|      MirroredStrategy       |        Synchronous         |       one       |             many             |                                                                                                                                                                                                      On each GPU                                                                                                                                                                                                      |
|         TPUStrategy         |        Synchronous         |       one       |             many             |                                                                                                                                                                                                      On each TPU                                                                                                                                                                                                      |
| MultiWorkerMirroredStrategy |        Synchronous         |      many       |             many             |                                                                                                                                                                                               On each GPU on each node                                                                                                                                                                                                |
|   ParameterServerStrategy   |        Asynchronous        |      many       |             one              | On the Parameter Server (Asynchronous distributed training with powerful GPUs requires a lot of bandwidth to the parameter server. However, the bandwidth available is proportional to the size (number of vCPUs) of the parameter server. Therefore, we recommended that you over-provision the compute capacity of the parameter server in order to increase the bandwidth and take full advantage of GPU workers.) |
|   CentralStorageStrategy    |        Synchronous         |       one       |             many             |                                                                                                                                                                                  On CPU, could be placed on GPU if there is only one                                                                                                                                                                                  |
|      Default Strategy       |      no distribution       |       one       |             one              |                                                                                                                                                                                            on any GPU picked by TensorFlow                                                                                                                                                                                            |
|      OneDeviceStrategy      |      no distribution       |       one       |             one              |                                                                                                                                                                                                 on the specified GPU                                                                                                                                                                                                  |

## 6.6. LIT (Languge Interpretability Tool)
The Language Interpretability Tool (LIT) is an open-source tool developed specifically to explain and visualize NLP natural language processing models.

It is similar to the What-If tool, which instead targets classification and regression models with structured data.

It offers visual explanations of the model‘s predictions and analysis with metrics, tests and validations.
![link](https://skillcertpro.com/wp-content/uploads/2022/i/02/word-image-454.png)

## 6.7. Tensorflow Probaility


# 7. MLOps

## 7.1. CI/CD architecture
![CI/CD architecture](https://cloud.google.com/architecture/images/architecture-for-mlops-using-tfx-kubeflow-pipelines-and-cloud-build-6-ci-cd-kubeflow.svg)

## 7.2. TFX
The following diagram shows how the various TFX libraries are integrated to compose an ML system.
![link](https://cloud.google.com/static/architecture/images/architecture-for-mlops-using-tfx-kubeflow-pipelines-and-cloud-build-2-tfx-libraries.svg)

You have to know TFX (TensorFlow Extended) and its limitations (can be used to build pipelines for Tensoflow models only), what are its standard components (e.g. ingestion, validation, transform) and how to build a pipeline out of them.

### 7.2.1. Tensorflow extend
* data components
  * ExampleGen: initial input component of a pipelien that ingests and optionally split the input dataset
  * StatistivsGen
  * SchemaGen
  * ExampleValidator
  * Transform
* model components
  * Trainer: produce standardize tf model and save the artifacts
  * Tunner: tunes hyperparameter
  * Evaluator: perform deep analysis of the trianing cycles to help you validate the model
  * InfraValidator: check the model is serverable from infrastructure
  * Pusher: deploy the model
  * BulkInferrer: perofrm batch inferencing
* pipeline nodes

### 7.2.2. Tensorflow data validation (TFDV)

[link](https://www.tensorflow.org/tfx/tutorials/data_validation/tfdv_basic)
```python
import tensorflow_data_validation as tfdv

# to compute statistics for our training data
train_stats = tfdv.generate_statistics_from_csv(data_location=TRAIN_DATA)

# visualize the result
tfdv.visualize_statistics(train_stats) 

# infer data schema
schema = tfdv.infer_schema(statistics=train_stats)
tfdv.display_schema(schema=schema)

# Compute stats for evaluation data
eval_stats = tfdv.generate_statistics_from_csv(data_location=EVAL_DATA)

# Compare evaluation data with training data
tfdv.visualize_statistics(lhs_statistics=eval_stats, rhs_statistics=train_stats,
                          lhs_name='EVAL_DATASET', rhs_name='TRAIN_DATASET')
```

### 7.2.3. Tensorflow transform
[link](https://www.tensorflow.org/tfx/tutorials/transform/simple)
TensorFlow Transform is a library for preprocessing input data for TensorFlow, including creating features that require a full pass over the training dataset. For example, using TensorFlow Transform you could:
* Normalize an input value by using the mean and standard deviation
* Convert strings to integers by generating a vocabulary over all of the input values
* Convert floats to integers by assigning them to buckets, based on the observed data distribution

Syntax to put transformed data into ApacheBeam pipeline
```python
result = apache_beam.Pipeline() | 'first step' >> do_this_first() | 'second step' >> do_this_last()
```

### 7.2.4. Tensorflow estimators and keras
[link](https://www.tensorflow.org/overview/)


### 7.2.5. Tensorflow model analysis
[link](https://www.tensorflow.org/tfx/model_analysis/get_started)
TensorFlow Model Analysis (TFMA) is a library for performing model evaluation.

* For: Machine Learning Engineers or Data Scientists
* who: want to analyze and understand their TensorFlow models
* it is: a standalone library or component of a TFX pipeline
* that: evaluates models on large amounts of data in a distributed manner on the same metrics defined in training. These metrics are compared over slices of data, and visualized in Jupyter or Colab notebooks.
* unlike: some model introspection tools like tensorboard that offer model introspection

### 7.2.6. Tensorflow serving


### 7.2.7. Put them together

Now we're ready to transform our data. We'll use Apache Beam with a direct runner, and supply three inputs:
* raw_data - The raw input data that we created above
* raw_data_metadata - The schema for the raw data
* preprocessing_fn - The function that we created to do our transformation
```python
def main(output_dir):
  # Ignore the warnings
  with tft_beam.Context(temp_dir=tempfile.mkdtemp()):
    transformed_dataset, transform_fn = (  # pylint: disable=unused-variable
        (raw_data, raw_data_metadata) | tft_beam.AnalyzeAndTransformDataset(
            preprocessing_fn))

  transformed_data, transformed_metadata = transformed_dataset  # pylint: disable=unused-variable

  # Save the transform_fn to the output_dir
  _ = (
      transform_fn
      | 'WriteTransformFn' >> tft_beam.WriteTransformFn(output_dir))

  return transformed_data, transformed_metadata
```
### 7.2.8. TFX on Cloud AI Platform Pipelines
[link](https://www.tensorflow.org/tfx/tutorials/tfx/cloud-ai-platform-pipelines)

## 7.3. Kubernetes (K8)
### 7.3.1. Google compute option
* compute engine 
  * (IaaS): :arrow_right: Made of highly scalable and automated compute resources. IaaS is fully self-service for accessing and monitoring computers, networking, storage, and other services
  * fully customizeable VM
* app engine 
  * (PaaS): :arrow_right: PaaS provides a platform for software creation
  * A fully managed environment lets you focus on code while App Engine manages infrastructure concerns. You simply take your code and deploy it on Google, then pay for the resources you consume (**serverless**)
  * You don't worry about the underlying infrastructure is the key here.
* kubernetes engine (GKE)
  * Hybrid between Iaas and PaaS; hybrid between compute engine and app engine
  * build for containerized application
    * want to aviod overhead of managing a full container cluster environment by yourself
    * has right to customize the container by yourself
  * containerzied application can be easily swappable 
* cloud run:
  * **stateless** service: :arrow_right: The server processes requests based only on information relayed with each request and doesn’t rely on information from earlier requests – this means that the server doesn’t need to hold onto state information between requests 
  * can handle multiple request at same time and scale up
* cloud functions
  * cannot handle multiple request at the same time
  * serverless logic
  * Cloud Functions only supports a single request at a time for each cloud function instance whereas Cloud Run is able to handle multiple requests at the same time and is able to scale up based on demand.
  * cloud functions can build very simple, lightweight and standalone piece of functionality, it can be difficult to run mode complex applicaiton --> need app engine

### 7.3.2. K8 architecture
The smallest unit of K8 is called pod, which define the overall environment for K8.
* a pod can contain more than one container
* if containers are within the same pod, they share the same resource and storage
  * each container have it's own ip address
  * different container in the same pod can communicate with each other

Google k8 engine
* k8 doesnt create nodes; cluster admins create nodes and add them to k8
* GKE manges this by deploying and registering comput engine instance as node

| Platform Type |                                                     Common Examples                                                     |
| :-----------: | :---------------------------------------------------------------------------------------------------------------------: |
|     SaaS      |                         Google Workspace, Dropbox, Salesforce, Cisco WebEx, Concur, GoToMeeting                         |
|     PaaS      |          AWS Elastic Beanstalk, Windows Azure, Heroku, Force.com, Google App Engine, Apache Stratos, OpenShift          |
|     IaaS      | DigitalOcean, Linode, Rackspace, Amazon Web Services (AWS), Cisco Metapod, Microsoft Azure, Google Compute Engine (GCE) |

## 7.4. Kubeflow
Kubeflow Pipelines is an open-source platform designed specifically for creating and deploying ML workflows based on Docker containers. Their main features:
* Using packaged templates in Docker images in a K8s environment
* Manage your various tests/experiments
* Simplifying the orchestration of ML pipelines
* Reuse components and pipelines

* A platform for DS/DE to build and experiment ML pipelines. 
* Kubeflow is the ML toolkit for Kubernetes.
* Kubeflow builds on Kubernetes as a system for deploying, scaling, and managing complex systems.
![kubeflow_overview](https://www.kubeflow.org/docs/images/kubeflow-overview-platform-diagram.svg)

Logical component that makeup kubeflow
* [central dashboard](https://www.kubeflow.org/docs/components/central-dash/)
* [kubeflow notebook](https://www.kubeflow.org/docs/components/notebooks/)
* [kubeflow pipelines](https://www.kubeflow.org/docs/components/pipelines/)
  * A pipeline component is a self-contained set of user code, packaged as a Docker image, that performs one step in the pipeline. ![pipeline_component](https://www.kubeflow.org/docs/images/pipelines-xgboost-graph.png)
* [katib](https://www.kubeflow.org/docs/components/katib/): for hyperparameter tuning and neural architecture search
* [training operators](https://www.kubeflow.org/docs/components/training/): training of ML models in Kubeflow through operators
* [multi-tenancy](https://www.kubeflow.org/docs/components/multi-tenancy/): Multi-user isolation and identity access management

[Kubeflow for CI/CD](https://github.com/marketplace/actions/kubeflow-for-ci-cd)

Kubeflow Servering: an open-source library for Kubernetes that enables serverless inferencing. It works with TensorFlow, XGBoost, scikit-learn, PyTorch, and ONNX to solve issues linked to production model serving. ![link](https://skillcertpro.com/wp-content/uploads/2022/i/02/word-image-437.png)

Triggering and scheduling jobs:
* On a schedule, using `Cloud Scheduler`.
* Responding to an event, using `Pub/Sub` and `Cloud Functions`. For example, the event can be the availability of new data files in a Cloud Storage bucket.
* As part of a bigger data and process workflow, using `Cloud Composer` or `Cloud Data Fusion`.


## 7.5. CI/CD
* AB and Canary testing
* Split traffic in production with small portion going to a new version of the model and verify that all metrics are as expcted, gradually increase the traffic split or rollback.

Google's Logic on building data science model:
![Google's Logic on building data science model](https://dzlab.github.io/assets/2022/01/20220108-gcp-ml-decision-flow.svg)

## 7.6. BigQuery ML
BigQuery is a managed data warehouse service, **it also has ML capabilities**. So if you see a question where the data is in BigQuery and the output will also be there then a natural answer is to use BigQuery ML for modeling.

* If using tensorflow and there is no preprocessing required in BigQuery, read data using the tfio.bigquery.BigQueryClient class is recommended.

## 7.7. What all can you do with BigQuery ML? What are its limitations
[link](https://cloud.google.com/bigquery-ml/docs/introduction)
BigQuery ML functionality is available by using:
* The Google Cloud console
* The bq command-line tool
* The BigQuery REST API
* An external tool such as a Jupyter notebook or business intelligence platform

Model availables: linear regression; binary/multiclass logistic; k-mean; matrix factorization (for creating product recommendation system); time-series; boosted-tree; deep neural network; autoML tables; tensorflow model importing (created model from previously trained tensorflow models and perform prediction); autoencoder
![big-query-supported-model](https://cloud.google.com/bigquery-ml/images/ml-model-cheatsheet.svg)

* Use it for quick and easy models, prototyping etc.
* It supports the following types of model: linear regression, binary and multiclass logistic regression, k-means, matrix factorization, time series, boosted trees, deep neural networks, AutoML models and imported TensorFlow models
* Example of training with BigQuery ML
* How to do online prediction with BigQuery ML

## 7.8. AI Platform
![link](https://skillcertpro.com/wp-content/uploads/2022/i/02/word-image-389.png)

### 7.8.1. Use automatic hyperparameter tuning
* AI Platform provides a blackbox optimization service that helps you automatically tune hyperparameters in complex ML models. When you're configuring a hyperparameter tuning job, we recommend that you set `enableTrialEarlyStopping` to `True`; this helps limits the cost of the hyperparameter tuning job
*  If you have a previous hyperparameter tuning job, you can set `resumePreviousJobId` to `True` to start from a state that is partially optimized. 
*  Set `maxParallelTrials` to be between 2 and `maxTrials`/2 in order to converge faster to good hyperparameter values, which in turn reduces cost of hyperparameter tuning.


### 7.8.2. Continuous evaluation overview
Continuous evaluation regularly samples prediction input and output from trained machine learning models that you have deployed to AI Platform Prediction. AI Platform Data Labeling Service then assigns human reviewers to provide ground truth labels for your prediction input. :arrow_right: useful for image classification evaluation


### 7.8.3. Vertex AI
#### 7.8.3.1. Prediction logging
There are two types of prediction logs that you can use to get information from your prediction nodes:
* Container logging, which logs the stdout and stderr streams from your prediction nodes to Cloud Logging. These logs are essential and required for debugging.
* Access logging, which logs information like timestamp and latency for each request to Cloud Logging.
  
#### 7.8.3.2. Model monitoring
##### 7.8.3.2.1. Data drift
* Concept drift - a change in $P(Y|X)$ is a shift in the actual relationship between the model inputs and the output :arrow_right: a big problem for steaming data
* Prediction drift - a change in $P(Y_hat|X)$ is a shift in the model's predictions. For example, the model to predict good credit customer can change in different country; can your business ready to handle different among of good credit customer in different area?
* Label drift - a change in P(Y ground truth) is a shift in the model's output or label distribution

Solution to data drift:
* Monitor data skew
* Continuous training
* Continuous modeling

##### 7.8.3.2.2. Feature store
A service to organize and store ML features through a central store. This allows you to share and optimize ML features important for the specific environment and to reuse them at any time.

#### 7.8.3.3. Model Deployment
Use reduced-precision floating-point types: Smaller models lead to lower serving latency: `mix-precision trianing`

Reduce model size using `post-training quantization`: a conversion technique that can reduce model size while also improving CPU and hardware accelerator latency, with little degradation in model accuracy. (`TensorFlow Lite Converter.`)

Use manual scaling for highly variable request volume: If the number of requests that your model receives inherently fluctuates faster than automatic scaling can keep up with, it can be more efficient to use manual scaling

Use autoscaling and set `minNodes` to zero when low latency isn't critical. This can help reduce cost when your model service isn't receiving any requests.

Use TF-TRT with NVIDIA GPU accelerators. When you use NVIDIA GPU accelerators for serving, we recommend that you use TensorFlow with TensorRT (TF-TRT)

Use `Cloud Monitoring` to configure alerts based on the ML metrics. You should monitor your model's traffic patterns, error rates, latency, and resource utilization to help you spot problems with your models, and to help find the right machine type to optimize latency and cost. 


## 7.9. APIs
### 7.9.1. Natural Language
### 7.9.2. Translation
### 7.9.3. Vision AI
### 7.9.4. Video AI
* AutoML Video Intelligence: is a service that allows you to customize the pre-trained Video intelligence GCP system according to your specific needs. In particular, AutoML Video Intelligence Object Tracking allows you to identify and locate particular entities of interest to you with your **specific tags**.
* Cloud Video Intelligence AI: similar but is a pre-configured and ready-to-use service, therefore not configurable for specific needs.

### 7.9.5. Other Products
* AutoML
* AI Platform Data Labelling Service
* AutoML Tables - [link](https://cloud.google.com/automl-tables/docs/quickstart)