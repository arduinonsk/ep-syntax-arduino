Установка
=====

Шаг 1
-----

Положить скрипт в папку %ETHERPAD/node_modules/ep_syntaxhighlightning/static/js/

Шаг 2
-----

Добавить строку

	<script src="/static/plugins/ep_syntaxhighlighting/static/js/shBrushArduino.js"></script>

в файл %ETHERPAD/node_modules/ep_syntaxhighlightning/templates/syntaxHighlightningScripts.ejs

Шаг 3
-----

Добавить строку 

	<option value="arduino">Arduino</option>

в файл %ETHERPAD/node_modules/ep_syntaxhighlightning/templates/syntaxHighlightningEditbarButtons.ejs