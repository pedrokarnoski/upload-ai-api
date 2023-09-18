# upload.ai

Bem-vindo ao repositório da api do projeto upload.ai! Este repositório contém o código-fonte e os recursos relacionados à api destinada a aplicação upload.ai.

## Descrição

upload.ai é uma API desenvolvida com Node.js e TypeScript que oferece recursos avançados de processamento de vídeos utilizando tecnologias como fastify, Prisma, Zod, OpenAI Node API Library e Vercel AI SDK.

## Recursos Principais

- **Upload de vídeos**: Faça o upload de vídeos para a API para análise e processamento de descrições e títulos para o YouTube.

- **Integração com OpenAI**: A integração com a OpenAI Node API Library permite o uso de modelos de linguagem avançados para tarefas de processamento de texto.

## Configuração

Antes de começar a usar o upload.ai, siga estas etapas de configuração:

1. Clone este repositório para o seu ambiente de desenvolvimento:

   ```bash
   git clone https://github.com/pedrokarnoski/upload-ai-api.git

2. Instale as dependências necessárias com o gerenciador de pacotes de sua escolha (escolha um dos seguintes comandos):

   - Usando npm:
     ```bash
     cd upload-ai-api
     npm install
     ```

   - Usando yarn:
     ```bash
     cd upload-ai-api
     yarn
     ```

   - Usando pnpm:
     ```bash
     cd upload-ai-api
     pnpm install
     ```

3. Crie uma nova conta na [OpenAI](https://platform.openai.com/). Gere uma chave para a [API](https://platform.openai.com/account/api-keys)
4. Adicone a chave gerada nas suas variáveis de ambiente no projeto, (.env) com o nome "OPENAI_KEY".
