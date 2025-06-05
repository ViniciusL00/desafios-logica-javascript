# 💻 Desafio de Lógica de Programação com JavaScript (Parte 4)

---

## 👋 Mensagem de Boas-Vindas

```javascript
console.log('Seja bem-vindo!');
```

---

## 🙋‍♂️ Saudação com Nome no Console

```javascript
let nome = 'Jinglebobs';
console.log(`Olá, ${nome}!`);
```

---

## 🙋‍♀️ Saudação com Nome via Alert

```javascript
let nome = 'Jinglebobs';
alert(`Olá, ${nome}!`);
```

---

## 🗣️ Pergunta com Prompt e Console

```javascript
let linguagem = prompt('Qual a linguagem de programação que você mais gosta?');
console.log(linguagem);
```

---

## ➕ Soma de Dois Valores

```javascript
let valor1 = 37;
let valor2 = 8;
let resultado = valor1 + valor2;
console.log(`A soma de ${valor1} + ${valor2} é igual a ${resultado}!`);
```

---

## ➖ Subtração de Dois Valores

```javascript
let valor1 = 50;
let valor2 = 32;
let resultado = valor1 - valor2;
console.log(`A diferença de ${valor1} - ${valor2} é igual a ${resultado}!`);
```

---

## 🧒 Verificando Maioridade

```javascript
let idade = prompt('Olá, qual é a sua idade?');
idade = Number(idade);

if (idade >= 18) {
  alert('Você é maior de idade, seja bem-vindo!');
} else {
  alert('Você é menor de idade, seja bem-vindo!');
}
```

---

## 🔢 Verificando Número Positivo, Negativo ou Zero

```javascript
let numero = prompt('Digite aqui qualquer número');
numero = Number(numero);

if (numero > 0) {
  alert('Esse número é positivo!');
} else if (numero < 0) {
  alert('Esse número é negativo');
} else {
  alert('Esse número é zero');
}
```

---

## 🔁 Contando de 1 a 10 com While

```javascript
let numero = 1;

while (numero <= 10) {
  console.log(numero);
  numero = numero + 1;
}
```

---

## 🎓 Verificando Nota (Aprovado ou Reprovado)

```javascript
let nota = 10;

if (nota >= 7) {
  console.log('Aprovado');
} else {
  console.log('Reprovado');
}
```

---

## 🎲 Gerando Número Aleatório com Math.random()

```javascript
let numeroAleatorio = Math.random();
console.log(numeroAleatorio);
```

---

## 🎯 Número Inteiro entre 1 e 10

```javascript
let numeroAleatorio = Math.floor(Math.random() * 10) + 1;
console.log(numeroAleatorio);
```

---

## 💰 Número Inteiro entre 1 e 1000

```javascript
let numeroAleatorio = Math.floor(Math.random() * 1000) + 1;
console.log(numeroAleatorio);
```

---

## 🏁 Conclusão

- ✅ Usar `console.log`, `alert` e `prompt`;
- ✅ Declarar e manipular variáveis;
- ✅ Utilizar estruturas condicionais `if/else`;
- ✅ Usar laços de repetição com `while`;
- ✅ Trabalhar com `Math.random()` para gerar números aleatórios.
