# tasktest3
В этом коде:

Создается Flask-приложение и SQLAlchemy-конфигурация для работы с SQLite.
Определена модель File для хранения метаданных о загруженных файлах.
Реализован эндпойнт /upload для загрузки CSV-файлов.
Реализован эндпойнт /files для получения списка файлов с информацией о колонках.
Реализован эндпойнт /data/<int:file_id> для получения данных из конкретного файла с возможностью фильтрации и сортировки (пример фильтрации и сортировки не представлен, но его можно добавить в соответствующем разделе кода).
Для того чтобы запустить этот код, сохраните его в файл main.py, создайте папку uploads в том же каталоге, что и main.py, и установите необходимые библиотеки с помощью команды:

pip install Flask Flask-SQLAlchemy pandas
Затем запустите приложение с помощью команды:

python main.py
После этого ваш сервис будет доступен по адресу http://127.0.0.1:5000.
