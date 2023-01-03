Репозиторий содержит в себе набор автотестов для тестирования формы регистрации/авторизации сайта: https://b2c.passport.rt.ru

Проект выполнен с использованием PageObject, Selenium и PyTest

Все тесты находятся в папке tests, в файле test_rostelecom. В папке pages хранится base_page, auth_page и отдельный файл elements, содержащий в себе локаторы для поиска элементов на странице. Отдельно файл settings с данными для авторизации и requirments со списком необходимых для установки библиотек.

Запуск тестов при помощи консольной команды:
python -m pytest -v --driver Chrome --driver-path <Путь до вебдрайвера>\chromedriver.exe test_rostelecom.py.
