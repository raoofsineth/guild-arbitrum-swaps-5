# guild-arbitrum-swaps

Скрипт покупает все монеты, которые нужно купить в guild arbitrum чтобы получить роль. Каждый контракт вызывается отдельно, здесь вас не спалить. Количество монет покупается минимально необходимое для выполнения задания (получение роли). Суммарно с комиссиями выходит ~ 1$ в ETH. Поставил time out в 3 секунды между транзакциями, иначе вылетает. На 1 аккаунт выходит около 40-50с.

1. Регистрируемся на https://arbiscan.io/login и создаем api key : https://arbiscan.io/myapikey
2. Копируем свой api key и вставляем в переменную API_KEY в файле main.py
3. Вставляем в файл private_keys.txt свои ptivate key от кошельков. Кол-во >= 1. Каждый приватник с новой строки.
