# Aplicação de Livraria

## Sobre ##

- Este projeto foi desenvolvido como parte do recrutamento da HBSIS
- A aplicação foi feita utilizando Angular 7

## Pré requisitos ##

- NodeJS 10 ou Superior (https://nodejs.org/en/)

## Componentes ##

> Componentes e frameworks utilizados no projeto

- Angular 7 ou superior (https://angular.io/guide/quickstart)
- Angular Material (https://material.angular.io/)

## Instalação ##

> Rode os comandos abaixo numa CLI

```sh
git clone git@github.com:moura-saulo/bookstore.git {app-name}
cd {app-name}
npm install
```

> Edite o parâmetro urlAPI nos arquivos environment e environment.prod com a URL da api local e de produção, respectivamente

## Colocar para Rodar ##

> Execute o comando abaixo para processar os arquivos .sass e concatenar os .js e .css injetando no index.html.
> O comando fica observando futuras modificações e repetindo o processo automaticamente
> O comando fará a aplicação ser aberta no browser automaticamente após a compilação, devido ao parâmetro "-o"

```sh
cd {app-name}
ng serve -o
```

## Produção ##

> Execute o comando abaixo para processar os arquivos .sass e concatenar os .js e .css injetando no index.html com os parâmetros de produção

```sh
cd {app-name}
ng build --prod
```

> Copie o conteúdo do diretório "dist" criado na aplicação após a compilação para a raiz do seu sevidor de aplicação
