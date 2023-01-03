Репозиторий содержит в себе набор автотестов для тестирования формы регистрации/авторизации сайта: https://b2c.passport.rt.ru

Проект выполнен с использованием PageObject, Selenium и PyTest

Установка всех необходимых библиотек производится консольной командой
pip install -r requirements.txt


В файл settings находятся данные для авторизации


В файле base.py содержится шаблон PageObject для Python.

В файле elements.py содержатся локаторы для поиска элементов на странице.

В файле registration_page.py содержится класс страницы регистрации на сайте Ростелеком.

В файле auth_page.py содержится класс страницы подтверждения регистрации.

В файле autotests_rostelecom.py располагается набор тестов для веб-интерфейса сайта.

В файле conftest.py находятся фикстуры по дополнительным настройкам.

Запуск тестов осуществляется консольной командой
python -m pytest -v --driver Chrome --driver-path <Путь до вебдрайвера>\chromedriver.exe autotests_rostelecom.py.
