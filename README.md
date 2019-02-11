# arts and crafts

Multi-layer Recurrent Neural Networks (LSTM, RNN) for word-level language models in Python using TensorFlow.

Used code from https://github.com/hunkim/word-rnn-tensorflow which is inspired from Andrej Karpathy's [char-rnn](https://github.com/karpathy/char-rnn).


I used *Love Letters of Nathaniel Hawthorne*, volumes 1 and 2. I found the books as text files from Project Gutenberg. 

http://www.gutenberg.org/ebooks/41309
http://www.gutenberg.org/ebooks/41368


# Basic Usage
To train with default parameters on your own corpus, 
replace the sample.txt file with an appropriately sized .txt file (at least 1 MB) 


train:
```bash
python train.py
```
run:
```bash
python sample.py
```

# Sample output

![alt text](https://github.com/sarahmfrost/artsandcrafts/blob/master/rnn_image1.PNG)
