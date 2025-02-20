(./figma-projeto-react-nlwconnect.png)
## Sobre o Projeto

Este é um projeto do estudo de um mini curso chamado NLW da Rocketseat, onde o objetivo é conhecer algumas funcionalidades importantes do react, nesse projeto usamos as tecnologias:
    "@hookform/resolvers": "^3.10.0",
    "@tailwindcss/postcss": "^4.0.4",
    "lucide-react": "^0.474.0",
    "next": "15.1.6",
    "orval": "^7.5.0",
    "postcss": "^8.5.1",
    "react": "^19.0.0",
    "react-dom": "^19.0.0",
    "react-hook-form": "^7.54.2",
    "tailwind-merge": "^3.0.1",
    "tailwindcss": "^4.0.4",
    "zod": "^3.24.1"
    [Projeto no Figma encotrase aqui:[(https://www.figma.com/community/file/1471119935944492720)]
    


## instalação

BAIXE O ARQUIVO ZIP OU FAÇA UM CLONE DO PROJETO NA SUA MAQUINA:


**BACKEND**
É necessario ter previamente instalado o node e o docker para funcionar esse projeoto

NO BACKEND INICIE A INSTALAÇÃO USANDO O COMANDO:
```BASH
npm install
```
abra o docker em sua maquina e no terminal rode o comando abaixo para startar o docker em segundo plano:
```BASH
docker compose up -d 
```
caso não eseja funcionando esse comando, verifique se o docker esta devidamente instalado, com o comando vc verá a versão do docker:
```BASH
docker -v
```
depois disso precisa rodar o comando para criar as tabelas no banco de dados:
```BASH
npm run db:migrate   
```
agora com tudo pronto podemos iniciar o backend com o comando:
```BASH
npm run dev
```

## Front-end

na pasta front-end instale as dependencias em outro terminal
```BASH
npm install
```
inicie o projeito com:
```BASH
npm run dev
```