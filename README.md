# Шпаргалка по работе с Git
- Репозиторий - просто папка и нужно сделать  эту папку репозиторием. Для этого [инициализируем репозиторий](./init_help.md) НЕ создавай репозиторий Git внутри другого Git-репозитория - в папке внутри папки, в которой уже есть Git. 
- Создан Git-репозиторий, но в нём пока ничего нет. Добавить туда файлы, это создать, например, файл todo.txt, в котором будет список дел, и readme.txt для информации о проекте. [Тут добавляем файлы в репозиторий и готовим к сохранению](./add_help.md)
- Коммит — это одна из основных сущностей в Git (и в других системах контроля версий). Коммит гарантирует, что изменения будут сохранены в истории и при необходимости к ним можно будет «откатиться». Это как если бы вы могли выполнить операцию Ctrl+Z для целой папки (репозитория). [Делаем первый коммит](./commit_help.md)
- Вывести историю коммитов понадобится для отслеживания того, что происходит в репозитории. [Просмотреть историю коммитов](./log_help.md)
- Создание новой ветки, переход в неё  и удаление [лежит здесь](./branch_help.md)
- В процессе работы с Git будет часто встречаться понятие «хеш коммита». Об этих странных строчках с бессмысленным (на первый взгляд) набором букв и цифр по команде git log из историю коммитов [читайте здесь] (./hash_help.md). 
 
