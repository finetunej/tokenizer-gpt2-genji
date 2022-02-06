# tokenizer-gpt2-genji
huggingface transformers compatible GPT2Tokenizer files for genji-v2 model

## usage

```python
from transformers import GPT2Tokenizer

tokenizer = GPT2Tokenzier.from_pretrained("gpt2-genji")
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
```
