# Laravel-5.4x Private Messenger

A full featured Laravel 5.4x Private Messenger service which includes multi user messaging and conversations. Perfect for any social, support or any other user communication applications.

## Laravel App Drop-in Service

This application will be a drop-in service which means you can drop it in to your application and extend it endlessly. Unlike a third party vendor package with a limited API you can alter the files, add, and extend without worrying about overwrites when a new version is released. New features and bug fixes will be posted at a site to named later so devs can build on the project as well as update alter their own code to suit. There will be blade view examples (plus a nice demo) and the asset dependencies will be shipped but no blade views will be included because you want it to fit into your layout. The application can easily fit into any html structure that you have with marginal editing needed. A feature rich API will also be included so devs can simply include the needed aspects in their own project. I decided on this approach because honestly using so many 3rd party vendor packages becomes messy and at the same time you cannot alter these packages to meet your specific needs, the drop in approach leaves everything open for you to develop to your hearts desire.

## Drop-in Laravel Structure

The structure will follow standard Laravel 5.4 structure IE: "app" being the root of your applications main PHP files, providers. services, routes, models, controllers, facades etc. If you are not using "app" as your applications main PHP root then some simple editing may be required but since you changed the default "app" folder you are already aware of this.
A user database table is necessary obviously, thios is not included, the migrations and seeds will be for the messenger app specific and will not effect your current apps database structure ( Hopefully :) )
So basically this will be yours and part of your app natively to alter any which way you want

Default Structure (overall)
* app
* bootstrsp
* config
* database
* public
* resources
* routes
* stroage
* tests
* vendor

What will be needed for messenger app

* app
   * Console
   * Events
   * Exceptions  
   * Helpers (or helpers.php below)
   * Http
      * Controllers
   * Listeners  
   * Models
   * Notifications
   * Providers
   * Repositories
   * Services
   * helpers.php
   
   I think you get the idea, pretty basic structure. Dont worry if you dont have the folders necessary they will be created by the application install
   
## Features Short List

User end
- One on one and Multi user messaging
- Notifications
- Custom folder creation
- Message storage stats and Info
- Block users
- Signature field
- Privacy settings
- Attachments
- More...

Admin end
- Turn on / off for users
- Limit per user by disk space or message count
- Select attachment extensions/mime
- Basically full control on how the user can use the app

As I get closer to a release I will post full list of features

## In development

Hope to have a beta commit as soon as I am happy with the coverage

## Teaser

Screens of a fully functional AJAX Pages version but can be used in any type environment.

![messenger-info](https://github.com/GaryCornell/Laravel-5.4x-Private-Messenger/blob/master/demo/messenger.png)

![messenger-settings](https://github.com/GaryCornell/Laravel-5.4x-Private-Messenger/blob/master/demo/messenger_settings.png)

## Contribute

Absolutely!!! Get in touch with me for more info

## License

MIT for now, havent decided yet


