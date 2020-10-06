# Ex.1

- Utilisation de la base de donnée : https://sp.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip
- Modele visuel de cette base de donnée sur: https://www.postgresqltutorial.com/postgresql-sample-database/

# Ex.2

Ecrivez une requête SQL qui affiche tous les titres et descriptions des films dont la description contient le mot Amazing.

- Input

```sql
dvdrental=> SELECT title, description FROM film WHERE description LIKE '%Amazing%';
```

# Ex.3

Ecrivez une requête SQL qui récupère tous les paiements supérieurs à 10. Il faudra récupérer l'id, le prénom, le nom du client ainsi que le montant et la date du paiement.

```
customer_id | first_name |  last_name   | amount |        payment_date
```

- Input

```sql
dvdrental=> SELECT payment.customer_id, customer.first_name, customer.last_name, payment.amount, payment.payment_date FROM payment INNER JOIN customer ON payment.customer_id = customer.customer_id WHERE amount>10;
```

# Ex.3a

Ecrivez une requête SQL qui affiche le chiffre d'affaire gagné par le video club depuis son ouverture.
