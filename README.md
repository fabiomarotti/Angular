# Angular
Repositório com estudos realizados sobre o framework Angular.

* https://angular.io/
* https://cli.angular.io/

* Requesitos: Node.js -> npm (Node Package Manager)

`$ node -v` versão do Node.js 

`$ npm -v` versão do Gerenciados de Pacotes

`$ ng -v` versão do Angular

`$ ng help` ajuda do Angular

## Instalar Angular CLI :: Command-Lin Interface

`$ npm install -g @angular/cli`  (-g: Instalação de modo Global)

## Criar um workspace "pasta do projeto" :: [+ detalhes](https://angular.io/guide/strict-mode)

`$ ng new nome_projeto`  gera um skeleton (esqueto de pastas/conteudo) -> Angular router -> CSS

`$ cd nome_projeto`    acessar pasta para executar os proximos comandos

## Abrir/iniciar o servidor :: http://localhost:4200/

`$ ng serve --open`  [+ detalhes](https://angular.io/cli/serve )

`$ ng serve -o` comando abreviado

## Estrutura das pastas
* `/e2e` : fazer testes unitários
* `/node_modules` : todos os pacotes necessários para tralhar ou instalar posteriormente <br>
(pasta a ser contida no arquivo: **gitignore** -> pasta muito grande)
* `/src` : Pasta Principal
* * **main.ts**
* * **polyfills.ts** : traduzida no transpilar
* * **style.css** : reflete na aplicação toda
* * **test.ts** : parametros de teste (arquivos de teste)
* `/src/app` : todos os aquivos/componentes da aplicação
    * **app-routing.module.ts**
    * **app.module.ts**
    * **app.component.ts**
    * _.html
    * _.css
    * _.spec.ts

Um componente X é composto por três arquivos:
* x.html
* x.css
* x.spec.ts
 
O componente principal chama: `app.component`, composto por:
* app.component.html
* app.component.css
* app.component.spec.ts


# Sintaxe
