# Модуль Г. Спидтаски

[Изначальное задание](/task/README.md)

Задания записанные нормально

# Время на выполнение : 4 часа


# Задачи

## Разработка интерфейса пользователя

### 1

Пропорционально уменьшить изображение до 1000x700 (по любой из сторон).

Использовать HTML+CSS ИЛИ графический редактор

### 2

Разработать набор иконок для видеоплеера

1. воспроизведение
2. пауза
3. отключение звука
4. увеличение/уменьшение громкости
5. быстрая перемотка вперед/назад

Задачу можно выполнить HTML+CSS ИЛИ с помощью графического редактора

### 3

Использовать HTML+CSS ИЛИ графический редактор

### 4

Добавьте темно-синий фильтр на изображение и добавьте на изображение
текст «Добро пожаловать в наш магазин»

Использовать HTML+CSS ИЛИ графический редактор

### 5

Сделать адаптивный макет (только секции) для блога: шапка, основная, боковая панель, футер.

Макет должен корректно отображаться в следующих значениях ширины: ≥576px, ≥768px, ≥992px

### 6

Создайте веб-страницу с 5 различными уникальными стилями для кнопок, каждая с анимацией
наведения и анимацией нажатия, анимации должны уникальными для обоих событий

## Разработка на стороне клиента

### 7

Создать параллакс эффект из представленных изображений.
Сцена остается в неподвижном состоянии. Второй слой (шторы) -
при движении мыши (влево/вправо) производят движения, а
так же двигается третий слой (люстра), но с меньшим смещением.

### 8

В центре экрана разместить окружность с радиусом не менее
200px. От центра окружности до
края окружности отрисовывается отрезок,
следующий за курсором мыши. При наведении в
центр окружности отрезок исчезает.

### 9

В центре страницы поместить квадрат размером не менее 400px. Менять его цвет в
зависимости от курсора мыши с плавным переходом цветов. В правом верхнем углу у вас
должен быть максимальный красный цвет. В левом нижнем углу у вас должен быть
максимальный синий цвет. В правом нижнем углу у вас должен быть максимальный белый
цвет. Верхний левый угол является чёрным цветом.

### 10

Случайное количество окружностей (от 3-х до 5-ти) разного размера
(диаметром от 100px до 200px) хаотично перемещаются по экрану.
Если они касаются курсора мыши, то должны оттолкнуться от него и
изменить свое направление. Также должна быть коллизия окружностей
с краем области.

### 11

Используя JavaScript, создайте область страницы на которой пользователь
может рисовать своим курсором при зажатой левой клавиши мыши.

## Разработка на стороне сервера

### 12

С помощью PHP добавить водяной знак “Proffessional” в нижнем правом краю изображения,
открыть ссылку на измененное изображение.
(Использовать файл 12.html для загрузки фотографии в ваш скрипт)

### 13

Дана строка. Необходимо найти подстроку, которая является самым длинным палиндромом.

> Wiki: Палиндромом - число, буквосочетание, слово или текст, одинаково читающееся в
> обоих направлениях. Например, число 101; слова «топот» в русском языке и фин.
> saippuakivikauppias (продавец мыльного камня; торговец стеатитом) — самое длинное
> слово-палиндром в мире; текст «а роза упала на лапу Азора» и прочие являются
> палиндромами.

Используйте файл 13.html

### 14

Создайте набор таблиц, необходимых для отношения «многие ко многим» между
автомобилями (номер автомобиля(уникальный), пробег) и водителями автомобилей (ФИО,
номер водительского удостоверения(уникальный), дата рождения).

В директории сохраните файл dump.sql

### 15

Создайте функцию для сортировки букв заданной строки в порядке возрастания.

«backdsts» => «abcdsst»

(Использовать файл 15.html)

### 16
Даны три таблицы: пользователи, товары и заказанные товары. С помощью запроса Вам нужно
получить список заказанных товаров, включая идентификатор пользователя, имя пользователя,
идентификатор заказа, время заказа, идентификатор товара и название товара.

В директории сохраните файл select.sql

## Разработка информационных ресурсов с использованием готовых решений

Каждая задача может быть выполнена как в в составе одного проекта WordPress, так и в
отдельном проекте.

### 17

Установите wordpress. Данные для авторизации администратора:

- Логин: admin2023
- Пароль: password2

### 18

Создайте плагин, который реализовывает шорткод [current-datetime]. Шорткод выводит
текущую дату и время сервера в формате:

```
Д Месяц(текстом) ГГГГ ЧЧ:ММ
(3 июля 2023 14:59)
```

### 19

Создайте плагин, который добавляет новый тип поста reviews. Плагин должен также
реализовать два шорткода:

[reviews-form] - выводит форму добавления отзыва в любом стиле. Отзыв может добавить как
авторизованный пользователь так и гость. Форма состоит из двух обязательных полей: имя и
сообщение.

[reviews-list] - выводит список отзывов в любом оформлении. Отзыв состоит из имени,
сообщения и даты публикации

### 20

Возьмите предоставленный шаблон и создайте тему на основе этого шаблона. Все стили
должны быть сохранены как и интерактив, который реализовывается через JavaScript. Тема
должна выглядеть идентично шаблону. Выводить посты и прочую информацию не нужно,
нужно вывести только admin-bar для администратора. Тема должна отображаться в списке тем,
изображение темы в списке должно соответствовать виду шаблона

## Инструкция для конкурсанта

Для выполнения заданий по технологии “Разработка информационных ресурсов с использованием готовых
решений” вам предоставляется CMS Wordpress 6.2.x. Остальные задачи необходимо решить без использования
фреймворков и сторонних библиотек.

Разработанные задания должен быть размещены по адресу http://xxxxxx-m4.moscow.ru/y/, где xxxxxx - логин
участника (указан на индивидуальной карточке), y — номер задачи. Медиа-файлы задач должны быть
скопированы в соответствующую папку задачи. Также в медиа возможны уточняющие требования,
специфичные для конкретной задачи.