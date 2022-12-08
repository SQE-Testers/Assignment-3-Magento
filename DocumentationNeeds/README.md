# User Manual

User manual of magento consists of a number of categories which further divide into sub-categories in the navigation .The categories include getting started , catalog , marketing , content , customers , sales , operations and configuration reference. It also includes search functionality in the user manual.They are total 8 categories in the navigation bar which further divides into subcategories.For example in category of marketing it further divides into marketing menu , channels , shopping tools , promotions , merchandising , communication , live search , seo search etc.Moreover, User manual of magento also provide search functionality . If you want to search for a specific user guide you can use the search bar. It has a separate section for key features which consist of a total nine key features. These key features are new to adobe commerce, what's new in the guide ,set up your store , build your catalog , design and publish , market and promote , sell and deliver , manage your store and  share your knowledge. Furthermore , when you click on any of the key features it opens a new page which consists of a variety of content related to key features.

https://docs.magento.com/user-guide/




# Installation document


Installation documents have navigation bars which have a logo on their top left corner and they have categories on the right side of the navigation bar.  These categories include 
- cloud , setup , development ,testing ,functional area and tutorials.Furthermore , these categories on navigation bar further divide into sub-categories. 
- For example, Testing categories have subcategories such as application testing guide ,functional acceptance testing , integration testing , javascript unit testing , php unit testing and web api functional testing.
 
https://devdocs.magento.com/guides/v2.4/install-gde/prereq/prereq-overview.html

Installation documents also include a sidebar on the left side which consist of key features of installation such as  installation flow ,system requirements , prerequisites which is further divided into apache , nginx , MYSQL  and PHP. Then we have Quick start install , contributor install which is further divide into clone the repository , changed to a released version and update installation dependencies. Then we have advanced install , post installation which is further divide into 
- Verify the installation
- Configure the application
- Optionally set a umask
- Install optional sample data
 
Then we have tutorials on how to set up all of these things.They also have search functionality in the installation guide.
Installation flow : 
First setup your server environment.Install the prerequisite software, including PHP, Apache, MySQL, and the search engine
Get authentication keys to the Magento Composer repository.
Get the Magento software.
Install the Magento software using the command line.
If the step fails because prerequisite software isn’t set up correctly, review our Prerequisites.
Verify the installation by viewing your storefront and the Admin
https://devdocs.magento.com/guides/v2.4/install-gde/install-flow-diagram.html
 
### System Requirements
 


The PHP installation instructions include a step for installing these extensions. Such as ext-openssl
ext-pcre
ext-pdo_mysql
ext-simplexml
ext-soap
Additionally Adobe Commerce requires:
Such as 
xt-dom
ext-fileinfo
ext-gd
ext-hash
ext-iconv
ext-intl
Then verify the php opache

https://php.net/manual/en/intro.opcache.php

### PHP settings

We recommend particular PHP configuration settings, such as memory_limit, that can avoid common problems when using Magento


#### PHPUnit
PHPUnit (as a command-line tool) 9.0.0


#### RAM ;
IT REQUIRES 2gb of ram

#### System dependencieis are 
bash
gzip
lsof
mysql
mysqldump
nice
php
sed
tar

#### Its supported browser are microsoft edge , firefox , safari , chrome  etc.

https://devdocs.magento.com/guides/v2.4/install-gde/system-requirements.html


### PRE - REQUISITES

Before you begin
Before you install Magento, you must do all of the following:
Set up one or more hosts that meet the Magento system requirements.
If you are setting up more than one web node with load balancing, set up and test that part of your system before you install Magento.
Make sure you can back up your entire system at various points during the installation so you can roll back in the event of issues.
Enter the following commands as a user with root privileges:
Ubuntu

- apt-get update
 
- apt-get upgrade
 
- CentOS
- yum -y update
 

#### Prerequisite check
To check your system for prerequisites, enter the following commands:
Apache

- CentOS: httpd -v
- Ubuntu: apache2 -v
- Magento supports Apache version 2.4 as the following result indicates:
- Server version: Apache/2.4.0 (Unix)


 
 

# Development Document
 
Magento helps you to manage your e-commerce store as above:

### Enable browsing products
Magento provides a seamless product browsing experience for your visitors. They get options to view various images for each product, check product reviews, zoom images, check the availability of stock, keep items on their wish list, share product links with friends via email or social media channels, etc.
Helps in managing orders
It becomes easy for customers to re-order their previous purchases, receive notifications via email and print invoices when your website is built on Magento. They can also get an RSS (Really Simple Syndication) feed for new orders. RSS is an online file that has details about everything a site has published. Apart from this, the administrators can view complete order histories. Another advantage of using Magento is that it generates personalized offers and discounts depending upon the shopping patterns of your customers.

### Advanced analytics and reporting
Magento provides visitor and user statistics, and sales and order analytics and helps in retargeting a customer easily. It integrates with Google Analytics and Website Optimizer and provides detailed insights into a customer’s needs. The administrator can monitor trends and outline a plan of action with the help of its inbuilt reporting system. Other than this, the reporting feature of Magento provides data on various parameters like total sales, most viewed products, most purchased products, sales return, orders received, etc.
 
### Insights
Things to keep in check while upgrading to Magento 2
Web store owners often worry about serving their customers with personalized and custom solutions. Moreover, it is equally worrisome for e-commerce providers to find out their customers are browsing their products and leaving their cart empty.

### Download
Allows catalog browsing
You can create a tailored and feature-packed website using Magento. Catalog browsing contains various useful features like:
Layered navigation
Product comparison
Reviews and ratings
Recently viewed products
Filter items by product tags
Products for cross-selling and up-selling
### Offers catalog management
Catalog management is very convenient with Magento. You can very easily classify products as per their size, color, design and features. Furthermore, you can:
Batch import and export the catalog
Batch product updates
Tax rates per location
### Customer group and product type
With Magento, you can create store-specific allocations instantly, manage product tags and create alerts for low inventory.
### Manages customer accounts and service
Magento helps you to save unlimited addresses in the Address Book. It allows customers to check and track order status, view order history, and receive order updates via email.
More than 250,000 merchants worldwide use Magento as their e-commerce platform. –Magento.com
### Simplifies payment facility and checkout
Magento easily integrates with a variety of payment gateways, may it be PayPal, Amazon, Google, etc. For offline payments, you can save credit card methods, accept purchase orders and customer store credits, etc.
Magento improves the checkout process and increases business conversion. It gives multiple payment methods and provides single-page checkout to customers. It also provides SSL security for front-end and back-end orders. Magento allows visitors to save items in shopping carts, gift-receiving messages for every item in an order and delivery schedules.
### Provides shipping services
Building an e-commerce platform on Magento enables you to display real-time career rates. It integrates easily with shipment providers like UPS, FedEx, etc. Customers can ship numerous shipments to different addresses in a single order and get reasonable shipping rates.
### Search engine optimization
Search engine optimization plays an imperative role in attracting customers to your e-commerce store. Magento provides SEO-friendly URLs. For controlling meta-tags on product landing pages, you can use the Magento Rewrite tool. It auto-generates the most used search terms page and site map.
### Provides international support
E-commerce takes your business to the global market. Magento supports multiple languages and currencies. Moreover, the availability of a product can be customized depending upon the demands of buyers of a specific location.
### Increases marketing activities
Websites built on Magento offer bundled products and different pricing as per the quantity selected. It provides tools to run campaigns, shows compared products and online surveys for marketing products on your website. This increases website visitors and leads to greater revenue generation.
### Enables shopping experiences through social media
Shopping via social media is in trend these days. Social media integration is imperative with your online store to increase outreach and sales. Magento enables you to include buttons on your website for all the social media portals that you have your presence on. Customers can click these buttons and visit your Magento store to buy your products.
They can also share your product links with friends and family via these social media portals. Interestingly, your customers can checkout through your e-commerce portal since Magento uses a Beetailer integration to integrate with social media websites.
 
https://www.zuantechnologies.com/blog/benefits-of-magento-development-for-new-ecommerce-business/
 

 # Tutorial

Magento is an open source E-commerce software, created by Varien Inc., which is useful for online business. It has a flexible modular architecture and is scalable with many control options that is helpful for users. Magento uses E-commerce platform which offers organizations ultimate E-commerce solutions and extensive support network. This tutorial will teach you the basics of Magento using which you can create websites with ease. The tutorial is divided into various sections and each of these sections contain related topics with screenshots explaining the Magento admin screens.

