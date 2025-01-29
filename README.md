# estudos-logica-com-javascript
# Fundamentos da Lógica de Programação
O que é lógica de programação?
Algoritmos e pseudocódigos
Variáveis e tipos de dados (string, number, boolean, array, object)
Operadores aritméticos e lógicos (+, -, *, /, %, &&, ||, !)
Estruturas condicionais (if, else if, else, switch)
Estruturas de repetição (for, while, do while)
Funções (function, return, parâmetros)
🔹 Exemplo prático:

javascript
Copiar
Editar
function verificaParOuImpar(numero) {
    if (numero % 2 === 0) {
        return "Par";
    } else {
        return "Ímpar";
    }
}
console.log(verificaParOuImpar(10)); // Saída: "Par"

# Estruturas de Dados e Arrays
Como armazenar e manipular coleções de dados (push, pop, shift, unshift, map, filter, reduce)
Objetos ({ chave: valor })
🔹 Exemplo prático:

javascript
Copiar
Editar
const frutas = ["Maçã", "Banana", "Uva"];
frutas.push("Laranja");
console.log(frutas); // ["Maçã", "Banana", "Uva", "Laranja"]
# Algoritmos e Exercícios Práticos
Sequência de Fibonacci
Fatorial de um número
Verificação de números primos
Palíndromos
Ordenação de arrays (Bubble Sort, Quick Sort)
🔹 Exemplo prático (Fibonacci Recursivo):

javascript
Copiar
Editar
function fibonacci(n) {
    if (n <= 1) return n;
    return fibonacci(n - 1) + fibonacci(n - 2);
}
console.log(fibonacci(7)); // Saída: 13
# Problemas Lógicos para Treinar
Plataformas para praticar desafios:

Codewars
HackerRank
LeetCode





# Executar no Navegador 🌐
Se seu código JavaScript for parte de uma página web, você pode executá-lo diretamente no navegador.

Usando o Console do Navegador
Abra o navegador (Chrome, Firefox, Edge, etc.).
Pressione F12 ou Ctrl + Shift + I para abrir as ferramentas do desenvolvedor.
Vá até a aba "Console" e digite seu código.
🔹 Exemplo:

javascript
Copiar
Editar
console.log("Olá, Mundo!");
Usando um Arquivo .js no HTML
Crie um arquivo script.js e adicione-o a um HTML:

html
Copiar
Editar
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Testando JavaScript</title>
</head>
<body>
    <script src="script.js"></script>
</body>
</html>
No script.js:

javascript
Copiar
Editar
alert("Olá, mundo!");
# Executar no Node.js 🖥️
Se quiser rodar JavaScript no terminal, precisa do Node.js instalado.

Passos para executar:
Instale o Node.js (se ainda não tiver) → Baixe aqui.
Crie um arquivo JavaScript, ex: app.js.
Escreva o código no app.js:
javascript
Copiar
Editar
console.log("Executando no Node.js!");
Abra o terminal e execute:
sh
Copiar
Editar
node app.js
Se aparecer Executando no Node.js!, deu certo! 🎉

# Executar com o NPX (sem precisar instalar pacotes)
Se você tiver o Node.js instalado, pode rodar comandos diretamente com npx.

sh
Copiar
Editar
npx node -e "console.log('Rodando com npx!')"
