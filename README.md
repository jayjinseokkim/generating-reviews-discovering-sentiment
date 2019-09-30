# generating-reviews-discovering-sentiment
Code for "Learning to Generate Reviews and Discovering Sentiment"

This is where we'll be putting code related to the paper [Learning to Generate Reviews and Discovering Sentiment](https://arxiv.org/abs/1704.01444).

Radford, A., Jozefowicz, R., & Sutskever, I. (2017). Learning to generate reviews and discovering sentiment. arXiv preprint arXiv:1704.01444.

Right now the code supports using the language model as feature extractor.

```
from encoder import Model

model = Model()
text = ['demo!']
text_features = model.transform(text)
```
