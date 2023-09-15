3Привет!
Это Ваш репозиторий для выполнения лабораторной работы.

Если Вы пользуетесь гитом в первый раз, инструкция ниже для Вас.  
Если уже работали с ним, можете сразу приступать к выполнению лабораторной работы.

- Установите Git  
Если у Вас Windows, зайдите на https://git-scm.com/downloads  
Нажмите на большую кнопку Download for Windows.  
Если у Вас linux гит у Вас уже установлен.  

- Откройте командную строку, выполните первоначальную конфигурацию:
    ```
    git config --global user.name "Your name"  
    git config --global user.email "your@email.com"
    ```
- Создайте на вашем ПК папку для лабораторных работ, перейдите в неё в командной строке (cd 'путь/к/вашей/папке')  
Склонируйте текущий репозиторий командой
    ```
    git clone [ссылка на репозиторий]  
    ```
    Например:
    ```
    git clone https://github.com/Mospolytech-IIT/osa-labs-2022-II-IvanIvanovStd
    ```
    На этом шаге github запросит ваши логин и пароль от учетной записи.

- После того, как репозиторий склонирован, приступайте к выполнению лабораторной работы в папке, которая у Вас появилась. Это Ваш локальный репозиторий.

- После выполнения лабораторной работы, необходимо закоммитить изменения и отправить их в remote (удаленный) репозиторий GitHub.  
Это делается следующим образом (вводим команду одну за другой):
    ```
    git add .
    git commit -m "Done Lab 1"
    git push origin main
    ```
    Первая команда ```add .``` - индексирует все файлы, которые нужно зафиксировать. Вместо ```.``` можно указать конкретный файл, но проще добавлять сразу все.  
    Вторая команда ```commit``` - выполняет коммит (фиксирует изменения), флаг -m ознает message, это комментарий к комиту, туда пишут, что именно было сделано.  
    Третья команда ```push``` - отправляет изменения в репозиторий, origin - наш удаленный репозиторий, main - ветка в удаленном репозитории.

    Если после выполнения команд получаете в командной строке ошибку (красный шрифт), обратите внимание на текст ошибки, обычно там содержится информация о том, что не так и как поправить.

- Откройте Ваш репозиторий в GitHub и проверьте, что изменения в нём отобразились.

Если хотите более подробно ознакомиться с работой в Git, рекомендуем пройти небольшие курсы:
- https://youtu.be/PEKN8NtBDQ0  
- https://git-scm.com/book/ru/v2/Введение-О-системе-контроля-версий 
- https://training.github.com/ 
