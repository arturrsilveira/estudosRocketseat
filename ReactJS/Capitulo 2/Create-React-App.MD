<h1 align="center">Rocketseat Ignite - Trilha React.Js</h1>
<h2 align="center">Capítulo 1</h2>
<br>

## ℹ️ Criando um Projeto Utilizando CRA

Site Oficial da Ferramenta http://create-react-app.dev

É uma ferramenta fornecida pelo time de desenvolvimento do Reactjs que fornece uma estrutura pré-configurada de um projeto evitando preocupações como configurações adicionais no projeto como Babel e Webpack, além de trazer alguns pacores importantes ja adicionados.

Para começarmos um novo Projeto se utilizando do CRA (Create React App) utilizamos o comando a seguir:

```jsx
yarn create react-app nomedoprojeto --template typescript
```

Onde 'nomedoprojeto' refere-se ao nome que iremos dar a este projeto e o 

'— template typescript' trata de definir que utilizaremos Typescript ao invés de Javascript.

No caso da desta aula utilizarei o comando a seguir:

```jsx
yarn create react-app dtmoney --template typescript
```

Após a criação do novo Projeto podemos eliminar alguns arquivos que vem por padrão mas que serão substituidos pelos arquivos da nossa aplicação.

Na pasta public excluiremos os arquivos:

- favicon.con
- logo192.png
- logo512.png
- manifest.json
- robots.txt

Na pasta src excluiremos os arquivos:

- App.css
- App.test.tsx
- index.css
- logo.svg
- reportWebVitals.ts
- setupTests.ts

E por fim na pasta raiz do projeto excluiremos o arquivo Readme, ficando conforme a imagem abaixo nossa pasta do projeto:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4b17ef09-1a1f-44f2-b151-3941a058283e/Sem_ttulo.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4b17ef09-1a1f-44f2-b151-3941a058283e/Sem_ttulo.jpg)

Dentro do arquivo index.html dentro da pasta public excluimos as linhas entre as TAGS:

```html
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1" />
...
...
...
<title>React App</title>
```

No arquivo index.tsx dentro de src removeremos as importações que não fazem mais sentido devido a exclusão dos arquivos anteriores, entçao retiraremos os itens abaixo:

- import './index.css';
- import reportWebVitals from './reportWebVitals';

App.tsx dentro da pasta src removeremos as importações que não fazem mais sentido devido a exclusão dos arquivos anteriores, entçao retiraremos os itens abaixo:

- import React from 'react';
- import logo from './logo.svg';
- import './App.css';

Removeremos todo conteúdo da function App( ) entre as TAGS abaixo para fazermos a inserção do nosso código:

```html
<div className="App">
...
...
...
</div>
```

Faremos a exportação da função function App( ) utilizando a instrução export em frente a declaração da função, ficando conform podemos ver abaixo:

```html
export function App(){
	return (
		<div className="App">
			<h1>Hello World</h1>
		</div>
	);
}
```

Isto é feito para evitar que no momento da importação desta função em outro arquivo possa ser feita a alteração do nome da mesma. Garantindo assim uma maior integridade e legibilidade no código da aplicação.



## 📝 Sobre
Feito com ❤️ por Artur Rafael da Silveira
[Entre em contato!](https://www.linkedin.com/in/arturrsilveira/) 👋🏽 

[![Linkedin Badge](https://img.shields.io/badge/-Artur-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/arturrsilveira/)](https://www.linkedin.com/in/arturrsilveira/) 
[![Gmail Badge](https://img.shields.io/badge/-arturrsilveira85@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:arturrsilveira85@gmail.com)](mailto:arturrsilveira85@gmail.com)