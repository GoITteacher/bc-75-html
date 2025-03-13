# html-css

1. Блокова модель, box-sizing;
2. Внутрішні (padding) та зовнішні (margin) відступи;
3. Структурні псевдокласи;
4. Флекси:
   - flex-container, flex-element, axis;
   - flex-direction (напрямок головної осі);
   - justify-content (вирівнювання елементів по головній осі);
   - align-items (вирівнювання елементів по поперечній осі);
   - flex-wrap (перенесення елементів по головній осі);
   - align-content (вирівнювання рядків по поперечній осі);
   - flex-grow (коефіцієнт зростання);
   - flex-shrink (коефіцієнт стиснення);
   - flex-basis (початкова ширина);
   - order (порядок розташування елементів на головній осі);
   - align-self (вирівнювання елемента по поперечній осі);

---

# Корисні посилання

- [Tower Defence Flex BOX](http://www.flexboxdefense.com/)
- [Flex BOX froggy](https://flexboxfroggy.com/#ru)

---

# CheatSheet

Властивості контейнера (батьківського елемента) display: flex;

1. display – задає контейнеру поведінку flex (flex або inline-flex).
2. flex-direction – визначає напрямок основної осі (row, row-reverse, column, column-reverse).
3. flex-wrap – визначає, чи елементи будуть переноситися (nowrap, wrap, wrap-reverse).
4. flex-flow – скорочений запис для flex-direction та flex-wrap (наприклад, row wrap).
5. justify-content – вирівнює елементи вздовж основної осі (flex-start, flex-end, center, space-between, space-around,
   space-evenly).
6. align-items – вирівнює елементи вздовж поперечної осі (flex-start, flex-end, center, baseline, stretch).
7. align-content – визначає вирівнювання рядків у flex-контейнері, якщо є перенесення (flex-start, flex-end, center,
   space-between, space-around, stretch).
8. gap – визначає відступи між елементами.
9. row-gap – визначає вертикальний відступ між рядками.
10. column-gap – визначає горизонтальний відступ між стовпцями.
11. place-content – скорочений запис для align-content та justify-content.

---

Властивості дочірніх елементів (flex-елементів)

1. order – визначає порядок відображення елемента (за замовчуванням 0).
2. flex-grow – визначає, наскільки елемент може розширюватися відносно інших (0 за замовчуванням).
3. flex-shrink – визначає, наскільки елемент може зменшуватися (1 за замовчуванням).
4. flex-basis – визначає початковий розмір елемента до застосування flex-grow та flex-shrink (auto за замовчуванням).
5. flex – скорочений запис для flex-grow, flex-shrink і flex-basis (наприклад, 1 0 auto).
6. align-self – визначає вирівнювання конкретного елемента незалежно від align-items (auto, flex-start, flex-end,
   center, baseline, stretch).
7. place-self – скорочений запис для align-self та justify-self (але justify-self не працює у flex-контейнері).
