# Module_28.1
Rostelecom website testing, testing object https://b2c.passport.rt.ru/ page.

Итоговая практическая работа по автоматизации тестирования.
Руководствуясь техническими требованиями по проекту https://docs.google.com/document/d/1BUTTUXKue4zZzbDxmfb1EhfvReL-UK3O/edit?usp=sharing&ouid=111986019032269986320&rtpof=true&sd=true
были составлены тест-кейсы https://docs.google.com/spreadsheets/d/1tF0XLn_2vE-LU_PY2cfypHhjdP_pQ_CoJrsiaIx0ylI/edit?usp=sharing и баг-репорты
с использованием автотестирования на тест-кейсы проверяющие основной функционал тестируемого раздела сайта.

Задания по тестированию раздела:
- Протестировать требования.
- Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.
- Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.
- Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов)

Применялось тестирование по позитивному и негативному сценарию. Применялась техника тест-дизайна "Анализ граничных значений" в проверке поля ввода "Имя" формы регистрации.

В файле settings необходимо указать действующий логин, пароль зарегистрированного пользователя.

Назначение тестов приведено в комментариях.

Запуск тестов при помощи команд в консоли:
python -m pytest -v --driver Chrome --driver-path chromedriver.exe tests/test.py

Для правильной работы тестов необходимо установить библиотеки в Python 3:

pytest

pytest-selenium

selenium

urllib3
