### Макрос для программы Notepad++ 
Автоматически переводит текст, написанный эрзянскoй кириллицей на латиницу, разработанную для проекта *RAVO*. 

*Notepad++* - бесплатный многофункциональный текстовый редактор с расширенным функционалом. Им удобно пользоваться при работе с большими объёмами текста. *Макрос* - последовательность действий пользователя в программе, записанная и сохраненная этой программой.

<hr>

### Порядок установки
1. Устанавливаем программу Notepad++ с официального сайта https://notepad-plus-plus.org/downloads/

1. Устанавливаем макрос в программу Notepad++ :

Скачиваем содержимое репозитория, зелёная кнопка *"Clone or download"* -> *"Download ZIP"*

![](https://docs.google.com/uc?id=1bjEW0acLfCM2XPVVHlsJNFh2eND3Vdv3)

Распаковываем архив, находим файл *shortcuts.xml*

![](https://docs.google.com/uc?id=1BdHSSllsFxHjC-UKfGfMfHTo0rmenZMz)

   
Далее необходимо заменить скачанный файл *shortcuts.xml* на аналогичный файл в программе  *Notepad++*. Папка с этим файлом по умолчанию скрыта, нам необходимо либо открыть скрытые папки Windows и найти этот файл по адресу:

  > C:\Users\%username%\AppData\Roaming\Notepad++\shortcuts.xml (для Windows 7|8)
  > C:\Documents and Settings\%username%\Application Data\Notepad++\shortcuts.xml (для Windows < 7)

Либо искать его через строку поиска Проводника Windows по названию файла shortcuts.xml

![](https://docs.google.com/uc?id=1bBVp5aYgHR47x8vEmHsFkPlVgw0eBz8-)
  
Найденный файл меняем на скачанный, соглашаемся с заменой.

![](https://docs.google.com/uc?id=1lgIP7p8_8xkDy0qpTf8XQnWJ3aQXx7DA)

![](https://docs.google.com/uc?id=1xfzZ_eeLYWI_FhII0LAoUCGNzRZDkPlI)
 
Перезапускаем Notepad++, теперь во вкладке Макросы мы видим наш макрос.

![](https://docs.google.com/uc?id=1QORSwZt12H1wf6bViniGbcyzi02d5SFJ)

Для того, чтобы перевести кириллический текст в латиницу. Выделяем его левой кнопкой мыши (обязательно!!!), выбираем Макросы - > erz_latinica. Текст автоматически будет изменен.
