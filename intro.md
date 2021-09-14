### Введение   

Что делаем сегодня?  

* знакомимся  

* создаем аккаунт на [GitHub](github.com)  

* создаем репозиторий `lingdata` в вашем аккаунте  

* изучаем форматы Markdown и HTML  

* файл-образец для работы:  [https://raw.githubusercontent.com/olesar/lingdata/gh-pages/data/example-webpage.html](https://raw.githubusercontent.com/olesar/lingdata/gh-pages/data/webpage.html)  

Для редактирования html рекомендуем использовать [NotePad++]() или другой продвинутый текстовый редактор    



#### Домашнее задание:  

* создаем/доделываем личную страницу и загружаем на гитхаб  

* заполняем анкету про ваш аккаунт на GitHub и ваши компьютерные навыки (см. почту)  

* находим интервью на YouTube для работы в течение модуля (оно понадобится для следующего домашнего задания)   


### Основы работы с GitHub

На занятиях по Python вы научитесь полноценно пользоваться GitHub как системой контроля версий. Для выполнения этого домашнего задания достаточно, чтобы вы  

* завели аккаунт на GitHub  

* создали там репозиторий  

* загрузили файлы в репозиторий  

Все эти действия можно совершать с помощью браузера, особенно если вы не знаете заклинаний `git add`, `git commit`, `git push` в командной строке.  

1. На странице [github.com](https://github.com/) нажмите Sing Up, заведите аккаунт (имя - любое), подтвердите его по электронной почте.

<img src="fig/github-signup.png" alt="sign up" width="70%"/>

2. Вам предложат создать новый репозиторий:

<img src="fig/github_new_repo.png" alt="new repo" width="70%"/>

Если так не получилось, зайдите на основную страницу своего гитхаба (например, моя - https://github.com/olesar, где olesar - название моего аккаунта) и нажмите кнопку New на вкладке Repositories

<img src="fig/github_new_repo1.png" alt="another new repo" width="50%"/>

3. Укажите имя репозитория, тип (Public) и добавьте файл README.

<img src="fig/github_repo_type.png" alt="another new repo" width="70%"/>

4. Зайдите в созданный репозиторий и добавляйте файлы с помощью кнопки `Add files`...

5. Чтобы отредактировать существующий файл, кликните на "карандашик" справа вверху.  

6. Кнопка Raw позволяет увидеть "сырое", техническое представление файла со всеми тегами разметки, если они есть.  

7. Чтобы создать папку внутри репозитория, нажмите `Create file` и создайте файл с именем `newfolder/readme.txt` или `newfolder/readme.md`, где `newfolder` - имя вашей папки. В файл readme рекомендуется написать краткий комментарий, для чего эта папка. Нажмите на кнопку `Commit new file` внизу страницы.



### Markdown   

Markdown (md) - это облегченный язык для разметки форматирования текстов. Он часто используется для написания документации на GitHub. 

Самое основное   

```markdown

# Заголовок 1
## Заголовок 2
### Заголовок 3

* ненумерованный
* список
  * элементы второго уровня
  * элементы второго уровня

1. нумерованный 
2. список

**Bold** и _Italic_ и `ключевые слова` text

[Link](url) and ![Image](src)

Три обратных апострофа  (```) выделяют и конец блока текста, обычно кода программы
```

Более подробно тут [Markdown CheatSheet](https://towardsdatascience.com/the-ultimate-markdown-cheat-sheet-3d3976b31a0) и [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).



### HTML

HTML - язык разметки форматирования веб-страниц. HTML-код работает также в файлах Markdown-а.  

Большинство тегов  html - парные, закрывающий тег содержит слэш. У тегов бывают атрибуты и значения. 

```html
<h1>Заголовок 1 уровня</h1>
<h2>Заголовок 1 уровня</h2>
<h2>Заголовок 1 уровня</h2>

<p>Абзац</p>

Принудительный перенос <br> строки (line break)

<b>полужирный</b> и <i>курсив</i> и <i><u>подчеркнутый</u> курсив</i>

с помощью CSS стилей в <span style="font-weight:bold; color:blue;">тексте</span>. 

<a href="github.com">гиперссылка</a>

<img src="https://ruscorpora.ru/i/logo.gif"/>картинка</a>
```