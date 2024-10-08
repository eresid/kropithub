# Урок 7. Умовні оператори

Умовні оператори дозволяють виконувати різні дії в залежності від певної умови. Це дуже важливо у програмуванні, оскільки дозволяє нашим програмам "думати" і виконувати певні блоки коду в залежності від результатів перевірки.

## Оператор if

Оператор if дозволяє виконати блок коду, якщо умова є істинною (true).

```typescript
let someNumber: number = 10;

if (someNumber > 5) {
    console.log("Число більше за 5");
}
```
У цьому прикладі виведеться повідомлення "Число більше за 5", оскільки умова someNumber > 5 є істинною.

## Оператор if...else

Оператор if...else дозволяє виконати один блок коду, якщо умова істинна, і інший блок, якщо вона хибна (false).

```typescript
let age: number = 17;

if (age >= 18) {
    console.log("Ви повнолітні");
} else {
    console.log("Ви ще неповнолітні");
}
```
У цьому прикладі виведеться "Ви ще неповнолітні", оскільки умова age >= 18 є хибною.

## Оператор else if

Якщо вам потрібно перевірити кілька умов, ви можете використовувати блоки else if.

```typescript
let score: number = 75;

if (score >= 90) {
    console.log("Оцінка: Відмінно");
} else if (score >= 75) {
    console.log("Оцінка: Добре");
} else if (score >= 60) {
    console.log("Оцінка: Задовільно");
} else {
    console.log("Оцінка: Незадовільно");
}
```
У цьому прикладі виведеться "Оцінка: Добре", оскільки score дорівнює 75.

## Тернарний оператор

Тернарний оператор (?:) дозволяє записати прості умовні вирази у більш стислому вигляді.

```typescript
let isMember: boolean = true;
let price: number = isMember ? 80 : 100;

console.log(`Ціна: ${price}`);
```
У цьому прикладі, якщо isMember дорівнює true, то price буде 80, інакше — 100.

## Оператор switch

Оператор switch дозволяє перевіряти одне значення на рівність кільком різним варіантам.

```typescript
let day: number = 3;

switch (day) {
    case 1:
        console.log("Понеділок");
        break;
    case 2:
        console.log("Вівторок");
        break;
    case 3:
        console.log("Середа");
        break;
    default:
        console.log("Невідомий день");
}
```
У цьому прикладі виведеться "Середа", оскільки day дорівнює 3.

## Посилання

- [Уроки JavaScript з нуля](https://www.youtube.com/watch?v=PJF2cB4kLso)
- [Посібник JavaScript: Умовні розгалуження: if, '?'](https://uk.javascript.info/ifelse)
- [Посібник JavaScript: Конструкція "switch"](https://uk.javascript.info/switch)