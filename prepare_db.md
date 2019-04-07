# Preparing the Database

Do the following as root

```sql
 create database shopdatabase;
 create user shopper1 identified by 'shoppassword';
 use shopdatabase;
 grant all privileges on shopdatabase to shopper1;
 grant all privileges on shopdatabase.* to shopper1;