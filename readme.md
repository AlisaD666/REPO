**Инструкция по работе с GIT**

* Создаем репозиторий 
1. Создать папку(без символов, пробелов и цифр, на англ языке) 
2. Доверять папке
3. Открыть терминал 
4. Проверяем, что в пути терминала та папка, которую создали (команда pwd)
5. Командой git init инициализуруем репозиторий

* Создаем папку
1. Создаем файл "readme.md"
2. Через команду git add .\readme.md сохраняем файл
3. Делаем первый коммит через команду git commit -m "Initial commit"
4. Идем в файл readme.md, пишем текст
5. Через команду git add .\readme.md сохраняем файл
6. Через команду git commit -m "Пишем комментарий об изменениях"
7. Через команду git log можно посмотреть все изменения файла(хэш коммита), выйти кнопка Q
8. Через команду git checkout и в нее добавляем первые 4 знака из хэша коммита, к которому хочу перейти
9. Через команду git checkout main можно вернуться в предыдущий коммит

*Готово! Вы великолепны :)*

