# План

1. backgorund image
1. pseudo elements
1. transition
1. svg [icomoon](https://icomoon.io/)
1. position

## Background Image

Короткий опис властивостей background у CSS та їх можливих значень:

1. background-color — задає колір фону.
   - Значення: будь-який допустимий колір (#hex, rgb(), hsl(), або transparent).
2. background-image — встановлює зображення або градієнт як фон.
   - Значення: url('image.jpg'), linear-gradient(), radial-gradient(), none.
3. background-repeat — визначає, чи буде повторюватися фон.
   - Значення: repeat (за замовчуванням), no-repeat, repeat-x, repeat-y, space, round.
4. background-position — визначає розташування фонового зображення.
   - Значення: left top, center center, right bottom, px або % значення.
5. background-size — встановлює розмір фонового зображення.
   - Значення: auto, cover, contain, конкретні розміри (px, %).
6. background-origin — визначає, звідки починається відображення фону.
   - Значення: border-box, padding-box, content-box.
7. background-clip — визначає, де обрізається фон.
   - Значення: border-box, padding-box, content-box, text.

Усі ці властивості можна об’єднати в background скорочений запис, наприклад:

background: #303030 url('image.jpg') no-repeat center/cover padding-box;

## Pseudo Element
