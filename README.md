# Analise de Sentimentos com Language Studio no Azure AI 🌐
🎯🧑‍💻Neste desafio, tive a oportunidade de aprender a realizar análise de sentimentos utilizando o Language Studio no Azure AI

📌 Links importantes:

- [Explore Speech Studio](https://aka.ms/ai900-speech)
- [Analyze text with Language Studio](https://aka.ms/ai900-text-analysis)

# Tópico 1: conhecendo a função de converter fala para texto📜

## Passo 1: Criando recurso do Speech service no Azure AI Services e convertendo fala em texto

Primeiro passo criar o recurso do Speech service dentro do Azure AI Services.
![image](https://github.com/user-attachments/assets/6ad8fee8-83c2-4ab8-8b78-08bbc0dd36f4)

![Captura de tela 2025-03-03 004556](https://github.com/user-attachments/assets/aad505f8-869d-4770-891f-50969a592e2d)


Após o recurso ter sido criado, tive que acessar o [Estúdio de fala do Azure](https://speech.microsoft.com/portal). Na página inicial, no tópico "Conversão de fala em texto", cliquei em "Conversão de fala em texto em tempo real".

**Observação:** Embora este tenha sido o método utilizado, o vídeo de referência demonstra um processo alternativo dentro do Estúdio de Fala, que também é válido.

Em seguida, realizei o upload de uma gravação de voz, que foi rapidamente convertida para texto.


Esse foi o resultado da conversão:

![Captura de tela 2025-03-03 004426](https://github.com/user-attachments/assets/c339b62f-0cda-4e08-977d-8eef482e6550)

# Tópico 2: Análise de sentimento

## Passo 1: Criando um recurso do Language Service no Azure AI Services

O primeiro passo foi criar um recurso do Language Service no Azure AI Services.

![Captura de tela 2025-03-03 004324](https://github.com/user-attachments/assets/1d9a8355-e8b3-482c-b553-8312561cf833)

Após o recurso ter sido criado, acessei o [Estúdio de linguagem do Azure](https://language.cognitive.azure.com/).

Assim que foi logado, foi preciso indicar a minha assinatura e o recurso que eu havia criado em um modal que abriu. Também é possível criar um novo recurso de linguagem aqui.

Após o login, selecionei minha assinatura e o recurso criado em um modal. Também há a opção de criar um novo recurso diretamente aqui.

Na aba "Classify text", cliquei em "Analyze sentiment and opinions". Selecionei "English" como idioma e inseri um texto sobre um computador para análise.
![Captura de tela 2025-03-03 012147](https://github.com/user-attachments/assets/2d50c9e2-4975-41e6-bd7f-637b9621e91a)


Resultado da análise do texto:
![Captura de tela 2025-03-03 012209](https://github.com/user-attachments/assets/5aad95cf-dd2b-42fd-9134-2020bc9f60b7)


###  Limpeza

Após a conclusão do desafio, todos os recursos criados foram removidos para evitar cobranças.

