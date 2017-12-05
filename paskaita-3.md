# Laravel: 3 paskaita

## Video

[YouTube įrašas](https://www.youtube.com/watch?v=TbV1g1bjCM4)

## Apie ką kalbėjome ir ką nuveikėme

1. Pabaigiam nagrinėti auth scaffolding (`php artisan make:auth`) rezultatus: routes, controllers, views, models, migrations.

2. `view($template, $data)` helperis, grąžinantis šabloną.

3. Blade template engine direktyvos, skirtos šablonų kūrimui ir paveldimumui: `@extends`, `@yield`, `@section`, [dokumentacija](https://laravel.com/docs/5.5/blade).

4. Dirbam su duomenimis ir šablonais:

* atvaizduojam produktų lentelę

* duomenis iškeliam iš lentelės į controllerį (masyvas, kuriame yra produktų masyvai)

* naudojam `@foreach` ciklo direktyvą duomenų išvedimui šablone

* norime duomenis iškelti į duomenų bazę, tad kuriame migraciją lentelės sukūrimui `create_products_table`, [dokumentacija](https://laravel.com/docs/5.5/migrations)

* kuriame modelį `Product`, kuris bus skirtas darbui su `products` lentelės duomenimis

**Protip** 
`php artisan make:model Product -m` galima paduoti option'ą `-m` arba `--migration`, tokiu atveju sukuriamas ir modelis, ir migracija, tad sutaupom vieną komandą ir veiksmus atliekam greičiau, kai reikia naujo resurso.

* modelio metodai: `all()`, `find()`, `save()`

* pakeičiam "įhardkodintus" duomenis controlleryje į modelio panaudojimą

5. `php artisan tinker` - paleidžiama interaktyvi aplinka sąveikauti su aplikacija bei greitai pasibandyti jos funkcionalumą neteršiant kodo [Wiki apie REPL (Read-eval-print loop)](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop)

6. `url()`, `route()`, `dd()`, `collect()` helperiai

7. Collections klasė lengvesniam ir aiškesniam darbui su masyvais, [dokumentacija](https://laravel.com/docs/5.5/collections).

8. Turime paruoštus metodus:

* `ProductsController:index` - produktų sąrašas 
* `ProductsController:show` - vieno produkto atvaizdavimas pagal id
* `ProductsController:create` - naujo produkto forma

## Užduotys

Bus papildyta.
