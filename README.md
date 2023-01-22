
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

## 👉 [CSV Parse API](https://www.npmjs.com/package/csv-parse)

- Descricao: Um "CSV Parse API" é uma API (Application Programming Interface) que fornece a capacidade de analisar arquivos CSV (Comma Separated Values) e transformá-los em um formato de dados mais fácil de trabalhar, como JSON. Isso permite que aplicativos consumam e trabalhem com dados em arquivos CSV de forma fácil e eficiente.

- Existem várias bibliotecas e serviços que fornecem a funcionalidade de análise de arquivos CSV, como a biblioteca papaparse para JavaScript, a biblioteca Python csv e a biblioteca Ruby csv. Além disso, muitos serviços de nuvem como AWS, Google Cloud e Azure oferecem serviços de análise de dados que incluem a capacidade de analisar arquivos CSV.

- Além disso, algumas empresas desenvolvem suas próprias soluções de parse de CSV para atender a necessidade específica de suas aplicações, e por isso é possível encontrar APIs específicas para parse de CSV.

- Em resumo, CSV Parse API é uma ferramenta que permite a análise de arquivos CSV e sua conversão para formatos de dados mais fáceis de serem trabalhados, como JSON. Ela pode ser implementada como biblioteca ou serviço, dependendo da necessidade da aplicação. [fonte](https://chat.openai.com/chat).

```js -parse
npm install csv

yarn add csv-parse
```

<hr>

## 👉 [Swagger](https://swagger.io/)

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

<hr>

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

<hr>

## 👉 banco de dados ORMs

- Pasta database na raiz é onde vai ficar o banco.

- Descricao: TypeORM é uma biblioteca ORM (Object-Relational Mapping) para TypeScript e JavaScript. Ele permite que você trabalhe com banco de dados relacionais usando objetos JavaScript ou TypeScript, em vez de escrever consultas SQL manualmente. Ele suporta vários bancos de dados populares, como MySQL, PostgreSQL, SQLite e Microsoft SQL Server.

- Com TypeORM, você pode definir modelos de entidade usando classes e decoradores, criar tabelas no banco de dados com base nesses modelos, inserir, atualizar, remover e selecionar dados usando métodos de repositório e, finalmente, usar transações para garantir a consistência dos dados. Ele também oferece recursos avançados como relacionamentos entre entidades, carregamento lazy e eager, cache de segundo nível, e muito mais.

- TypeORM é uma boa escolha para projetos que precisam de uma camada de abstração do banco de dados e suporte para TypeScript. Ele é amplamente utilizado em projetos Node.js e pode ser facilmente integrado com frameworks como Express e NestJS. [fonte](https://chat.openai.com/chat).

## 👉 [typeORM](https://typeorm.io/)

```jsx
    yarn typeorm migration:create -n CreateEntidade

```

```jsx
    yarn typeorm migration:run

```

<hr>

## injeção de dependência

### TSyringa

- Descricao: TSyringe é uma biblioteca de injeção de dependência para TypeScript disponível no npm (Gerenciador de Pacotes Node). Ele fornece uma forma fácil e eficiente de gerenciar as dependências em aplicativos TypeScript, incluindo a capacidade de gerenciar dependências singleton e transientes. Ele também oferece suporte para construtores com múltiplos parâmetros e pode ser usado com qualquer framework JavaScript. A biblioteca TSyringe é mantida por uma comunidade ativa e é frequentemente atualizada para incluir novos recursos e correções de bugs [fonte](https://chat.openai.com/chat).

## 👉 [TSyringe](https://www.npmjs.com/package/tsyringe?activeTab=readme)

```jsx
npm install --save tsyringe

yarn add tsyringe

```

<hr>

## Biblioteca para criptografar as senhas

### Bcrypt

- Descricao: bcrypt é uma biblioteca de criptografia de senhas de fluxo de trabalho de hash de senha baseado em Blowfish. Ele é projetado para ser mais seguro do que outras bibliotecas de hash de senha, como o MD5 ou SHA-1, pois utiliza uma "custo" (cost) para aumentar o tempo de processamento e aumentar a segurança. A ideia é que, quanto maior o custo, mais difícil será para um atacante quebrar a senha criptografada. Outra vantagem do bcrypt é que ele gera uma "salt" (sal) aleatória para cada senha, o que significa que mesmo que duas senhas sejam iguais, as senhas criptografadas serão diferentes. Bcrypt é amplamente utilizado em aplicações web para armazenar senhas de forma segura e é uma boa escolha para aplicações que precisam de alta segurança. [fonte](https://chat.openai.com/chat)

## 👉 [bcrypt](https://www.npmjs.com/package/bcrypt)

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

## 👉 [JWT](https://jwt.io/)

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

<hr>

### Gerador de MD5 hash

## 👉[MD5 qualquer](https://www.md5hashgenerator.com/)

ex: gerarummd5teste

saida: 7a21a6ec9cbba5b2995985f76edfec5c

<hr>

## Biblioteca para fazer que os erros sejam repassados

### express-async-errors

- Descricao: É um módulo de Node.js que permite lidar com erros de forma assíncrona em aplicativos Express.
 Ele faz isso adicionando uma função de middleware ao Express que captura exceções não tratadas geradas por rotas assíncronas e
 garante que elas sejam tratadas corretamente. Isso ajuda a evitar que erros críticos sejam ignorados e causem falhas no aplicativo.
 [fonte](https://chat.openai.com/chat)

## 👉 [express-async-errors](https://www.npmjs.com/package/express-async-errors)

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

## 👉 [JEST](https://jestjs.io/pt-BR/docs/getting-started).

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

## Biblioteca para traduzir os imports para o tsconfig

### tsconfig-paths

- Descricao: tsconfig-paths é um pacote npm que permite resolver caminhos de módulo em arquivos TypeScript (tsconfig.json) de forma semelhante a como o Node.js resolve caminhos de módulo com base no arquivo package.json. Ele é útil quando você está usando caminhos relativos para importar módulos em seu código TypeScript, pois permite que você configure esses caminhos uma vez no arquivo tsconfig.json e os use em todo o seu projeto. Além disso, ele também permite a você usar caminhos de módulo baseados em alias, o que pode tornar seu código mais legível e fácil de manter. [fonte](https://chat.openai.com/chat)

## 👉 [tsconfig-paths -npm](https://www.npmjs.com/package/tsconfig-paths).

```jsx
npm install --save-dev tsconfig-paths

yarn add tsconfig-paths -D

yarn add --dev tsconfig-paths

```

<hr>


<!-- 

## Biblioteca para 

### 

- Descricao: [fonte](https://chat.openai.com/chat)

👉 []().

```jsx
npm 

yarn

```

<hr>

 -->

# Requisitos

**RF** => Requisitos funcionais

- Descricao: Os requisitos funcionais são especificações que descrevem as funcionalidades e características de um sistema, produto ou serviço. Eles incluem informações sobre o que o sistema deve fazer, como ele deve fazê-lo e os resultados esperados. Esses requisitos são geralmente expressos em termos do usuário e são usados ​​como base para o desenvolvimento de software, projetos de engenharia e outros projetos. Eles são geralmente documentados em um documento chamado "Especificação de Requisitos" e são revisados ​​e aprovados pelos stakeholders antes do início do desenvolvimento. [fonte](https://chat.openai.com/chat)

**RNF** => Requisitos não funcionais

- Descricao: Os requisitos não funcionais são especificações que descrevem as características de um sistema, produto ou serviço que não se relacionam diretamente com suas funcionalidades. Eles incluem informações sobre desempenho, escalabilidade, segurança, usabilidade, compatibilidade, conformidade e outras características importantes que afetam o uso e a operação do sistema. Esses requisitos são geralmente expressos em termos técnicos e são usados ​​como base para o desenvolvimento de software, projetos de engenharia e outros projetos. Eles são geralmente documentados em um documento chamado "Especificação de Requisitos" e são revisados ​​e aprovados pelos stakeholders antes do início do desenvolvimento. [fonte](https://chat.openai.com/chat)

**RN** => Regra de negócio

- Descricao: As regras de negócio são as regras e políticas estabelecidas pela empresa ou organização para governar as operações e decisões de negócios. Elas descrevem como as tarefas e processos de negócios devem ser realizados, quais são as condições para tomar decisões e como essas decisões afetam os resultados financeiros e outros aspectos do negócio. Elas são geralmente baseadas nas estratégias e objetivos de negócios da empresa e são aplicadas em todos os níveis da organização. Elas podem ser formalmente documentadas ou transmitidas de forma informal, por exemplo, através de treinamento e orientação. As regras de negócio são utilizadas para guiar a tomada de decisão e garantir a consistência no processo de negócios, além de ajudar a mitigar riscos e garantir a conformidade com regulamentos. [fonte](https://chat.openai.com/chat)

<hr>

## cadastro de carro

<!-- id, nome, descricao, valor_diaria, disponivel, multa, marca -->
**RF**

- Deve ser possivel cadastrar um novo carro.
- deve ser possivel listar todas as cartegorias

**RNF**

- null

**RN**

- nao deve ser possivel cadastrar um carro com uma placa ja existente.

- nao deve ser possivel alterar a placa de um carro ja cadastrado.

- o carro deve ser cadastrado como disponibilidade true, como padrao.

- O cadastro deve ser feito pelo user adm.

<hr>

## listagem de carro

<!-- id, nome, descricao, valor_diaria, disponivel, multa, marca -->
**RF**

- Deve ser possivel listar todos carros disponiveis.
- Deve ser possivel listar todos carros disponiveis pela marca.
- Deve ser possivel listar todos carros disponiveis pela categoria.
- Deve ser possivel listar todos carros disponiveis pelo nome do carro.

**RNF**

- null

**RN**

- O usuario nao precisa estar logado no sistema.

<hr>

## Cadastro de especificacao no carro

<!-- id, nome, descricao, valor_diaria, disponivel, multa, marca -->
**RF**

- Deve ser possivel cadastrar uma especificacao para um carro ou mais carros
- Deve ser possivel cadastrar varias especificacoes para um carro.
- Deve ser possivel listar as especificacoes.
- Deve ser possivel listar os carros.

**RNF**

- null

**RN**

- nao deve ser possivel cadastrar umsa especificacao para um carro nao cadastrado.
- nao deve ser possivel cadastrar uma mesma especificacao para o mesmo carro.
- O cadastro deve ser feito por um adm.

<hr>

## Cadastro de imagens do carro

<!-- id, nome, descricao, valor_diaria, disponivel, multa, marca -->
**RF**

- Deve ser possivel cadastrar uma imagem ou mais para um carro.
- Deve ser possivel listar todos os carros.

**RNF**

- utilizar o multer para upload dos arquivos

**RN**

- nao deve ser possivel cadastrar uma imagem para um carro nao cadastrado.
- nao deve ser possivel cadastrar uma mesma imagem para o mesmo carro.
- Deve ser possivel cadastrar mais de uma imagem para o mesmo carro.
- O cadastro deve ser feito por um adm.

<hr>

## Aluguel de carro

<!-- id, nome, descricao, valor_diaria, disponivel, multa, marca -->
**RF**

- Deve ser possivel cadastrar um aluguel.
- Deve ser possivel listar todos os carros.

**RNF**

- utilizar o multer para upload dos arquivos

**RN**

- O aluguel deve ter duracao minima de 24 horas.
- nao deve ser possivel cadastrar um aluguel para um carro nao disponivel.
- nao deve ser possivel cadastrar um aluguel para um carro nao cadastrado.
- nao deve ser possivel cadastrar um aluguel para um carro ja alugado.
- nao deve ser possivel cadastrar mais de um aluguel para o mesmo cliente.
- O cadastro deve ser feito por um adm.

<hr>