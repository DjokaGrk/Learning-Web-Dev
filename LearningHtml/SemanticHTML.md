# Semantic HTML

Semantic HTML je deo HTML5 standarda koji se koristi za označavanje sadržaja na
web stranici. Semantic HTML omogućava pretraživačima i drugim alatima da
razumeju značenje sadržaja, a ne samo njegov izgled. To znači da se koristi
odgovarajući HTML element za svaki deo sadržaja, umesto da se koristi samo
jedan ili dva elementa za sve.

## Koja je razlika izmedju Presentational i Semantic HTML?

Presentational HTML se koristi za stilizovanje i formatiranje sadržaja, dok se
Semantic HTML koristi za označavanje značenja sadržaja. Na primer, umesto da
koristimo `<div>` element za sve, možemo koristiti
`<header>, <nav>, <article>, <section>, <footer>`itd.
Da označimo različite delove stranice

## When Should You Use the Emphasis Element Over the Idiomatic Text Element?

Idiomatic text se pise sa `<i lang="fr">ovo je primer kada zelimo da se
obrati paznja na nesto kao drugi jezik</i>`

## When Should You Use the Strong Element Over the Bring Attention To Element?

`<strong>ovo je primer kada zelimo da se obrati paznja na nesto kao drugi jezik</strong>`

## What Are Description Lists, and When Should You Use Them?

U HTML-u, opisne liste (description lists) su struktura koja se koristi za
prikazivanje pojmova i njihovih opisa. Ova vrsta liste se sastoji od dve
osnovne oznake: <dl>, <dt>, i <dd>.

Oznake:

<dl>: Ova oznaka predstavlja početak opisne liste.

<dt>: Ova oznaka se koristi za definisanje pojma (term).

<dd>: Ova oznaka se koristi za pružanje opisa povezanog sa pojmom
definisanim u <dt>

## How Do Block and Inline Quotes Work in HTML?

Inline citat:
Kada koristite inline citate, citat se uključuje unutar teksta. Na primer:

```

<q cite="https://www.freecodecamp.org/news/learn-to-code-book">
Učenje je proces koji traje ceo život.</q>
```

Block citat:
Block citati se koriste za duže odlomke ili citate i često su formatirani
tako da se odvoje od ostatka teksta. Na primer:

```
<blockquote>
  "Učenje je proces koji traje ceo život. Važno je nastaviti istraživati
  i širiti svoje horizonte, kako bismo postigli lični i profesionalni razvoj."
</blockquote>
```

## How Do You Display Abbreviations and Acronyms in HTML?

razlika izmedju akronima i skraćenica je u tome što se akronimi čitaju kao reči, dok se skraćenice koriste kao skraćene verzije reči ili fraza. Na primer, "NASA" je akronim, dok je "Dr." skraćenica za "doktor".

```
<p><abbr title="HyperText Markup Language">HTML</abbr> is the foundation of the web</p>
```
## How Do You Display Addresses in HTML? 
Html Addresses je najbolje staviti jer pokazuje contact iformacije na stranici 

radi se: 
```` 
<Address>
<h2>Kuvarica.rs</h2>
<p> Sime Pogacarevica 4<br>
17520, Bujanovac<br>
Srbija
</p>
<p>Phone:<a href="tel:+381692519478">+381692519478</a></p>
<p>Phone:<a href="mailto:djokagrk@gmail.com">djokagrk@gmail.com</a></p>
</Address> 
````
## How Do You Display Times and Dates in HTML?

U HTML-uz, možete koristiti oznaku `<time>` za prikazivanje vremena i datuma. 
Oznaka `<time>` omogućava da se označi vreme ili         datum u 
standardizovanom formatu, što olakšava pretraživačima i drugim alatima da 
razumeju i interpretiraju te informacije. 


Na primer, možete koristiti `<time>` oznaku na sledeći način:
`YYYY-MM-DDTHH:MM:SS` `T` je separator izmedju vramena i datuma  
















