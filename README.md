# [Laravel Vuejs - Argon Design](https://appseed.us/apps/vuejs/laravel/argon-design-system-creative-tim)

Full-Stack [Vue](https://vuejs.org/) [Argon Design](https://www.creative-tim.com/product/vue-argon-design-system) with [Laravel](https://laravel.com/) backend server.

<br />

![Laravel Vuejs Argon Design - Gif animated presentation.](https://github.com/app-generator/static/blob/master/products/argon-design-system-intro.gif?raw=true)

<br />

## Product Features

This full-stack app is built using a decoupled architecture, where the [Vue Argon Design](https://www.creative-tim.com/product/vue-argon-design-system) frontend communicates with the [Laravel](https://laravel.com/) backend through secure ajax call.

 - [Laravel](https://laravel.com/) backend
 - SQLite database, managed by Sequelize ORM. A simple Users tabel is provided.
 - JWT token authentication
 - [Vue](https://vuejs.org/) [Argon Design](https://www.creative-tim.com/product/vue-argon-design-system) crafted by the famous Creative-Tim agency.
 - Login and Registration features

To use and start this starter, a few simple steps must be followed: 

 - clone, build and start the [Laravel boilerplate](https://github.com/app-generator/laravel-boilerplate) backend
 - clone, built and start the [Vue Argon Design](https://github.com/app-generator/vuejs-argon-design-system) frontend

<br />

## [Laravel boilerplate](https://github.com/app-generator/laravel-boilerplate) backend 
 
The backend server is a simple [Laravel](https://laravel.com/) with **JWT authentication**, **MySql** database, **Native ORM**, unit tests and basic tooling.
 
```
$ #############################
$ # clone and build the backend

$ git clone https://github.com/app-generator/laravel-boilerplate.git
$ cd laravel-boilerplate
$ vi .env # setup DB connection and JWT 

$ composer install # install modules
$ php artisan key:generate # setup Laravel
$ php artisan migrate:fresh --seed # create database

$ cd public 
$ php -S localhost:3000 # start the server 

```

<br />

## [Vue Argon Design](https://github.com/app-generator/vuejs-argon-design-system)

[Vue](https://vuejs.org/) app enhanced with **JWT Authentication**. 

```
$ #############################
$ # clone and build the Vue Frontend

$ git clone https://github.com/app-generator/vuejs-argon-design-system.git
$ cd vuejs-argon-design-system
$ yarn
$ yarn start # Frontend runs on port 8080
```

<br />

## Resources

 - [Laravel boilerplate](https://github.com/app-generator/laravel-boilerplate) backend sources
 - [Vue Argon Design](https://github.com/app-generator/vuejs-argon-design-system) sources
 - [Laravel Vuejs Argon - Demo](https://express-vuejs-argon-design.appseed.us/)

<br />

### What is [Laravel](https://laravel.com/)

Laravel is a free, open-source[3] PHP web framework, created by Taylor Otwell and intended for the development of web applications following the model–view–controller (MVC) architectural pattern and based on Symfony. The source code of Laravel is hosted on GitHub and licensed under the terms of MIT License. Read more about **Laravel** [here](https://en.wikipedia.org/wiki/Laravel).

<br />

### What is [Vue](https://vuejs.org/)

[Vue](https://vuejs.org/) (pronounced /vjuː/, like view) is a progressive framework for building user interfaces. Unlike other monolithic frameworks, Vue is designed from the ground up to be incrementally adoptable. The core library is focused on the view layer only, and is easy to pick up and integrate with other libraries or existing projects. On the other hand, Vue is also perfectly capable of powering sophisticated Single-Page Applications when used in combination with modern tooling and supporting libraries. Read more about **Vue** [here](https://vuejs.org/v2/guide/).

<br />

### [Vue Argon Design](https://www.creative-tim.com/product/vue-argon-design-system)

Start your development with a Design System for Bootstrap 4. It is open source, free and it features many components that can help you create amazing websites. **Vue Argon Design** is built with over 100 individual components, giving you the freedom of choosing and combining. All components can take variations in colour, that you can easily modify using SASS files. Read more about **Vue Argon Design** [here](https://www.creative-tim.com/product/vue-argon-design-system)

<br />

## Support

For issues and features request, use **Github** or access the [support page](https://appseed.us/support) provided by **AppSeed** 

<br />

## License
MIT @ [AppSeed](https://appseed.us)

<br />

---
[Laravel Vuejs - Argon Design](https://appseed.us/apps/vuejs/laravel/argon-design-system-creative-tim) provided by **AppSeed**
