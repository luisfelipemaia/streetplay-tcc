# streetplay-tcc
Para o funcionamento correto da aplicação é necessário executar:
    npm install express
    npm install cors
    npm install -g nodemon
    npm install prisma --save-dev
    npx prisma init
    //Para ligar o server, 3 opções
        npm run start (reinicia o server constantemente para uso direto, melhor opção)
        node src/serer.js (normal, ruim)
        node --watch src/server.js (reinicia o serer a cada alteração salva)
    //Para vizualizar o banco de dados
        npx prisma studio
Extenções sugeridas:
    Intelicode
    json
    npm intellisense
    prisma
    thunder client