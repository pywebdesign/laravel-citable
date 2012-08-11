laravel-citable
===============

Laravel-citable stant for Laravel port of the CI_table class. CI_table is the nice table class found in the codeigniter framework.

to use, put the file in your application library.

on your view file, you can generate table like this:
```
//first you need a 2d array
<?php $data = array(array(...),array(...),...); ?>
//then you need a table object
<?php $table = new Table ?>
// just call the generate() function and pass the array to get a simple table
<?php echo $table->generate($data); ?>
//isn't that nice!