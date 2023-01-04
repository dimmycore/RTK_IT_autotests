Репозиторий содержит в себе набор автотестов для тестирования формы регистрации/авторизации сайта: https://b2c.passport.rt.ru


Установка всех необходимых библиотек производится консольной командой

```bash
pip install -r requirements.txt
```


Запуск тестов осуществляется консольной командой

```bash
python -m pytest -v --driver Chrome --driver-path C:/Documents/chromedriver.exe test_rtk.py
```
