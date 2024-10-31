# Clothing Shop - Clone<br>
A website created as a clone of an existing brand for fashion accessories and clothing.<br><br>
This website was developed for a client who needed a clone of the existing fashion brand Mona, which is represented in the Balkan. The technologies used are:

* HTML
* CSS
* JavaScript
* PHP
* MySQL (PHPmyAdmin)
* XAMPP

To launch the website, a few steps need to be completed beforehand:

* Download the XAMPP software package that includes a web server.
* Navigate to the folder where XAMPP is installed, go to the htdocs folder, and place the folder with the website files there.
* Start XAMPP and activate the Apache and MySQL modules.
* In phpMyAdmin, create a new database that has been provided in advance.
* Launch the website using localhost and the folder name of the site.

The site allows unregistered users to browse, but ordering is only available if the user is logged in with their account. Each time the page is refreshed, the recommended products change, pulled from the database. In the top left corner, there is a hamburger menu that, when opened, displays product categories. Each product category has its items organized by different types.

The product page is created dynamically, pulling data from the database based on the product name and displaying the description on the same page. If the user is not registered, a login button is shown instead of the order button.

To log in, the user needs to enter their email and password. If the user does not have an account, there is an option to register below the login button. When a user logs in, a PHP session begins, and a new logout button is added to the navigation menu to end the user's session. A logged-in user can view their details by clicking on the profile icon.

Additionally, if a logged-in user adds an item to the cart, a cart session begins, which can be ended if the user deletes all items, logs out, or completes the purchase.

Variables in the code are mostly in the Serbian language, the same as the displayed language.
