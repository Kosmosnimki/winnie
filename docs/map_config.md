# Описание карты

Конфигурационный файл в формате JSON формирует список провайдеров данных и слоев, загружаемых на карту конструктора. Список слоев можно структурировать по рубрикам верхнего уровня с помощью параметра "children". Все элементы, у которых есть "children" считаются группами.

### `map` - ключ, содержащий описание структуры и параметров слоев карты

- `<Boolean> list` - стиль мета-меню для отображения названий рубрик
  - `true` - выпадающий список, адаптированный под мобильные интерфейсы
  - `false` - горизонтальное меню для десктопов

- `<Boolean> expanded` - показывает рубрику выбранную по-умолчанию

### 'children' - ключ, содержащий описание группы слоев
  



