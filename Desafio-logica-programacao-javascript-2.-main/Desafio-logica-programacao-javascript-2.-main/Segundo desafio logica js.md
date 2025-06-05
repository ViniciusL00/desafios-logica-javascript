# 🧠 Segundo Desafio de Lógica de Programação com JavaScript (2)

---

## 📅 1. Verificando o Dia da Semana

**Objetivo:** Mostrar uma mensagem personalizada de acordo com o dia da semana.

```javascript
let diaDaSemana = prompt('Olá, qual dia da semana está acessando nossa página?');

if (diaDaSemana === 'Sábado') {
  alert('Bom fim de semana!');
} else if (diaDaSemana === 'Domingo') {
  alert('Bom fim de semana!');
} else {
  alert('Boa semana!');
}
```

---

## ➕➖ 2. Número Positivo ou Negativo

**Objetivo:** Verificar se um número é positivo ou negativo e exibir um alerta.

```javascript
let numero = prompt('Digite um número positivo ou negativo');

if (numero > 0) {
  alert('Número positivo!');
} else {
  alert('Número negativo!');
}
```

---

## 🕹️ 3. Sistema de Pontuação

**Objetivo:** Mostrar mensagem de vitória ou tentativa com base na pontuação.

```javascript
let pontuacao = 105;

if (pontuacao >= 100) {
  console.log('Parabéns, você venceu!');
} else {
  console.log('Tente novamente para ganhar.');
}
```

---

## 💰 4. Mensagem com Template String

**Objetivo:** Informar o saldo da conta usando template string.

```javascript
let saldoConta = 15000; // Saldo da conta
alert(`Seu saldo é de R$ ${saldoConta}.`);
```

---

## 🙋‍♂️ 5. Boas-vindas Personalizadas

**Objetivo:** Perguntar o nome do usuário e mostrar uma saudação personalizada.

```javascript
let nome = prompt('Como você se chama?');
alert(`Seja bem-vindo ${nome}`);
```

---

## ✅ Conclusão

- ✅ Neste segundo desafio, exploramos estruturas condicionais e interações com o usuário através de `prompt`, `alert` e `console.log`.
