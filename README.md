# 📕 Goodreads: DistilBERT AutoModel (Tensorflow)

## Use Book Reviews to Predict Ratings

<div align="center">
    <img src="https://github.com/justinsiowqi/-Goodreads-DistilBERT-AutoModel-Tensorflow-/blob/main/Sesame%20Street.gif?raw=true" alt="Sesame Street" style="width: 500px;"> 
</div>
<div align="center">
  © Sesame Street (1969 TV Series)
</div>

<div>
    
&nbsp;
    
In this notebook, we will create a **DistilBERT model** that is able to take book reviews, understand them and use them to predict book ratings. The **AutoTokenizer** and **AutoModel** classes from the **HuggingFace library** will come in handy here! 

Also, since we're working with two huge datasets, we'll need to make certain adjustments to speed up the processing. This can be achieved through **Datatable**, **random sampling** and **fast tokenizers**. 

Let's dive in!

## Getting Started

These steps will guide you in running the project on your own computer.

### Prerequisites

* Python 3.10.8

### Installing

```
install datatable
install pandas
install pickle
install numpy
import tensorflow 
install transformers
```
