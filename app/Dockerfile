FROM node:16-alpine

WORKDIR  /app
COPY package.json .

# Instalar dependências
RUN apk add --no-cache python3 g++ make
RUN yarn install --production

# Copiar todos os arquivos do projeto para /app no container
COPY . .


# Definir o comando de inicialização
CMD ["node", "src/index.js"]

# Expor a porta correta
EXPOSE 3000
