# Book-Recommender
✨Um sistema de recomendação de livros usando python e LLM. As recomendações podem ser feitas através de prompts, tags de categorias e emoções. 


Refazendo um trabalho da faculdade da disciplina de Inteligencia Artificial, com o intuito de praticar.

### O projeto é dividido em quatro partes.
* Data-Exploration - Filtragem e Organização de metadados para que tenhamos um dataset limpo e facilitar a manipulação ✅
* Vector Search - Possibilita que o usuario faça pedidos de recomedaçã. Usando langchain, o sistema analisa as descrições dos livros e devolve 10 recomendações que cabem no que foi pedido. ✅
* Categories Classification - Filtragem e simplificação dos generos de livros no database, usando LLM para fazer a classificação de texto. ✅
* Sentiment Analysis - Usando a descrição dos livros, o sistema classifica os tipos de emoções que o livro passa analisando o texto das descrições e devolve as recomendações com maior propabilidade de passar a emoção filtrada ✅

* Dashboard 👷🏽‍♀️🚧


## ⭐Instruções de uso:

Antes de começar é nescessario gerar uma API key do hugging face🔗https://huggingface.co/

### Verifique-se que as bibliotecas nescessarias estão instaladas
* Para Data-Exploration: pip install pandas numpy matplotlib seaborn
* Para Vector-Search: pip install python-dotenv langchain langchain-community langchain-huggingface chromadb sentence-transformers protobuf==3.20.3

### Verifique também que o dataset _books.csv_ se encontra na pasta books-data
