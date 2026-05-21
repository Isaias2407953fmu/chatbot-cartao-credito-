# chat-bot-cartao-credito-
APS - IAAM

git init
git add .
git commit -m "Primeira versão do chatbot Flask"
git branch -M main
git remote add origin https://github.com/Isaias2407953fmu/chatbot-cartao-credito.git
git push -u origin main

# Chat Bot Cartão de Crédito

Chatbot em Flask que usa Naive Bayes pra classificar dúvidas sobre cartão.

## Como rodar
1. `pip install -r requirements.txt`
2. `python app.py`
3. Acessar `http://127.0.0.1:5000`

## Treino
O arquivo `dados/perguntas.csv` contém as frases e categorias usadas no treino.
