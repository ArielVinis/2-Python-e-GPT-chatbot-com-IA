# OpenAI: Python e GPT - Criando Chatbot com IA

## Sobre o Projeto

Este repositório contém a implementação de um chatbot inteligente utilizando a API da OpenAI com Python. O projeto demonstra como integrar o GPT para gerar respostas dinâmicas, além de funcionalidades avançadas, como processamento de imagens com OpenAI Vision, em uma aplicação web desenvolvida com Flask.

🔗 **Repositório:** [2-Python-e-GPT-chatbot-com-IA](https://github.com/ArielVinis/2-Python-e-GPT-chatbot-com-IA)

## Objetivos

- Integrar a API da OpenAI para criar um chatbot inteligente.
- Desenvolver uma aplicação web com Flask para interagir com o chatbot.
- Implementar funcionalidades avançadas, como:
  - Processamento e interpretação de imagens com OpenAI Vision.
  - Gerenciamento do histórico de conversas.
  - Functions Calling para funcionalidades adicionais, como validação de cupons.
- Refinar o contexto e a personalização da conversa para diferentes cenários.

## Tecnologias Utilizadas

- **Python**: Linguagem principal da aplicação.
- **OpenAI API**: Para integração com o GPT e outras funcionalidades.
- **Flask**: Microframework para criação do servidor web e definição de rotas.
- **numpy**: Suporte para operações matemáticas.
- **python-dotenv**: Gerenciamento de variáveis de ambiente.
- **tiktoken**: Manipulação de tokens para a API da OpenAI.
- **opencv-python**: Processamento de imagens.
- **Outras dependências**: Definidas em `requirements.txt`.

## Funcionalidades do Projeto

1. **Integração com o Front-End**
   - Conexão do GPT ao front-end do chatbot através de rotas definidas com Flask.
   - Associação de um documento para definir o contexto da conversa.

2. **Refinamento do Contexto**
   - Personalização da experiência do usuário para contextos específicos, como em um e-commerce.
   - Utilização de documentos distintos para adaptar a conversa à persona desejada.

3. **Gerenciamento do Histórico**
   - Implementação de assistentes e threads para manter um histórico coerente das interações.
   - Uso de metadados para gerenciar o histórico e melhorar a contextualização das respostas.

4. **Refatoração e Functions Calling**
   - Organização do código em funções estruturadas para interação com a API da OpenAI.
   - Implementação de Functions Calling para funcionalidades avançadas, como a validação de cupons.

5. **Interpretação de Imagens com OpenAI Vision**
   - Adaptação da aplicação Flask para a leitura e processamento de imagens.
   - Gerenciamento de imagens temporárias e análise via OpenAI Vision para gerar respostas dinâmicas.

## Estrutura do Projeto
```
chatbot-ia/
├── src/
│ ├── app.py # Aplicação Flask principal
│ ├── routes/ # Definição das rotas do chatbot
│ ├── services/ # Funções para interação com a API da OpenAI
│ ├── templates/ # Arquivos HTML para o front-end
│ └── static/ # Arquivos estáticos (JS, CSS, imagens)
│
├── .env # Variáveis de ambiente
├── requirements.txt # Lista de dependências
└── README.md # Documentação do projeto
```


## Como Configurar e Executar a Aplicação

1. **Clone o repositório:**
  ```sh
  git clone https://github.com/ArielVinis/2-Python-e-GPT-chatbot-com-IA.git
  cd 2-Python-e-GPT-chatbot-com-IA
  ```

2. **Crie e ative o ambiente virtual:**
  ```sh
  python -m venv venv
  source venv/bin/activate   # Linux/MacOS
  venv\Scripts\activate      # Windows
  ```

3. **Instale as dependências:**
  ```sh
  pip install -r requirements.txt
  ```

4. **Configure as variáveis de ambiente:
• Crie um arquivo .env e defina as variáveis necessárias, por exemplo:
  ```ini
  OPENAI_API_KEY=your_openai_api_key
  ```

5. **Execute a aplicação:**
  ```sh
  flask run
  ```

## Considerações Finais
Este projeto oferece uma abordagem prática para a criação de chatbots com inteligência artificial, integrando desde a conexão básica com a API da OpenAI até funcionalidades avançadas, como processamento de imagens e gerenciamento do histórico de interações.
Contribuições e sugestões são bem-vindas! 🚀
