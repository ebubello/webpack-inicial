# Webpack Starter

Este es el proyecto inicial para crear aplicaciones utilizando webpack.

### Notas : 

Recontruir modulos de Node

npm install

Construir un build

npm run build


Para un proyecto verificar:

node --version
npm --version

npm init -y (Crea el package.json)

crea el folder src, luego index.html, index.js y folder JS

npm install webpack webpack-cli --save-dev (instalar webpack y genera el folder node_modules).

en package.json agregar "script" : "build": "webpack"

para salvar los cambios ( npm run build )

crear webpack.config.js

importar npm i -D html-loader html-webpack-plugin ( hace dos cosas, mueve el archivo html al folder dist y inclusta el bundle directamente en el html.)


Comandos GIT:

git add .
git commit -m "Readme Creado"
git push
