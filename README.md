# Подсветка синтаксиса 1С для Atlassian FishEye and Crucible
В репозитории содержится файл с описанием правил подсветки синтаксиса 1С в Atlassian FishEye and Crucible
Чтобы добавить подсветку синтаксиса 1С необходимо:

1. Скопировать файл "bsl.def" в подкаталог "syntax" каталога установки Atlassian FishEye and Crucible.
2. В файле "filename.map" в каталоге "/syntax" прописать соответствие файлов с расширением ".bsl" лексеру "bsl.def", см. пример в файле "filename.map" репозитория
3. Перезапустить FishEye
