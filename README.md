## Навигация

1. pwd (от англ. <strong><em>p</em></strong><em>rint <strong>w</strong>orking <strong>d</strong>irectory</em>, <br>

«показать рабочую папку») — покажи, в какой я папке;

2. ls (от англ. <strong><em>l</em></strong><em>i<strong>s</strong>t directory contents</em>, <br>

«отобразить содержимое директории») — покажи файлы и папки в текущей папке;

3. ls -a — покажи также скрытые файлы и папки, названия которых начинаются с символа .;

4. cd first-project (от англ. <strong><em>c</em></strong><em>hange <strong>d</strong>irectory</em>, <br>

«сменить директорию») — перейди в папку first-project;

5. cd first-project/html — перейди в папку html, которая находится в папке first-project;

6. cd .. — перейди на уровень выше, в родительскую папку;

7. cd ~ — перейди в домашнюю директорию (/Users/Username);

7. cd / — перейди в корневую директорию.

## Работа с файлами и папками

### Создание

1. touch index.html (англ. touch, «коснуться») — создай файл index.html в текущей папке;

2. touch index.html style.css script.js — если нужно создать сразу несколько файлов, можно напечатать их имена в одну <br>

строку через пробел;

3. mkdir second-project (от англ. <strong><em>m</em></strong><em>a<strong>k</strong>e <strong>dir</strong>ectory</em>, <br>

«создать директорию») — создай папку с именем second-project в текущей папке.

### Копирование и перемещение

1. cp file.txt ~/my-dir (от англ. <strong><em>c</em></strong><em>o<strong>p</strong>y</em>, «копировать») — <br>

скопируй файл в другое место;

2. mv file.txt ~/my-dir (от англ. <strong><em>m</em></strong><em>o<strong>v</strong>e</em>, «переместить») — <br>

перемести файл или папку в другое место.

### Чтение

1. cat file.txt (от англ. <em>con<strong>cat</strong>enate and print</em>, «объединить и распечатать») — <br>

распечатай содержимое текстового файла file.txt.

### Удаление

1. rm about.html (от англ. <strong><em>r</em></strong><em>e<strong>m</strong>ove</em>, «удалить») — удали файл about.html;

2. rmdir images (от англ. <strong><em>r</em></strong><em>e<strong>m</strong>ove <strong>dir</strong>ectory</em>, <br>

«удалить директорию») — удали папку images;

3. rm -r second-project (от англ. <strong><em>r</em></strong><em>e<strong>m</strong>ove,

</em> «удалить» + <strong><em>r</em></strong><em>ecursive</em>, «рекурсивный») — удали папку second-project и всё, <br>

что она содержит.

## Полезные возможности

Команды необязательно печатать и выполнять по очереди. Можно указать их списком — разделить двумя амперсандами (&&).

У консоли есть собственная память — буфер с несколькими последними командами. 

По ним можно перемещаться с помощью клавиш со стрелками вверх (<strong>↑</strong>) и вниз (<strong>↓</strong>).

Чтобы не вводить название файла или папки полностью, можно набрать первые символы имени и дважды нажать Tab. 

Если файл или папка есть в текущей директории, командная строка допишет путь сама.

Например, вы находитесь в папке dev. Начните вводить cd first и дважды нажмите Tab. 

Если папка first-project есть внутри dev, командная строка автоматически подставит её имя. Останется только нажать Enter.