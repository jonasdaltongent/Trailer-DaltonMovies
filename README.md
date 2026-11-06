# Handleiding voor de leraar — Projectles 3: Afwerken en inleveren

**Vak:** Toegepaste Informatica · **Klas:** 3MWWE (2de graad Maatschappij- en welzijnswetenschappen, doorstroomfinaliteit)
**Soort les:** projectles 3 van *Dalton @ the movies* (lessenplan MWW § 7), in de plaats van een les uit het lessenplan; `lesnr` is `P3`
**Lesduur:** 1 × 50 minuten: 10 minuten instructie + 40 minuten keuzewerktijd · **Lokaal:** 18, Windows 11, Canva in Chrome + de eigen gsm met de Canva-app + oortjes
**Lesdag:** donderdag 12 november 2026, 8ste lesuur (14.35–15.25) · **Evaluatie:** **20 punten** op de trailer in Canva, met een checklist (zeven criteria, `lesvoorbereiding.md` § 22)
**Kernleerplandoel:** `BV2_04.02` (toepassen), met `BV2_04.04`, `BV2_04.03` en `BV2_05.01` ondersteunend
**Opdracht in Classroom:** *Projectles 3 — Afwerken en inleveren* (onderwerp *Project Dalton @ the movies*), **20 punten, deadline vr 13 november 2026, 20.00 uur**, alleen de link naar de lespagina; geen werkdocument

<!-- Beginvragen (stap 1 van CONTEXT.md), 06-11-2026. Jonas: "Ja!" (projectles 3 maken) en koos in de chat telkens het
     voorstel:
     klas 3MWWE · projectles 3 van *Dalton @ the movies* (lessenplan MWW, § 7: "aftiteling met namen en bron van de muziek,
     checklist, inleveren als link in Classroom"), in de plaats van een les uit het lessenplan; `lesnr` `P3` · lesdag
     do 12 november 2026, 8ste uur (14.35–15.25) · vorige les: projectles 2 (Muziek, tekst en geluid), gegeven op do 29-10;
     de meeste groepen hebben hun clips, titels en muziek in Canva → lesstart = ophalen uit projectles 2; deze les = afwerken,
     aftiteling, nakijken en inleveren · lokaal 18, Windows 11, Canva in Chrome (schoolaccount) + de eigen gsm met de
     Canva-app, zoals projectles 1 en 2 · **20 punten** op het eindproduct, op een korte checklist (Jonas kijkt zelf na in
     Canva; de verbetertool slaat de les over) · **geen werkdocument**: **elke leerling** plakt de link naar het
     Canva-ontwerp van de groep in Classroom (*Toevoegen of maken* › *Link*) en klikt op *Inleveren* · deadline
     **vr 13 november 2026, 20.00 uur** (het eindproduct op vr 13-11, lessenplan § 7) · context *Dalton @ the movies*,
     repository Trailer-DaltonMovies. -->

## 1. Inhoud van het pakket

```text
W10 - Project 3 - MWW - Afwerken en inleveren/
├── index.html              de lespagina: startpagina in beelden · route · één stap · checklist
├── presentatie.html        9 dia's; dia 1 is de vaste startdia "Zo start je"
├── css/style.css, css/slides.css     (projectles 2 + .aftit, ul.punten, .tl3-aftit | .aftit5, .punten7)
├── js/script.js, js/slides.js        (script.js met het blok "Een nieuwe leerling aan dezelfde computer")
├── assets/                 logo "Dalton @ the movies", GO! Dalton Gent, lettertypes (OFL), mascotte Dalton, logo's classroom/docs/lespagina,
│                           stapjes/ (14 schermafbeeldingen: 11 uit projectles 1 en 2, 3 nieuwe van Canva), video/inleveren.mp4
├── lesvoorbereiding.md · dalton-lesfiche.html · lesdoelen.json · classroom.json · README.md
```

**Geen werkdocument, geen zip, geen bronbestanden, geen zelftest, geen codewoord** (Jonas, 06-11-2026): wat beoordeeld wordt, is de trailer in Canva.
De map `werkdocument/` van het sjabloon is weggehaald. De verbetertool slaat de les over (`_tools/verbeteren-uitzonderingen.json`): Jonas kijkt zelf na
in Canva, via de link die elke leerling inlevert, op de checklist van `lesvoorbereiding.md` § 22 (en § 14: wat telt en wat niet).

### 1b. Hoe de lespagina werkt

- **Startpagina**: *Wat heb je nodig?* in drie beelden (de opdracht met **Toevoegen of maken** en **Inleveren**, de lespagina, het Canva-ontwerp met de gsm),
  *Dit maak je vandaag* (de tijdlijn met achteraan de aftiteling), *Na deze les kan je*, *Vast?*.
- **Een leidraad voor groepjes van drie in één gedeeld Canva-ontwerp**, zoals projectles 2: bovenaan elke stap staat wie **monteur** is (A in stap 2, B in
  stap 3, C in stap 4; in stap 5 stelt de eigenaar het delen in en levert iedereen zelf in).
- **Handelingen met stapjes**: start in *Kort* (`data-modus-start="kort"`), *Toon stapjes*. Infokaders: *De checklist van je trailer* (stap 2, de zeven criteria met punten),
  *Waarom een aftiteling?* (stap 3, met een tekening), *Wie mag in beeld?* (stap 4).
- **Stap 5** is de laatste stap: delen en inleveren, met het filmpje *Inleveren* (`assets/video/inleveren.mp4`, uit het sjabloon) en de mascotte *inleveren*. Geen slot en geen zelftest.
- **Extra** (telt niet mee): de voice-over met de Canva-app op de gsm, en de trailer downloaden als mp4 (alleen als Jonas het vraagt).
- **Dia 8** toont de kloktijden van do 12-11, 8ste uur (14.35–15.25), met stap 1 als *samen ✓*; **T** rekent opnieuw. Elke stap heeft dezelfde minuten op de dia, in de Dalton-lesfiche
  en in `lesvoorbereiding.md` (3 + 14 + 7 + 8 + 8 = 40).
- **Mascotte Dalton**: startpagina, stap 5, eindmelding; dia 2, 3, 8 en 9. `data-ai-hulp="uit"`.
- **Route**: stap 1–3 *Afwerken*, stap 4–5 *Nakijken en inleveren*, *Extra*.
- **Nieuwe leerling aan dezelfde computer** (Jonas, 06-11-2026): `js/script.js` wist de vinkjes als de pagina in een ander lesuur wordt geopend dan het laatste (functie `nieuwLesuur`).

## 2. Klaarzetten

### Stap 1 — Publiceren via GitHub Pages

Repository [`jonasdaltongent/Trailer-DaltonMovies`](https://github.com/jonasdaltongent/Trailer-DaltonMovies), Pages op branch `main`, map `/ (root)`.
Lespagina: <https://jonasdaltongent.github.io/Trailer-DaltonMovies/> · dia's: <https://jonasdaltongent.github.io/Trailer-DaltonMovies/presentatie.html>
(het adres staat ook op dia 8 en in `classroom.json` en `lesdoelen.json`). *Status: zie `_index/lessen.md` en `_index/logboek.md`.*

### Stap 2 — De opdracht in Classroom, met de koppeling

Als **concept** in [3MWWE - Informatica](https://classroom.google.com/c/MjUzNjQyOTk0NDFa), onder het onderwerp **Project Dalton @ the movies**.
**Concept gemaakt op 06-11-2026** (titel *Projectles 3 — Afwerken en inleveren*, 20 punten, deadline vr 13-11 20.00 uur, alleen de link). **Ingepland** op 06-11-2026 voor do 12-11 om 14.05 (een half uur vóór de les): Classroom publiceert dan zelf een half uur vóór de les, do 12-11 om 14.05 (`_afspraken/publiceren.md`).

| | Opdracht: **Projectles 3 — Afwerken en inleveren** |
|---|---|
| **Onderwerp** | Project Dalton @ the movies |
| **Bijlage** | alleen de link naar de lespagina (geen werkdocument) |
| **Punten · deadline** | 20 · vrijdag 13 november 2026, 20.00 uur |

Instructietekst (`classroom.json`):

```text
1. Open de lespagina (link): daar staan de stappen en de checklist van je trailer.
2. Je werkt in het Canva-ontwerp van je groep. Je hebt je gsm nodig, met de Canva-app, en oortjes als je die hebt.
3. Iedereen van de groep voegt hier de link naar jullie Canva-ontwerp toe (Toevoegen of maken › Link) en klikt op Inleveren, ten laatste <deadline>.
```

### Stap 3 — Met de hand, als de koppeling niet werkt

Maak in Classroom een opdracht met het onderwerp *Project Dalton @ the movies*, **20 punten**, uiterste inleverdatum **vr 13-11, 20.00 uur**, en voeg met
**Bijvoegen** › **Link** de lespagina toe. Geen werkdocument.

### Afvinklijst vóór de les

Met een **leerlingaccount** nakijken (zie ook § 8). Je scherm wint van de lespagina.

- [ ] **Oortjes** (de mail van projectles 2 vroeg het al): bij het nakijken speelt elke groep de trailer af.
- [ ] **Demo-ontwerp met twee of drie stockvideo's en een nummer uit Canva** in je eigen Canva (Video › Liggende video; bij **+** › **Stockvideo's**), voor de aftiteling, het delen en het inleveren (dia 4).
- [x] Knopnamen van de lege pagina, het tekstvak, **Delen**, het toegangsniveau, **Link kopiëren** en **Downloaden** nagekeken met demoleerling3 (06-11-2026, § 2b); Classroom niet (§ 8).
- [ ] De dia's staan op het bord; de kloktijden kloppen met het lesuur.
- [ ] Het wachtwoord van de computers op het bord (niet op een dia).
- [ ] Jonas weet dat hij de trailers nakijkt in Canva via de ingeleverde links (`lesvoorbereiding.md` § 14 en § 22); de verbetertool doet niets.

### 2b. Nagelezen klikpaden

Gezien op het scherm van het leerlingaccount **demoleerling3** (06-11-2026, Chrome, in het testontwerp *Trailer – De laatste bus*; er is niets gedeeld, verstuurd, opgenomen of
gedownload; de testwijzigingen zijn ongedaan gemaakt). Op de lespagina staan:

- **Een lege pagina achteraan**: in de tijdlijn rechts van de laatste clip het grijze **+** › menu **Uploads** · **Stockvideo's** · **Stockfoto's** · **Leeg**. **Leeg** zet een pagina
  van **5.0 s** achteraan, met een werkbalk **Vervangen** · de duur (**5.0s**) · de achtergrondkleur · **Positie**. In ons testontwerp was ze **zwart** (de pagina neemt de kleur van de andere pagina's over).
- **Tekst op die pagina**: **Tekst** › **Voeg een tekstvak toe** zet het tekstvak op de **geselecteerde** pagina (de nieuwe pagina na het toevoegen).
- **Titel en maker van een nummer**: in de audiotrack toont de balk van het aangeklikte nummer de **titel** en de duur (*Return From the Battlefield • 38.5s*), de **maker** niet. Het knopje
  **⋯** op het nummer en de werkbalk (**Vervangen**, **Briefje**, **Vervagen**, **Beat Sync**, **Bijschriften**) tonen de maker ook niet. Wel de lijst bij **Elementen**: de titel in het zoekvak intypen
  toont het nummer met de maker eronder (*Christian Andersen • 1:55*, label **EDU**). De lespagina zegt dit in stap 3.
- **Delen**: rechtsboven **Delen** › venster **Ontwerp delen**: *Personen met toegang* · **Toegangsniveau** (lijstje: **Alleen jij hebt toegang** · **GO! Dalton Gent** — *Iedereen in GO! Dalton Gent heeft met deze link toegang tot dit ontwerp*) ·
  **Link kopiëren** · pictogrammen **Downloaden**, **Naar leerkracht versturen**, **Weergave**, **Google Classroom**, **Herinnering**, **LMS**, **Kopiëren naar klembord**, **Alles zien**.
  Ook bovenaan in de balk: de knop **Naar leerkracht versturen** (niet geklikt; de lespagina zegt in stap 5 dat we via Classroom inleveren).
- **Downloaden als MP4**: **Delen** › **Downloaden** › **Bestandstype** *MP4-video* (*Aanbevolen*) · **Kwaliteit** *480p · 720p · 1080p · 4K* · **Downloaden**; met de melding *Video's met audio uit onze populaire
  muziekbibliotheek mogen alleen worden gebruikt voor persoonlijke en niet-commerciële doeleinden*. Niet gedownload. Het klikpad is **Delen** › **Downloaden**, niet *Extra*.
- **Classroom**: **Toevoegen of maken** › **Link** staat in de Nederlandse help ([6020285](https://support.google.com/edu/classroom/answer/6020285?hl=nl), gelezen 06-11-2026:
  "Klik onder Jouw werk op Toevoegen of maken › selecteer Google Drive, Link of Bestand. Selecteer de bijlage of voer de URL in voor een link en klik op Toevoegen"). Op een leerlingscherm niet gezien (§ 8).

## 3. Het verloop van de les

Zie `lesvoorbereiding.md` § 15–17 en de notities bij elke dia. In het kort: dia 1 (aanmelden; oortjes), dia 2 lesstart (*muziek te luid*), dia 3 *wat telt* (de checklist met punten),
dia 4 **demo live** (aftiteling, delen, inleveren), dia 5 de tekening van de aftiteling, dia 6 controle (*wat staat er bij de muziek?*), dia 7 *Iedereen doet stap 1* (3'), dia 8 keuzewerktijd,
dia 9 de exitvraag (*wat lever je in?*).

- **Eerste rondgang (stap 2):** eerst de groepen die in projectles 2 achterstonden. Loopt het recept, stopt de trailer vóór het einde?
- **Tweede rondgang (stap 4–5):** staat de muziek in de aftiteling met titel en maker? Heeft **elk** groepslid de link ingeleverd? Staat het toegangsniveau op *GO! Dalton Gent*?
- Mondeling op het einde: *lever in, ook als het nog niet perfect is; tot vrijdag 20.00 uur mag je de trailer nog verbeteren: de link blijft dezelfde.*

## 4. Verbetersleutel

Jonas kijkt de trailer na in Canva, via de ingeleverde link, op de zeven criteria van `lesvoorbereiding.md` § 22 (20 punten), met § 14 (wat telt en wat niet). De punten per criterium en de aftrek staan daar; hier
wat je per criterium moet zien:

| Criterium | Wat je verwacht te zien |
|---|---|
| 1. Het trailerrecept (4) | de vijf blokken herkenbaar; het einde van het verhaal staat er niet in |
| 2. Montage (3) | geen zwarte of lege stukken, geen rommel aan het begin of einde van een clip |
| 3. De titel (2) | de titel van de film in beeld, groot, een kleur die afsteekt, lang genoeg om te lezen |
| 4. Overgangen (2) | weinig en dezelfde soort; harde overgangen in de spanning |
| 5. Muziek en geluid (3) | muziek uit Canva (geen geüpload liedje), stemmen verstaanbaar, vervaging of logisch einde |
| 6. De aftiteling (3) | een pagina achteraan met de voornamen van de drie groepsleden en de muziek: titel, maker en *Canva* |
| 7. Ingeleverd (3) | een werkende link naar het ontwerp van de groep, door de leerling zelf, vóór de deadline |

### Essentiële fouten — geef hier altijd feedback op

- Een liedje van Spotify of YouTube geüpload in plaats van muziek uit Canva (auteursrecht).
- Iemand herkenbaar in beeld die niet weet dat de trailer getoond wordt (portretrecht).
- Een link met *Mag bewerken* voor iedereen van de school, of een link die om toegang vraagt (toegangsniveau *Alleen jij hebt toegang*).
- Alleen *Muziek van Canva* in de aftiteling, zonder titel en maker.

## 5. Schermafbeeldingen (optioneel)

`assets/stapjes/`: 11 beelden uit projectles 1 en 2 (Canva en de gsm) en 3 nieuwe van 06-11-2026 (`canva-delen-toegang.png`, `canva-link-kopieren.png`, `canva-downloaden.png`): `zoom`-opnames van Claude in Chrome met het
profiel van demoleerling3 (Profile 8), bijgesneden met één rood kader met witte rand (Pillow); geen namen, geen e-mailadressen. De tekeningen van Classroom (de opdracht met **Toevoegen of maken**, de tabbladen)
zijn HTML en CSS, niet gezien op een leerlingscherm.

## 6. Het materiaal opnieuw maken

Er is geen script: alles is HTML en CSS. De kloktijden: `python3 _tools/zet_lesmomenten.py "<lesmap>"` (zet `2026-11-12/14.35/15.25/3MWWE/8`).

## 7. Leerplandoelen in je jaaroverzicht

`lesdoelen.json` (`klasgroepen` `3 MWW`): `BV2_04.02` (kern), `BV2_04.04`, `BV2_04.03`, `BV2_05.01` (ondersteunend). De pre-push hook schrijft ze naar het jaaroverzicht.

## 8. Wat nog moet blijken in de klas

Nagekeken op 06-11-2026 met het leerlingaccount demoleerling3 (computer, Canva); Classroom kon niet (het Google-profiel vroeg om opnieuw in te loggen: dat doet alleen Jonas). **Niet te testen of nog niet gezien:**

1. **Classroom, leerling: *Toevoegen of maken* › *Link*.** Naam van de knop in het venster (de help zegt *Toevoegen*, Jonas schreef *Link toevoegen*): de lespagina zegt "klik op de knop die de link toevoegt".
   Weigert Classroom een Canva-link, of toont hij hem als een kaart met de titel van het ontwerp? De tekeningen in stap 5 zijn niet naar een scherm gemaakt.
2. **De rol *Mag bekijken*.** In het lijstje van het toegangsniveau staat geen rol; of er na het kiezen van *GO! Dalton Gent* nog een rol te kiezen is (en wat de standaard is), zagen we niet: het wijzigen van het
   toegangsniveau van het testontwerp werd niet toegestaan, dus de link bleef op *Alleen jij hebt toegang*. Staat de standaard op bewerken? Dan moet stap 5 het zeggen. De lespagina zegt: "staat er een rol naast, kies **Mag bekijken**".
3. **Kan een groepslid dat geen eigenaar is het toegangsniveau wijzigen?** Niet na te gaan met één testaccount. De lespagina laat de **eigenaar** het toegangsniveau instellen en iedereen de link kopiëren.
4. **De kleur van de lege pagina**: in ons testontwerp zwart; in een nieuw ontwerp mogelijk wit. De lespagina zegt "zwart of wit, volgens je ontwerp".
5. **Waar staat de maker van een nummer?** Niet in de tijdlijn: alleen via **Elementen** (de titel intypen). Lukt dat bij elk nummer? Heeft een groep in projectles 2 de maker al genoteerd?
6. **De knop *Naar leerkracht versturen*** in Canva (balk en Delen): wat hij doet, is niet getest. Gaan leerlingen hem gebruiken in plaats van Classroom? De lespagina zegt: "we leveren in via Classroom, niet via die knop".
7. **Een tekstvak op de nieuwe pagina**: kwam in onze test op de geselecteerde pagina. Als de afspeelkop er niet staat?
8. **Downloaden als MP4** (Extra): niet uitgevoerd; hoe lang het duurt en hoe groot het bestand wordt is niet gezien.
9. **De Canva-app op de gsm** (clip toevoegen, voice-over): zoals in projectles 1 en 2 niet in de app gezien.
10. Heeft elke groep een afgewerkt ontwerp uit projectles 2, kloppen de tijden (stap 2 in 14 minuten, stap 3 in 7), en lukt het wisselen van monteur?
