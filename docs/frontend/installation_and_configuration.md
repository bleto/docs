# Installation and configuration

## Quick Start

1. In case that you do not have [node.js](https://nodejs.org/en/download/) installed - install latest stable version
2. Choose your package manager:
    1. [npm](https://www.npmjs.com/get-npm)
    2. [yarn](https://yarnpkg.com/en/docs/install#mac-stable)


## Instalation

Download project repository (ergonode) to your local directory:
```bash
git clone git@github.com:ergonode/frontend.git
```
Open your terminal in local project, and execute:
```bash
npm install
```
#### Create .env
Execute CLI command and set you API URL:
```bash
npm run cli:run
```
> *You can also copy .env.dist file as .env and set your API URL configuration.*
> 
```.env``` file configuration:
1. ```API_PROTOCOL``` - protocol variable (e.g. ```http``` / ```https```)
2. ```API_HOST``` - host variable (e.g. ```localhost```)
3. ```API_PREFIX``` - prefix (e.g. ```/api/{version}```)
4. ```API_PORT``` -  port if exists (e.g. ```8000```)

#### Run server
```bash
#development
npm run dev

#production
npm run build
npm run start
```

## Npm - commands

| Commends    | Description                            |
|-------------|----------------------------------------|
| npm install | Installing node package manager |
| npm run dev | Starting local sever listening changes |
| npm run lint | Starting style and code linters |
| npm run test | Starting unit tests |
| npm run build | Build aplication |
| npm run start | Starting production build |
