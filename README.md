# pyqt5-ide

> Созданный по подобию ***vs code*** редактор файлов

## Применение

При первом заходе будет предложено выбрать рабочую директорию.
Директория, как ни странно, откроется в списке слева, а открытые вами файлы будут отображаться сверху.

Как и в самой обычной среде разработки, в этой имеются возможности создания, сохранения и удаления файлов:
```
File > New file ( Ctrl+N )
File > Save file ( Ctrl+S )
File > Delete file
```
В *ide* имеются интерпретаторы, которые можно добавить самому, о чём написано ниже.

## Интерпретаторы

С самого начала имеется один простенький изотерический [интерпретатор](interpreters/example.py),
но для добавления своих можно использовать [***следующий API***](docs/API.md).

Для использования нужно всего лишь:
```
Run > <название нужного интерпретатора>
```

## Будущее проекта

- Синтаксическая подсветка
- Карта документа
- Редактор изображений

## Послесловие

В целом, чтобы использовать это приложение не нужно иметь определённых знаний чего-либо, всё вполне интуитивно понятно.
