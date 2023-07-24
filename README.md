# SQLLessons7
1. City tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

SELECT city,country FROM City
INNER JOIN Country ON City.country_id = Country.id;

2. Customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

SELECT payment.payment_id,customer.first_name,customer.last_name FROM payment
INNER JOIN customer ON customer.customer_id = payment.customer_id;


3. Customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

SELECT rental.rental_id,customer.first_name,customer.last_name FROM rental
INNER JOIN customer ON customer.customer_id = rental.customer_id;

