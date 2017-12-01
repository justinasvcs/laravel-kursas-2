# Laravel: 1 paskaita

## Video

Nėra :( Pamiršau paspausti lemiamą mygtuką "Start broadcasting".

## Apie ką kalbėjome ir ką nuveikėme

1. [PHP FIG](http://php-fig.org): 

* [PSR-1](http://www.php-fig.org/psr/psr-1/) (Basic Coding Standard)
* [PSR-2](http://www.php-fig.org/psr/psr-2/) (Coding Style Guide)
* [PSR-0](http://www.php-fig.org/psr/psr-1/) (Autoloading Standard (deprecated))
* [PSR-4](http://www.php-fig.org/psr/psr-2/) (Autoloader)

2. [Composer](https://getcomposer.org): PHP trečiųjų šalių bibliotekų valdymo įrankis, įdiegimas savo kompiuteryje

3. [Packagist](https://packagist.org): pagrindinė Composer paketų repozitorija (saugykla)

4. MVC (model-view-controller) patternas, jo privalumai. Gaminame savo minimalų framework'ą pagal MVC.

4.1. Pagrindiniai projekto katalogai ir failai (TODO: įkelti repozitoriją su pagamintu produktu):

* `index.php` - entry point'as, kuriame automatiškai pagal URL nusprendžiama, kokio controllerio ir kokio jo actiono (metodo) reikės
* `app/controllers` - aplikacijos controlleriai
* `app/models` - aplikacijos modeliai
* `resources/views` - aplikacijos šablonai
* `src/framework` - core failai (`Db.php`, `Controller.php`, kuriuos galima būtų perpanaudoti bet kuriame naujame savo projekte)

4.2. Naudojame Composer suteikiamą PSR-4 autoload'ą, aprašomą `composer.json` faile, generuojam `vendor/autoload.php`, kuris atlieka reikiamą darbą pasinaudojus komandine eilute: `composer dumpautoload`.

## Užduotys

-
