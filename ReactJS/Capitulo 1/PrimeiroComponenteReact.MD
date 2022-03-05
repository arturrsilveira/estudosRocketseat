- Componentes no react são como se fossem TAGs no HTML, são formas de encapsular uma quantidade de código dentro de um único elemento, e este elemento possui sua própria estrura, estilização e funcionamento.
- Componentes são formas de dividir a nossa aplicação em pedaços menores que quando conectados formam algo maior, nesse caso a nossa aplicação.
- No React tudo são componentes.
- Oque é um componente no React?
    - É uma função com nome que começa pela primeira letra sempre maiúscula, e esta função devolve um HTML.
        
        ```jsx
        export function App() {
        	return <h1>Função de Exemplo</h1>
        }
        ```
        
    - Temos como convenção de sempre começar o arquivo por letra maiúscula e uma função por arquivo, nunca mais de um componente no mesmo arquivo.