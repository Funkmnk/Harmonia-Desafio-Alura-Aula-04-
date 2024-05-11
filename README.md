# Harmonia (Desafio Alura Aula 04)

### Harmonia: Seu Guia Personalizado para uma Vida Organizada.

#### Descrição:
Este código cria um chatbot assistido por IA chamado Harmonia, que auxilia os usuários em questões organizacionais. O chatbot usa os seguintes recursos:

- **Google Generative AI:** Gera respostas de texto usando o Gemini, um modelo de IA de linguagem.
- **NLTK:** Processa texto removendo stop words, pontuação e calculando semelhança semântica.

#### Requisitos:

- Python instalado
- Conta do Google Cloud com acesso à API do Google Generative AI

#### Instalação:

```pyton
pip install -q -U google-generativeai nltk
```

#### Configuração da API do Google:

- Acesse [Google AI Studio](https://aistudio.google.com/app/apikey) e ative a API do Google Generative AI.
- Crie uma chave de API e salve-a como [SECRET_KEY](https://youtu.be/9IiWoiBhWiA?si=6GioB5rvKdbo2idy&t=853).

#### Execução:

- Execute o script Python.
- Você será saudado pelo chatbot Harmonia, que fará perguntas para entender seu problema organizacional.
- Forneça respostas detalhadas e o chatbot oferecerá soluções e orientações personalizadas.
- Use palavras-chave como "sair", "encerrar" ou "sair" para encerrar a conversa.

#### Funções Auxiliares:
- **preprocessar_texto:** Remove stop words e pontuação do texto.
- **similaridade_semantica:** Calcula a similaridade entre dois textos.
- **gerar_resposta:** Gera respostas usando o Gemini.

#### Observações:

- O chatbot Harmonia pode fornecer respostas diferentes dependendo da entrada do usuário.
- As soluções organizacionais recomendadas são baseadas em textos gerados por IA e podem variar em eficácia.
- O chatbot não armazena ou rastreia seus dados pessoais.
