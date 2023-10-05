# Language modeling

Additional materials:

- [Blogpost about LSTM](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- [Blogpost about word embeddings](https://lena-voita.github.io/nlp_course/word_embeddings.html)
- [Blogpost about language modeling](https://lena-voita.github.io/nlp_course/language_modeling.html)


Some examples of applications beyond NLP:

- [Decision transformer](https://arxiv.org/abs/2106.01345) -- трансформер (архитектура, которую мы рассмотрим на следующей паре!) для RL. Идея заключается в том, чтобы представить данные для RL как последовательность троек: состояние среды - действие - награда
- [GATO](https://arxiv.org/abs/2205.06175) -- мультимодальный агент, который принимает на вход и генерирует разные модальности
- [CoLES](https://www.scopus.com/record/display.uri?eid=2-s2.0-85132703424&doi=10.1145%2F3514221.3526129&origin=inward&txGid=a67c6089b81d3f9a0f30014a0da97438) -- немного другой принцип, чем языковое моделирование, - маскирование (про которое Дарима немного сказала на паре, но подробнее тоже на следующей разберём). Здесь транзакции представляют в виде последовательности
