# Vivid Store
A Free eCommerce Add-on For Concrete5 5.7

* [See the Roadmap here](https://github.com/VividWeb/vivid_store/wiki/Roadmap)
* [Read the license here](https://github.com/VividWeb/vivid_store/blob/development/LICENSE.txt)

## Installing from Command Line
We no longer include the third party dependencies in our GitHub repository. So, a simple download of the repo will not work.
You'll need composer to install the dependencies.
* Install in your packages folder
```
git clone https://github.com/VividWeb/vivid_store.git
```
* Use [Composer](https://getcomposer.org/) to install third party dependencies
```
composer install
```


## A word on contributing
Vivid Store welcome contributions in all forms: Discussions, issue reporting, bug fixes, pull requests, feature requests. 

## Naming Conventions

* Class Names, and folders in /src/VividStore should be singular.
* File and Class Names should inherit their folder name. (prepended or appended)
  * Example 1: /Product/ProductGroup.php as opposed to /Product/Group.php
  * Example 2: /Report/SalesReport.php as opposed to /Report/Sales.php
* When using "use" statements, alias classes as StoreClassName. This and the aforementioned class naming convention should help avoid any similarly named Aliases. This also prevents things like stepping on the toes of any global Aliases.
