
<img src="https://github.com/carlosmartos13/nlw-connect-rockeseat/blob/main/figma-projeto-react-nlwconnect.png" />


## Sobre o Projeto 
Este é um projeto do estudo de um mini curso chamado NLW da Rocketseat, onde o objetivo é conhecer algumas funcionalidades importantes do react, nesse projeto usamos as tecnologias:
- @hookform/resolvers
- @tailwindcss/postcss
- lucide-react
- next
- orval
- postcss
- react
- react-dom
- react-hook-form
- tailwind-merge
- tailwindcss
- zod
- [Projeto no Figma:](https://www.figma.com/community/file/1471119935944492720)
    


## instalação

BAIXE O ARQUIVO ZIP OU FAÇA UM CLONE DO PROJETO NA SUA MAQUINA:


**BACKEND**
É necessario ter previamente instalado o node e o docker para funcionar esse projeoto

NO BACKEND INICIE A INSTALAÇÃO COM UM TERMONAL NA PASTA BACKEND USANDO O COMANDO:
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
