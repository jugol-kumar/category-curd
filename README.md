
#Laravel Slug Generator package
- Author : Jugol Kumar
- email: Jugolkumar23@gmail.com
---


#1. Install The Package Using Composer On Your Project.


```sh 
$ composer require jugol-kumar/category-curd
 ```

#2. Publish Vendor Folder And Files

```sh
$ php artsian vendor:publish jugol-kumar\category-curd\CategoryCrudServiceProvider
```

#3. Using In controller 

```php
CategoryCrudFacade::generate(\App\Models\User::class, 'your title', 'field name');

// your-title
```

```php
// after using this title
CategoryCrudFacade::generate(\App\Models\User::class, 'your title', 'field name');

// your-title-1
```



