# Patika_SQL_Egitimi_Odev1
1. Soru 1
'select title,description from film'
--Soru 2
select * from film where length >60 and length <75
--soru3
select * from film where rental_rate= 0.99 and  replacement_cost =12.99
-- soru 4
SELECT last_name FROM customer where first_name = 'Mary';
-- Soru 5 
select * from film where not (length  >50) and  NOT(rental_rate = 2.99 or rental_rate = 4.99)
