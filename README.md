# postman-autotest
Задание:
http://hr-challenge.interactive-ventures.com/qa-auto.html


## Как запустить тесты:

- Запустите Postman
- Нажмите Import и выберите файл [Sample REST API.postman_collection.json](Sample%20REST%20API.postman_collection.json)
- Перейдите на вкладку Environments
- Создайте новый Environment с параметром baseUrl и значением
``` hr-challenge.interactive-ventures.com ```
- Перейдите на вкладку Collections
- Нажмите правой кнопкой мыши на коллекцию Sample REST API и выберите Run Collection - Run


## Как открыть отчет о тестировании
- Запустите Postman
- В верхнем левом углу выберите "File" (Файл).
- В выпадающем меню выберите "Import" (Импорт).
- В диалоговом окне "Import" выберите "Test Results" (Результаты тестов) и затем щелкните на кнопке "Choose File" (Выбрать файл) или перетащите файл .postman_test_run в это окно.
- После этого Postman откроет файл и отобразит результаты выполнения тестов, включая информацию о запросах, успешных и неуспешных тестах, времени выполнения и т. д.