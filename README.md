
#Laravel Slug Generator package
- Author : Jugol Kumar
- email: Jugolkumar23@gmail.com
---


#1. Install The Package Using Composer On Your Project.


```sh 
$ composer require jugol-kumar/category-curd
 ```


#2. Using in controller 

```php
CategoryCrudFacade::generate(\App\Models\User::class, 'your title', 'field name');

// your-title
```

```php
// after using this title
CategoryCrudFacade::generate(\App\Models\User::class, 'your title', 'field name');

// your-title-1
```



