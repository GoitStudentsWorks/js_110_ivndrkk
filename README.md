## Підготовка до роботи

1. Переконайся, що на комп'ютері встановлено LTS-версію Node.js.
   [Скачай та встанови](https://nodejs.org/en/) її якщо необхідно.
2. Встанови базові залежності проекту в терміналі командою `npm install`.
3. Запусти режим розробки, виконавши в терміналі команду `npm run dev`.
4. Перейдіть у браузері за адресою
   [http://localhost:5173](http://localhost:5173). Ця сторінка буде автоматично
   перезавантажуватись після збереження змін у файли проекту.

## 🔑 Унікальні назви класів у CSS

Щоб уникнути конфліктів стилів та забезпечити організованість коду, рекомендується використовувати унікальні назви класів, прив’язуючи їх до назви вашої секції. Це дозволить легко зрозуміти, до якої частини сторінки відноситься стиль, і зменшить ризик перезапису правил іншими членами команди.

Рекомендація щодо структури назви класу:

"Назва секції + Назва елемента"

## 📌 Готові стилі для тексту в common.css
У файлі common.css вже налаштовані стилі для тексту, відповідно до макета. Вони включають заголовки, основний текст (Body) і підписи (Caption). Ці стилі адаптовані для всіх пристроїв, тому вам не потрібно створювати їх з нуля. Просто використовуйте готові класи.

🎨 Доступні класи

Заголовки:

h1: Основний заголовок.
h2: Підзаголовок.
h3: Менший заголовок.

Основний текст (Body):

.body1-light: Основний текст із легким начертанням (Light).
.body1-medium: Основний текст із середнім начертанням (Medium).

Підпис (Caption):

.caption: Текст для підписів.
