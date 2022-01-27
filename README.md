
# -Ethio-Pharmacy


  Members Name           ID                  Section
 1. Feven Belay         UGR/3979/12              1
 2. Abraham Shimekt     UGR/0129/12              1
 3. Rut Birhanu         UGR/8243/12              3
 4. Bamlaku Hiruy       UGR/4774/12              3
 5. Hiwot Derese        UGR/2790/12              3


# Requirements to run the source code
1. Use Intellij idea or vs code
2. JDK version 17
3. MYSQL database
4. To access the admin dashboard:
     >first register using the sign up page.
     >then go to mysql database and change the role of the registered user using the following command.
     >select * from user ; and know the id of the user you want to assign ROLE_ADMIN.
     >then update role set name ="ROLE_ADMIN" where id = the id you want.
     >then use the email and password to access the admin dashboard to add products.
     >as a casual user you can login using your user name and password. registered users are by default assigned as ROLE_USER .
5. the application needs the admin to add products. it doesn't authomatically add proudcts.
          
# Title: Ethio-Pharmacy

Description:

Our web app Ethio-Pharmacy is targeted to help Ethiopian's shop Medicines online. As we made a research there is no web app that specifically has functionality to shop medicines online in Ethiopia. Our project is aimed at developing a web application that will over come the difficulties of lack of appropirate digital pharmacy in Ethiopia.It allows pharmacies to use our app to sell their medicines and allow pharmacies to order medicines in discount with delivery services.

Webapp features:

The proposed system or the web app has the following features.

• It has authorization feature that allow different users to manipulate data differently based on their role. The system has two actors. The end user and the admin.

The user has the following authorities: He can Read, add, delete and update orders in his dashboard.

The Admin has following authorities: Read, add, update and delete medicines

• The authentication feature has the following features: The user will be able to sign up, login and log out. The user can also delete and update his account profile.



