# autocorrectionwithtext
This repository is auto correction with text
from textblob import TextBlob

text = TextBlob('he is a gret peron')
print(text.correct())
