# Тестирование веб-приложений
1. Тест-план для веб-приложения "Интернет-магазин": https://docs.google.com/spreadsheets/d/1WodOPX38I1PmjzEdDfud1mN3XC-Zaxa5hpvLwbDk6xo/edit?usp=sharing
2. Чек-лист для тестирования корзины, оплаты и истории заказов: https://docs.google.com/spreadsheets/d/1bgkDxF5Rc-ftBt-xZDEu5gpKzPkGzZVJyUNLPR8k7Bg/edit?usp=sharing
3. Тест-кейсы для корзины, оплаты и истории заказов:
- QASE: https://app.qase.io/project/G7?previewMode=side&suite=122&tab=properties
- Pdf: [G7-2024-05-13.pdf](https://github.com/VikaDov/web/files/15299211/G7-2024-05-13.pdf)
3. Создание простой веб-страницы: ![browser_BWtqIDBap2](https://github.com/VikaDov/web/assets/118528449/727534ff-8dcd-4d9f-b89e-dc43575fd992)
4. Отчеты о дефекте для корзины, оплаты и истории заказов:
- YouTrack (отчеты о дефектах): [БАГ_РЕПОРТЫ_мобильное.xlsx](https://github.com/user-attachments/files/15825485/_._.xlsx)
- QASE (результаты тестового прогона): [G7-Express+run+2024_05_18.pdf](https://github.com/VikaDov/web/files/15366604/G7-Express%2Brun%2B2024_05_18.pdf)
5. Проверка тестовых сценариев в веб-приложении с использованием Charles Proxy:
- Изменение кол-ва товаров в корзине (в запросе 2 товара, а в ответе 500 товаров):
- Сервер возвращает статус-код 403: https://drive.google.com/file/d/1dM2KPw3cNyAjc8CvrOWGrod57_Z8Buov/view?usp=drive_link
- Перенаправление запроса с https://demoshopping.ru на https://qa.demoshopping.ru: https://drive.google.com/file/d/1lijB5DmsuaocM77r3lK6YmXvsyjkbG-z/view?usp=drive_link
