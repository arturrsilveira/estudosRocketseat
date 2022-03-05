<h1 align="center">Rocketseat Ignite - Trilha React.Js</h1>
<h2 align="center">Capítulo 1</h2>
<br>

## ℹ️ Aula 02

- Propriedades no React funcionam como se fossem atributos em uma TAG HTML, são informações varáveis que passamos para que um componente React possa funcionar de forma diferente.
- No exemplo abaixo possuimos o componente listadeItens e passamos os dados através do atributo item, desta forma o componente listadeItens se comportará diferente conforme as variáveis são passadas.
    
    ```jsx
    <listadeItens item="Arroz" />
    <listadeItens item="Feijão" />
    <listadeItens item="Carne" />
    ```
    
- E para receber estas avariáveis utilizamos os argumentos da função como podemos ver abaixo:
    
    ```jsx
    export function listadeItens(props) {
    	return (
    		<h1>{props.item}</h1>
    	);
    }
    ```
    
- Desta forma recebemos no argumento props os dados da variável enviada e exibimos o seu valor acessando através de props.item, ou seja props ponto e o nome do argumento que recebe a variável.
    
- Caso as informações sejam inúmeras podemos enviar um objeto para o componente contendo todas, como podemos ver abaixo:

```jsx
const item = {
	nome: 'Arro',
	descricao: '5kg',
	preco: 'R$ 10,00'
}

export function compra() {
	return (
		<listadeItens item={item} />
	);
}
```

- Dentro do componente listadeItens iremos recuperar novamente através do props, mas de uma forma um pouco diferente:


## 📝 Sobre
Feito com ❤️ por Artur Rafael da Silveira
[Entre em contato!](https://www.linkedin.com/in/arturrsilveira/) 👋🏽 

[![Linkedin Badge](https://img.shields.io/badge/-Artur-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/arturrsilveira/)](https://www.linkedin.com/in/arturrsilveira/) 
[![Gmail Badge](https://img.shields.io/badge/-arturrsilveira85@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:arturrsilveira85@gmail.com)](mailto:arturrsilveira85@gmail.com)