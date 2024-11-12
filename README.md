## Правила и регламент

- [Правила, рекомендации и порядок проведения](https://github.com/hexlet-college-students/exam-rules)

## Задание

Ваша задача состоит в том, чтобы сверстать html таблицу с указанными стилями и атрибутами.

### Примечания

Запрещено менять какие-либо файлы кроме **index.html** и **styles/app.css**.

Результат, который ожидают тесты вы можете посмотреть по адресу **tests/example.spec.js-snapshots**.

Вы можете самостоятельно протестировать свою работу с помощью команды `make test`, либо `npm test`.

Кроме того, не забывайте запускать команду `npm run vite`, чтобы убедиться, что все работает. Используйте инструменты разработчика в браузере для дебага приложения.

Для дебага работы экшенов вы можете выгружать артефакты из `github actions`. Для работы приложения необходимо иметь `Node.js` не ниже 20 версии.

Скриншот тестирование выполняется для операционной системы Linux.

## 1 задача

В файле **index.html** подключите стили, которые расположены по адресу **styles/app.css** и **styles/default.css**. В **body** документа создайте заголовок первого уровня c классом **heading** и содержанием `l1-element-layout-v1`.

## 2 задача

После заголовка в **body** документа добавьте тег **table**, который должен содержать **thead** и **tbody**.

Добавьте в тег **thead** следующее содержимое, в виде ячеек таблицы:

```csv
ID, First Name, Last Name, Goes By, Gender, Class, Alive
```

Добавьте в тег **tbody** следующее содержимое в виде рядов тяблицы с ячейками:

```csv
1, Malcolm, Reynolds, MalCap'n, M, Captain, Yes
2, Zoe, Washburn, Zoe, F, First Mate, Yes
3, Hoban, Washburn, Wash, M, Pilot, No
```

Добавьте для последнего ряда таблицы класс `disabled`.

## 3 задача

В файле **styles/app.css**:

Добавьте для каждого нечетного ряда следующее свойство:

```css
  background-color: #024156;
```

Используйте для этого псевдоклассы.

## 4 задача

В файле **styles/app.css**:

Добавьте для элемента с классом **heading** в качестве заднего фона изображение **styles/image.png**. Задайте для приложения в **body** такое расположение элементов, чтобы заголовок находился ровно над таблицей и оба элемента находились посередине страницы по оси x.
