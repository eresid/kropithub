# Урок 5. Математичні операції

## Базові математичні операції

TypeScript підтримує базові математичні операції, такі як додавання, віднімання, множення, ділення, залишок від ділення та піднесення в степінь.

```typescript
let a = 10;
let b = 3;

let sum = a + b; // 13
console.log("Додавання: " + sum);

let difference = a - b; // 7
console.log("Віднімання: " + difference);

let product = a * b; // 30
console.log("Множення: " + product);

let quotient = a / b; // 3.3333333333333335
console.log("Ділення: " + quotient);

let remainder = a % b; // 1
console.log("Залишок від ділення: " + remainder);

let power = a ** b; // 1000
console.log("Піднесення до степеня: " + power);
```

## Оператори Інкремент та Декремент

У TypeScript також є оператори інкремент (++) та декремент (--), які збільшують чи зменшують число на одиничку.

```typescript
let x = 5;

x++; // 6
console.log("Після інкременту: " + x);
x--; // 5
console.log("Після декременту: " + x);
```

## Оператори присвоєння

Математичні операції можна поєднувати з присвоєнням до змінної.

```typescript
let c = 10;

c += 5; // 15
c -= 3; // 12
c *= 2; // 24
c /= 4; // 6
c %= 2; // 0
```

## Посилання

- [Вихідний код уроку в CodePen](https://codepen.io/Yevhen-Sakara/pen/JjQxYWJ)
- [Посібник JavaScript: Базові оператори, математика](https://uk.javascript.info/operators)