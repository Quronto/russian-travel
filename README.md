# Проект: Путешествие по России

В этом проекте представлена "поeздка" по России. Тут можно увидеть прекрасные пейзажи нашей родины, а также прочесть небольшие статьи про некоторые красивые места.
В этом проекте я использовал несколько новых технологий, вот некторые из них с примерами: 
1. Тег @media мы использовали для реализации одинаковых свойств, но для разных разрешений экрана:
``` css
@media screen and (max-width: 425px) {
  .lead {
    max-width: 320px;
    padding-bottom: 64px;
  }
}
```
2. Использовали calc() для упрощения адаптивной вёрстки:
``` css
max-width: calc(100% - 296px);
```
3. А также использовали grid для создании сетки:
``` css
.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(284px, 1fr));
  grid-template-rows: repeat(auto-fit, minmax(213px, 1fr));
  gap: 16px;
}
  ```

Ссылка на сайт: https://quronto.github.io/russian-travel/index.html