create database shopdb;
 create user shopper identified by 'shoppass';
 use shopdb;
 grant all privileges on shopdb to shopper;
 grant all privileges on shopdb.* to shopper;
 localhost:2678/add_product.html