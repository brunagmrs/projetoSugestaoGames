# Projeto de ChatBot da Imersão IA
Neste projeto estão os arquivos que eu desenvolvi ao longo da imersão, especificamente nos últimos dias, com o auxílio das últimas aulas fornecidas pela alura.

## 👩‍💻 Chatbot Game
No arquivo chatbotgame.ipynb consta o código realizado para a criação do chat.
link do código: [chatBotGame](https://github.com/brunagmrs/projetoSugestaoGames/blob/main/chatBotGame.ipynb)

**Objetivo**

Sugerir jogos para o usuário para que ele possa jogar, conhecer, se divertir. Caso o usuário não goste de nenhuma opção ele pode pedir outras.

**Funcionalidades do Chat**

O chat de sugestão de Games possuí um menu de interação com o usuário, onde o usuário pode fazer as seguintes ações

- Inserir Preferências várias vezes, o quanto o usuário achar necessário, em forma de frases.
- Receber Sugestões de acordo com as preferências descritas ao chat
- Ver histórico com o chat desde que ele não tenha limpado suas conversas
- Sair da conversa com o chat

```python
def exibir_menu():
  """Exibe o menu de opções para o usuário."""
  while True:
    print("\n--------------------")
    print("O que você gostaria de fazer?")
    print("1. Informar minhas preferências")
    print("2. Receber sugestões de jogos")
    print("3. Ver histórico da conversa")
    print("4. Sair")
    print("--------------------")
```


É importante ressaltar que foi utilizado o Gemini para criação do código, os códigos fornecidos pela Alura e a criação do código foi feita no Google AI Studio! Independente da classificação foi muito gratificante participar da Imersão, Google e alura são minhas referências na área da tecnologia 💙
