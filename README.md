novela-streaming
│
├ README.md
├ package.json
├ .gitignore
│
├ frontend
│  ├ index.html
│  ├ catalogo.html
│  ├ novela.html
│  ├ episodio.html
│  ├ login.html
│  ├ cadastro.html
│  ├ perfil.html
│  │
│  ├ css
│  │   └ style.css
│  │
│  └ js
│      ├ app.js
│      ├ busca.js
│      └ player.js
│
├ admin
│  ├ dashboard.html
│  ├ adicionar-novela.html
│  ├ adicionar-episodio.html
│  ├ gerenciar-usuarios.html
│  └ admin.js
│
├ backend
│  ├ server.js
│  │
│  ├ routes
│  │   ├ novelas.js
│  │   └ usuarios.js
│  │
│  ├ models
│  │   ├ Novela.js
│  │   └ Usuario.js
│  │
│  └ controllers
│      ├ novelaController.js
│      └ usuarioController.js
│
└ database
   └ novelas.json