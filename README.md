# BoostyGoal
## Текущая версия проекта v0.6
Приложение для создания виджетов с информацией Boosty для OBS.
Текущий спектр доступной информации: Цели по подписчикам и сумме сбора.

Пока-что имеет только базовый функционал и простенькое меню.
Для запуска приложения требуется среда [Node.js](https://nodejs.org/ru) не ниже рекомендуемой 19.0.1 версии.


Порядок установки:

1. Скачать архив с исходным кодом и распаковать куда-нибудь.
2. Запустить пакетный файл install.bat для установки модулей.
3. Запустить run.bat для подъёма локального сервера.
4. Перейти на localhost:2727 для доступа в веб редактор.<br>
![image](https://github.com/zevordex/BoostyStreamWidget/assets/60899690/854e00f2-da5e-4e7c-b12f-a22082fd0810)
6. Изучить редактор и ознакомиться с обучающим виджетом.
7. После создания виджета открываем OBS
8. Создать в источниках "браузер"<br>
![image](https://github.com/zevordex/BoostyStreamWidget/assets/60899690/c11b4767-85f7-478c-89a1-6429cb4ba815)
9. В настройках браузера нажать на галочки: отключать когда не видим, обновить браузер когда сцена активна.
10. Установить URL до виджета.<br>
При установке ссылки http://localhost:2727/widgetLink?id=0 нужно заменить цифру параметра id на идентификатор виджета.
![image](https://github.com/zevordex/BoostyStreamWidget/assets/60899690/cbe28aad-4e4c-4db6-a440-71dc82f4f786)
11. Если всё сделано правильно то можно заметить как появляется текст на виджете.<br>
В случае если что-то пошло не так или появились вопросы - создайте issue.
