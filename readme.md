# Создание ветки

используем команды git init (инициализируем папку)
* git add + название файла
* git commit -m "initial commit"
* git branch + название новой ветки

*посмотреть статус можно с помощью команды git branch
ветка с символом звездочка, будет являться основной*

Чтобы переключиться между ветками, необходимо ввести команду
* git checkout + название ветки
после переключения, пусть с master изменится на название ветки.

Далее можно создавать новые проекты, вносить изменения и пр.

Чтобы залить свои проекты с веток, создаем новый репозиторий на github.

копируем ссылку и вводим команду git remote add origin + ссылка нановый репозит. 
* git push -u origin master

чтобы залить вторую ветку вводим команду 
* git push -u origin и название второй ветки.

Добавим изменения и сольем их с веткой мастер, чтобы все изменения появились в основном коде. 

проверим статус слияния командой 
* git merge --no--ff master


