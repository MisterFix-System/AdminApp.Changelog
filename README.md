# AdminApp.Changelog

## v.1.0.1
* Add new Menu - Search AC Data (search by Code / Customer Name / Company Name)
* Update Customer Dropdown when creating new order - add phone number
* Implement COMPANY ORDER feature with Payment Option: Full / Credit
* Send Payment Information to Customer after the service has been set to done by Technician if the customer need to submit more payment
* Disable Deposit Feature
* Adjust Technician Commission calculation

-------------------------------------------------------------------------------------------

## v.1.0.0-rc.11
* Split Order Status to spesific menu
* Add counter when order status is Waiting for Worker
* Update Career form - add image and implement to main web
* CRUD Work Gallery and show to main web (AC service page)
* Update Technician Feature: Add Total Income to data table, add button action to submit transfer proof (go to detail -> click Confirm Income Transfer button)
* Update Product Item: Add Is Enable Invoice Reduction form

## v.1.0.0-rc.10
FIX FEEDBACK:
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/17
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/29
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/3
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/26
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/12
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/11
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/8
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/7
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/36
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/31
* https://github.com/MisterFix-System/AdminApp.Changelog/issues/30

UPDATE FEATURE:
* Add ID to product item, customer, company, service package, technician
* Update sidebar label menu
* Add description to Team feature and implement to main web

NEW FEATURE:
* Email service - send email to customer when order information is updated (publish, status changes, payment success)


## v.1.0.0-rc.9
UPDATE FEATURE:
* New Qr Code Design -- https://github.com/MisterFix-System/AdminApp.Changelog/issues/2

BUGFIX
* Fix logic to show AC history

## v.1.0.0-rc.7
NEW FEATURE:
* CRUD AC Brand
* CRUD AC Type
* CRUD Freon Type
* Export to Excel (Customer, Company)
* Show AC Service History
* Admin to Main Web data integration

UPDATE FEATURE:
* Add Logo to Company Group
* Use dropdown data to populate AC data (Brand, Type, Freon) when creating Customer AC data
* Add Service date field to Order feature
* Add Icon field to Service Package


## v.1.0.0-rc.6
NEW FEATURE:
Main Web Content Management :
* CRUD Main web static content, 
* CRUD Contact, 
* CRUD Career, 
* CRUD MisterFix Team, 
* CRUD Business Item, 
* CRUD Booking Option

FEATURE UPDATE:
* Fetch Main web static content data into Main Website
* Fetch booking option data into Main Website

## v.1.0.0-rc.5
NEW FEATURE:
* Order Management - Manual Create, Read, Update, Delete Order and publish order

## v.1.0.0-rc.4
FEATURE UPDATE:
* Company Management - Add PIC information (Name, Phone, Email)

## v.1.0.0-rc.3
FEATURE UPDATE:
* Product Management - CRUD Product Item Price Configuration, CRUD Service Package Configuration

NEW FEATURE:
* CRUD Operator
* CRUD Customer by Worker using Worker App

## v.1.0.0-rc.2
New Features:
* Create, Read, Update, Delete AC for Personal Customer
* Create, Read, Update, Delete Company Category
* Create, Read, Update, Delete Company Group
* Create, Read, Update, Delete Company Customer
* Create, Read, Update, Delete AC for Company Customer
* Qr Code Generator

## v.1.0.0-rc.1
Initial Features:

* Login access as Superadmin
* Create, Read, Update, Delete Personal Customer
* Create, Read, Update, Delete Worker
* Create, Read, Update, Delete Product Item
* Create, Read, Update, Delete Service Package
* Create, Read, Update, Delete Service Package Item
