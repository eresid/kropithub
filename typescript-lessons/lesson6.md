# Урок 6. Логічні оператори

Логічні оператори використовуються для перевірки умов і прийняття рішень у вашому коді. Вони повертають значення true або false в залежності від того, чи є умова істинною чи хибною.

## Оператор && (AND)

Оператор && повертає true, якщо обидві умови є істинними. Якщо хоча б одна умова є хибною, результат буде false.

```typescript
let age = 25;
let hasLicense = true;

if (age >= 18 && hasLicense) {
  console.log("Можна керувати автомобілем.");
} else {
  console.log("Керувати автомобілем не можна.");
}
```

## Оператор || (OR)

Оператор || повертає true, якщо хоча б одна умова є істинною. Якщо обидві умови хибні, результат буде false.

```typescript
let isWeekend = true;
let isHoliday = false;

if (isWeekend || isHoliday) {
  console.log("Сьогодні вихідний.");
} else {
  console.log("Сьогодні робочий день.");
}
```

## Оператор ! (NOT)

Оператор ! повертає протилежне значення умови. Якщо умова істинна, результат буде false, і навпаки.

```typescript
let isRaining = false;

if (!isRaining) {
  console.log("Можна йти на прогулянку.");
} else {
  console.log("Краще залишитися вдома.");
}
```

## Комбінації логічних операторів

Логічні оператори можна комбінувати, щоб перевіряти складніші умови. Також можна використовувати круглі дужки для визначення пріоритетності.

```typescript
let age = 20;
let hasLicense = false;
let youAreTankDriver = true;

if ((age >= 18 && hasLicense) || youAreTankDriver) {
  console.log("Можна керувати автомобілем.");
} else {
  console.log("Керувати автомобілем не можна.");
}
```

## Посилання

- [Логічні оператори і все що необхідно про них знати](https://www.youtube.com/watch?v=Nn79iOFiBuY)
- [Посібник JavaScript: Логічні оператори](https://uk.javascript.info/logical-operators)