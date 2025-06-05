# 🧠 Terceiro Desafio de Lógica de Programação com JavaScript (3)

---

## 🔢 Contador de 1 até 10

**Objetivo:** Criar um contador que comece em 1 e vá até 10 usando `while`.

```javascript
let contador = 1;

while (contador <= 10) {
    console.log(contador);
    contador = contador + 1;
}
```

---

## 🔁 Contador de 10 até 1

**Objetivo:** Criar um contador que comece em 10 e vá até 1 usando `while`.

```javascript
let contador = 10;

while (contador >= 1) {
    console.log(contador);
    contador = contador - 1;
}
```

---

## ⏳ Contagem Regressiva Personalizada

**Objetivo:** Pedir um número e contar regressivamente até 0 usando `while`.

```javascript
let numero = parseInt(prompt('Digite um número para iniciar a contagem regressiva'));

while (numero >= 0) {
    console.log(numero);
    numero = numero - 1;
}
```

---

## 📈 Contagem Progressiva Personalizada

**Objetivo:** Pedir um número e contar de 0 até ele usando `while`.

```javascript
let numero = parseInt(prompt('Digite um número para iniciar a contagem até'));
let contador = 0;

while (contador <= numero) {
    console.log(contador);
    contador = contador + 1;
}
```

---

## 🏁 Conclusão

- ✅ Neste desafio, Usamos loops `while` para fazer contagens progressivas e regressivas com JavaScript. Saber controlar o fluxo de repetição é essencial para criar programas dinâmicos, como cronômetros, animações, jogos e muito mais.
