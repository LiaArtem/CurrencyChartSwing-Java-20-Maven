# CurrencyChartSwing-Java-20-Maven
Maven Java 20 Swing NetBeans project - Construction of charts of currencies of NBU on years for watching of tendencies of change.

Отправка в Github
---------------------------------------------------------------------------------

В Github создаем в public repository - CurrencyChartSwing-Java-20-Maven
- Генерируем токен:
  - В Github -> Profile -> Developer settings (https://github.com/settings/apps) -> Personal access tokens -> Generate new token
    - Note - Netbeans
    - Expiration - 90 days
    - Выбираем - repo
    - Generate token
    - Копируем код токена
  - Копируем ключ (пример: ghp_****************************)

В Netbeans:
  - -> Team -> Git -> Initialize repository (если еще не создан)
  - -> Team -> Commit
  - -> Team -> Remote -> Push
    - Specify Git Repository Location
        - URL: https://github.com/LiaArtem/CurrencyChartSwing-Java-20-Maven.git
        - User: git
        - Password: ghp_****************************
        - Next
            - master -> master  (Next)
            - master -> origin/master  (Finish)