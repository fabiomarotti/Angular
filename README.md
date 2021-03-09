# Angular
Repositório com estudos realizados sobre o framework Angular.

* https://angular.io/
* https://cli.angular.io/

* Requesitos: Node.js -> npm (Node Packege Managere)

$ node -v

$ npm -v

* Instalar Angular CLI :: Command-Lin Interface

$ npm install -g @angular/cli  // -g: Global

$ ng -v

$ ng help


* Criar um workspace "pasta do projeto" :: https://angular.io/guide/strict-mode

$ ng new nome_projeto // gera um skeleton (esqueto de pastas/conteudo)
-> Angular router
-> CSS

$ cd nome_projeto     // acessar para executar proximos comandos

* Abrir/iniciar o servidor :: http://localhost:4200/

$ ng serve --open   // https://angular.io/cli/serve

$ ng serve -o

## Estrutura das pastas
* /e2e : fazer testes unitários
* /node_modules : todos pacotes necessarios para tralhar/ instalar pacotes posteriormente (pasta contida no gitignore -> pasta muito grande)
* /src : Pasta Principal
* * main.ts
* * polyfills.ts : traduzida no transpilar
* * style.css : reflete na aplicação toda
* * test.ts : parametros de teste (arquivos de teste)
* /src/app : todos os aquivos/componentes da aplicação
    * app-routing.module.ts
    * app.module.ts
    * _.html
    * _.css
    * _.spec.ts

Um componente X é composto por três arquivos:
 x.html
 x.css
 x.spec.ts
 
O componente principal chama: app.component, composto por:
 app.component.html
 app.component.css
 app.component.spec.ts
# Sintaxe
