# Classificação de E-mails Spam com Naive Bayes

Este projeto foi desenvolvido como parte da disciplina **Sistemas Inteligentes** na faculdade, com o objetivo de aplicar técnicas de **aprendizado supervisionado** utilizando um dataset real disponível no Kaggle.

## 📨 Objetivo

Classificar e-mails como **Spam** ou **Ham** (não spam), utilizando um modelo baseado em **Naive Bayes**.

## 📊 Dataset

- **Nome:** Spam Email
- **Arquivo:** `spam.csv`
- **Origem:** [Kaggle](https://www.kaggle.com/datasets/abdallahwagih/spam-emails)

O dataset contém mensagens de texto rotuladas como "spam" ou "ham" (não spam). Foi utilizado para treinar e testar um classificador supervisionado.

## 🧠 Técnica Utilizada

- **Modelo:** Multinomial Naive Bayes (`MultinomialNB`)
- **Pré-processamento:** 
  - Limpeza e normalização dos textos
  - Remoção de stopwords
  - Vetorização com `CountVectorizer`

## ✅ Resultados

- **Acurácia no conjunto de teste:** **98.65%**

## 📎 Arquivos

- `notebook.ipynb`: Código-fonte do projeto em Python (Jupyter/Colab)
- `projeto.pdf`: Documento completo com descrição teórica, metodologia e resultados
- `spam.csv`: Dataset utilizado para treinamento e validação

## 📜 Licença

Este projeto está sob a **Licença Apache 2.0** — consulte o arquivo [`LICENSE`](./LICENSE) para mais detalhes.

O dataset utilizado está disponível publicamente no Kaggle e é licenciado sob **Apache License 2.0**, com uso permitido para fins de **pesquisa e análise**.

## ⚠️ Aviso Legal

Este repositório é destinado **exclusivamente para fins educacionais e acadêmicos**. Nenhum dado aqui deve ser utilizado para fins comerciais ou que infrinjam direitos de terceiros.
