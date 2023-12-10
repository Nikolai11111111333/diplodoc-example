# Basic "About page" 

This is an example for basic documenation project.
It contains simple structure with couple of pages (this page, another page) and nested sub-section. 

Diplodoc provides you with unique name how this project can be reached on https://diplodoc.com like 
"https://common---gh-aje0e4eg9hffg001r5e5.viewer.diplodoc.com/en/" 

If you would like to extend your project - please refer to [YFM Project Organization guide](https://diplodoc.com/docs/en/project/)

All changes for this project can be done within you public github repository called "diplodoc-example/docs". 
To make changes and apply them: 

- go to your repo under "diplodoc-example/docs" 
- make changes for project structure or content
- commit & push into your repository 
- go to "Actions" tab for docs repository 
- run "Release" action and wait till completion 
- done, updates should be available for everyone. 


In case if you would like to make proxy from your own domain to this Documentation - please [Contact Us](https://diplodoc.com/#contact) - we will support you accordingly till appropriate documentation creation. 




# Возможности GitBook

### Таблицы

<table><thead><tr><th>Заголовок 1</th><th>Заголовок 2</th><th data-type="checkbox">Checkbox</th></tr></thead><tbody><tr><td>Ячейка 1</td><td>Ячейка 2</td><td>true</td></tr><tr><td>Ячейка 3</td><td>Ячейка 4</td><td>false</td></tr></tbody></table>

***

### Чек-листы

```
- [x] Задача 1
- [ ] Задача 2
- [ ] Задача 3
```

_**Пример:**_

* [x] Задача 1
* [ ] Задача 2
* [ ] Задача 3

***

### Внутренние ссылки

_**Пример:**_

Перейти к [Заголовку 1](vozmozhnosti-gitbook.md#zagolovok-1)

### Заголовок 1

Какой-то контент

***

### Автоматические ссылки

```
<http://example.com/>

<address@example.com>
```

_**Пример**_

[http://example.com/](http://example.com/)

[address@example.com](mailto:address@example.com)

***

### HTML

Markdown поддерживает использование прямого HTML внутри документа, так что вы можете использовать любые HTML-теги для более сложного оформления:

```html
<kbd>CTRL</kbd> + <kbd>P</kbd>
```

_**Пример:**_

CTRL + P

***

### HTML-коды

Например, вы можете использовать HTML-код `&macr;` для добавления черты над буквой:

```html
A&macr;
```

_**Пример:**_

A¯

***

### Комментарии

Вы можете вставить комментарии в свой markdown-файл, которые не будут отображаться в окончательном отформатированном виде:

```
[//]: # (Это комментарий, он не будет отображаться)
```

_**Пример:**_

***

### Эмодзи (Github)

Вы можете использовать эмодзи в своих Markdown-файлах. [Существует множество эмодзи](https://gist.github.com/rxaviers/7360908), которые вы можете использовать, вот некоторые из них:

```
:smile:
:laughing:
:blush:
```

_**Пример:**_

:smile: :laughing: :blush:

***

### Cards

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td></td><td>Card 1</td><td></td><td></td><td></td></tr><tr><td></td><td>Card 2</td><td></td><td></td><td><a href="wiki-test.md">wiki-test.md</a></td></tr><tr><td></td><td>Card 3</td><td></td><td><a href=".gitbook/assets/wooden-desk-with-a-mouse.jpg">wooden-desk-with-a-mouse.jpg</a></td><td></td></tr></tbody></table>

***

### Tabs

{% tabs %}
{% tab title="First Tab" %}
1
{% endtab %}

{% tab title="Second Tab" %}
2
{% endtab %}
{% endtabs %}

***

## Drawing

Ввел

```
Википедии резюмируются в 5 простых идеях:
Википедия — это онлайн-энциклопедия;
у неё нейтральная точка зрения;
в ней свободный контент, который может редактировать и распространять каждый;
все участники Википедии должны взаимодействовать уважительно и вежливо между собой; 
в Википедии нет строгих правил.
```



<img src=".gitbook/assets/file.excalidraw (1).svg" alt="Википедия" class="gitbook-drawing">

***

## Math & TeX

$$
f(x) = x * e^{2 pi i \xi x}
$$

***

### Google Forms

{% embed url="https://forms.gle/nzXUcc7HfixZSu5YA" %}

***

### Google таблица

{% embed url="https://docs.google.com/spreadsheets/d/18kMnomghHm5KymUKk2Sopc5tpZaH_qLrEQttPttFafw/edit?usp=sharing" %}

***

### Папка в  Google Drive

{% embed url="https://drive.google.com/drive/folders/1XQZicnzzjZxVF4shJKpEDmndd8qnJPZB?usp=sharing" fullWidth="false" %}

***

### Google Slides

{% embed url="https://docs.google.com/presentation/d/1bKP2w1r_ZNkNGV253JEu1icGCg18EYn7z1bRLinNRWI/edit?usp=sharing" %}

***

### Slides.com

{% embed url="https://slides.com/nikolai11111111333/deck" %}

***

### Рисунок

<img src=".gitbook/assets/file.excalidraw (2).svg" alt="" class="gitbook-drawing">

***

### Hint

{% hint style="info" %}
Текст
{% endhint %}

{% hint style="warning" %}
Текст
{% endhint %}

{% hint style="danger" %}
Текст
{% endhint %}

{% hint style="success" %}
Текст
{% endhint %}

### Quote

> 1

### Expandable

<details>

<summary>1</summary>

<mark style="color:blue;">**Текст**</mark>

_Текст_

~~Текст~~



</details>

***

### Яндекс Диск

{% embed url="https://disk.yandex.ru/d/jimX4XUzLnTM_Q" %}

***

### Яндекс форма

{% embed url="https://forms.yandex.ru/cloud/65747c5050569057733cbd48/" %}

