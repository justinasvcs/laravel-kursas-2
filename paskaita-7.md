# Laravel: 7 paskaita

## Video

[YouTube įrašas](https://www.youtube.com/watch?v=amr7oAQ-lq0)

## Apie ką kalbėjome ir ką nuveikėme

1. [Laravel Debugbar](https://packagist.org/packages/barryvdh/laravel-debugbar) - įrankis, palengvinantis development procesą, klaidų išgaudymą ir pan.

2. Model klasių parametrai: `$timestamps`, `$table`, konstantos `CREATE_AT`, `UPDATED_AT`.

3. Modelių sąryšiai (Eloquent relationships): `hasOne()`, `hasMany()` ir atvirkštinis `belongsTo()`.

4. Produktų ir kategorijų sąryšių kūrimas, atitinkami atnaujinimai aplikacijoje.

5. Lazy loading (kiekvienam susietam objektui nauja SQL užklausa, tad N+1 užklausų) vs eager loading (dvi užklausos, visi rezultatai, kiek mums reikia).

6. Named routes ir route kintamieji, kuriems galima aprašyti taisykles naudojantis [regular expressions](https://regexr.com).

## Užduotys

1. Pasinaudojus User modeliu apibrėžiam sąryšius:

* vienas vartotojas gali turėti daug produktų
* vienas vartotojas gali turėti daug kategorijų

Taip pat reikalingi atvirkštiniai metodai, jog produktas gali priklausyti vienam vartotojui.
