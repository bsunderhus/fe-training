# Roteiro de treinamento Node

Antes de mais nada, [Node](https://nodejs.org) (instala logo vai…). Esse roteiro tem como objetivo ensinar o que é Node e o que você como desenvolvedor web tem que saber.

Uma vez dominado o Treinamento Web. Node vem de bandeja. Sendo assim, não focaremos em javascript em si, mas sim em API’s básicas existentes no ambiente e como amarrá-las.

Com isso dito, tenha em mente que esse treinamento poderia todo ser resumido em ler a [documentação](https://nodejs.org/dist/latest-v6.x/docs/api/) Node (Algumas exceções).

- [ ] [O que é Node?](https://en.wikipedia.org/wiki/Node.js) _a wikipédia pt-BR tá longe de certo. Que bom que cientista da computação tem que saber inglês_
- [ ] [Bê-a-bá](https://github.com/ericdouglas/traduz-ai/blob/master/nodejs/001-guia-para-iniciantes-absolutos-em-nodejs.md)
- [ ] [NPM](https://www.sitepoint.com/beginners-guide-node-package-manager/)*
- [ ] [Módulos](https://nodejs.org/api/modules.html)* _[commonjs](http://requirejs.org/docs/commonjs.html), basicamente_
- [ ] [File System](https://nodejs.org/api/fs.html)*
    - [ ] [mastigado e exemplificado](https://www.tutorialspoint.com/nodejs/nodejs_file_system.htm)
- [ ] [Eventos](https://nodejs.org/dist/latest-v6.x/docs/api/events.html)
    - [ ] [mastigado e exemplificado](https://www.sitepoint.com/nodejs-events-and-eventemitter/)
- [ ] [HTTP](https://blog.risingstack.com/your-first-node-js-http-server/)*
    - [ ] [express](https://www.tutorialspoint.com/nodejs/nodejs_express_framework.htm) _sim, HTTP é obrigatório, enquanto que express não, é cômico e você não sabe_
    - [ ] O [protocolo](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)* em si.
- [ ] [Database](https://blog.risingstack.com/node-js-database-tutorial/)
    - [ ] [MySQL](https://www.sitepoint.com/using-node-mysql-javascript-client/)
    - [ ] [MongoDB](https://www.tutorialspoint.com/mongodb/)
- [ ] [Do Node pro Browser (Module bundler)](https://medium.com/@gimenete/how-javascript-bundlers-work-1fc0d0caf2da)* _pick one! anyone! desde que você escolha o webpack ou parcel..._
    - [ ] [Browserify](https://scotch.io/tutorials/getting-started-with-browserify)
    - [ ] [Webpack](https://webpack.js.org/)
    - [ ] [Parcel](https://parceljs.org/)
    - [ ] [Rollup](https://rollupjs.org)
- [ ] [Task Runners]()
    - [ ] [Gulp](http://tableless.com.br/gulp-o-novo-automatizador/)


No final deste roteiro, seu objetivo é construir um servidor que tenha armazenado alguma forma de dado (pode ser em um arquivo mesmo, nada muito complexo) e um cliente que acesse e mostre de forma interativa esses dados.

Tanto o item Database, Do Node pro Browser e Ferramentas de Build são totalmente optativos (e **dispensáveis** para fazer o projeto final desse roteiro). Para desenvolvimento front-end é totalmente desnecessário saber como lidar diretamente com o processamento de um banco de dados. Module bundling e ferramentas de build são problemas de quem monta o ambiente de desenvolvimento, não do desenvolvedor front-end em si. Dito isso, gosto de dizer que mesmo assim é importante conhecer essas ferramentas! Para esfregar na cara do criador do ambiente que o ambiente dele é mal feito!
