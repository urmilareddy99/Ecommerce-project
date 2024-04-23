# Ecommerce-project
<h2>File Structure of Project</h2>
cpanel: Stores configuration files and settings related to your hosting control panel<br>
softaculous: Related to the Softaculous App Installer, it contains scripts and backups for software installed using Softaculous.<br>
htaccess: A configuration file for use with Apache Web Server. It can control high-level settings of your website.<br>
wp-admin: Contains the files necessary for the WordPress administrative dashboard.<br>
wp-content: This is where themes, plugins, and uploads are stored. Essentially, it's the folder that contains most user-generated and customizable data.<br>
wp-includes: The core WordPress files that are necessary for the CMS to function but generally not modified by the user.<br>
<h4>Hosting and Domain Setup:<br></h4>
Hosting: Dashinfinity hosting provider that supports WordPress is used to host the website.
Domain: Registered a domain name that reflects my brand.
<h4>WordPress Installation:</h4>
Installed WordPress by using softaculous App Installer .
<h4>E-commerce Plugin Installation:</h4>
WooCommerce: The most popular e-commerce plugin for WordPress. I have installed and activate it to add e-commerce functionality.
Alternative Plugins: Rublon plugin is used for multifactor authentication.Stripe is used as a payment gateway.Elementor is used to setup wordpress site.
<h4>Theme Selection:</h4>
Chose a responsive WordPress Astra theme that is compatible with your e-commerce plugin. 
<h4>Core Pages Setup:</h4>
Home Page: Design this page to immediately capture attention and showcase featured products, deals, or categories.
Product Pages: Each product should have its own page with details, images, prices, and an add-to-cart button.
Shopping Cart and Checkout Process:
Ensure the shopping cart is easily accessible on every page and that the checkout process is straightforward, secure, and includes multiple payment options.
<h4>WordPress Setup</h4>
<h3>Theme:</h3>Astra
<h3>List of Plugins Used:</h3>
<ul>
  <li>WooCommerce</li>
  <li>Elementor</li>
  <li>Rublo Authenticator</li>
  <li>Stripe Payment Gateway for Woocoomerce</li>
</ul>
<b>Individual Contribution</b>
<h4>Rublon setup and Integration with wordpress</h4>
In order to use rublon,the person has to setup and create an admin account in <a href="https://admin.rublon.net/auth/login">Rublon</a>
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/0a963f9a-d496-4b51-ad54-f159b6b42af2">
on creating an account,Go to applications and create an application with the below information.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/8ef097c8-3169-4ebf-99fb-e3cc7214283a">
Use the system token and secret key in admin console to integrate with wordpress.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/2093edda-7585-419c-95bb-443c0eecbdb4">
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/6899f47a-4b8e-4b6c-adf4-4ddaf5367ee5">
On saving with above information.Rublon is integrated with wordpress.
<h4>SSL Status</h4>
The website is secured and has SSL certificate installed.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/bf44b04c-ed11-4620-8a68-c92dae7fc2dc">
<h4>Database</h4>
The team has selected to user mysql database.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/47916d65-7913-4c0b-8aef-d0a5274dc1d9">
Click on connect now.The table of my wordpress site are stored in mysql database and use phpMyAdmin to connect to it.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/7cc17545-2b92-48d4-84cc-51f81abd853b">



<h3>Screenshot from the website</h3>
1.  The below screenshot is a home page of the website we have developed.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/ff58c7f0-ec4c-46dd-8cef-daf7564dd523">
2.  The user can register an account by clicking on the account page on the nav bar
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/50dac135-cb5a-4b39-9570-d1c4dfd69b44">
3.  The below screenshot is from the account page on logging in.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/0870abfc-1802-46e2-9264-8c9758bc455d">
4.  When the user is logging in ,it asks you to setup MFA.I have used Rublon Multifactor authentication.My contribution to the project is to setup MFA.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/5a27e3f7-7fab-4847-98e7-82ca9b994361">

5.  The user has to setup MFA by installing Rublon authenticator either from playstore/Appstore and scan the QR code on installing to add the account.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/8974632b-3ed7-4c51-b80f-65a4532fd7fa">
6.  The user need to scan the qr code as second factor authentication for each time the user is logging in.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/64afea74-4076-4fb6-a7da-4120e3472d68">
7.  The user can shop the products by clicking on the shop menu in the navbar page and add it to cart.Finally checkout the product you needed.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/72e4dde5-ebcd-4e63-a2da-68c1d21ddf23">
Add the item to cart
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/62790a22-d8a8-4edc-acd4-bc41ea051a49">
Check out the item and pay using stripe 
<img src="ttps://github.com/urmilareddy99/Ecommerce-project/assets/127900238/86a47466-df59-419b-b0c5-097482556830">
8.  On checking out the item, the item is placed.
<img src="https://github.com/urmilareddy99/Ecommerce-project/assets/127900238/295d8f2e-82bb-4d12-bfef-61c0f3f3451e">







