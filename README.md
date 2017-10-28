# drive-fetcher

Загружает информацию по указанным маркам с https://www.drive.ru

### Настройка локальной машины для запуска скрипта

 * Установить Python3 (https://www.python.org/downloads/release/python-342/)
 * Прописать в переменную окружения PATH к установленному каталогу с python.exe (по умолчанию это C:\Python34\) и добавить путь к C:\Python34\Scripts
 * Установить git-клиента https://git-scm.com/downloads
 * Запустить консоль git
 * Клонировать репозиторий себе на локальную машину
    ```bash
    git clone https://github.com/efpato/drive-fetcher.git
    ```
 * Перейти в склонированный каталог и выполнить:
    ```bash
    pip install -r requirements.txt
    ```

### Примеры использования

```bash
python fetch kia
python fetch kia ford greatwall
```
На выходе получаем excel-файл report.xlsx
