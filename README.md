Symfony 3 Base Project
======================

Installed bundles and other stuff
---------------------------------

- FriendsOfSymfony/FOSUserBundle
- Your own UserBundle to extend from FosUserBundle (with createdAt and updatedAt extra fields added)
- KnpLabs/KnpPaginatorBundle
- Bootstrap 3 with horizontal login
- Form templates
- Symfony Reverse Proxy configured to allow esi parts
- phpunit/phpunit (with a symbolic link under your bin folder. Simply run './bin/phpunit')
- Atlantic18/DoctrineExtensions (Slug generation)
- twig/extensions (time_diff)
- translation enabled in config
- symfony/assetic-bundle installed and configured
- doctrine/doctrine-fixtures-bundle

Installation
------------

PHP >= 5.5.9 required

## Installing Composer

Composer is the dependency manager used by modern PHP applications and it can also be used to create new applications.

Download the installer from [getcomposer.org/download](https://getcomposer.org/download/), execute it and follow the instructions.

## Creating a new project with Composer

  ```
  php composer.phar create-project itrascastro/symfony-3-base-project my_project_name
  ```

If you did a global install and do not have the composer.phar in that directory run this instead:

  ```
  composer create-project itrascastro/symfony-3-base-project my_project_name
  ```
