# Node.js com serverless framework <br>

> Este é o projeto de exemplo para o curso [Node.js com serverless framework](tbd) na Alura.<br>


## Executando localmente<br>

O projeto foi feito da forma mais simples possível para facilitar o uso. Não foram usados nenhum framework ou biblioteca para o front-end.<br>

Todo o projeto roda a partir do arquivo `index.mjs`, que é o arquivo principal do projeto. Para executá-lo, basta rodar o comando:<br>

```bash
node index.mjs
```

Ou se preferir, você pode usar o [nodemon](https://www.npmjs.com/package/nodemon) para executar o projeto:

```bash
npm run dev
```

Isso vai garantir que você não precise ficar reiniciando o servidor a cada alteração que fizer. Todo o front-end da aplicação está na pasta `interface`, toda a API da aplicação está dentro do arquivo `index.mjs`.<br>

Depois de executar o projeto, você pode acessar a aplicação em `http://localhost:3000`.<br>
