# AGENTS.md

Denne filen gir veiledning til AI-agenter som jobber med innhold i dette repositoryet.

> [!important] Dette er en TEMPLATE
> Dette er en mal for en ungdomsbedrifts kunnskapsbase. Enkelte seksjoner under må tilpasses når bedriften fyller ut sin informasjon. Seksjoner markert med 🔧 skal oppdateres av agent/team etter hvert som bedriften tar form.

---

## Prosjektoversikt

Dette er en kunnskapsbase for ungdomsbedriften **[BEDRIFTSNAVN - FYLL INN]**.

**Formål:** Strukturere dokumentasjon, læring og prosjektledelse ved hjelp av Obsidian og Markdown.

**Status:** 🔧 _[Ny/Oppstartsfase/Aktiv/Avsluttet]_ - Oppdater dette etter hvert som bedriften utvikler seg.

### 🤖 Agent-oppgave: Første gangs oppsett

Når teamet åpner denne kunnskapsbasen første gang, hjelp dem med:

1. **Identifiser bedriftsnavn** - Spør om bedriftsnavn og oppdater `[BEDRIFTSNAVN]` i denne filen og `index.md`
2. **Kartlegg team** - Fyll ut seksjonen "Teamstruktur" under basert på faktiske roller
3. **Definer tjenester** - Hjelp dem fylle ut `02-marked/pris-og-tjenester.md`
4. **Opprett første mål** - Veilede utfylling av `00-handbok/formaal-og-maal.md`
5. **Oppdater denne filen** - Fjern placeholder-tekst og erstatt med faktisk informasjon

---

## Repositorystruktur og arkitektur

Repositoryet følger en nummerert mappestruktur for logisk organisering:

- `00-handbok/` - Permanent referansemateriale (formål, roller, beslutninger)
- `01-bedrift/` - Bedriftsinformasjon og profil
- `02-marked/` - Salg, leads og prissetting
- `03-prosjekter/` - Kundeprosjekter og leveranser
- `04-okonomi/` - Budsjett og økonomisk oppfølging
- `05-laering/` - Læringslogger og retrospektiver (VIKTIG for UB!)
- `06-moter/` - Teammøter og statusoppdateringer
- `07-research/` - Markedsanalyse og innsikter
- `08-ressurser/` - Verktøy og ressurser
- `_templates/` - Obsidian-maler for konsistent dokumentasjon

### Prioritet ved oppstart

**Uke 1-2 (Kritisk):**
- `00-handbok/formaal-og-maal.md`
- `00-handbok/roller-og-ansvar.md`
- `02-marked/pris-og-tjenester.md`
- `04-okonomi/budsjett.md`

**Løpende (Viktig):**
- `05-laering/laeringslogger/` - UKENTLIG
- `06-moter/` - Etter hvert møte
- `02-marked/leads.md` - Ved nye henvendelser

**Senere (Når relevant):**
- `03-prosjekter/` - Når første kunde kommer
- `07-research/` - Når de trenger markedsinnsikt

---

## Dokumentasjonsmønstre

### Frontmatter-standarder

Alle Markdown-filer bruker YAML frontmatter med disse vanlige feltene:

```yaml
---
title: "Tittel på dokumentet"
date: "YYYY-MM-DD"
owner: "Navn på ansvarlig"
status: "utkast|godkjent|levende-dokument|arkivert"
tags: ["kategori", "type"]
type: "meeting|project|learning|decision|etc"
summary: "2-3 setninger som oppsummerer innholdet"
---
```

**Viktige felt:**
- `title` - Alltid påkrevd
- `summary` - VELDIG viktig for AI-søk og oversikt
- `owner` - Hvem er ansvarlig for å oppdatere denne?
- `status` - Hvor langt er vi kommet?

### 🤖 Agent-oppgave: Frontmatter-validering

Når du hjelper med å opprette eller redigere dokumenter:
- ✅ Sjekk at frontmatter er komplett
- ✅ Generer `summary` hvis den mangler
- ✅ Foreslå passende `tags` basert på innhold
- ✅ Sett `owner` til den som ber om hjelp (hvis kjent)

---

## Malsystem

Prosjektet bruker 9 Obsidian-maler i `_templates/`:

| Template | Bruksområde | Frekvens |
|----------|-------------|----------|
| `motenotat.md` | Teammøter | Etter hvert møte |
| `laeringslogg.md` | Personlig refleksjon | Ukentlig (anbefalt) |
| `prosjekt-oversikt.md` | Nye kundeprosjekter | Ved signert avtale |
| `kunde-intervju.md` | Kartlegging av behov | Før tilbud sendes |
| `leveranseplan.md` | Prosjektplanlegging | Etter avtale signert |
| `ukerapport.md` | Ukentlig status | Hver fredag (valgfritt) |
| `beslutning.md` | Viktige valg | Når nødvendig |
| `kreativ-brief.md` | Designoppdrag | Ved behov |
| `retrospektiv.md` | Team-læring | Etter prosjektavslutning |

### 🤖 Agent-oppgave: Template-assistanse

Når brukere skal lage nytt innhold:
1. **Foreslå riktig template** basert på hva de beskriver
2. **Pre-fyll kjente felter** (navn, dato, prosjektnavn)
3. **Gi kontekstuelle tips** fra lignende eksempler (se [lions-kristiansand](https://github.com/[org]/lions-kristiansand))
4. **Valider** at alle påkrevde seksjoner er fylt ut

---

## Lenkingkonvensjon

Bruker Obsidians `[[wikilink]]`-syntaks for interne forbindelser mellom dokumenter.

**Eksempler:**
- `[[index|Hovedside]]` - Lenke til hovedside med eget navn
- `[[00-handbok/formaal-og-maal]]` - Lenke til dokument i annen mappe
- `[[03-prosjekter/kundenavn/oversikt|Prosjekt]]` - Lenke til prosjekt

### 🤖 Agent-oppgave: Link-vedlikehold

- Når du oppretter nye dokumenter, **foreslå relevante lenker**
- Hvis du refererer til andre deler av basen, **bruk wikilinks**
- Oppdater index-filer når nye dokumenter opprettes

---

## 🔧 Teamstruktur (SKAL FYLLES UT)

> [!warning] Denne seksjonen må oppdateres!
> Når teamet er definert, oppdater denne seksjonen med faktiske navn og roller.

**Mal for utfylling:**

```markdown
Prosjektet følger en rollebasert organisering:
- **Daglig leder**: [Navn] - Koordinering og prioritering
- **Teknisk ansvarlig**: [Navn] - Utvikling og tekniske valg
- **Salg/marked**: [Navn] - Leads og kundeforhold
- **Designer**: [Navn] - Merkevare og visuell identitet
- **Økonomi**: [Navn] - Budsjett og fakturering
- **[Annen rolle]**: [Navn] - [Ansvar]
```

**Faktisk team:**

_[Agent: Hjelp teamet med å fylle ut denne seksjonen basert på 00-handbok/roller-og-ansvar.md]_

### 🤖 Agent-oppgave: Team-synkronisering

- Hold denne seksjonen synkronisert med `00-handbok/roller-og-ansvar.md`
- Når roller endres, oppdater begge steder
- Referér til riktig person når du foreslår ansvarlig for oppgaver

---

## 🔧 Tjenester og fokusområder (SKAL FYLLES UT)

> [!warning] Oppdater basert på hva bedriften faktisk tilbyr

**Eksempler (slett og erstatt med faktisk info):**
- Nettsider
- Grafisk design
- SoMe-innhold
- Foto/video
- Annet: ___

**Faktiske tjenester:**

_[Agent: Hent fra 02-marked/pris-og-tjenester.md når den er fylt ut]_

### 🤖 Agent-oppgave: Tjeneste-kontekst

- Bruk denne informasjonen når du hjelper med salg og tilbud
- Foreslå bare tjenester bedriften faktisk kan levere
- Vurder teamets kompetanse (fra roller-og-ansvar) når du gir råd

---

## Vanlige arbeidsflyter

### Legge til nytt innhold

1. Bruk passende mal fra `_templates/`
2. Fyll ut frontmatter-metadata
3. Opprett interne lenker med `[[side-navn]]`-syntaks
4. Link fra relevante indekssider

### Prosjektdokumentasjon (kunde-flyt)

```
Lead inn → 02-marked/leads.md
    ↓
Kundeintervju → Bruk kunde-intervju template
    ↓
Tilbud sendt → Lagre i 02-marked/tilbud/
    ↓
Vunnet! → Opprett mappe i 03-prosjekter/kundenavn/
    ↓
Prosjektoversikt → Bruk prosjekt-oversikt template
    ↓
Leveranseplan → Bruk leveranseplan template
    ↓
Møter → Dokumenter med motenotat template
    ↓
Levering → Fakturer (04-okonomi/fakturaer/)
    ↓
Retrospektiv → Bruk retrospektiv template (05-laering/)
```

### 🤖 Agent-oppgave: Prosjekt-assistanse

Ved nye kundeprosjekter:
1. Opprett mappestruktur: `03-prosjekter/[kunde-slug]/`
2. Generer `oversikt.md` fra template
3. Foreslå realistisk leveranseplan
4. Oppdater `02-marked/leads.md` (flytt til "Vunnet")
5. Minn om å opprette retrospektiv når prosjektet er ferdig

### Læringsdokumentasjon

- **Ukentlig refleksjon** med `_templates/laeringslogg.md` (VIKTIG for UB!)
- **Teamretrospektiver** med `_templates/retrospektiv.md`
- **Beslutningssporing** i `00-handbok/beslutningslogg.md`

### 🤖 Agent-oppgave: Lærings-påminnelse

- Hvis ingen læringslogger siste 7 dager → foreslå å skrive en
- Etter avsluttet prosjekt → påminn om retrospektiv
- Ved viktige beslutninger → foreslå logging i beslutningslogg

---

## Terminologi og kontekst

Dette er et norsk prosjekt med spesifikk ungdomsbedrift-terminologi:

**Grunnleggende:**
- **UB** = Ungdomsbedrift
- **UE** = Ungt Entreprenørskap (organisasjonen som driver UB-programmet)
- **DL** = Daglig leder
- **PL** = Prosjektleder

**Salg:**
- **Lead** = Potensiell kunde
- **Depositum** = Forskuddsbetaling (vanligvis 50%)
- **Pro bono** = Gratis arbeid for ideelle organisasjoner

**Teknisk:**
- **SoMe** = Sosiale medier
- **Wireframe** = Enkel skisse av design
- **MVP** = Minimum Viable Product

**Se `ordliste.md` for fullstendig oversikt**

### 🤖 Agent-oppgave: Språk og terminologi

- Bruk **norsk** som primærspråk i all dokumentasjon
- Bruk etablerte forkortelser (UB, DL, SoMe) konsekvent
- Forklar fagbegreper første gang de brukes
- Referér til `ordliste.md` hvis usikker

---

## Git og versjonskontroll

Repositoryet er et standard Git-repo.

**Commit-meldinger:**
- Beskrivende: "Oppdater budsjett med Lions-inntekt"
- Ikke: "Update file"

### 🤖 Agent-oppgave: Endringshåndtering

Når du hjelper med endringer:
- ❌ **ALDRI commit automatisk** uten brukerbekreftelse
- ✅ Foreslå passende commit-melding
- ✅ Vis hvilke filer som endres
- ✅ Advar hvis viktige filer (budsjett, avtaler) endres

---

## Obsidian-integrasjon

Dette prosjektet er optimalisert for Obsidian med:
- `.obsidian/`-konfigurasjon for konsistent lenkeatferd
- Malsystem for rask dokumentopprettelse
- Grafvisning for å visualisere kunnskapssammenhenger
- Asset-håndtering i `assets/`-mappe (bilder, PDF-er)

**Anbefalte plugins (valgfritt):**
- Templater (avanserte templates)
- Dataview (generere oversikter)
- Calendar (visualisere tidsbaserte notater)

---

## AI-integrasjonsnotater

Kunnskapsbasen er spesielt designet for AI-assistentintegrasjon:

✅ **Gjør:**
- Bruk strukturert metadata for kontekstforståelse
- Følg etablerte maler for konsistens
- Referér til `ordliste.md` for terminologi
- Foreslå lenker til relaterte dokumenter
- Hjelp med å holde informasjon synkronisert (f.eks. budsjett vs faktiske tall)
- Generer forslag basert på templates
- Påminn om beste praksis (ukentlige læringslogger, møtenotater)

❌ **Ikke gjør:**
- Endre etablert struktur (00-08 mappenavn)
- Opprette filer utenfor definerte mapper
- Endre frontmatter-standarder
- Bruke engelsk uten grunn (dette er et norsk prosjekt)
- Commit endringer uten brukerbekreftelse
- Slette historiske dokumenter (bruk `status: arkivert` i stedet)

### 🤖 Spesielle hensyn for UB-kontekst

**Dette er en ungdomsbedrift:**
- Elevene er 16-19 år
- Dette er et læringsprosjekt (ikke profesjonell virksomhet)
- Fokus på læring > profitt
- Refleksjon og dokumentasjon er VIKTIG for karakteren
- Vær pedagogisk og oppmuntrende

**Hjelp med:**
- Forklare konsepter (budsjett, prissetting, prosjektledelse)
- Forenkle komplekse oppgaver
- Gi eksempler fra lignende UB-er
- Minn om læringsmål (ikke bare forretningsmål)

---

## 🔧 Meta: Oppdatering av denne filen

Denne AGENTS.md skal oppdateres etter hvert som bedriften utvikler seg.

### Når oppdatere?

- **Første uke:** Fyll ut bedriftsnavn, team, tjenester
- **Etter første prosjekt:** Legg til lærdommer i "Vanlige arbeidsflyter"
- **Ved nye rutiner:** Dokumenter i "Arbeidsflyter"
- **Ved verktøyendringer:** Oppdater "Obsidian-integrasjon"

### 🤖 Agent-oppgave: AGENTS.md vedlikehold

- **Foreslå oppdateringer** når du oppdager utdatert informasjon
- **Fjern placeholder-tekst** når faktisk info er fylt ut
- **Legg til bedriftsspesifikke tips** basert på deres arbeidsmåte
- **Hold seksjoner synkronisert** med faktiske filer (roller, tjenester, osv.)

**Eksempel på oppdatering:**

Hvis teamet bestemmer seg for å alltid ha møte hver mandag kl. 16:00, oppdater "Vanlige arbeidsflyter" med dette.

---

## Inspirasjon og eksempler

For å se et fullstendig utfylt eksempel, sjekk [lions-kristiansand](https://github.com/[org]/lions-kristiansand).

**Bruk lions-kristiansand til:**
- Se hvordan læringslogger skal se ut
- Eksempler på møtenotater
- Komplett prosjektdokumentasjon
- Budsjett-eksempler

---

Ved arbeid med dette repositoryet, prioriter å:
1. Opprettholde etablerte dokumentasjonsmønstre
2. Bruke norsk språk og UB-terminologi
3. Følge template-systemet konsekvent
4. Fokusere på læring (ikke bare forretning)
5. Oppdatere denne AGENTS.md når bedriften utvikler seg

**Lykke til med ungdomsbedriften! 🚀**
