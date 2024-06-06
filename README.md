<body>
    <h1>API REST de Gerenciamento de Filmes e Categorias</h1>
    <p>Este projeto é uma API REST para gerenciar filmes e categorias. Foi construído usando <strong>Node.js</strong>, <strong>Express</strong> e <strong>MongoDB</strong>. A API permite a criação, recuperação, atualização e exclusão de filmes e categorias, e suporta CORS para permitir requisições de diferentes origens.</p>

  <h2>Funcionalidades</h2>
  <ul>
      <li><strong>Gerenciamento de Filmes:</strong> Criar, ler, atualizar e excluir registros de filmes.</li>
      <li><strong>Gerenciamento de Categorias:</strong> Criar, ler, atualizar e excluir registros de categorias.</li>
      <li><strong>Filmes e Categorias:</strong> Recuperar filmes juntamente com suas categorias associadas.</li>
  </ul>

  <h2>Tecnologias Utilizadas</h2>
  <div style="display: flex; gap: 10px;">
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" width="98px" height="26px" alt="Node.js logo">
      <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" width="98px" height="26px" alt="Express.js logo">
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" width="98px" height="26px" alt="MongoDB logo">
  </div>

  <h2>Estrutura do Projeto</h2>
  <pre>
  movie-category-api/
  │
  ├── controllers/
  │   ├── CategoryController.js
  │   └── MovieController.js
  ├── database/
  │   └── db.js
  ├── models/
  │   ├── Category.js
  │   └── Movie.js
  ├── routes/
  │   └── routes.js
  ├── index.js
  ├── package.json
  └── README.md
  </pre>

  <h2>Instalação</h2>
  <p>Para executar este projeto localmente, siga estes passos:</p>
  <ol>
      <li>Clone este repositório: <code>git clone https://github.com/seuusuario/movie-category-api</code></li>
      <li>Navegue até o diretório do projeto: <code>cd movie-category-api</code></li>
      <li>Instale as dependências: <code>npm install</code></li>
      <li>Inicie o servidor: <code>npm start</code></li>
  </ol>

  <h2>Endpoints da API</h2>
  <h3>Filmes</h3>
  <ul>
      <li>GET /movies - Recuperar todos os filmes</li>
      <li>POST /movie - Criar um novo filme</li>
      <li>DELETE /movie/:id - Excluir um filme pelo ID</li>
      <li>PUT /movie/:id - Atualizar um filme pelo ID</li>
  </ul>
  <h3>Categorias</h3>
  <ul>
      <li>GET /categories - Recuperar todas as categorias</li>
      <li>POST /category - Criar uma nova categoria</li>
      <li>DELETE /category/:id - Excluir uma categoria pelo ID</li>
      <li>PUT /category/:id - Atualizar uma categoria pelo ID</li>
  </ul>
  <h3>Filmes e Categorias</h3>
  <ul>
      <li>GET /movies-categories - Recuperar todos os filmes juntamente com suas categorias associadas</li>
  </ul>

  <h2>Contribuindo</h2>
  <p>Contribuições são sempre bem-vindas! Se você encontrar algum problema ou tiver sugestões para melhorar este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.</p>

  <h2>Autor</h2>
  <p>Este projeto foi desenvolvido por <strong>Giuseppe Barbetta</strong> ©.</p>
</body>
</html>
