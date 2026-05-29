<div align="center">

# TheCore4

## FitLife Digital

**Eksamenscase i digital transformation, arkitektur og brugercentreret udvikling**

*Fra analog fitnesskæde til hybrid digital platform*

<br>

![Semester](https://img.shields.io/badge/Semester-4.-0A7EA4?style=for-the-badge)
![Uddannelse](https://img.shields.io/badge/Uddannelse-IT--arkitektur-164B7A?style=for-the-badge)
![Skole](https://img.shields.io/badge/Erhvervsakademi-Aarhus-1B263B?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Proof%20of%20Concept-2E8B57?style=for-the-badge)

</div>

---

## Om projektet

**FitLife Digital** er vores tværfaglige eksamenscase på 4. semester på **IT-arkitektur** ved **Erhvervsakademi Aarhus**. Projektet undersøger, hvordan en lokalt forankret og overvejende analog fitnesskæde kan transformeres til en **hybrid digital fitnessplatform**, uden at miste det nærvær, de personlige relationer og den lokale identitet, der skaber værdi for brugerne.

Projektet samler fagene **Enterprisearkitektur**, **IT-arkitektur**, **Brugerinddragelse** og **Agil udvikling** i én samlet løsning, hvor forretningsforståelse, brugerbehov og teknisk implementering kobles tæt sammen.

## Den centrale idé

FitLife Digital tager afsæt i et centralt spørgsmål:

> Hvordan kan digitale services styrke træningsoplevelsen før, under og efter træning, uden at erstatte det fysiske fællesskab?

Med udgangspunkt i interviews, brugerrejser, prototypearbejde og teknisk udvikling har vi designet og realiseret et **Proof of Concept**, der fokuserer på digital booking af hold og personlig træning.

## Hvad løsningen adresserer

Platformen er udviklet med fokus på at skabe:

- bedre overblik over træningsmuligheder og bookinger
- mere fleksibel og brugervenlig booking af hold og personlig træning
- tydelig digital understøttelse af brugerrejsen
- en mere sammenhængende oplevelse mellem fysisk center og digitale services

Løsningen er bevidst afgrænset til den mest værdiskabende del af brugerrejsen: **bookingflowet**. Her demonstrerer projektet, hvordan manuelle og fragmenterede processer kan omsættes til en samlet digital oplevelse med fokus på brugervenlighed, arkitektur og forretningsmæssig relevans.

## Arkitektur og services

PoC'en er bygget som en **microservice-baseret løsning**, hvor ansvaret er fordelt på tydelige services:

- **FitLifeApp** fungerer som samlet brugerflade og BFF-lag
- **IDPService** håndterer login, autentificering og tokenudstedelse
- **UserService** ejer brugerdata, profiler og relaterede oplysninger
- **CatalogService** ejer træningskataloget, herunder hold, sessioner og træningstyper
- **BookingService** håndterer bookinger, afmeldinger, ventelister og bookinghistorik

Arkitekturen kombinerer **synkron servicekommunikation** og **asynkron hændelsesdrevet integration**, så platformen kan understøtte en mere skalerbar, tydelig og robust ansvarsfordeling.

## Akademisk ramme

Projektet er udviklet som et tværfagligt eksamensprojekt med afsæt i:

- **Brugerinddragelse og design**, herunder interviews, brugerrejser, prototyping og evaluering
- **Enterprisearkitektur**, herunder målbillede, governance, principper og transition
- **IT-arkitektur og infrastruktur**, herunder microservices, deployment og servicekommunikation
- **Agil udvikling**, herunder iterativ udvikling, test, TDD, CI og løbende feedback

## Scope og status

FitLife Digital er et **Proof of Concept** og demonstrerer de centrale arkitekturvalg og den vigtigste brugerrejse i løsningen. Projektet validerer retningen for en fremtidig digital platform, men er ikke en færdig produktionsløsning.

For at bevæge løsningen mod produktion vil der blandt andet skulle arbejdes videre med:

- drifthærdning og monitorering
- yderligere sikkerhed og integrationshåndtering
- større datagrundlag og forretningsmæssig modning
- videreudvikling af brugeroplevelsen uden for bookingflowet

## Teamet bag

**TheCore4** består af:

- Sarah Fahlén
- Frederik Søgaard Andersen
- Nikolaj Solvang
- Mohammad Haj

---

<div align="center">

### TheCore4
*FitLife Digital · 4. semester · IT-arkitektur · Erhvervsakademi Aarhus*

</div>
