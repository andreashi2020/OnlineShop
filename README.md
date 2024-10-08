# OnlineShop: a Spring and Hibernate based online shopping system where user can review items and place orders. 

## This application provides two features:
1.	Users can login and different users may have different roles, some are registered buyers some are administrators. I implemented specific access-control on each role.
I developed a security workflow through in-memory and JDBC authentication provided by Spring Security. Administrator was authorized with a high-level authority using Spring authorization, for example, administrators have the authority to add new product into the item pool. 
2.	User should be able to place his order. So, I created a Spring Web Flow to support the ordering procedure.
The main architecture of this application is based on Spring MVC.

## Hibernate was utilized to communicate with the backend database, providing better support for data storage and access. 

