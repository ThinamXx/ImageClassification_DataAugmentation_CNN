# **Image Classification and Data Augmentation**

**Fastai Library or API**
- [Fast.ai](https://www.fast.ai/about/) is the first deep learning library to provide a single consistent interface to all the most commonly used deep learning applications for vision, text, tabular data, time series, and collaborative filtering.
- [Fast.ai](https://www.fast.ai/about/) is a deep learning library which provides practitioners with high-level components that can quickly and easily provide state-of-the-art results in standard deep learning domains, and provides researchers with low-level components that can be mixed and matched to build new approaches

**Data Augmentation**
- Data augmentation is a strategy that enables practitioners to significantly increase the diversity of data available for training models, without actually collecting new data. Data augmentation techniques such as cropping, padding, and horizontal flipping are commonly used to train large neural networks.

**Preparing the Model**
- I have used [Fastai](https://www.fast.ai/about/) API to train the Model. It seems quite challenging to understand the code if you have never encountered with Fast.ai API before.
One important note for anyone who has never used Fastai API before is to go through [Fastai Documentation](https://docs.fast.ai/). And if you are using Fastai in Jupyter Notebook then you can use doc(function_name) to get the documentation instantly.

**Dataset**
- Fastai has its own [Dataset](https://docs.fast.ai/datasets.html).I have used Fastai's PETS Dataset using the following lines of codes:
```javascript
untar_data(URLs.PETS)/'images'
```
