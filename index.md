# Manoa Xchange
[![ci-manoaxchange](https://github.com/manoaxchange/manoaxchange/actions/workflows/ci.yml/badge.svg)](https://github.com/manoaxchange/manoaxchange/actions/workflows/ci.yml)
## Overview

Living on campus tends to be a short lived experience. Many students either move into off campus housing or go abroad after finishing their degree(s). Lots of campus specific goods are built up, and there is a need for a marketplace where students can buy and sell them. Introducing Manoa Xchange, a convenient marketplace application that does just that! For more information continue reading or check out our [organization page](https://github.com/manoaxchange).

## Goals

Large masses of students quickly come and go in the dorms of UH Manoa. This leads to lots of campus specific items that are discarded by previous students. Our goal is to create an application that helps to promote and incentivize buying and selling goods between the students of UH Manoa. This allows students to reuse and repurpose items that were used by other students, reducing the amount of items that were going to be discarded. 

## What our Application provides

Our application provides a marketplace for students to purchase and sell goods. Anybody can browse the marketplace, and can easily search the marketplace by using a search bar or using one of many premade filters. However, there is more site functionality when people log in as a User (aka UHM student). Users are able to browse the marketplace, and are able to browse sellers and their user profile page (that lists the user's wares and rating). Users are also able to order/offer/buy goods from the marketplace, and create/list goods on the marketplace. Users are also able to report users and/or items on the markertplace. Admins are able to remove items on the marketplace that are deemed as unsafe, inappropriate, or illegal.

## Deployment

You can access our (in working) deployed website here:
[Manoa Xchange](https://manoaxchange.shop/)

## User Guide

The following sections provides a walkthrough of ManoaXchange's user interface and application features. As this project is in development, every page is accessible but not fully functional.

### Landing Page
This page is visible to people who first land on the site and contains a welcome message for everyone.
##### Not Logged In
If you are not logged in, then you will have a landing page with 'shop' and 'categories' as navbar options. Also, there is a sign up prompt underneath the welcome message.
![Landing](images/M3/landing.png)
![Landing](images/M3/home2.png)
##### Logged In
If you are logged in as a user, then the navbar will have an added 'sell', 'sellers', and 'my items' option. Admin accounts have all that was stated previously with an addition 'ADMIN' option.
![Logged In User](images/M3/loggedin-home.png)
![Logged In User](images/M3/loggedin-home-admin.png)
### Sign-Up Page
New users without an account can sign up on this page.
![SignUp](images/M3/signup.png)
### Sign-In Page
Users with an existing account or after registering, users can now login to the site on this page.
![SignIn](images/M3/login.png)
### Shop Page
The shop page is available for anybody, and it shows items. There is also a side menu where users can select what category they are interested in or they can search for items.
![Shop](images/M3/shop1.png)
![Shop](images/M3/shop2.png)

### Admin
The admin can see all of the users, and all of the items. Reports will be displayed on the admin's home page.
![Admin](images/M3/admin-report.png)
Admins can remove items by clicking on the red button in the **Remove** column.
![Admin Remove](images/M3/admin-remove.png)
Admins can also dismiss reports by clicking on the blue button in the **Dismiss** column.
### Item Page
The item page contains all of the information about the item. The item can be reported, and the user can message the seller.
![Item Page](images/M3/item-page.png)
#### Reporting Button
When the user clicks on the inappropriate item text, there is a pop-up where a report can be submitted.
![Report](images/M3/report.png)

#### Message Seller
Messaging the seller will show a confirmation message, and upon clicking **Message** an email will be sent to both the buyer and the seller.
![](images/M3/message-seller.png)
![](images/M3/email.png)
![](images/M3/email-message.png)

### My Items Page
There is also a **My Items** page, where users can see the items that they put up for sale, and they can edit, mark as sold, or remove the item by clicking on the options dropdown button.
![](images/M3/my-items.png)
![](images/M3/edit.png)
![](images/M3/sold.png)
![](images/M3/delete.png)

### Sell Page
Users can post items for sale.
![Sell Item](images/M3/sell.png)

### Sellers Page
Users can view a collection of other user profiles that have items for sale.
![Sellers](images/M3/sellers.png)

### Profile
Each member has a profile page that can be visited by other users.
![Profile](images/M3/profile-page.png)

### Sellers Profile
Profiles visited by other users. Users have the ability to give  users ratings based on how they feel about the him/her. Other users can also view the items that are being sold by that specific user.
![Sellers Profile](images/M3/sellers-profile.png)
![Ratings](images/M3/rating.png)

## Development History

The following sections document the development history of ManoaXchange.

### Milestone 1 - Basic Necessities
For the first milestone, the goal is to create the mockup pages, and creating the basic schema of the items.
Milestone 1 was managed using [Manoaxchange GitHub Project Board M1](https://github.com/orgs/manoaxchange/projects/1)
![](images/m1-project-board-fin.png)

### Milestone 2 - Connecting Databases & Refining UI
For the second milestone, the goal is to polish up and refine our application. Existing pages will look less bare with additional CSS/bootstrap properties, and our collection database will have connections between each other and function correctly.
Milestone 2 was managed using [Manoaxchange GitHub Project Board M2](https://github.com/orgs/manoaxchange/projects/2)
![](images/m2-project-board-fin.png)

### Milestone 3 - Finish Implementing Rating and Seller's Page & Refine UI
For the third milestone, the goal is to finish implementing the last features and refining the user interface. On top of that, community feedback will be need to ensure user friendliness and usability. Milestone 3 was managed using [ManoaXchange Github Project Board M3](https://github.com/orgs/manoaxchange/projects/3).
![](images/m3-pp.png)
## Team Members

Manoa Xchange was designed and implemented by Nicholas Kaw, Gian Portillo, and Giorgio Tran. Since this project was not supervised by a project manager, all members contributed and adhered to the [Team Contract](https://docs.google.com/document/d/10dSg54SKbQ1Hqc51PzH4RVmZYIIof93CubZPhwS6ZQs/edit?usp=sharing).

If you have any comments or questions, feel free to contact us on our via GitHub or email:
- [Nicholas Kaw](https://github.com/nickkaw) | <kawn@hawaii.edu>
- [Gian Portillo](https://github.com/Geeean) | <gtp@hawaii.edu>
- [Giorgio Tran](https://github.com/giorgio-tran) | <ttran2@hawaii.edu>

## Community Feedback
Here's a link to our [Community Feed Form](https://forms.gle/NDgyVLG9TfiVwxum8)

Manoa Xchange is a website that is made by us for our community members. We've asked some community members what their opinion about Manoa Xchange is. Here is what they had to say.

> I can see the potential of this application. It reminds me of Facebook marketplace, but for UH students. I think there are several improvements or features that could be added to improve the experience of the users. For example, adding a stock system when selling items in bulk, or adding another box for sellers to write their preferred method of delivery (meeting on campus, etc.). Overall, this application is really useful and would allow students to buy/sell items to each other really easily.

-- Micheal Tran, Biology

> I enjoy the idea of creating a buying/selling website which will cater towards only University of Hawaii students/alumni. The good thing about choosing a specific target, which will most likely be dorm students, is that getting items will be convenient/accessible. Also, having the variety of categories this website includes will make it easier for people to look up or sell items. Lastly, the website is very simplistic to know where to find items, without being distracted/confused by unnecessary imagery. One improvement that could be made is when more items are added to the website, specifically in each category, there doesn't seem to have some sort of organization of how items are listed. This could create the issue of being overwhelmed when you browse through the .

-- Paul Derick Cabuyao, Biology
## Developer Guide
### Meteor
1. Install meteor. Please follow the instructions from the [Meteor Documentation](https://docs.meteor.com/install.html)

### API Credentials
#### Gmail API
1. Create a Gmail account to be used for the project
2. Follow the instructions in the section **Gmail API Setup in Node.js** on [this guide](https://fusebit.io/blog/gmail-api-node-tutorial/?utm_source=www.google.com&utm_medium=referral&utm_campaign=none) to obtain credentials
3. Keep note of: Client ID, Client Secret, and Refresh Token. They will be used as environmental variables.
4. [Enable the Gmail API](https://developers.google.com/gmail/api/quickstart/nodejs#enable_the_api)

#### Cloudinary API
1. Create a [Cloudinary](https://cloudinary.com/) account
2. Log in, go to Settings &rarr; Upload, and add an 'Upload Preset'
3. Adjust settings if desired, and continue by pressing 'Save'
4. Keep note of the upload preset's name
5. Going back to the home page, keep note of: Cloudinary URL, Cloud Name, API Key, and API secret. They will be used as environmental variables.

### Running Application
1. Clone the application to your local machine
2. Navigate to the root directory of the application and enter `cd app` in the terminal to navigate to the app directory
3. Run `meteor npm install`
4. Inside of the `config` directory create a file called `settings.devauth.json`. This file will be gitignored, and it contains default data to be loaded as well as Gmail and Cloudinary secrets.
5. In `settings.devauth.json` paste the following code:
    ```json
    {
      "defaultAccounts": [
        { "email": "kawn@hawaii.edu", "password": "changeme", "role": "admin" },
        { "email": "gtp@hawaii.edu", "password": "changeme", "role": "admin" },
        { "email": "ttran2@hawaii.edu", "password": "changeme" }
    
      ],
    
      "defaultItems": [
        { "name": "Organic Chemistry 7th Edition", "image":  "https://via.placeholder.com/500.png?text=Item", "price":  20.00, "owner": "kawn@hawaii.edu", "description":  "Brand new, only used for one semester.", "category": "Books",
          "sold": false
        },
        { "name": "Keyboard", "image": "https://via.placeholder.com/500.png?text=Item", "price":  30.00, "owner": "kawn@hawaii.edu", "description":  "Brand new, all keys are functional.", "category": "Electronics",
          "sold": true
        },
        { "name": "Bike", "image":  "https://via.placeholder.com/500.png?text=Item", "price":  20.00, "owner": "gtp@hawaii.edu", "description":  "Brand new, only used for one semester.", "category": "Transportation", "sold": false },
        { "name": "Dish", "image":  "https://via.placeholder.com/500.png?text=Item", "price":  20.00, "owner": "gtp@hawaii.edu", "description":  "Brand new, only used for one semester.", "category": "Housewares", "sold": true },
        { "name": "Tshirt", "image":  "https://via.placeholder.com/500.png?text=Item", "price":  20.00, "owner": "ttran2@hawaii.edu", "description":  "Brand new, only used for one semester.", "category": "Clothing", "sold": false },
        { "name": "Some random stuff", "image":  "https://via.placeholder.com/500.png?text=Item", "price":  20.00, "owner": "ttran2@hawaii.edu", "description":  "Brand new, only used for one semester.", "category": "Miscellaneous", "sold": false }
      ],
    
      "defaultProfiles": [
        { "email": "kawn@hawaii.edu", "firstName": "Nicholas", "lastName": "Kaw", "bio": "Econ Major, Ics Minor", "picture": "https://github.com/nickkaw.png", "owner": "kawn@hawaii.edu" },
        { "email": "ttran2@hawaii.edu", "firstName": "Giorgio", "lastName": "Tran", "bio": "Kinesiology Graduate, Ics MD", "picture": "https://github.com/.png", "owner": "ttran2@hawaii.edu" },
        { "email": "gtp@hawaii.edu", "firstName": "Gian", "lastName": "Portillo", "bio": "Ics Major", "picture": "https://github.com/.png", "owner": "gtp@hawaii.edu" }
      ],
    
      "gmailAuth": {
        "TYPE": "OAuth2",
        "USER": "<gmail-email>",
        "CLIENT_ID": "<gcloud-client-id>",
        "CLIENT_SECRET": "<gcloud-secret>",
        "REFRESH_TOKEN": "<gcloud-refresh-token>"
      },
    
      "REDIRECT_URI": "https://developers.google.com/oauthplayground",
    
      "CLOUDINARY_URL": "<cloudinary-url>",
      "CLOUDINARY_NAME": "<cloudinary-name",
      "CLOUDINARY_APIKEY": "<cloudinary-api-key",
      "CLOUDINARY_APISECRET": "<cloudinary-api-secret",
      "CLOUDINARY_UPLOADPRESET": "<cloudinary-uploadpreset>"
    
    }
    ```
6. Change the Gmail and Cloudinary credentials with your own
7. Navigate back into `app` via the terminal
8. Run `meteor npm run start`
9. This is the result of successfully starting the application:
    ```
    giorgio@Giorgios-MacBook-Air app % meteor npm run start
    
    > meteor-application-template-react@ start /Users/giorgio/repos/manoaxchange/app
    > meteor --no-release-check --exclude-archs web.browser.legacy,web.cordova --settings ../config/settings.devauth.json
    
    [[[[[ ~/repos/manoaxchange/app ]]]]]          
    
    => Started proxy.                             
    => Started HMR server.                        
    Browserslist: caniuse-lite is outdated. Please run:
      npx browserslist@latest --update-db
      Why you should do it regularly: https://github.com/browserslist/browserslist#browsers-data-updating
    Browserslist: caniuse-lite is outdated. Please run:
      npx browserslist@latest --update-db
      Why you should do it regularly: https://github.com/browserslist/browserslist#browsers-data-updating
    => Started MongoDB.                           
    I20221129-13:56:19.926(-10)? Creating the default user(s)
    I20221129-13:56:19.934(-10)?   Creating user: kawn@hawaii.edu.
    I20221129-13:56:19.999(-10)?   Creating user: gtp@hawaii.edu.
    I20221129-13:56:20.063(-10)?   Creating user: ttran2@hawaii.edu.
    I20221129-13:56:20.125(-10)? Creating default items.
    I20221129-13:56:20.126(-10)?   Adding: Organic Chemistry 7th Edition (kawn@hawaii.edu)
    I20221129-13:56:20.148(-10)?   Adding: Keyboard (kawn@hawaii.edu)
    I20221129-13:56:20.149(-10)?   Adding: Bike (gtp@hawaii.edu)
    I20221129-13:56:20.150(-10)?   Adding: Dish (gtp@hawaii.edu)
    I20221129-13:56:20.150(-10)?   Adding: Tshirt (ttran2@hawaii.edu)
    I20221129-13:56:20.151(-10)?   Adding: Some random stuff (ttran2@hawaii.edu)
    I20221129-13:56:20.153(-10)? Creating default profiles.
    I20221129-13:56:20.153(-10)?   Adding: kawn@hawaii.edu (kawn@hawaii.edu)
    I20221129-13:56:20.172(-10)?   Adding: ttran2@hawaii.edu (ttran2@hawaii.edu)
    I20221129-13:56:20.172(-10)?   Adding: gtp@hawaii.edu (gtp@hawaii.edu)
    I20221129-13:56:20.212(-10)? Monti APM: completed instrumenting the app
    => Started your app.
    
    => App running at: http://localhost:3000/
    
    ```
10. The application can be accessed via [https://localhost:3000/](https://localhost:3000/) 

### Quality Assurance
For quality assurance, eslint is used in order to standardize the overall style of the code. 
1. cd into the `app` directory and run `meteor npm run lint`
2. There should not be any errors that show up, and this is an example of what it looks like with no errors:
    ```
    giorgio@Giorgios-MacBook-Air app % meteor npm run lint
    
    > meteor-application-template-react@ lint /Users/giorgio/repos/manoaxchange/app
    > eslint --quiet --ext .jsx --ext .js ./imports && eslint --quiet --ext .js ./tests
    
    giorgio@Giorgios-MacBook-Air app %
    ```

## Community Feedback

Coming soon!
