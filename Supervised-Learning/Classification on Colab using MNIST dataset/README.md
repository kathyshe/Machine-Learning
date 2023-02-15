**Introduction**

The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems. This dataset is one of the most common datasets used for image classification and accessible from many different sources.

MNIST dataset, which is a set of 70,000 small images of digits
handwritten by high school students and employees of the US Census Bureau.
Each image is labeled with the digit it represents.
This set is called the “hello world” of Machine Learning:
Whenever people come up with a new classification algorithm they are curious to see how it will perform on MNIST.

Scikit-Learn provides many helper functions to download popular datasets. MNIST is one of them.

    >>> from sklearn.datasets import fetch_openml
    >>> mnist = fetch_openml('mnist_784', version=1)
    >>> mnist.keys()
    dict_keys(['data', 'target', 'feature_names', 'DESCR', 'details',
               'categories', 'url'])

Google Colab provides free access to a Jupyter Notebook and a small version of the MNIST dataset. Aspiring data scientists can use the platform to practice and experiment with the MNIST dataset. The advantage of using Google Colab is that many popular Python libraries are already pre-installed, making it easy to get started with deep learning and computer vision. The MNIST dataset is also readily available as a sample, allowing users to quickly dive into data science and machine learning.

![classification1](https://user-images.githubusercontent.com/113223572/218920263-7619b9d5-3f00-4d03-a9d6-1169d5d6a745.JPG)

![classification2](https://user-images.githubusercontent.com/113223572/218920294-b4f1e194-11d8-419f-be92-535e5029ab8e.JPG)


**Implementation:**

https://colab.research.google.com/drive/1nhHVH-gTQnfi3rv7ZS-mjmm8y8Za7uqo?usp=sharing


Execute classification.ipynb: https://github.com/divyapandey03/Machine-Learning/blob/main/Supervised%20Learning/Classification%20on%20Colab%20using%20MNIST%20dataset/classification.ipynb

**Output:**

s1

s2

s3

s4

s5
