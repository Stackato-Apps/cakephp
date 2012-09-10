# CakePHP Database Configuration Sample

## Deploy on Stackato

    stackato push -n

## Changes

    app/Config/core.php (minor)
    app/Config/database.php

## Lessons Learned

Because class properties can only be initialized with constant values 
[PHP Manual](http://www.php.net/manual/en/language.oop5.properties.php). 
So you'll need to set up $default in the constructor instead. 
Cake will instantiate the class.
