

## bibliotecas / framworks / ferramentas usadas



👉 [MULTER](https://www.npmjs.com/package/multer)

```js 
npm install --save multer

yarn add multer
```

```jsx
npm install -D @types/multer

yarn add @types/multer -D
```

<hr>


👉 [CSV Parse API](https://www.npmjs.com/package/csv-parse)

```js -parse
npm install csv

yarn add csv-parse
```
<hr>




[Swagger](https://swagger.io/)

```js -parse
npm install swagger-ui-express

yarn add swagger-ui-express
```

```jsx
npm install -D @types/swagger-ui-express

yarn add @types/swagger-ui-express -D 
```
<hr>

## 👉 docker

```jsx
docker build -t Locadora-veiculos .

```

```jsx
docker run -p 3333:3333 Locadora-veiculos

```

verifica o ip do container

```jsx
docker inspect --format='{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' nome_do_container

``` 

tb da para ver o ip por esse comando

```jsx
docker exec nome_do_container cat /etc/hosts

``` 


## 👉 docker-compose  

```jsx
docker-compose up

```
```jsx
docker-compose up -d

```
```jsx
docker-compose up --force-recreate

```

##  banco de dados ORMs

 - pasta database na raiz é onde vai ficar o banco.

 👉 [typeORM](https://typeorm.io/)
 
 ```jsx
    yarn typeorm migration:create -n CreateEntidade

 ```

 ```jsx
    yarn typeorm migration:run

 ```

## injeção de dependência

### TSeringa

 - Um contêiner de injeção de dependência leve para TypeScript/JavaScript para injeção de construtor.


👉 [TSyringe](https://www.npmjs.com/package/tsyringe?activeTab=readme)

```jsx
npm install --save tsyringe

yarn add tsyringe

```
 

## Biblioteca para criptografar as senhas

### Bcrypt

 - Descricao: Faz a criptografia da senhas


👉 [bcrypt](https://www.npmjs.com/package/bcrypt)


```jsx
npm install bcript

yarn add bcrypt

```

```jsx
npm install @types/bcript -D

yarn add @types/bcript -D

```
<hr>

## Biblioteca para autenticacao

### J W T

 - Descricao: Um token JSON Web (JWT) é um padrão aberto (RFC 7519) que define uma maneira de transmitir de maneira segura e confiável as informações entre as partes como um objeto JSON. Ele consiste em três partes: cabeçalho, payload (conteúdo) e assinatura. O cabeçalho geralmente contém informações sobre o tipo de token e o algoritmo usado para assinar o token. O payload contém as informações de usuário, como o nome de usuário e papel do usuário. A assinatura é usada para garantir que o remetente do token é confiável e que o conteúdo do token não foi alterado durante a transmissão. JWT é amplamente utilizado em autenticação e autorização em aplicativos web e mobile.[fonte](https://chat.openai.com/chat)


👉 [JWT](https://jwt.io/)


### JSONWEBTOKEN 


👉 [jsonwebtoken - npm](https://www.npmjs.com/package/jsonwebtoken)


```jsx
npm install jsonwebtoken

yarn add jsonwebtoken

```

```jsx
npm install @types/jsonwebtoken -D

yarn add @types/jsonwebtoken -D

```

### gerador de MD5 hash

👉[MD5 qualquer](https://www.md5hashgenerator.com/)

ex: gerarummd5teste

saida: 7a21a6ec9cbba5b2995985f76edfec5c


<hr>


## Biblioteca para fazer que os erros sejam repassados.

### express-async-errors

 - Descricao: É um módulo de Node.js que permite lidar com erros de forma assíncrona em aplicativos Express.
 Ele faz isso adicionando uma função de middleware ao Express que captura exceções não tratadas geradas por rotas assíncronas e
 garante que elas sejam tratadas corretamente. Isso ajuda a evitar que erros críticos sejam ignorados e causem falhas no aplicativo.


👉 [express-async-errors](https://www.npmjs.com/package/express-async-errors)


```jsx
npm install express-async-errors --save

yarn add express-async-errors

```

<hr>



## Biblioteca para fazer os testes.

### JEST

 - Descricao: Jest é uma biblioteca de teste JavaScript criada pela Facebook. 
 Ele é projetado para ser fácil de usar e inclui recursos como testes automatizados de unidade, 
 cobertura de código e relatórios de teste. Jest também pode ser integrado com outras ferramentas 
 de teste, como Enzyme e Puppeteer, para testar aplicativos React e aplicativos web. Além disso, 
 Jest é compatível com a maioria dos principais gerenciadores de pacotes, como npm e yarn, e 
 pode ser usado com vários tipos de projetos, incluindo projetos Node.js e projetos de aplicativos 
 web.

👉 [JEST](https://jestjs.io/pt-BR/docs/getting-started)


```jsx
npm install --save-dev jest

yarn add jest @types/jest -D

```

<hr>









