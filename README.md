Pretrained models associated with the project: [https://github.com/bdvllrs/generalization-vision](https://github.com/bdvllrs/generalization-vision).

To load the model using gensim (tried with gensim version 4.0.1 on python 3.8.5):

```python
import gensim

model_path = "models/none_epoch-4.model"
model = gensim.models.Word2Vec.load(model_path)
```

The "none" model corresponds to a vanilla SkipGram trained without visual word embeddings (our baseline in the paper).
