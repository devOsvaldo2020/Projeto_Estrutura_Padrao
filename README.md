
## bibliotecas / framworks / ferramentas usadas

👉 [MULTER](https://www.npmjs.com/package/multer)

- Descricao: Multer é uma biblioteca middleware para lidar com upload de arquivos em aplicativos Node.js. Ele fornece uma maneira fácil de lidar com as informações enviadas pelo cliente em uma solicitação multipart/form-data, que é o tipo de solicitação usado para enviar arquivos via formulário HTML.

= Multer fornece uma maneira fácil de acessar os arquivos enviados e suas informações, como o nome do arquivo e o tamanho, e pode ser usado para armazenar os arquivos em um disco local ou em um serviço de armazenamento de arquivos na nuvem, como o Amazon S3. Ele também oferece recursos avançados como suporte para upload de vários arquivos, validação de arquivos e manipulação de erros.

- Multer é uma boa escolha para projetos que precisam lidar com upload de arquivos, especialmente se estiver trabalhando com arquivos de grande tamanho e/ou número de arquivos. Ele é fácil de configurar e usar e é amplamente utilizado em projetos Node.js, especialmente em aplicativos web e APIs REST. [fonte](https://chat.openai.com/chat).

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

- Descricao: Um "CSV Parse API" é uma API (Application Programming Interface) que fornece a capacidade de analisar arquivos CSV (Comma Separated Values) e transformá-los em um formato de dados mais fácil de trabalhar, como JSON. Isso permite que aplicativos consumam e trabalhem com dados em arquivos CSV de forma fácil e eficiente.

- Existem várias bibliotecas e serviços que fornecem a funcionalidade de análise de arquivos CSV, como a biblioteca papaparse para JavaScript, a biblioteca Python csv e a biblioteca Ruby csv. Além disso, muitos serviços de nuvem como AWS, Google Cloud e Azure oferecem serviços de análise de dados que incluem a capacidade de analisar arquivos CSV.

- Além disso, algumas empresas desenvolvem suas próprias soluções de parse de CSV para atender a necessidade específica de suas aplicações, e por isso é possível encontrar APIs específicas para parse de CSV.

- Em resumo, CSV Parse API é uma ferramenta que permite a análise de arquivos CSV e sua conversão para formatos de dados mais fáceis de serem trabalhados, como JSON. Ela pode ser implementada como biblioteca ou serviço, dependendo da necessidade da aplicação. [fonte](https://chat.openai.com/chat).

```js -parse
npm install csv

yarn add csv-parse
```

<hr>

[Swagger](https://swagger.io/)

- Descricao: Swagger é uma ferramenta que permite a criação e documentação de APIs RESTful. Ele é composto por uma especificação, que define como as APIs devem ser estruturadas e documentadas, e uma série de ferramentas de desenvolvimento, que permitem a criação, teste e interação com APIs. A especificação Swagger é compatível com várias plataformas e linguagens de programação, tornando-a uma escolha popular para desenvolvimento de API. Ele também tem uma interface visual, chamada Swagger UI, onde os desenvolvedores podem experimentar e testar as chamadas da API. [fonte](https://chat.openai.com/chat).

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

## 👉 banco de dados ORMs

- pasta database na raiz é onde vai ficar o banco.

- Descricao: TypeORM é uma biblioteca ORM (Object-Relational Mapping) para TypeScript e JavaScript. Ele permite que você trabalhe com banco de dados relacionais usando objetos JavaScript ou TypeScript, em vez de escrever consultas SQL manualmente. Ele suporta vários bancos de dados populares, como MySQL, PostgreSQL, SQLite e Microsoft SQL Server.

- Com TypeORM, você pode definir modelos de entidade usando classes e decoradores, criar tabelas no banco de dados com base nesses modelos, inserir, atualizar, remover e selecionar dados usando métodos de repositório e, finalmente, usar transações para garantir a consistência dos dados. Ele também oferece recursos avançados como relacionamentos entre entidades, carregamento lazy e eager, cache de segundo nível, e muito mais.

- TypeORM é uma boa escolha para projetos que precisam de uma camada de abstração do banco de dados e suporte para TypeScript. Ele é amplamente utilizado em projetos Node.js e pode ser facilmente integrado com frameworks como Express e NestJS. [fonte](https://chat.openai.com/chat).

 👉 [typeORM](https://typeorm.io/)

```jsx
    yarn typeorm migration:create -n CreateEntidade

```

```jsx
    yarn typeorm migration:run

```

## injeção de dependência

### TSyringa

- Descricao: TSyringe é uma biblioteca de injeção de dependência para TypeScript disponível no npm (Gerenciador de Pacotes Node). Ele fornece uma forma fácil e eficiente de gerenciar as dependências em aplicativos TypeScript, incluindo a capacidade de gerenciar dependências singleton e transientes. Ele também oferece suporte para construtores com múltiplos parâmetros e pode ser usado com qualquer framework JavaScript. A biblioteca TSyringe é mantida por uma comunidade ativa e é frequentemente atualizada para incluir novos recursos e correções de bugs [fonte](https://chat.openai.com/chat).

👉 [TSyringe](https://www.npmjs.com/package/tsyringe?activeTab=readme)

```jsx
npm install --save tsyringe

yarn add tsyringe

```

## Biblioteca para criptografar as senhas

### Bcrypt

- Descricao: bcrypt é uma biblioteca de criptografia de senhas de fluxo de trabalho de hash de senha baseado em Blowfish. Ele é projetado para ser mais seguro do que outras bibliotecas de hash de senha, como o MD5 ou SHA-1, pois utiliza uma "custo" (cost) para aumentar o tempo de processamento e aumentar a segurança. A ideia é que, quanto maior o custo, mais difícil será para um atacante quebrar a senha criptografada. Outra vantagem do bcrypt é que ele gera uma "salt" (sal) aleatória para cada senha, o que significa que mesmo que duas senhas sejam iguais, as senhas criptografadas serão diferentes. Bcrypt é amplamente utilizado em aplicações web para armazenar senhas de forma segura e é uma boa escolha para aplicações que precisam de alta segurança.[fonte](https://chat.openai.com/chat)

fonte: <https://chat.openai.com>

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

### Gerador de MD5 hash

👉[MD5 qualquer](https://www.md5hashgenerator.com/)

ex: gerarummd5teste

saida: 7a21a6ec9cbba5b2995985f76edfec5c

<hr>

## Biblioteca para fazer que os erros sejam repassados

### express-async-errors

- Descricao: É um módulo de Node.js que permite lidar com erros de forma assíncrona em aplicativos Express.
 Ele faz isso adicionando uma função de middleware ao Express que captura exceções não tratadas geradas por rotas assíncronas e
 garante que elas sejam tratadas corretamente. Isso ajuda a evitar que erros críticos sejam ignorados e causem falhas no aplicativo.
 [fonte](https://chat.openai.com/chat)

👉 [express-async-errors](https://www.npmjs.com/package/express-async-errors)

```jsx
npm install express-async-errors --save

yarn add express-async-errors

```

<hr>

## Biblioteca para fazer os testes

### JEST

- Descricao: Jest é uma biblioteca de teste JavaScript criada pela Facebook.
   Ele é projetado para ser fácil de usar e inclui recursos como testes automatizados de unidade,
   cobertura de código e relatórios de teste. Jest também pode ser integrado com outras ferramentas
   de teste, como Enzyme e Puppeteer, para testar aplicativos React e aplicativos web. Além disso,
   Jest é compatível com a maioria dos principais gerenciadores de pacotes, como npm e yarn, e
   pode ser usado com vários tipos de projetos, incluindo projetos Node.js e projetos de aplicativos
   web.[fonte](https://chat.openai.com/chat)

👉 [JEST](https://jestjs.io/pt-BR/docs/getting-started).

```jsx
npm install --save-dev jest

yarn add jest @types/jest -D

```

Para rodar ele só digitar:

```js
yarn jest --init
```

```js
yarn ts-jest -D
```

e ir repondendo as perguntas

<hr>
