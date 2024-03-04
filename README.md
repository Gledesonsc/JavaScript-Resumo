# JavaScript - Resumo

## Introdução
JavaScript é uma linguagem de programação de alto nível, interpretada e orientada a objetos amplamente utilizada para desenvolvimento web.

## Sintaxe Básica
- **Variáveis:** Declaradas usando `var`, `let` ou `const`.
- **Tipos de Dados:** Incluem strings, números, booleanos, arrays, objetos, etc.
- **Operadores:** Aritméticos, relacionais, lógicos, etc.

```javascript
// Exemplo de variável e operadores
let x = 5;
let y = 10;
let z = x + y; // z será 15
```

## Estruturas de Controle
- **Condicional:** `if`, `else if`, `else`.
- **Loop:** `for`, `while`, `do-while`, `for...in`, `for...of`.

```javascript
// Exemplo de estruturas de controle
let idade = 18;
if (idade >= 18) {
    console.log("Você é maior de idade.");
} else {
    console.log("Você é menor de idade.");
}
```

## Funções
- **Declaração de Funções:** `function`.
- **Funções Anônimas:** `function()`.
- **Arrow Functions:** `(params) => {}`.

```javascript
// Exemplo de função
function saudacao(nome) {
    return "Olá, " + nome + "!";
}
console.log(saudacao("Mundo")); // Saída: Olá, Mundo!
```

## Objetos e Arrays
- **Objetos:** Conjuntos de pares chave-valor.
- **Arrays:** Coleções ordenadas de elementos.

```javascript
// Exemplo de objeto e array
let pessoa = {
    nome: "João",
    idade: 30,
    cidade: "São Paulo"
};
let numeros = [1, 2, 3, 4, 5];
```

## Eventos
- **Manipulação de Eventos:** Adicionando comportamento a elementos HTML.

```javascript
// Exemplo de manipulação de eventos
document.getElementById("botao").addEventListener("click", function() {
    alert("Botão clicado!");
});
```

## DOM Manipulation
- **Seleção de Elementos:** `document.getElementById()`, `document.querySelector()`, etc.
- **Manipulação de Elementos:** `innerHTML`, `appendChild()`, etc.

```javascript
// Exemplo de manipulação do DOM
document.getElementById("titulo").innerHTML = "Novo Título";
```

## Promises e Async/Await
- **Promises:** Representa o sucesso ou a falha de uma operação assíncrona.
- **Async/Await:** Sintaxe para trabalhar com código assíncrono de forma mais síncrona.

```javascript
// Exemplo de Promises e Async/Await
function esperaTempo(tempo) {
    return new Promise((resolve, reject) => {
        setTimeout(() => {
            resolve("Tempo de espera concluído.");
        }, tempo);
    });
}

async function exemploAsync() {
    console.log("Início da função async");
    await esperaTempo(2000);
    console.log("Espera concluída.");
}

exemploAsync();
```

## Conclusão
JavaScript é uma linguagem poderosa e versátil, amplamente utilizada para desenvolvimento web, permitindo interatividade e dinamismo em páginas HTML.
Este resumo cobre apenas conceitos básicos; há muito mais para explorar em JavaScript!


# Sites para Estudar JavaScript

1. **MDN Web Docs**
   - Website: [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
   - Descrição: Uma excelente referência para aprender JavaScript, oferecendo documentação detalhada, tutoriais e exemplos.

2. **freeCodeCamp**
   - Website: [freeCodeCamp](https://www.freecodecamp.org/)
   - Descrição: Plataforma interativa que oferece cursos gratuitos de programação, incluindo JavaScript. Você pratica escrevendo código real enquanto aprende.

3. **Codecademy**
   - Website: [Codecademy](https://www.codecademy.com/learn/introduction-to-javascript)
   - Descrição: Oferece cursos interativos de JavaScript para todos os níveis de habilidade. Você pode aprender no seu próprio ritmo e praticar em tempo real.

4. **JavaScript.info**
   - Website: [JavaScript.info](https://javascript.info/)
   - Descrição: Oferece tutoriais detalhados e exemplos práticos sobre JavaScript, cobrindo desde o básico até tópicos mais avançados.

5. **W3Schools**
   - Website: [W3Schools JavaScript Tutorial](https://www.w3schools.com/js/)
   - Descrição: Uma referência popular para aprender tecnologias web, incluindo JavaScript. Oferece tutoriais, exemplos e exercícios práticos.
