---
name: kontrolna-pitanja
description: Piše "Контролна питања" (pitanja za proveru znanja) na kraju skripti za gimnaziju, u stilu koji Igor Marković koristi u svojim skriptama (npr. fizika/4_osztaly/Skripta_Talasna_svojstva_cestica_i_kvantna_teorija_H_atoma.pdf) — pitanja po poglavljima, 6 po poglavlju, podeljena na 4 srednje teška i 2 "teža pitanja", sva pojmovna (bez računanja). Koristi ovaj skill SVAKI PUT kada treba napisati, dopuniti, proveriti ili ispraviti kontrolna pitanja, pitanja za proveru razumevanja, ili pitanja za kraj poglavlja u bilo kojoj skripti (fizika ili drugi predmet) — čak i kada korisnik samo kaže "dodaj pitanja na kraj", "napravi pitanja za ovo poglavlje" ili "treba mi par pitanja iz ovoga", bez eksplicitnog pominjanja stila.
---

# Kontrolna pitanja — kućni stil

Ovaj skill opisuje tačan format i duh kontrolnih pitanja koji Igor Marković koristi u svojim
skriptama za gimnaziju (referentni primer: *Таласна својства честица и квантна теорија
атома водоника*, 4. razred). Cilj pitanja nije provera računske spretnosti nego provera
razumevanja — da li učenik ume da objasni, poveže i odbrani zaključak svojim rečima.

## Gde pitanja idu

Kontrolna pitanja su **poslednja celina skripte**, posle eventualnog pregleda ključnih
relacija/formula. Naslov celine je prost, bez broja poglavlja:

```
Контролна питања
```

Odmah ispod naslova ide jedan kratak, *kurzivom* pisan uvodni pasus (2–3 rečenice) koji
objašnjava filozofiju pitanja. Prilagodi ga sadržaju skripte, ali zadrži ovu poruku — primer
iz referentne skripte:

> *Питања која следе проверавају разумевање, а не рачунску спретност — ниједно се не
> решава уврштавањем бројева у формулу. У сваком поглављу прва четири питања су средње
> тежине и траже тачно репродуковање и повезивање појмова; последња два, издвојена
> поднасловом, тежа су и захтевају извођење закључка, поређење двају описа или уочавање
> тога зашто неки аргумент уопште има доказну снагу.*

## Struktura po poglavlju

Za svako poglavlje skripte (podnaslov identičan naslovu poglavlja u glavnom tekstu, npr.
`1. Таласно-честични дуализам материје`) ide **tačno 6 pitanja**, numerisana 1–6 i
**nezavisno numerisana od poglavlja do poglavlja** (svako poglavlje počinje opet od 1, ne
nastavlja globalni brojač):

- **Pitanja 1–4** — srednja težina. Traže tačno reprodukovanje pojma i povezivanje dva
  pojma iz tog poglavlja. Rešivo bez računanja, samo objašnjenjem.
- Pre pitanja 5, ubaci kurzivom pisan podnaslov `Тежа питања` (bez broja).
- **Pitanja 5–6** — teža. Traže jedno od sledećeg: izvođenje zaključka rečima (ne
  računom), poređenje dva modela/opisa/ogleda, ili objašnjenje zašto neki eksperimentalni
  nalaz ili argument uopšte ima dokaznu snagu.

Nijedno pitanje se ne rešava uvrštavanjem brojeva u formulu, čak ni teža. Ako poglavlje ima
formulu, pitanje pita *zašto* formula izgleda tako, *šta* fizički znači neki njen deo, ili
*šta sledi* iz nje — nikad "izračunaj za date vrednosti".

## Kako se pitanje formuliše

Svako pitanje mora da referencira **konkretan, imenovani** sadržaj iz tog poglavlja — ime
naučnika, naziv ogleda/eksperimenta, naziv zakona ili postulata, konkretan pojam uveden u
tekstu. Izbegavaj uopštena pitanja koja bi važila za bilo koje poglavlje bilo koje skripte.

Tipični glagoli/konstrukcije kojima pitanje počinje ili se gradi (koristi ih kao repertoar,
ne kopiraj doslovno):

- `Објасни зашто...` / `Образложи зашто...`
- `Зашто...` (direktno pitanje)
- `По чему се ... разликује од ...?`
- `Шта је ...? Објасни ...`
- `Покажи како се ... преписује као ...`
- `Упореди ...` / `Поређењем ... и ... закључи ...`
- `Изведи тај закључак речима и објасни ...` (za teža pitanja)
- `Образложи корак по корак зашто ...` (za teža pitanja)

Pitanje je po pravilu dvodelno: prva rečenica postavlja situaciju ili tvrdnju iz teksta,
druga eksplicitno traži objašnjenje, poređenje ili posledicu ("Objasni zašto...", "Šta iz
toga sledi za...", "Na kom svojstvu se tvoj zaključak zasniva?").

### Primeri (iz referentne skripte, za osećaj registra)

Srednje pitanje:
> Де Брољ је полазну релацију између таласне дужине и импулса извео за фотон. Објасни
> зашто њено проширење на честице са ненултом масом мировања није логична последица
> дотадашње теорије, него хипотеза, и шта је у том тренутку говорило у њен прилог.

Teže pitanje:
> Оглед са двоструким прорезом може се извести тако слабим снопом да се у апаратури
> налази највише један електрон. Објасни зашто тај резултат оповргава тумачење по коме
> интерференција настаје међусобним деловањем електрона у снопу и шта он говори о томе
> чему се талас придружује.

## Jezik i ton

- Pisano ćirilicom, ekavicom, u istom registru kao i glavni tekst skripte (formalno,
  precizno, bez fraza tipa "lako je videti" ili "očigledno").
- Obraćanje učeniku u drugom licu jednine, imperativ: "Objasni...", "Izvedi...", "Uporedi...".
- Nema pitanja sa ponuđenim odgovorima (nije test sa više ponuđenih odgovora) — sva pitanja
  su otvorenog tipa, traže pisani odgovor u par rečenica.
- Nema datih rešenja/odgovora uz pitanja — ovo je kontrolna lista za proveru, ne radna sveska
  sa rešenjima.

## Radni postupak kad praviš pitanja za novu/drugu skriptu

1. Pročitaj skriptu i izdvoji poglavlja (isti naslovi koji se koriste u telu teksta).
2. Za svako poglavlje izvuci 4–6 **imenovanih** elemenata koje pitanje može da targetira:
   ime naučnika/ogleda, formulu ili zakon, ključni pojam uveden u "Кључни појмови" na kraju
   poglavlja (ako postoji), ili zaključak istaknut u boksu "Суштина у једној реченици".
3. Napiši 4 srednja pitanja — svako targetira drugi element, svako traži objašnjenje/vezu,
   ne definiciju napamet.
4. Napiši 2 teža pitanja — traže ili izvođenje zaključka rečima, ili poređenje dva nalaza/
   modela/ogleda iz istog poglavlja, ili objašnjenje dokazne snage nekog argumenta.
5. Proveri da nijedno pitanje ne traži uvrštavanje brojeva — ako jesi tako nešto napisao,
   preformuliši ga u pojmovno pitanje o tom istom odnosu.
6. Ako skripta nema sekciju "Кључни појмови" ili "Суштина у једној реченици" po poglavlju,
   pitanja i dalje važe — samo ih izvuci direktno iz tela teksta tog poglavlja.
