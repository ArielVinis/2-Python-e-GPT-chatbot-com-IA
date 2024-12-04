# OpenAI: Python e GPT: criando chatbot com IA

## ⚙️ Configuração do Ambiente

### Criando e Ativando o Ambiente Virtual

**Windows:**

```bash
python -m venv curso_2_openai
curso_2_openai\Scripts\activate
```

### Instalação das Bibliotecas

```bash
pip install numpy openai python-dotenv tiktoken flask opencv-python
```

## 📚 Referências de Leitura

- [Documentação Whisper](https://openai.com/research/whisper)
- [Documentação Dall-E](https://openai.com/research/dall-e)
- [Preços OpenAI](https://openai.com/pricing)
- [Áudios Longos](https://platform.openai.com/docs/guides/speech-to-text/prompting)

## 01. Integrando a API com o front-end

- Fazer a conexão do GPT com o front-end do nosso chatbot, através da criação de rotas usando o microframework Flask;
- Conectar seu chatbot com a API da OpenAI e associar um documento para definição de contexto no seu chatbot.

## 02. Refinando o contexto de um chatbot

- Aplicar a mudança de contexto em chatbots, criando uma experiência mais personalizada ao usuário em um e-commerce com base no uso de uma persona;
- Utilizar documentos distintos para adequar o chatbot a um contexto específico, proporcionando uma experiência de usuário mais consistente, baseada na seleção adequada de contextos.

## 03. Gerenciando o histórico do chatbot com um assistente

- Qual é o papel de assistentes e threads na construção de um chatbot;
- A implementar threads e assistentes com capacidade de consulta em arquivos para estruturação de respostas contextualizadas;
- A usar metadados para gerenciar um assistente por aplicação.

## 04. Refatorando o código e incluindo ferrmantas: Functions Calling

- Estruturar functions utilizando a OpenAI;
- Descrever functions para uso com a API da OpenAI;
- Implementar Functions Calling para validação de um cupom no e-commerce EcoMart.

## 05. Interpretando imagens com OpenAI Vision

- Adaptar uma aplicação Flask com chamadas JavaScript para que seja possível realizar a leitura de imagens em uma aplicação com chatbot;
- Gerenciar imagens temporárias para interpretação utilizando OpenAI Vision;
- Analisar imagens para composição de respostas do chatbot.
