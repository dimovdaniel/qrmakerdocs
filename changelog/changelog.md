# Changelog

## 4.1.0 - 2024-10-16

### New
* [Items reorder](https://x.com/dimovdaniel/status/1846246169267118374)
* Enable / Disable categories


### Updating
To update from the previous release.
Login as admin. Upload the version_update.zip file in the "Apps".
Then go to "Settings". 
The update will be applied.

### List of updated files
[Updated files](https://gist.github.com/dimovdaniel/a2686a153217626173869df7ffe8f4ec)




## 4.0.0 - 2024-01-02

### New
* Laravel v10
* Link for each product
* Apps in a separate menu
* Table in the QR Maker
  
### Modules
* Custom JS & CSS per vendor - free module


### Updating

To update from the previous release, follow the [standard update procedure](https://mobidonia.gitbook.io/mresto/changelog/updating-shared-hosting).

Before update, make sure to make a backup
This update requires PHP 8.2

After that, log in as admin

## 3.6.0 - 2023-05-29

### Modules
* Tips - free module
* Social profiles - free module
* Stock
* Razorpay subscription
* Glow - new theme

### New
* Allow staff to login in owner app

### Improvements
* Improvements in KDS and POS module


### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 3.6.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them. NOTE: For this update we strongly recommend to backup your database and files.

### List of updated files

[Updated files](https://paste.laravel.io/ee10ec9c-8702-42e4-8ffa-8bd8708c9a38)

## 3.5.0 - 2023-01-21

### New
* Order ID per vendor

### Improvements
* Vat calculation
* Pages slug
* Coupons
* Timezone

### Modules
SaaS Dashboard - SaaS related dashboard

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 3.5.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them. NOTE: For this update we strongly recommend to backup your database and files.

### List of updated files

[Updated files](https://paste.laravel.io/b947fc4c-0af1-41e7-a4f2-dcc947496cfe)

## 3.4.x - Continues updates

* 3.4.1 Clone on item level - activated - change in resources/views/items/edit.blade.php and config/config.php

 
## 3.4.0 - 2022-11-12

### Video

{% embed url="https://youtu.be/mgJ-l95nAaI" %}

### New

* Login / Register clients (via the new module)
* Export clients (via the new module)
* Export companies/restaurants
* Better client details in order details (via the new module)
* Make order of value is 0
* Delete client account with remove of personal data
* Admin menu reorganization

### Bugs

* Bug: timezone in live orders

### Modules

* Client Login / Register module
* Clone module - clone single item
* Custom domain - multiple domain domain1,domain2
  
### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 3.4.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them. NOTE: For this update we strongly recommend to backup your database and files.

### List of updated files

[Updated files](https://paste.laravel.io/0bbe4bc1-ef8b-48c5-bb7f-c28272eb80b1)


## 3.3.x - Continues updates

* 3.3.1 Small improvements [Changes](https://share.cleanshot.com/EzvOZR) [Files](https://paste.laravel.io/6dfcd9f1-9daf-4682-87f0-ba4ace82e7a6)


## 3.3.0 - 2022-08-05

### Video

{% embed url="https://youtu.be/wgnqKEyjkPE" %}

### New

* Item Search
* Cart counter
* Restaurant Search in Admin
* KDS compatible and KDS API
* On Address change, change location of vendor
* Community plugins
* Custom Domain on multiple domains
* API: Deactivate Account- APP
* My orders button on success page
* Login as from vendor details
* Pusher event on order update

### Bugs

* Bug:When no orders, can't change filters
* Bug:Return only staff users in Staff List
* Bug:Options with special character or arabic
* Bug:Items import redirect to index page, and more robust import
* Bug:Saving Simple Delivery area without phone
* Bug:Stripe subscribe issues
* Bug:Landing page can't be disabled - error in saving .env
* Bug:Problematic image removed from pwa

### Modules

* [Kitchen Display System](https://www.loom.com/share/4a8460875c2c4d1aa0227ea94009de91)

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 3.3.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them. NOTE: For this update we strongly recommend to backup your database and files.

### List of updated files

[Updated files](https://paste.laravel.io/7dce0e61-8c18-4752-b906-3fbe7c5248c6)

## 3.2.x - Continues updates

* 3.2.2 Multiple fixes [INFO](https://share.cleanshot.com/rjhERB) [Files](https://gist.github.com/dimovdaniel/cdb1c3c252d1e06788a4f8716cb238ff)
* 3.2.1 Fix problem sending to Whatsapp [Files](https://paste.laravel.io/ce079a93-20c7-4ca1-8016-a3caf4477ada)



## 3.2.0 - 2022-03-20

### Video

{% embed url="https://youtu.be/tJTldQBxW4o" %}

### New

* Verify install and setup is ok
* Specific CSS / JS for the menu page
* Modules per pricing plan
* Better LoginAS
* Disable DineIn
* Different whatsapp phone per delivery area
* Discount price - offer price on each item
* Change  /restaurants - URL Route in admin
* Expo Push notifications

### Modules

* Drivers per vendor    
* Manager Module
* Tiny PNG - AWS S3 - Google Cloud
* MailChimp add users on new vendor
* Allow orders after working time of the store
* Theme Switcher per vendor
* Links in side menu of the vendor

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 3.2.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them. NOTE: For this update we strongly recommend to backup your database and files.

### List of updated files

[Updated files](https://paste.laravel.io/4062a600-893b-45ba-9334-c2bac45c2df2)

## 3.1.x - Continues updates

* 3.1.3 Register problem with recaptcha enabled fix [Files](https://paste.laravel.io/2c4cd9a8-4187-4193-921a-6fed48727193)
* 3.1.2 Register Vendor in admin and Vendor Finances fix in 3.1.0 [Files](https://paste.laravel.io/6a1da2e8-9ee8-4022-97af-c05010ea77b9)
* 3.1.1 Flags and  Finances fixes in 3.1.0 [Files](https://paste.laravel.io/a58c2b81-a9af-44e5-b092-56df0294d0b6)
  
## 3.1.0 - 2022-01-16

### Video

{% embed url="https://youtu.be/OxyhrtVz3ME" %}

### New

* Phone number input
* Improved apps page
* Staff can see live orders.
* Filter by order status and payment

### Fixes

* Stripe subscribe cancel button
* Phone in QR delivery is not displayed.
* Other small bug fixes

### Modules

* Detrack module

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 3.1.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them. NOTE: For this update we strongly recommend to backup your database and files.

### List of updated files

[Updated files](https://paste.laravel.io/400952df-62f9-40b2-8380-0d6f8bb0b070)



## 3.0.x - Continues updates

* 3.0.6 - 3.0.3, 3.0.4, 3.0.5 + Language switch fix [Files](https://paste.laravel.io/0e424692-add2-4822-bc1f-52559fbbdbbf)
* 3.0.5 - POS fixes [Files](https://paste.laravel.io/06b893a6-ebee-41cd-b586-a30b8d46d0db)
* 3.0.4 - 3.0.3+ Small fixes. Error was made in the zipping of the update in 3.0.3 [Files](https://paste.laravel.io/8563ed64-4b02-4629-87ae-65a0480c145a)
* 3.0.3 - Remove apps,Disable Continues order per vendor, Logo custom css - file changed is config/config.php
* 3.0.2 - Disable ordering on vendor level, Default theme select, Bug fix on logo save, No working hours[Files](https://paste.laravel.io/61619615-1d64-47f4-9e13-e7d18a3e89a2)
* 3.0.1 - Coupons Fix, Order change QTY fix, Coupons Deduction fix - [Files](https://paste.laravel.io/1cca9e36-bf76-4f62-860f-9b40db662861)

## 3.0.0 - 2021-11-08

### Video

{% embed url="https://youtu.be/tvwLPyzpqP4" caption="" %}

### New

* QR Per table ( not  mentioned in the video )
* New apps organization
* Modify Qty on each item in order
* Force users to paid plans
* Disable pickup/delivery.
* Compatible with new modules and easier to make design changes on menu

### Fixes

* Lot of small bug fixes

### Modules

* [Custom Domain](https://mobidonia.gumroad.com/l/COWDi)
* [Elegant template](https://mobidonia.gumroad.com/l/JZhPWc)
* [Allergens](https://mobidonia.gumroad.com/l/oEPpzI)
* [Delivery plugin](https://mobidonia.gumroad.com/l/delqr)
* [Coupons](https://mobidonia.gumroad.com/l/djizl)
* [Featured vendors](https://mobidonia.gumroad.com/l/RuaBRD)
* [Prepare Time](https://mobidonia.gumroad.com/l/kyFdp)
* [Default tax](https://mobidonia.gumroad.com/l/defaulttax)
* [Language Pack](https://mobidonia.gumroad.com/l/languepack)


### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 3.0.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them.
NOTE: For this update we strongly recommend to backup your database and files. 

### List of updated files
[Updated files](https://paste.laravel.io/a4bed46b-b8cc-49bd-be87-61ba88a29e41)

## 2.7.x - Continues updates

* 2.7.6 - Stripe Vendor defined fix -  [Files](https://paste.laravel.io/3eb30e62-be6c-4fbf-afb5-25a3ebf54498)
* 2.7.5 - Small security update [Information](https://www.reddit.com/r/mobidoniacc/comments/qdrf13/275_security_update/) [Updated files](https://paste.laravel.io/d8fbbf22-e8a8-4504-8c64-a58fd21fe9a1)
* 2.7.4 - Admin fixes [Files](https://paste.laravel.io/d10fffcd-102e-4a1a-be41-54f15ec8035b)
* 2.7.3 - Pricing plan bug - was showing vendor currency, compatible with [Lion POS](https://codecanyon.net/item/lion-pos-saas-cloud-point-of-sale-script/33733665) - [Updated Files](https://paste.laravel.io/6ec88159-ad36-4ae8-8535-eb43a8372a7d)
* 2.7.2 - Fixes in Missing Variants, Local Files for later usage [Files](https://paste.laravel.io/9a8eab2c-cce4-4d90-a3f0-2ad4e4f5bf70)

## 2.7.0 - 2021-09-04

### New

* RTL Support
* Missing variants created by system

### Improvements

* Categories delete fix
* Date in local format
* Validation on plan create
* Subdomain value will be changed only in Vendor is newer than 1 day

### Fixes

* Bern timezone missing

### Modules

* [Expenses](https://mobidonia.gumroad.com/?sort=page_layout#NwxgX)
* [All-Access Pass](https://mobidonia.gumroad.com/?sort=page_layout#PVVGE) \( All plugins free, apps on 50% \)
* [Cloner](https://mobidonia.gumroad.com/?sort=page_layout#pVCjei)

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 2.7.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them. NOTE: For this update we strongly recommend to backup your database and files.

### List of updated files

[Updated files](https://paste.laravel.io/5d1428c2-d525-49d1-9330-f69a0385e40a)

## 2.6.x - Continues updates

* 2.6.5 - Go to store button in owner admin, Better self update, Better apps management, Compatible with the new clone plugin [Files](https://paste.laravel.io/51fd3249-3c6e-4d8c-8e16-24263266725d)
* 2.6.4 - Stripe vendor keys, Modal close button, Edit item category [Files](https://paste.laravel.io/8d1f3a9a-2f10-483d-9b75-89366c2ccbc8)
* 2.6.3 - Option to control char count on item in menu,TermsAndServices check above submit button [Files](https://paste.laravel.io/a9ded193-d04f-4f83-9894-b4a1cf09836f)
* 2.6.2 - Google translate - fixes for module [Files](https://paste.laravel.io/66c2ccf2-ff5e-48b3-b6ca-798f895eaddf)
* 2.6.1 - Show vendor closed in modal, GT don't translate some elements [Files](https://paste.laravel.io/3795a2fa-d1b6-4865-9c40-9f63a7c215c0)

## 2.6.0 - 2021-08-15

### Video

{% embed url="https://youtu.be/c0W9cfGkba4" caption="" %}

### New

* Easy change of all "Restaurants" to something like shop, vendor, company \( now restaurants table is renamed to companies\)

### Fixes

* Added missing string for translate
* Plan set by admin, was overwritten
* Dark / Light logo

### Modules

* [Stripe Link Checkout](https://mobidonia.gumroad.com/l/stripech) \( Stripe Hosted Checkout \)
* [Staff](https://mobidonia.gumroad.com/l/staffmodule) \( allow staff to manage orders\)
* [FlutterWave Module](https://mobidonia.gumroad.com/l/flutterwavepayments) \( accept payment via FlutterWave \)
* [Google Translate Module](https://mobidonia.gumroad.com/l/googletranslate) \( Easily add language translate for any language to the menu \)

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 2.6.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them. NOTE: For this update we strongly recommend to backup your database.

**List of updated files** [Updated files](https://paste.laravel.io/f49cce51-0a1a-458a-9ebc-1ee1165ac1bf)

## 2.5.x - Continues updates

* 2.5.8 - Fix for custom timezone [Files](https://gist.github.com/dimovdaniel/8e651a2a1f9687561b6c0736b1402e4e)
* 2.5.7 - Fix for WhatsApp message, show location tab in restaurant - [Modified Files](https://gist.github.com/dimovdaniel/0804439f2e2452d7a687e5c298985ced)
* 2.5.5 and 2.5.6 - Option to remove shift, error on delete restaurant, Table in whatsapp message [Files](https://gist.github.com/dimovdaniel/4831bc289ac4b02356cbf9294e8d9785)
* 2.5.4 - Validation string for new payment platforms [Files](https://gist.github.com/dimovdaniel/8ccff90ecf9137fd412c6e757994a252)
* 2.5.3 - Fix for language selector in items [Files](https://gist.github.com/dimovdaniel/5275ae0d2a5c9b33d6e6b3ee6210393f)
* 2.5.2 - Change language from admin, Over night fixes, extra ; in some pages  [Files](https://gist.github.com/dimovdaniel/79477130d7c98b03d44f5913762c9f7a)
* 2.5.1  - Hotfix for 2.5.0 [Updated files](https://gist.github.com/dimovdaniel/83e01921ebe704a0a5258387f46b1625)

## 2.5.0 - 2021-06-19

### 2.5.1 - Hotfix for 2.5.0

[Updated files](https://gist.github.com/dimovdaniel/83e01921ebe704a0a5258387f46b1625)

### Video

{% embed url="https://youtu.be/J\_mBypwyBl4" caption="" %}

### New

* Logo for restaurants in the header area

### Improvements

* Better SEO
* Items import
* Limit number of orders in plan

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 2.5.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them.

**List of updated files**

[File list](https://gist.github.com/dimovdaniel/fb8786456f106660b85ccbe3e58744af)

## 2.4.x - Continues updates

* 2.4.3 - Subscription fixes, Landing fixes, Import fixes  [Files](https://i.imgur.com/nmxO4ik.png)
* 2.4.2 - Local Bank fixes, decimal orders prevent, better whatsapp message [Files](https://gist.github.com/dimovdaniel/cb945997092427699ee7a811e265e61e)
* 2.4.1 - Local Bank fixes, Saving Stripe Fixes, Working Hours Fixes - [Files](https://gist.github.com/dimovdaniel/c0791ee6280805b30e1acd8eafddbb93)

## 2.4.0 - 2021-04-16

### Video

{% embed url="https://youtu.be/fkZZHYLLems" caption="" %}

### New

* Payment modules as Plug And Play
* Each payment method can be set so money from orders goes to vendor
* Restaurant management reorganization
* New Printing module
* vendors can set their own time slots intervals, prepare time and timezone

### Fixes

* Tax calculation fixes
* Lot of small fixes

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 2.4.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them.

If you have lot of users / clients and you are using other payment method for orders than Stripe, I will recommend full project backup, database and files. Afterwords you will need to download the desired payment method, and set up the way you like it. Please look into the update video to see what has been changed in the payment methods. Restaurants will need to reset the api keys for Mollie or PayPal if they where accepting direct payments.

**List of updated files**

[File list](https://gist.github.com/dimovdaniel/71f85505b15f776f1cd2e2e5b173d2a7)

## 2.3.x Continues updates

* 2.3.2 - Support for the impressum app. [Files](https://gist.github.com/dimovdaniel/45b4b2476896e2920550ef58c33bacab)
* 2.3.1 - Fix for restaurant orders \(array\_key\_exists\(\)\) - File changed: app/Order.php

## 2.3.0 - 2021-03-17

### New

* Apps \( instal new modules via upload \)
* Free app - invoice pdf printer 
* Owner API - API endpoint for owner actions

### Fixes

* Fixes for Financial reports
* Fixes for testimonials and 
* Other small fixes

### How to update

Just log in as admin, go to "Updates" and you should see new "New Update 2.3.0" button. Click on the button to update. Note that this is a bigger update. Please check the List of files to confirm it will not overwrite some of your changes if you have them.

**List of updated files**

[File list](https://gist.github.com/dimovdaniel/c1eaaacc8f36fa71ef44a4cbbdc26087)

## 2.1.x - 2.2.x - Continues updates

* 2.2.3 - Fix for handling restaurant-name like aliases -[Files](https://gist.github.com/dimovdaniel/6ebd98a48eba52906fb536dfd80d45e5)
* 2.2.2 - Fixes in calculating tax, Fixes in  financial report, add new item image missing - [Files](https://gist.github.com/dimovdaniel/a63e2dbabde132691d892430199a06f9)
* 2.2.1 - Custom Fields on orders, Social Links, Restaurant address improvements - [Files](https://gist.github.com/dimovdaniel/4e5e670a13bbcb52e1d1143f34752c44)
* 2.2.0 - Categories sorting, Fix for Stripe 3d secure or plan subscribe - [Files](https://gist.github.com/dimovdaniel/4e168f71933b3249a4e853e5f6995b21)
* 2.1.9 - Temporary update 
* 2.1.8 - Temporary update 
* 2.1.7 - Fix for restaurant save, Memory Limit info, Migrate in update - [Modified Files](https://gist.github.com/dimovdaniel/fcf3703ec281b69265869ad9b9953742)
* 2.1.6 - Fixes on variant show - [Modified Files](https://gist.github.com/dimovdaniel/90d555271a5db0c6f2cf7980e69befab)
* 2.1.5 - New way of updates, fixes in image upload in settings  - [Modified Files](https://gist.github.com/dimovdaniel/786c82b2776eda1d47a97a5ec9c970c4) -- \(YOU WILL GET ERROR 500 - but that is ok, since now we have new system for update \)
* 2.1.4 - WhatsApp Message is separate blade file - [Modified Files](https://gist.github.com/dimovdaniel/7a3fad29bf15241fe310fdecd8e0da68)
* 2.1.3 - Fixes in Stripe connect - [Modified Files](https://gist.github.com/dimovdaniel/644f827344deed01443309429f56a542)
* 2.1.2 - Missing Translations, Live Order fix, CSS fixes, Fix on deleting demo data -   [Modified files](https://gist.github.com/dimovdaniel/165ae8c25bbf1fce08cb5a2243127fef)

## 2.1.1  - 2021-02-10

### New

* WhatsApp Ordering

### Fixes

* Stripe 3D Secure
* HasDineIn Problem - when there is only dine in.

### Improvements

* Full list of currencies
* Better error 500 show
* Show/Hide Cookie Consent

### How to update

Just log in as admin, go to "Site Settings" and on right top you should new "New Update 2.1.1". Click on the button to update.

**List of updated files** [File list](https://gist.github.com/dimovdaniel/497727c35598c29d644b0a95c8d974de)

## 2.0.x  - Continues updates

* 2.0.7 - JS Notify Fixes, Don't show empty categories, Phone min.
* 2.0.6 - Translate plugin fix for PHP 8
* 2.0.5 - Fixes for orders - no action displayed
* 2.0.4 - Stripe Subscribe fixes
* 2.0.3 - Pusher fixes
* 2.0.2 - Site map generation and Stripe Connect fixes
* 2.0.1 - Fixes for Dine in option and small bug fixes

## 2.0.0 - 2021-01-15

This is a major update and is not available via 1 Click update. You will need to follow the guide for updating. **Note** that now, you need to change php version to 7.4 or 8.0.

{% embed url="https://youtu.be/FeN7\_c8k2kY" caption="" %}

### New

* Update to latest Laravel 8
* Redefined Ordering process
* Multilingual menus
* Option restaurants to change currency
* New install and 1 click update process
* Bug Fixes
* Easy way to add new payment methods

### Updating

To update from the previous release, follow the [standard update procedure](https://mobidonia.gitbook.io/mresto/changelog/updating-shared-hosting).

After that, log in as admin

## 1.9.7 - 2020-12-17

This is a combined update from 1.8.0 to 1.9.7

### Fixes

* Variant selection bug fix
* Call waiter pop-up select not showing fixed
* Plus button in the cart was not showing on mobile
* Updated menus privileges on the front end
* Delete user when an admin deletes restaurant
* Duplicate email send 
* Admin order accepting 
* Checkbox when placing an order to accept T&S
* Sound on pusher notification
* Category delete when there are no items
* Thank you page after successful payment
* Fixes for Paystack

### How to update \( [Video](https://www.loom.com/share/bd05fb6bdceb46b3942bcf3b8e9f5e34) \)

Just log in as admin, and you should see "New Update 1.9.X. Click on the button.

## 1.8.0 - 2020-12-05

### **New**

* Call Waiter button
* PayPal subscriptions
* PayPal payments
* PayStack subscriptions
* Mollie payments
* XML Sitemaps
* Close account and get all data in json
* Easy Share on web and QR

### **Improvements**

* Dark / Light logo
* Better ordering flow
* The correct menu is shown based on settings
* The phone number on takeaway order
* Password field was prepopulated
* Better settings screen
* EPS, PSD, JPEG, SKETCH files for the templates \( only from download from CodeCanyon \)

### **Fixes**

* Saving env adds new lines
* Language link doesn't work
* PayStack fixed
* Language selector on landing not showing selected language
* Deleting customer log entry results in an error
* 2 Emails where send to the restaurant on register

### How to update \( [Video](https://www.loom.com/share/bd05fb6bdceb46b3942bcf3b8e9f5e34) \)

Just log in as admin, and you should see "New Update 1.8.0. Click on the button.

## 1.7.9 - 2020-11-12

### Improvements

* Inline editing on the front page
* Customer can see orders they have made
* Remove Project branding from the restaurant menu page
* Options to disable Guest log
* Option to edit categories name in the menu
* Delete demo data button added
* Optin to completely delete restaurant
* Bugfix: When selecting variants, $ is US$
* Bugfix: Wildcard domain QR make
* Option to change required characters in a phone number

### How to update \( [Video](https://www.loom.com/share/bd05fb6bdceb46b3942bcf3b8e9f5e34) \)

Just log in as admin, and you should see "New Update 1.7.9. Click on the button.

## 1.7.8 - 2020-11-08

### Improvements

* Dine-in / Takeaway when making an order
* Option to not offer a free plan \( set FREE\_PLAN\_ID to 0 \)
* Images for a menu item, are no longer required
* Fixes on working with the variants
* Fixes on registering customer visit by the customer
* Deactivated restaurant, no longer accessible

### How to update \( [Video](https://www.loom.com/share/bd05fb6bdceb46b3942bcf3b8e9f5e34) \)

Just log in as admin, and you should see "New Update 1.7.8. Click on the button.

## 1.7.7 - 2020-11-01

This is a combined update from 1.7.3 till 1.7.7

### Improvements

* Change landing page images via settings

### Fixes

* Stripe system status check
* REcaptcha fix
* Plan removing fixes
* Fixes for managing options and variants

### How to update \( [Video](https://www.loom.com/share/bd05fb6bdceb46b3942bcf3b8e9f5e34) \)

Just log in as admin, and you should see "New Update 1.7.X. Click on the button.

## 1.7.3 - 2020-10-28

{% embed url="https://www.loom.com/share/15cc92bffca0416da783972f55bbce79" caption="" %}

This is a combined update from 1.5.8 till 1.7.3

### Improvements

* Tables and area management
* Local order \( Continuous orders and online card payments \)
* Orders \| Report and live orders
* Customer log
* Subscribe via stripe
* Manually assign restaurant to pricing plan

{% hint style="info" %}
This update introduces Stripe as default way for accepting subscriptions. To enable it, you need to register stripe account, and create product in it. When you create the pricing plans, you will need to enter Stripe pricing\_id for each plan.

New variables in .env

ENABLE\_STRIPE\_CONNECT=true  
ENABLE\_FINANCES\_OWNER=true  
ENABLE\_FINANCES\_ADMIN=true  
ENABLE\_STRIPE=true  
STRIPE\_KEY='pk\_test\_XXXXXXXXXXXXXX'  
STRIPE\_SECRET='sk\_test\_XXXXXXXXXXXXXXX',  
SUBSCRIPTION\_PROCESSOR=Stripe  
QRSAAS\_DISABLE\_ODERING=false
{% endhint %}

### How to update \( [Video](https://www.loom.com/share/bd05fb6bdceb46b3942bcf3b8e9f5e34) \)

Just log in as admin, and you should see "New Update 1.7.3. Click on the button.

## 1.5.8 - 2020-10-17

This is a combined update from 1.5.6 \| 1.5.7 and 1.5.8

### Improvements

* Google ReCaptcha added
* Better Favicon generation
* Better frontend language manager
* Limit plan fix
* Better URL route for restaurant edit
* Other small bug fixes

### How to update \( [Video](https://www.loom.com/share/bd05fb6bdceb46b3942bcf3b8e9f5e34) \)

Just log in as admin, and you should see "New Update 1.5.5". Click on the button.

{% hint style="success" %}
This update changes the config for the frontend languages

To modify the list of available language add new .env variable

FRONT\_LANGUAGES=EN,English,FR,French
{% endhint %}

{% hint style="success" %}
In this update we introduced the Google Recaptcha.  
We are using this [plugin](https://laravel-recaptcha-docs.biscolab.com/docs/intro) for Laravel. And we have implemented the invisible recaptcha.

To enable it on the registration form, you have to create your own API keys [here](https://www.google.com/recaptcha/admin).  
reCAPTCHA type:**v2 Invisible**

Then you need to enter thous keys in .env

in your .env file

RECAPTCHA\_SITE\_KEY=YOUR\_API\_SITE\_KEY RECAPTCHA\_SECRET\_KEY=YOUR\_API\_SECRET\_KEY
{% endhint %}

## 1.5.5 - 2020-09-30

### Improvements

* System setup status and better error handling
* Translation management
* Custom CSS and JS for frontend and backed set from the admin
* Landing page into separate files for easier update
* Gravatar image corrections

### How to update \( [Video](https://www.loom.com/share/bd05fb6bdceb46b3942bcf3b8e9f5e34) \)

Just log in as admin, and you should see "New Update 1.5.5". Click on the button.

{% hint style="warning" %}
This update will change your landing page. But your landing.blade.php file is not modified. Landing now uses home.blade.php and uses separate files to show content. We did this for easier future updates.

The content of the landing page is now in resources/views/qrsaas/partials

To show your old landing, just add .env variable  
QR\_LANDING=landing

To modify the list of available language add new .env variable

LANGUAGES={ "EN":"English","FR":"French"}
{% endhint %}

## 1.5.4 - 2020-09-29 \( test update \)

{% hint style="info" %}
This is the first incremental update that can be done via the 1Click Update button.  
If you receive an error like HOME ACTION NOT ALLOWED it is because you are logged in as admin, but the admin ID is not 1. Open config/laraupdater.php and at the bottom modify the variable allow\_users\_id to have the admin ID, or set to false to accept all admins.
{% endhint %}

### **Fixes**

* Paddle vendor id correct setup

## 1.5.3 - 2020-09-29

### Improvements

* One-Click update button 
* Favicon change setup from admin settings
* Removed more unnecessary fields in admin
* Fixes on the  menu on mobile phone
* Spelling mistakes corrected on landing
* Removed 40 00+ Unnecessary developer files
* Plan limit:  now prevent the user to add new items in the menu if the limit is reached

### How to update

Follow the standard update procedure

From this version on, when there is a new update, log in as admin, and you will see a blue card on left, indicating that there is an update you can apply.

{% hint style="warning" %}
This update brings updates on the landing page. if you have modified, you may want to back it before updating.
{% endhint %}

## 1.5.2 - 2020-09-24 \( [Video](https://youtu.be/gZ7WGhdOq5I) \)

### Fixes

* Better documentation 
* Option to add / change the print templates provided
* Option to translate the QR Maker page for restaurants
* Removed unnecessary fields and options for admin
* Categories Filter fixed
* Removed wizard option from the install screen
* Option to disable landing page DISABLE\_LANDING in .env

### How to update

Follow the standard update procedure

Or, here is the list of file modified, so you can change them one by one if you prefer.

{% embed url="https://1drv.ms/u/s!AqVDdjJrM4dRhoV2HokQUTkzOTlIqg" caption="" %}

## 1.5.1 - 2020-09-19

### Initial Version

