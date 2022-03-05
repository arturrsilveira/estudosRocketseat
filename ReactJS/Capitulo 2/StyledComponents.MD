<h1 align="center">Rocketseat Ignite - Trilha React.Js</h1>
<h2 align="center">Capítulo 2</h2>
<br>

## ℹ️ Instalação do Styled Componentes

Site Oficial: [https://styled-components.com](https://styled-components.com/)

Styled Components é uma biblioteca (lib) que utiliza o conceito de CSS-in-JS, ou seja, que nos permite escrever códigos CSS dentro do Javascript

Para fazer a instalação utilizamos o comando a seguir:

```jsx
yarn add styled-components
```

Não utilizaremos Classes (ClassName) para estilizar os componentes, criaremos componentes ja estilizados. Desta forma não iremos atribuir uma classe (ClassName) em uma TAG do tipo <h1> por exemplo

Dando prosseguimento ao tutorial da nossa aula faremos a importação de styled de dentro do pacote styled-components no componente App.tsx

![https://github.com/arturrsilveira/estudosRocketseat/blob/main/ReactJS/Capitulo%202/sty.png](https://github.com/arturrsilveira/estudosRocketseat/blob/main/ReactJS/Capitulo%202/sty.png)

É possível observar que o VsCode informa que a importaçãop esta errada, no entanto se deve ao problema de que como estamos utilizando TypeScript é necessário a utilização de tipagem, neste caso as definições de tipo do style-components não vem junto instalado por padrão, desta forma se faz necessário a instalação a parte.

```jsx
yarn add @types/styled-components -D
```

O Parâmetro -D se faz necessário pois esta é uma dependência der desenvolvimento e não de produção, desta forma ao final da aplicação ela não fará parte do código final .

Portanto faremos a substituição da tag <h1> por um componente estilizado do tipo <h1> que receberá as estilizações que desejarmos e após utilizaremos este componente criado e estilizado como se fosse uma tag HTML, conforme podemos ver abaixo:
![https://github.com/arturrsilveira/estudosRocketseat/blob/main/ReactJS/Capitulo%202/sty2.png](https://github.com/arturrsilveira/estudosRocketseat/blob/main/ReactJS/Capitulo%202/sty2.png)





## 📝 Sobre
Feito com ❤️ por Artur Rafael da Silveira
[Entre em contato!](https://www.linkedin.com/in/arturrsilveira/) 👋🏽 

[![Linkedin Badge](https://img.shields.io/badge/-Artur-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/arturrsilveira/)](https://www.linkedin.com/in/arturrsilveira/) 
[![Gmail Badge](https://img.shields.io/badge/-arturrsilveira85@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:arturrsilveira85@gmail.com)](mailto:arturrsilveira85@gmail.com)