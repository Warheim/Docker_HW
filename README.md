# Docker homework #1
Порядок запуска контейнера:
1. Находясь в корневой директории, создайте образ: выполните команду sudo docker build .
2. Выполните команду sudo docker image ls и скопируйте IMAGE ID созданного образа или скопируйте IMAGE ID
после создания образа (в последней строке лога терминала).
3. Запустите контейнер, выполнив команду sudo docker run -d -p ЖЕЛАЕМЫЙ НОМЕР СВОБОДНОГО ПОРТА, НАПРИМЕР 7777:80 IMAGE ID
4. Проверьте работу контейнера в браузере, набрав в адресной строке localhost:ЗАНЯТЫЙ ВАМИ ВЫШЕ НОМЕР ПОРТА
или с помощью команды в терминале: curl localhost:ЗАНЯТЫЙ ВАМИ ВЫШЕ НОМЕР ПОРТА
