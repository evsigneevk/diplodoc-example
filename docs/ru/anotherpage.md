# Simple documentation project with YFM


## Project Structure
Basic project contains few config files and pages with actual content. Both config files and markdown linked into the following structure:


```
input-folder
|-- .yfm (config file for whole project)
|-- toc.yaml (table of content)
|-- presets.yaml (presets for vairables)
|-- index.yaml (index page)
|-- pages (Content pages)
    |-- faq.md
    |-- how-to.md
|-- _assets (directory with pictures)
    |-- image1.png
    |-- image2.png
|-- _includes (directory for reusable content)
    |-- faq_shared_block.md
```

## Cuts

{% cut "Заголовок ката" %}

Контент, который отобразится по нажатию.

{% endcut %}

## Tabs

{% list tabs %}

- Название таба 1

  Текст таба 1.

  * Можно использовать списки.
  * И **другую** разметку.

- Название таба 2

  Текст таба 2.

{% endlist %}


