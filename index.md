# Manoa Xchange
## Overview

Living on campus tends to be a short lived experience. Many students either move into off campus housing or go abroad after finishing their degree(s). Lots of campus specific goods are built up, and there is a need for a marketplace where students can buy and sell them.

## Goals

Large masses of students quickly come and go in the dorms of UH Manoa. This leads to lots of campus specific items that are discarded by previous students. Our goal is to create an application that helps to promote and incentivize buying and selling goods between the students of UH Manoa. This allows students to reuse and repurpose items that were used by other students, reducing the amount of items that were going to be discarded. 

## What our Application provides

Our application provides a marketplace for students to purchase and sell goods. Anybody can browse the marketplace, and can easily search the marketplace by using a search bar or using one of many premade filters. However, there is more site functionality when people log in as a User (aka UHM student). Users are able to browse the marketplace, and are able to browse sellers and their user profile page (that lists the user's wares and rating). Users are also able to order/offer/buy goods from the marketplace, and create/list goods on the marketplace. Users are also able to report users and/or items on the markertplace. Admins are able to remove items on the marketplace that are deemed as unsafe, inappropriate, or illegal.

## Deployed Application

You can access our (in working) deployed website here:
[ManoaXchange](http://188.166.104.165/)

## User Guide

The following sections provides a walkthrough of ManoaXchange's user interface and application features. As this project is in development, every page is accessible but not fully functional.

### Landing Page
This page is visible to people who first land on the site. There is a carousel that shows random items in the store.
![Landing](images/landing.png)
### Logged In User
When the user is logged in, the navbar will have 'sell' and 'sellers' options.
![Logged In User](images/logged-in-user.png)
### Shop Page
The shop page is available for anybody, and it shows items. There is also a side menu where users can select what category they are interested in or they can search for items.
![Shop](images/shop.png)
### Admin
The admin can see all of the users, and all of the items. Reports will be displayed on the admin's home page.
![Admin](images/admin.png)
### Item Page
The item page contains all of the information about the item, and the item can be purchased or added to cart.
![Item Page](images/item_page.png)
### Sell Page
Users can also post items for sale.
![Sell Item](images/sell_page.png)
### Profile
Each member has a profile page that can be visited by other users.
![Profile](images/user_profile.png)

## Development History

The following sections document the development history of ManoaXchange.

### Milestone 1 - Basic Necessities
For the first milestone, the goal is to create the mockup pages, and creating the basic schema of the items.
Milestone 1 was managed using [Manoaxchange GitHub Project Board M1](https://github.com/orgs/manoaxchange/projects/1)
![](images/milestone1-11092022.png)
![](images/m1-project-page-description.png)

### Milestone 2 - Connecting Databases & Refining UI
For the second milestone, the goal is to polish up and refine our application. Existing pages will look less bare with additional CSS/bootstrap properties, and our collection database will have connections between each other and function correctly.
Milestone 2 was managed using [Manoaxchange GitHub Project Board M2](https://github.com/orgs/manoaxchange/projects/2)

## Team Members

Manoaxchange was designed and implemented by Nicholas Kaw, Gian Portillo, and Giorgio Tran. Since this project was not supervised by a project manager, all members contributed and adhered to the [Team Contract](https://docs.google.com/document/d/10dSg54SKbQ1Hqc51PzH4RVmZYIIof93CubZPhwS6ZQs/edit?usp=sharing).

If you have any comments or questions, feel free to contact us on our via GitHub or email:
- [Nicholas Kaw](https://github.com/nickkaw) <kawn@hawaii.edu>
- [Gian Portillo](https://github.com/Geeean) <gtp@hawaii.edu>
- [Giorgio Tran](https://github.com/giorgio-tran) <ttran2@hawaii.edu>

## Brainstorming
- Possibly using Amazon S3 for image uploading or Cloudinary
- Implementing rating system for both sellers and items
