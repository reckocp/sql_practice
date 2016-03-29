1.  50
        <!-- SELECT COUNT (*) FROM books; -->
2.  25|Small Cotton Gloves|Automotive, Shoes & Beauty|Multi-layered modular service-desk|9984
    83|Small Wooden Computer|Health|Re-engineered fault-tolerant adapter|9859
    100|Awesome Granite Pants|Toys & Books|Upgradable 24/7 access|9790
    40|Sleek Wooden Hat|Music & Baby|Quality-focused heuristic info-mediaries|9390
    60|Ergonomic Steel Car|Books & Outdoors|Enterprise-wide secondary firmware|9341
        <!-- sqlite> SELECT *
       ...> FROM items
       ...> ORDER BY price DESC
       ...> LIMIT 5; -->
3.  76|Ergonomic Granite Chair|Books|De-engineered bi-directional portal|1496
        <!-- sqlite> SELECT * from items
        ...> WHERE category LIKE '%books%'; -->
4.  40|Corrine|Little|rubie_kovacek@grimes.net
    Other address: 44|40|54369 Wolff Forges|Lake Bryon|CA|31587
        <!-- sqlite> SELECT * from addresses
        ...> WHERE street LIKE '%ZETTA%'; -->

        <!-- sqlite> SELECT * FROM users
        ...> where id=40; -->

        <!-- sqlite> SELECT * FROM addresses
        ...> where user_id=40; -->
5. 39|Virginie|Mitchell|daisy.crist@altenwerthmonahan.biz
      <!-- sqlite> SELECT * from USERS
      ...> WHERE first_name LIKE '%virginie%';

      sqlite> SELECT * FROM addresses
      ...> WHERE user_id = 39;

      sqlite> UPDATE addresses
      ...> SET city = "New York", zip = "10108"
      ...> WHERE street = "12263 Jake Crossing"; -->
6. 46,477
      <!-- sqlite> SELECT SUM(price) FROM items
      ...> WHERE category LIKE "%tools%"; -->
7. 2125
      <!-- sqlite> SELECT SUM(quantity) FROM orders; -->
8. 420566
      <!-- sqlite> SELECT SUM(price*quantity) FROM orders
      JOIN items
      On orders.item_id = items.id
      WHERE category = "Books"; -->
9.
  <!-- sqlite> INSERT INTO users (first_name, last_name, email)
  ...> VALUES ("Colin","Recko","reckocp@gmail.com");

  sqlite> INSERT INTO orders (user_id,item_id,quantity,created_at)
  ...> VALUES (51,72,4,2016-03-28);
Oops. Made a mistake I had to fix.
  sqlite> UPDATE orders
  ...> SET created_at = CURRENT_TIMESTAMP
  ...> WHERE created_at = 1985; -->
