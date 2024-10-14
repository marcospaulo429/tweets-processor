# Tweets Processor

## Introdução
O uso de inteligência artificial no mercado financeiro vem crescendo anualmente devido à grande capacidade desses algoritmos em ajudar na tomada de decisões, na previsão de tendências e na análise de sentimentos. No âmbito da análise de sentimentos, essa pesquisa foi conduzida com o objetivo de fazer um pipeline eficiente de pré-processamento de tweets sobre ações da bolsa de valores brasileira e preparar os tweets coletados para uma análise mais aprofundada usando LLMs para classificar os sentimentos nas frases.

## Objetivo 
Desenvolver técnicas de pré-processamento de linguagem natural para melhorar a performance do modelo de classificação de sentimentos feito posteriormente pelo aluno de mestrado Leandro Araujo (coautor).

## Métodos

1- Lowercase. 2- Retirar SPAM (exemplo: “imploro por socorro”). 3-Remover URL. 4-Remover RT. 5-Remover emails. 6-Remoção de menções (@). 7-Remover hashtags. 
8-Remover \n. 9-Remover números. 10-Remover símbolos desnecessários. 11-Remover tweets que não são em português-BR. 12-Normalizador. 13-Remover acentos. 
14-Remover stopwords. 15-Remover palavrões. 
16-Lematização, 17-Tokenização, TF-IDF e Bag of Words.
