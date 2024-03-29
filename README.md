# Projeto Trybe Futebol Clube

# Contexto
Projeto individual feito com TypeScript, Sequelize e Express. Neste projeto utilizando os princípios SOLID da Programação Orientada a Objeto, e as tipagens corretas para Sequelize, foi-se feito uma API para um site Front-end já pronto, onde o usuário faz um Login que se autenticado na API, recebe um token JWT que o permite acesso ao site por um certo período, permitindo ver, adicionar ou editar os jogos, além de ver o ranking dos times por pontos obtidos por jogo jogado. Neste projeto a maior dificuldade foi de criar classes respeitando princípios SOLID e com tipagem correta para Sequelize(Aprendi que como Sequelize utiliza classe Estática, para disponibilizar esse acesso ao constructor de um Model era necessário usar uma tipagem de instância daquela classe, para assim ter acesso ao User.findAll(), por exemplo). Projeto que me orgulho que me fez desenvolver tanto lógica em TypeScript, quanto aprimorar meus conhecimentos em Sequelize, Express.js, JWT, e testes unitários e de integração(Também feitos por mim usando Mocha Chai e Sinon), além de me fazer relembrar os conteúdos de front-end que estavam um pouco enferrujados.

## Técnologias usadas

Front-end:
> Desenvolvido usando: React, CSS3, HTML5, ES6

Back-end:
> Desenvolvido usando: NodeJS, ExpressJS, MYSQL, Sequelize, TypeScript, POO, Jwt, SOLID, Jest.


## Instalando Dependências

```bash
cd Project-Trybe-Futebol-Club/ 
npm install && npm run postinstall
``` 

## Executando aplicação

* Para rodar a aplicação:

  ```bash
  npm run compose:up
  ```

Api rodando em http://localhost:3001/ e front rodando em http://localhost:3000/

## Executando Testes

* Para rodar todos os testes:

  ```
    npm test
  ```
