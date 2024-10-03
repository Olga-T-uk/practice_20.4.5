import json

with open("orders_july_2023.json", "r") as file:
    orders = json.load(file)

max_price = 0
max_order = ''

for order_num, order_data in orders.items():
    price = order_data['price']
    if price > max_price:
        max_order = order_num
        max_price = price

print(f'Самый дорогой заказ: {max_order}, стоимость: {max_price}')

# 2. Поиск заказа с наибольшим количеством товаров
max_quantity = 0
max_quantity_order = ''

for order_num, order_data in orders.items():
    quantity = order_data['quantity']
    if quantity > max_quantity:
        max_quantity_order = order_num
        max_quantity = quantity

print(f'Заказ с наибольшим количеством товаров: {max_quantity_order}, количество товаров: {max_quantity}')

# 3. Поиск дня с наибольшим количеством заказов
orders_per_day = {}

for order_data in orders.values():
    date = order_data['date']
    if date not in orders_per_day:
        orders_per_day[date] = 0
    orders_per_day[date] += 1

max_orders_day = max(orders_per_day, key=orders_per_day.get)
print(f'День с наибольшим количеством заказов: {max_orders_day}')

# 4. Поиск пользователя с наибольшим количеством заказов
orders_per_user = {}

for order_data in orders.values():
    user_id = order_data['user_id']
    if user_id not in orders_per_user:
        orders_per_user[user_id] = 0
    orders_per_user[user_id] += 1

max_orders_user = max(orders_per_user, key=orders_per_user.get)
print(f'Пользователь с наибольшим количеством заказов: {max_orders_user}')

# 5. Пользователь с самой большой суммарной стоимостью заказов
total_spent_per_user = {}

for order_data in orders.values():
    user_id = order_data['user_id']
    price = order_data['price']
    if user_id not in total_spent_per_user:
        total_spent_per_user[user_id] = 0
    total_spent_per_user[user_id] += price

max_spent_user = max(total_spent_per_user, key=total_spent_per_user.get)
print(f'Пользователь с самой большой суммарной стоимостью заказов: {max_spent_user}, сумма: {total_spent_per_user[max_spent_user]}')

# 6. Средняя стоимость заказа
total_price = sum(order_data['price'] for order_data in orders.values())
average_price = total_price / len(orders)
print(f'Средняя стоимость заказа: {average_price:.2f}')

# 7. Средняя стоимость товаров
total_quantity = sum(order_data['quantity'] for order_data in orders.values())
average_price_per_item = total_price / total_quantity
print(f'Средняя стоимость товаров: {average_price_per_item:.2f}')
