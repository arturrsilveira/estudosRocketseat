<h1 align="center">Rocketseat Ignite - Trilha React.Js</h1>
<h2 align="center">Capítulo 1</h2>
<br>

## ℹ️ HOOKS

- useState: Sempre que uma variável possuir um troca de valores, seja por um clique em um botão, ou até mesmo uma consulta a uma API fazemos o monitoramento dela utilizando o useState, pois ela vai causar uma alteração no layout da minha aplicação.
- Utilizamos o hook useEffect toda vez que queremos que algo aconteça em uma determinada situação após a alteração de algum estado monitorado.
- Fazemos a importação conforme o habitual do react

```jsx
import { useState, useEffect } from 'react
```

- useEffect recebe dois parãmetros, sendo o promeiro, a função qual desejo executar, e o segundo, quando quero executar.

```jsx
export function teste() {
	useEffect(() =>{}, )
	.....
	.....
}
```

- O segundo paramêtro chamamos de dependência, no quais depedências devem ocorrer para que a função seja executada no primeiro parâmetro.
- Caso array de dependencias estiver vazio [ ] a função chamada pelo useEffect será excutada uma única vez assim que o componente for exibido em tela (renderizado).
- Caso for esquecido de passar o segundo parâmetro para o euseEffect, no caso o array de dependencias o useEffect entrará em looping, executando a função do primeiro parâmetro indefinidamente.


## 📝 Sobre
Feito com ❤️ por Artur Rafael da Silveira
[Entre em contato!](https://www.linkedin.com/in/arturrsilveira/) 👋🏽 

[![Linkedin Badge](https://img.shields.io/badge/-Artur-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/arturrsilveira/)](https://www.linkedin.com/in/arturrsilveira/) 
[![Gmail Badge](https://img.shields.io/badge/-arturrsilveira85@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:arturrsilveira85@gmail.com)](mailto:arturrsilveira85@gmail.com)