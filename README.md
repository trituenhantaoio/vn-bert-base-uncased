# Update Feb, 2nd
The model is available on [Hugging Face](https://huggingface.co/trituenhantaoio)
## Usage
```python
from transformers import BertForSequenceClassification
from transformers import BertTokenizer
model = BertForSequenceClassification.from_pretrained("trituenhantaoio/bert-base-vietnamese-uncased")
tokenizer = BertTokenizer.from_pretrained("trituenhantaoio/bert-base-vietnamese-uncased")
```
# vn-bert-based-uncased
Pretrained Vietnamese BERT

To use the model, please download [the release](https://github.com/trituenhantaoio/vn-bert-base-uncased/releases/download/v0.1/vn-bert-base-uncased.zip).

You can also see the example of loading and using the model in this [colab notebook](https://colab.research.google.com/github/trituenhantaoio/vn-bert-base-uncased/blob/main/How_to_use_vn_bert_base_uncased_trituenhantao_io.ipynb).

Good luck!

### References

```
@article{ttnt2020bert,
  title={Vietnamese BERT: Pretrained on News and Wiki},
  author={trituenhantao.io},
  year = {2020},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/trituenhantaoio/vn-bert-base-uncased}},
}
```

[trituenhantao.io](https://trituenhantao.io)
