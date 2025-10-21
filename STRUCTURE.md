# Kunnskapsbase Struktur

Dette dokumentet forklarer den **potensielle** strukturen for ungdomsbedriftens kunnskapsbase.

> [!important] Progressiv oppbygging
> Mapper og filer opprettes **on-demand** av agenten når de faktisk trengs.
> IKKE opprett alt på forhånd - det skaper bare støy og forvirring.

---

## Mappestruktur (potensiell)

### 00-handbok/ 📚

**Prioritet:** 🔴 KRITISK
**Opprett når:** Første samtale med agenten
**Formål:** Permanent referansemateriale

**Inneholder:**
- `index.md` - Oversikt over håndboken
- `formaal-og-maal.md` - Hvorfor eksisterer vi? Hva skal vi oppnå?
- `roller-og-ansvar.md` - Hvem gjør hva i teamet?
- `beslutningslogg.md` - Append-only logg over viktige valg

**Typisk tidspunkt:** Dag 1
**Trigger:** Student spør "Hvor begynner vi?" eller "Hva er første steg?"

**Agent skal:**
1. Spørre om bedriftsnavn
2. Spørre om formål/mål
3. Kartlegge teammedlemmer og roller
4. Opprette mappe og fylle ut med faktiske svar

---

### 01-bedrift/ 🏢

**Prioritet:** 🟡 LAV (kan vente)
**Opprett når:** Trenger "om oss" til pitch/nettside
**Formål:** Bedriftsprofil og identitet

**Inneholder:**
- `index.md` - Oversikt
- `om-oss.md` - Hvem vi er, hva vi gjør
- `visuell-profil.md` - Logo, farger, fonts (valgfritt)
- `verdigrunnlag.md` - Verdier og prinsipper (valgfritt)

**Typisk tidspunkt:** Uke 2-4
**Trigger:** Student sier "Vi trenger å lage om oss-side" eller "Vi skal pitche"

---

### 02-marked/ 📈

**Prioritet:** 🔴 KRITISK
**Opprett når:** Første lead eller ved prissetting
**Formål:** Salg og markedsføring

**Inneholder:**
- `index.md` - Oversikt
- `leads.md` - Potensielle kunder (tabell)
- `pris-og-tjenester.md` - Hva tilbyr vi og til hvilken pris?
- `tilbud/` - Undermappe for sendte tilbud (opprett ved behov)
  - `YYYY-MM-DD-kundenavn.md`

**Typisk tidspunkt:** Uke 1-2
**Trigger:**
- "Vi har fått en henvendelse"
- "Hva skal vi ta betalt?"
- "Hjelp meg sende tilbud"

**Agent skal:**
1. Først opprette `leads.md` og `pris-og-tjenester.md`
2. Tilbud-mappen opprettes først når faktisk tilbud skal sendes

---

### 03-prosjekter/ 🚀

**Prioritet:** 🟠 HØY (når relevant)
**Opprett når:** Første kunde vunnet
**Formål:** Kundeprosjekter og leveranser

**Struktur:**
```
03-prosjekter/
├── index.md
└── [kundenavn]/           # Opprett per kunde
    ├── oversikt.md        # Hovedfil
    ├── avtale.md
    ├── leveranseplan.md
    ├── kreativ-brief.md   # Hvis relevant
    └── moter/             # Kundemøter
        └── YYYY-MM-DD-mote.md
```

**Typisk tidspunkt:** Uke 2-8 (varierer mye)
**Trigger:** "Vi har fått en kunde!" eller "Avtale signert"

**Agent skal:**
1. Opprette `03-prosjekter/` mappen
2. Opprette `03-prosjekter/index.md`
3. Opprette `03-prosjekter/[kunde-slug]/` basert på kundenavn
4. Fylle ut `oversikt.md` med info fra samtalen
5. Opprette andre filer etter behov (avtale, leveranseplan)

---

### 04-okonomi/ 💰

**Prioritet:** 🟠 HØY
**Opprett når:** Budsjettplanlegging eller første faktura
**Formål:** Økonomi og regnskap

**Inneholder:**
- `index.md` - Oversikt
- `budsjett.md` - Årlig budsjett
- `fakturaer/` - Sendte fakturaer (opprett ved behov)
  - `YYYY-MM-DD-kunde.md`

**Typisk tidspunkt:** Uke 1 (budsjett) eller ved første faktura
**Trigger:**
- "Vi må lage budsjett"
- "Hvordan sender vi faktura?"

**Agent skal:**
1. Først opprette `budsjett.md` (vanligste)
2. Fakturaer-mappen opprettes når første faktura skal sendes

---

### 05-laering/ 🎓

**Prioritet:** 🔴 KRITISK (for UB-karakter!)
**Opprett når:** Første refleksjon eller retrospektiv
**Formål:** Personlig og team-læring

**Inneholder:**
- `index.md` - Oversikt og tips
- `laeringslogger/` - Personlige refleksjoner
  - `YYYY-MM-DD-navn-tema.md`
- `retrospektiver/` - Team-refleksjoner
  - `YYYY-MM-DD-periode.md`

**Typisk tidspunkt:** Uke 1 (første læringslogg), etter prosjekter (retro)
**Trigger:**
- "Jeg må skrive læringslogg"
- "Vi skal ha retrospektiv"
- Agent påminner: "Ingen læringslogger siste uka - vil du skrive en?"

**Agent skal:**
1. Oppmuntre til ukentlige læringslogger
2. Foreslå retrospektiv etter hvert prosjekt
3. Gi tips til god refleksjon

---

### 06-moter/ 🤝

**Prioritet:** 🟠 HØY
**Opprett når:** Første teammøte
**Formål:** Interne møter og status

**Inneholder:**
- `index.md` - Møterutiner
- `YYYY-MM-DD-motenavn.md` - Individuelle møtenotater

**Typisk tidspunkt:** Uke 1-2
**Trigger:** "Vi skal ha møte" eller "Hjelp meg dokumentere møtet"

**Merk:** Kundemøter ligger under respektive prosjekter i `03-prosjekter/[kunde]/moter/`

---

### 07-research/ 🔍

**Prioritet:** 🟡 MEDIUM
**Opprett når:** Trenger markedsanalyse
**Formål:** Undersøkelser og innsikter

**Inneholder:**
- `index.md` - Oversikt
- `konkurransekart.md` - Hvem konkurrerer vi mot?
- `verktoyvalg.md` - Hvilke verktøy bruker vi?
- `kunde-intervjuer/` - Kundesamtaler
  - `YYYY-MM-DD-kundenavn.md`

**Typisk tidspunkt:** Uke 2-4
**Trigger:**
- "Hvem er konkurrentene våre?"
- "Hvilke verktøy skal vi bruke?"

---

### 08-ressurser/ 🛠️

**Prioritet:** 🟡 LAV
**Opprett når:** Trenger samling av verktøy/lenker
**Formål:** Ressurser og hjelpemidler

**Inneholder:**
- `index.md` - Oversikt med lenker
- Eventuelt andre ressursfiler

**Typisk tidspunkt:** Uke 3-8
**Trigger:** "Hvor finner vi...?" eller "Kan du lage en ressursliste?"

---

## Typisk progresjon

### Uke 1: Grunnmuren
```
✅ 00-handbok/formaal-og-maal.md
✅ 00-handbok/roller-og-ansvar.md
✅ 02-marked/pris-og-tjenester.md
✅ index.md (oppdatert med lenker)
```

### Uke 2-3: Aktivitet starter
```
✅ 02-marked/leads.md (første lead)
✅ 06-moter/ (første møtenotat)
✅ 05-laering/laeringslogger/ (første refleksjon)
✅ 04-okonomi/budsjett.md
```

### Uke 4-8: Første kunde
```
✅ 03-prosjekter/[kunde]/oversikt.md
✅ 03-prosjekter/[kunde]/avtale.md
✅ 04-okonomi/fakturaer/ (første faktura)
✅ 02-marked/tilbud/ (hvis sendt tilbud)
```

### Senere: Modenhet
```
✅ 05-laering/retrospektiver/ (etter prosjekt)
✅ 07-research/ (når relevant)
✅ 01-bedrift/ (hvis nødvendig)
✅ 08-ressurser/ (hvis nyttig)
```

---

## For agenter/AI

### Opprettelsesprotokoll

**ALLTID:**
1. Sjekk om mappe eksisterer før oppretting
2. Opprett `index.md` først i nye mapper
3. Bruk templates fra `_templates/` når relevant
4. Fyll ut med FAKTISK data fra samtalen (ikke placeholder)
5. Oppdater hovedfilen `index.md` med ny seksjon

**ALDRI:**
- Opprett alle mapper på forhånd
- Lag tomme placeholder-filer
- Opprett mapper "for sikkerhets skyld"
- Kopier boilerplate uten faktisk innhold

### Eksempel: Riktig vs Feil

❌ **FEIL:**
```
Student: "Hva skal jeg gjøre først?"
Agent: *Oppretter alle 8 mapper med tomme filer*
```

✅ **RIKTIG:**
```
Student: "Hva skal jeg gjøre først?"
Agent: "La oss starte med grunnlaget. Hva heter bedriften?"
Student: "TechKids AS"
Agent: "Hva er hovedformålet med TechKids?"
Student: "Vi skal lage apper for barn"

*Agent oppretter:*
- 00-handbok/index.md
- 00-handbok/formaal-og-maal.md (FYLT med faktisk info)

Agent: "Flott! Formål er dokumentert. Hvem er i teamet?"
[... fortsetter progressivt ...]
```

---

## For lærere/veiledere

**Forvent at ALLE bedrifter vil ha:**
- ✅ `00-handbok/` (formål, roller)
- ✅ `02-marked/` (leads, priser)
- ✅ `06-moter/` (møtenotater)

**De fleste vil ha:**
- ✅ `03-prosjekter/` (minst ett prosjekt)
- ✅ `04-okonomi/` (budsjett)
- ✅ `05-laering/` (læringslogger - PÅKREVD for karakter!)

**Noen vil ha:**
- `01-bedrift/` (hvis de lager nettside/pitch)
- `07-research/` (hvis ambisiøse med analyse)
- `08-ressurser/` (hvis de samler mye verktøy)

**Vurderingskriterier:**
- Er `05-laering/` brukt regelmessig? (Kritisk for UB!)
- Er `00-handbok/` fylt ut med reflekterte mål?
- Er prosjekter godt dokumentert i `03-prosjekter/`?

---

## Lenker

- **Mal-eksempel:** Se [lions-kristiansand](https://github.com/[org]/lions-kristiansand) for fullstendig utfylt eksempel
- **Templates:** Alle maler ligger i `_templates/`
- **Onboarding:** Se `ONBOARDING.md` for step-by-step guide
- **Agent-instruksjoner:** Se `AGENTS.md` for detaljert AI-veiledning
