# Computer-Store-Backend-using-NodeJs
Rest API CRUD and settings sequelize using Node Js &amp; Postman


Project Computer Store
=======================

<ul>
  <li>Settings sequelize for database.</li>
  <li>CRUD Admin.</li>
  <li>CRUD Customer.</li>
  <li>CRUD Product.</li>
  <li>AUTH (Authentication dan Authorization).</li>
  <li>Transaction.</li>
</ul>

<br>

Command Sequelize Computer Store :

- Tabel “product” :
sequelize model:create --name product --attributes
name:string,price:double,stock:double,image:string
- Tabel “admin” :
sequelize model:create --name admin--attributes
name:string,username:string,password:string
- Tabel “customer” :
sequelize model:create --name customer --attributes
name:string,phone:string,address:string,image:string,username:string,pas
sword:string
- Tabel “transaksi” :
sequelize model:create --name transaksi --attributes
customer_id:integer,waktu:date
- Tabel “detail_transaksi” :
sequelize model:create --name detail_transaksi --attributes
transaksi_id:integer,product_id:integer,price:double,qty:double

<strong>Output Relation Database in PHPMyAdmin :</strong>

![database komp](https://user-images.githubusercontent.com/65702027/156685753-a2210a64-ee7c-4f6f-971b-274f1d9b0327.PNG)
