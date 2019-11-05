## Par de pontos mais próximo: TSNE Word Vectors

**Nome:** Vinicius Ferreira Bernardo de Lima <br/>
**Matrícula:** 15/0151331

**Nome:** João Robson Santos Martins <br/>
**Matrícula:** 15/0154003

Em Machine Learning, mais especificamente no ramo NLP (Natural Language Processing), o pré processamento do texto usado como feature deve levar em consideração eventuais erros gramaticais presentes no dataset. Para minimizar esse problema e reduzir a dimensionalidade das features (tokens únicos no texto), pode ser utilizado o [Word2Vec](https://radimrehurek.com/gensim/models/word2vec.html) para produzir conjuntos de palavras próximas gramaticalmente.
Nesse projeto, utilizando o dataset com [notícias da agência Reuters de 2016 a 2018](https://www.kaggle.com/astoeckl/newsen) encontrado na plataforma Kaggle, foi gerado um TSNE o qual comprime as 100 dimensões geradas pelo Word2Vec em um par de coordenadas x e y para cada palavra. Com isso, foi utlizado o algoritimo de par de pontos mais próximos para descobrir as palavras mais próximas gramaticalmente e semanticamente do dataset.
