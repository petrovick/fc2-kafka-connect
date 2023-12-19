### Entrnaodn o container


```
docker ps | grep 4connect-mysql

docker exec -it b119b7f449cb bash

mysql -u root -p
>root


create table categories (id int auto_increment primary key, name varchar(255));
insert into categories (name) values ('Eletronicos');

```