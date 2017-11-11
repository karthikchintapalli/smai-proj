# smai-proj

## Requirements
1. python3
2. numpy
3. cPickle # use `pickle` instead as default pickle in python3 is cPickle and does not require a separate installation of the library
4. keras
5. tensorflow

## Lexical features

1. avg. chars per e-mail
2. digits to total chars. ratio
3. ratio of spaces to total chars. | avg length of word
4. normalized freq. of special characters(commas and semi-colons)
5. avg. words per email
6. avg. sentence length
7. vocab richness

## Syntactic features

1. freq of function words
2. freq of punctuation
3. freq. of personal pronouns and adjective.
4. pos tag bigrams/trigrams

## Structural features

1. avg ratio of no. of paras to length of doc
2. avg no. of sentences per paragraph.
3. Type of greeting.

## Content features:
1. 

## Reference papers
https://arxiv.org/pdf/1609.06686.pdf

http://www.aclweb.org/anthology/E17-2106