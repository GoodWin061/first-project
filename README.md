
# Шпаргалка markdown

## Выделение текста

Вы можете выделять текст в markdown с помощью символов `_` или `*`. Например:

Пример _курсива_ и **жирного** текста.

## Заголовки

Заголовки можно создавать с помощью символа `#`. Чем больше `#`, тем меньше заголовок. Например:

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня

## Выделение кода

Чтобы выделить текст как код, поместите его в тройные кавычки `````. 

```
mkdir my_project
cd my_project
git init
```
Это лишь некоторые функции markdown.

Git хранит всю свою служебную информацию в этой папке, в том числе и таблицу, в которой можно найти коммит по хешу.
Эта странная, но важная строка служит главным идентификатором коммита.
Хеш-алгоритм выдаст одно и то же значение для одного набора данных — это не зависит от того, где и как он был запущен.
HEAD — это файл в .git, в файле — ссылка, по ссылке — хеш. Совсем как в сказке: иголка — в яйце, яйцо — в утке, утка — в зайце.
HEAD указывает на последний коммит. Если передать его в качестве параметра, Git поймёт вас.