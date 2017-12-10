# Laravel: 5 paskaita

## Video

[YouTube įrašas](https://www.youtube.com/watch?v=RClBxj315pU)

## Apie ką kalbėjome ir ką nuveikėme

1. Pabaigiam įrašo update dalį.

2. Metodai nuotraukos pašalinimui/pakeitimui; logika, kaip tai valdome.

3. Įrašo naikinimas (paskutinis CRUD elementas).

4. Migracijos products lentai, nuotrauka tampa jau nebebūtinas elementas įrašo sukūrimui.

5. Intro: Seeder klasės.

## Užduotys

* Primenu, kad būtina būti pasiruošusiems kategorijų migraciją, modelį, pilnai veikiantį controllerį ir viewsus. Kitos pateiktos užduotys šįsyk daugiau kaip mankšta ir galvosūkiai :)

* Paprasta: Jeigu produkto įrašas neturi nuotraukos, atvaizduoti nustatytą placeholderį, [pavyzdys](http://aquasportsgoa.com/wp-content/themes/456sailing/assets/img/no-product-image.png)

* Sudėtinga: Galimybė vartotojui įkelti nuotrauką arba nurodyti URL nuotraukos, kuri guli kažkur internete. Iš čia galima skelti užduotį į dar du etapus:

1. Jeigu išsaugota nuoroda, atvaizduojame paveikslėlį pagal ją, failo įkėlimas nėra reikalingas. Jeigu failas įkeliamas, tuomet viskas lieka taip pat, kaip ir dabar esame pasidarę.

2. Susitvarkius su šita dalimi galima pasidaryti dar gudriau: išsitraukti paveikslėlį pagal pateiktą nuorodą, jį išsisaugoti savo aplikacijoje. Visa logika būtų sudėta tik saugant nuotrauką, o atvaizdavimas viskam būtų vienodas.

* Šiek tiek frontendo: Paspaudus ant "Trinti" mygtuko reikėtų išmesti veiksmo patvirtinimo dialogą. Paprastas variantas: [JS confirm](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_confirm), gražesnis ir reikalaujantis daugiau darbo: [Bootbox.js](http://bootboxjs.com/) ar pan. alternatyva
