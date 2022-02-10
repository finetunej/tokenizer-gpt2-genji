# tokenizer-gpt2-genji
huggingface transformers compatible GPT2Tokenizer files for genji-v2 model

## usage

clone this repo and inside run this code to load the tokenizer from the gpt2-genji folder

```python
from transformers import GPT2Tokenizer

tokenizer = GPT2Tokenizer.from_pretrained("gpt2-genji")
print(tokenizer.encode("良い天気だね。"))
```

## note

to avoid ambiguous attempts at tokenization by language models, ban them from generating:

```
[37605]
[22522]
[5099]
[39752]
[32368]
[17992]
[39187]
[40367]
[47571]
[15790] 
[40265]
[27032]
[28156]
[30298]
[34650]
[36685]
```
