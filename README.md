## PBL5 E-commerce website 

# ====== FRONT-END =======

- Responsive Layout
- Shopping Cart, Wishlist, Product Reviews
- Coupons & Discounts
- Product attributes: cost price, promotion price, stock, size...
- Blog: category, tag, content, web page 
- Module/Extension: Shipping, payment, discount, ...
- Upload manager: banner, images,..
- Laravel Socialite implement(Facebook, Google & twitter) & Customer login
- Payment integration(Paypal)

## ======= ADMIN =======

- Admin roles, permission
- Product manager
- Media manager using unisharp laravel file manager
- Banner manager
- Order management
- Category management
- Brand management
- Shipping Management
- Review Management
- Blog, Category & Tag manager
- User Management
- Coupon Management
- System config: email setting, info shop, maintain status,...
- Line Chart & Pie chart ...
- Profile Settings

### Set up :

1. Clone the repo and cd into it
2. In your terminal ```composer install```
3. Rename or copy ```.env.example``` file to ``.env``
4. php artisan key:generate
5. Set your database credentials in your ```.env``` file
6. Set your Braintree credentials in your ```.env``` file if you want to use PayPal
7. Import db file(```database/e-shop.sql```) into your database (```mysql,sql```)
8. ```npm install```
9. ```npm run watch```
10. run command[laravel file manager]:-  ```php artisan storage:link```
11. Edit ```.env``` file :- remove APP_URL
10. ```php artisan serve``` or use virtual host
11. Visit ```localhost:8000``` in your browser
12. Visit /admin if you want to access the admin panel. Admin Email/Password: ```admin@gmail.com```/```1111```. User Email/Password: ```user@gmail.com```/```1111```

### Screenshots :

![Screenshot (79)](https://github.com/duyhau0802/PBL5-Advance-Ecommerce-in-laravel-7-master/assets/114060333/7169f593-331a-419b-a8ba-6943009f4bb6)

![Screenshot (80)](https://github.com/duyhau0802/PBL5-Advance-Ecommerce-in-laravel-7-master/assets/114060333/0974e08d-9919-474c-9b1f-79aedadaa84f)

![Screenshot (81)](https://github.com/duyhau0802/PBL5-Advance-Ecommerce-in-laravel-7-master/assets/114060333/7a5ef2cf-f91f-4b0e-9b7a-0179d1e18b98)

![Screenshot (85)](https://github.com/duyhau0802/PBL5-Advance-Ecommerce-in-laravel-7-master/assets/114060333/0f727227-eb0b-4984-92ab-9fe75f63faf5)

![Screenshot (86)](https://github.com/duyhau0802/PBL5-Advance-Ecommerce-in-laravel-7-master/assets/114060333/51a31cd0-790a-4615-b005-c423a0d84631)

![Screenshot (87)](https://github.com/duyhau0802/PBL5-Advance-Ecommerce-in-laravel-7-master/assets/114060333/8c887ec4-9be3-47a4-b7a0-c21aac6d37f7)

#### Admin page
![Screenshot (82)](https://github.com/duyhau0802/PBL5-Advance-Ecommerce-in-laravel-7-master/assets/114060333/4ef684e2-9987-423e-9006-10f491e0e393)

![Screenshot (83)](https://github.com/duyhau0802/PBL5-Advance-Ecommerce-in-laravel-7-master/assets/114060333/8e262981-4455-4f6d-ba81-2a0fcd24d374)

![Screenshot (84)](https://github.com/duyhau0802/PBL5-Advance-Ecommerce-in-laravel-7-master/assets/114060333/933b7f46-5775-4ff1-9a68-1b6a98a96e34)

### This project using Template Name: Eshop
- Author Name: Naimur Rahman
- Author URI: http://www.wpthemesgrid.com/
- Description: Eshop - eCommerce HTML5 Template.

