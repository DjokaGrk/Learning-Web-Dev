# Basics of HTML

HTML (HyperText Markup Language) is the standard language for creating web pages.

## Basic Structure of an HTML Document
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>Welcome to HTML Basics</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

Na https://www.freecodecamp.org/ postoji drugacija struktura gde se radi deo po deo iz osnova i onda se radi vezbanje

25.04.2025. radim

* working with media
  * Replaced Elements
    ```
    <img src="url" alt="desctriptive text"></img>
    ```
    element odredju sta se nalazi u njemu znaci u ovo primeru nalazi se slika gde se moze menjati pozicija i Leyout i nista vise
  ** Media optimization
    * size
    * file format (png, jpeg) najbolji su webp avif formati
    * Compress
  * Image Licenses and how work
    * nabaviti licencu
    * nabaviti pisanu dozvolu
    * Poštena upotreba je pravni princip koji omogućava ograničeno korišćenje zaštićenog materijala bez potrebe za dobijanjem dozvole od nosioca autorskih prava. Evo ključnih tačaka o poštenoj upotrebi slika:
    Svrha i karakter upotrebe: Komercijalna vs. obrazovna upotreba može uticati na poštenu upotrebu. Neprofitne obrazovne svrhe su često verovatnije da će se kvalifikovati kao poštena upotreba nego komercijalne aplikacije.

    Priroda zaštićenog dela: Korišćenje faktičkih dela (npr. fotografije javnih događaja) je verovatnije da će se smatrati poštenom upotrebom nego korišćenje čistih kreativnih dela (npr. umetnički radovi ili fotografije koje su namenjene umetničkoj svrsi).

    Količina i suštinsko značenje: Korišćenje malog dela slike može favorizovati poštenu upotrebu. Međutim, korišćenje "srca" dela, čak i ako je mali deo, može ići protiv poštene upotrebe.

    Uticaj na tržište: Ako upotreba slike može potencijalno naškoditi tržištu za originalno delo ili njegove derivate, to može ići protiv utvrđivanja poštene upotrebe.

    Transformativna upotreba: Ako upotreba dodaje novo značenje, izražaj ili poruku originalnoj slici, verovatnije je da će se smatrati poštenom upotrebom.

    Važno je napomenuti da se poštena upotreba utvrđuje na osnovu pojedinačnih slučajeva, i ne postoje jasna pravila. Kada niste sigurni, preporučuje se da zatražite dozvolu od nosioca autorskih prava ili da se konsultujete sa pravnim stručnjakom.

  * Sta je svg i kako se koristi
   svg = scalble vector grafic
   moze se koristiti kao xml jer ne gubi klalitet
  * What Are the Roles of the HTML Audio and Video Elements, and How Do They Work? atributi: loop, controls, muted for video: poster
  * How Do You Embed Videos onto Your Page Using the iframe Element?
   treba da se promeni od youtu.be/blabla nad youtube.com/embed/blabla
   postoje atributi kao sto su allfullscreen width , height etc
   moze su embedovati mapa (srcdoc="") url i drugo...
* Build a Video Compilation Page
  ```
  ovako bi izgledala strana
  <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <title>Video Compilation Page</title>
</head>

<body>
<main>
        <h1>Front End Web Development</h1>
        <p>Front End Web Development involves designing and building user interfaces of websites using HTML, CSS, and
            JavaScript. </p>
        <section>
            <h2>HTML</h2>
            <p>HTML, or HyperText Markup Language,</p>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/GDGejH3SDNQ?si=KJYLgcz4kyyroYMB" title="html and coding introduction video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen=""></iframe>
        </section>
        <section>
            <h2>CSS</h2>
            <p>CSS</p>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/OXGznpKZ_sA?si=s3KDSZvrhU_PU9XL" title="css tutorial video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen=""></iframe>
        </section>
        <section>
            <h2>JavaScript</h2>
            <p>JavaScript</p>****
            <iframe width="560" height="315" src="https://www.youtube.com/embed/jS4aFq5-91M?si=zKQhHEYwU4tnMmVm" title="javascript programming video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen=""></iframe>
        </section>
    </main>
</body>

</html>
  ```
* Working with Links
  * What Are the Different Target Attribute Types, and How Do They Work?
  * What Is the Difference Between Absolute and Relative Paths?
  * What Is the Difference Between Slashes, a Single Dot, and Double Dot in Path Syntax?
  * What Are the Different Link States, and Why Are They Important?







