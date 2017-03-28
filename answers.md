1)SELECT count(*) FROM "users";
50

2)select title price from items order by price desc limit 5

Small Wooden Table
Small Wooden Computer
Small Steel Car
Small Plastic Pants
Small Plastic Computer

3)select title, category, price from items where category like '%books' order by price limit 1
'Ergonomic Granite Chair', price - 1496, books

4)select users.first_name, users.last_name, addresses.street from users, addresses where users_id = addresses.users_id, street = '6439 Zetta Hills', city = 'Willmouth' , state = 'WY'
'Corrine','Little'

5)update addresses set city = 'New York', state = 'NY', zip = '10108' WHERE user_id = 39
her address was updated.

6)select sum(price) from items where category = 'Tools'
7383

7)select sum(quantity) from orders
 2125

8)select sum(price * quantity) from orders, items where category = 'Books' and items.id = orders.item_id;
420566

9)insert into users(id,first_name,last_name,email) values ('51', 'Justin', 'Valentin', 'Justin valentine88@gmail.com')
INSERT INTO orders(id,user_id,item_id,quantity,created_at) values ('388','51','92','3','2017-03-28 20:40:21.307789');
-------------------------------------------------------------------------------------------------------------------------
