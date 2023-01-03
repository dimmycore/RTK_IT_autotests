Репозиторий содержит в себе набор автотестов для тестирования формы регистрации/авторизации сайта: https://b2c.passport.rt.ru

Проект выполнен с использованием PageObject, Selenium и PyTest

Установка всех необходимых библиотек производится консольной командой
pip install -r requirements.txt

Все тесты находятся в папке tests, в файле autotests_rostelecom.
В папке pages хранится base_page, auth_page и отдельный файл elements, содержащий в себе локаторы для поиска элементов на странице. 
В файл settings находятся данные для авторизации

Запуск тестов при помощи консольной команды:
python -m pytest -v --driver Chrome --driver-path <Путь до вебдрайвера>\chromedriver.exe autotests_rostelecom.py.
