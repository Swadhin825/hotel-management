mysql> use Hotel_db;
Database changed
mysql> select * from Hotel_db;
ERROR 1146 (42S02): Table 'Hotel_db.Hotel_db' doesn't exist
mysql> select * from reservation;
ERROR 1146 (42S02): Table 'Hotel_db.reservation' doesn't exist
mysql> show tables;
+--------------------+
| Tables_in_Hotel_db |
+--------------------+
| reservations       |
+--------------------+
1 row in set (0.04 sec)

mysql> select * from reservations;
+----------------+------------+-------------+---------+---------------------+----------------+
| reservation_id | guest_name | contact_no  | room_no | check_in_time       | check_out_time |
+----------------+------------+-------------+---------+---------------------+----------------+
|              1 | swadhin    | meher       |     12 | 2026-01-31 15:07:19 | NULL            |
|              2 | ram        | 525641225   |      45 | 2026-01-31 15:30:20 | NULL           |
+----------------+------------+-------------+---------+---------------------+----------------+
2 rows in set (0.00 sec)
