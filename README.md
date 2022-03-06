# Axios Notes


## Axios
Promise based HTTP client for the browser and node.js
Docs: https://axios-http.com/docs/

Install axios

`npm install axios`

include it in the html header

`<script src="./node_modules/axios/dist/axios.min.js"></script>`


## json-server
Get a full fake REST API with zero codingz
Github: https://github.com/typicode/json-server

Install JSON Server

`npm install -g json-server`

Start JSON Server

`json-server --watch db.json` (From github guides, doesn't work for me)

`npx json-server --watch db.json` (Worked)

