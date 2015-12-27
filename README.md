Symfony 3 Base Project by Ismael Trascastro
===========================================

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

- Clone this repository

    ```
    git clone https://github.com/itrascastro/Symfony-3-Base-Project myproject
    ```

- Run composer update

    Move into your project

    ```
    cd myproject
    ```

    and run this composer command

    ```
    composer update
    ```