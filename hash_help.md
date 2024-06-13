* Git хеширует (преобразует) информацию о коммите с помощью алгоритма SHA-1 (от англ. Secure Hash Algorithm — «безопасный алгоритм хеширования») и получает для каждого коммита свой уникальный хеш — результат хеширования.
Обычно хеш — это строка в 40 символов, которая состоит из цифр от 0 до 9 и латинских букв A—F (неважно, заглавных или строчных).

* Строка обладает следующими важными свойствами: если хеш получить дважды для одного и того же набора входных данных, то результат будет гарантированно одинаковый; если хоть что-то в исходных данных поменяется (хотя бы один символ), то хеш тоже изменится (причём сильно). 

* Git хранит таблицу соответствий хеш → информация о коммите. По хеш можно узнать всё остальное: автора и дату коммита и содержимое закоммиченных файлов. Можно сказать, что хеш — основной идентификатор коммита.

* Их можно будет передавать в качестве параметра разным Git-командам, чтобы указать, с каким коммитом нужно произвести то или иное действие.

* Все хеши и таблицу хеш → информация о коммите Git сохраняет в служебные файлы. Они находятся в скрытой папке .git в репозитории проекта.