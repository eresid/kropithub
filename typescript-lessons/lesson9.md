# Урок 9. Оператори порівняння

Оператори порівняння використовуються для порівняння значень. Вони повертають булевий результат — або true, або false, в залежності від результату порівняння.

## Рівність (==)

Перевіряє рівність двох значень, але без урахування їх типів.

```typescript
let a = 5;
let b = '5';

// true, бо значення рівні, хоч типи різні
console.log(a == b);
```

## Строга рівність (===)

Перевіряє рівність двох значень разом із їх типами.

```
let a = 5;
let b = '5';

// false, бо типи різні
console.log(a === b);
```

## Нерівність (!=)

Перевіряє, чи не рівні два значення, не зважаючи на типи.

```
let a = 5;
let b = '5';

// false, бо значення рівні
console.log(a != b);
```

## Строга нерівність (!==)

Перевіряє, чи не рівні два значення разом із їх типами.

```typescript
let a = 5;
let b = '5';

// true, бо типи різні
console.log(a !== b);
```

## Більше (>)

Порівнює, чи перше значення більше за друге.

```typescript
let a = 10;
let b = 5;

console.log(a > b); // true
```

## Менше (<)

Порівнює, чи перше значення менше за друге.

```typescript
let a = 10;
let b = 15;

console.log(a < b); // true
```

## Більше або дорівнює (>=)

Перевіряє, чи більше перше значення за друге або дорівнює йому.

```typescript
let a = 10;
let b = 10;

console.log(a >= b); // true
```

## Менше або дорівнює (<=)

Перевіряє, чи менше перше значення за друге або дорівнює йому.

```typescript
let a = 10;
let b = 15;

console.log(a <= b); // true
```

## Посилання

- [Посібник JavaScript] [Оператори порівняння](https://uk.javascript.info/comparison)