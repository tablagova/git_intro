# Как пользоваться Git

Инициализация
git init

Ввод данных индентификации в конфиг
git config user.name "Guido van Rossum"
git config user.email "guido@python.org" 

Добавление файлов в индекс (для последуюощего коммита)
git add README.md 
или всех
git add . 

Содание коммита
git commit -m "Добавлен README.md"

Проверка статуса 
git status

Просмотр цепочки изменений
git log