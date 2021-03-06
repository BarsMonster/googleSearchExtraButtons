### Google Search Extra Buttons

Добавление кнопок на страницу поиска Гугла.

(Fx, Chrome, Opera, Safari)
Хостинг: [greasyfork.org](https://greasyfork.org/en/scripts/7543-google-search-extra-buttons)

* Fx - ставится с помощью Scriptish/GreaseMonkey (аддоны для скриптов);
* Chrome - непосредственно, без расширений (на странице chrome://extensions/ ставится как распакованный скрипт в "режиме разработчика"; в папке должен быть manifest.json; или другими способами);
* Opera - создаётся юзерскрипт в файле, помещается в папку... ( инструкция );
* Safari - ставится с помощью NinjaKit (не проверялось, но ничего особого в скрипте нет).

Добавляет 5 кнопок рядом с кнопкой поиска:

* искать документы PDF;
* искать за последний день;
* искать за последнюю неделю;
* искать за последний месяц;
* искать за последний год;
* если раскомментировать строчку "S" с именем домена и поставить некоторый домен - будет кнопка поиска по сайту;
* если в последней строчке написать не 'ru', а что-то другое - подсказки будут на английском; если ничего не вписать - без подсказок;
* впишите в код список ваших сайтов для поиска (например, ['slashdot.org','digg.com']). 

Основано на [статье BarsMonster](http://habrahabr.ru/post/179367/) .


![Для поиска по сайту](https://raw.githubusercontent.com/spmbt/googleSearchExtraButtons/master/googleSearchExtraButt20150218-white.png)

![Список для поиска по сайту в тёмном дизайне заголовка](https://raw.githubusercontent.com/spmbt/googleSearchExtraButtons/master/googleSearchExtraButt20150218-dark.png)