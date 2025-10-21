# Ungdomsbedrift - Kunnskapsbase Template

**En minimal, progressiv kunnskapsbase-template for ungdomsbedrifter.**

> [!important] Progressive struktur
> Dette er IKKE en ferdig-utfylt kunnskapsbase. Mapper og filer opprettes **etter behov** når bedriften vokser.

---

## 🎯 Hva er dette?

En startpakke for ungdomsbedrifter (UB) som vil:
- ✅ Dokumentere læring og refleksjon (viktig for karakter!)
- ✅ Holde oversikt over prosjekter og økonomi
- ✅ Bruke AI-assistenter effektivt
- ✅ Unngå overwhelming med for mye struktur

**Filosofi:** Start minimalt, voks organisk.

---

## 🚀 Quick Start (2 minutter)

### 1. Fork/klon dette repoet

```bash
git clone https://github.com/[your-org]/ub-knowledge-base-template.git min-ub
cd min-ub
```

### 2. Åpne i Obsidian

1. Last ned [Obsidian](https://obsidian.md/) (gratis)
2. `File → Open vault → Open folder as vault`
3. Velg mappen du nettopp klonet

### 3. Velg din tilnærming

**A) Med AI-assistent (ANBEFALT):**
- Les `AGENTS.md` for hvordan agenten skal hjelpe
- Koble til Claude/ChatGPT/Cursor
- Si: "Hjelp meg komme i gang"

**B) Manuelt:**
- Les `ONBOARDING.md` for step-by-step guide
- Start med å opprette `00-handbok/`

---

## 📂 Hva er inkludert?

**Kun 15 filer totalt:**

```
ub-knowledge-base-template/
├── README.md              # Dette dokumentet
├── ONBOARDING.md          # Menneske-guide (start her!)
├── AGENTS.md              # AI-veiledning (viktigste for AI!)
├── STRUCTURE.md           # Forklarer mappestrukturen
├── index.md               # Minimal landingsside
├── .gitignore             # Git-konfigurasjon
├── .obsidian/             # Obsidian settings
└── _templates/            # 9 Obsidian templates
    ├── motenotat.md
    ├── prosjekt-oversikt.md
    ├── laeringslogg.md
    ├── kunde-intervju.md
    ├── leveranseplan.md
    ├── ukerapport.md
    ├── beslutning.md
    ├── kreativ-brief.md
    └── retrospektiv.md
```

**Ingen placeholder-mapper. Ingen støy. Kun det dere trenger.**

---

## 💡 Hvordan virker det?

### Traditional template (❌ problemet):

```
template/
├── 00-handbok/
│   ├── index.md (placeholder)
│   ├── formaal-og-maal.md (placeholder)
│   └── roller-og-ansvar.md (placeholder)
├── 01-bedrift/
│   ├── index.md (placeholder)
│   └── om-oss.md (placeholder)
├── 02-marked/
│   ├── index.md (placeholder)
│   ├── leads.md (placeholder)
│   └── pris-og-tjenester.md (placeholder)
... 30+ placeholder-filer

Problem: 90% støy, 10% faktisk innhold ved oppstart
```

### Vår tilnærming (✅ løsningen):

```
template/
├── AGENTS.md              # Instruksjoner til AI
├── ONBOARDING.md          # Guide for mennesker
├── _templates/            # Maler (brukes on-demand)
└── index.md               # Minimal start

AI/elev oppretter struktur progressivt:

Dag 1: "Hva heter bedriften?"
  → Oppretter 00-handbok/formaal-og-maal.md (med faktisk info)

Uke 2: "Vi har fått en lead!"
  → Oppretter 02-marked/leads.md (med faktisk lead-data)

Uke 4: "Vi skal dokumentere møte"
  → Oppretter 06-moter/YYYY-MM-DD-mote.md (med faktisk innhold)
```

**Resultat:** 90% faktisk innhold, 10% struktur fra dag 1.

---

## 🤖 AI-drevet onboarding

Denne templaten er spesielt designet for bruk med AI-assistenter.

**AGENTS.md inneholder:**
- ✅ Progressive creation protocol
- ✅ Onboarding-workflow med konkrete scenario
- ✅ Template-valg og -bruk
- ✅ Frontmatter-standarder
- ✅ Pedagogisk tilnærming for 16-19 åringer
- ✅ Proaktive påminnelser (læringslogger!)

**Eksempel på AI-interaksjon:**

```
Student: "Hva skal jeg gjøre først?"

AI: "La oss starte med grunnlaget. Hva heter bedriften?"
Student: "TechKids AS"

AI: "Flott! Hva er hovedformålet?"
Student: "Vi skal lage apper for barn"

AI: *Oppretter:*
    - 00-handbok/formaal-og-maal.md (FYLT med faktisk info)
    - 00-handbok/roller-og-ansvar.md
    - Oppdaterer index.md

AI: "Neste steg - vil dere sette priser?"
```

---

## 📚 Dokumentasjon

| Fil | For hvem | Når lese |
| --- | -------- | -------- |
| `README.md` | Alle | Nå (du er her!) |
| `ONBOARDING.md` | Studenter/mennesker | Første dag |
| `AGENTS.md` | AI-assistenter | Før første interaksjon |
| `STRUCTURE.md` | Lærere/nysjerrige | Når du vil forstå strukturen |
| `index.md` | Alle | Åpne i Obsidian |

---

## 🎓 Fokus på læring (viktig for UB!)

Ungdomsbedrift handler om **læring**, ikke bare business.

**Denne templaten fremhever:**
- 📝 **Læringslogger** (ukentlig refleksjon)
- 🔄 **Retrospektiver** (team-læring etter prosjekter)
- 📋 **Beslutningslogg** (hvorfor tok vi dette valget?)
- 🎯 **Formål** (hvorfor eksisterer vi?)

**AI-en påminner proaktivt:**
- "Ingen læringslogg siste uka - vil du skrive en?"
- "Prosjektet er ferdig - skal vi kjøre retrospektiv?"

---

## 🔄 Progresjon

**Typisk utvikling over et år:**

```
Uke 1:
  template/
  ├── 00-handbok/ (formål, roller)
  ├── index.md
  └── _templates/

Uke 4:
  + 02-marked/ (leads, priser)
  + 06-moter/ (2-3 møtenotater)
  + 05-laering/laeringslogger/ (3-4 logger)

Uke 8:
  + 03-prosjekter/[kunde1]/ (første prosjekt)
  + 04-okonomi/ (budsjett, faktura)

Uke 20:
  + 03-prosjekter/[kunde2]/, [kunde3]/
  + 05-laering/retrospektiver/
  + 07-research/ (konkurranseanalyse)
```

**AI-en bygger strukturen etter faktiske behov - ikke på forhånd.**

---

## vs. Fullstendig eksempel

**Vil du se hvordan en ferdig kunnskapsbase ser ut?**

Se [lions-kristiansand](https://github.com/[org]/lions-kristiansand):
- ✅ 3 fullførte prosjekter
- ✅ 10+ læringslogger
- ✅ 15+ møtenotater
- ✅ Komplett økonomi
- ✅ Salgshistorikk

**Bruk det som inspirasjon, ikke som mal å kopiere.**

---

## 🛠️ Teknisk

**Krever:**
- Obsidian (gratis)
- Git (for versjonskontroll)

**Valgfritt:**
- AI-assistent (Claude, ChatGPT, Cursor)
- GitHub/GitLab (for backup og samarbeid)

**Ingen:**
- ❌ Node.js
- ❌ Build-steg
- ❌ Dependencies
- ❌ Hosting

Kun Markdown-filer + Obsidian.

---

## 💬 For lærere og veiledere

**Hvorfor denne tilnærmingen?**

1. **Reduserer cognitive load** - Studenter ser kun det de har laget
2. **Fremmer eierskap** - De bygger strukturen selv
3. **Unngår "template-hell"** - Ingen 30+ tomme filer
4. **AI-vennlig** - Minimal støy i retrieval
5. **Pedagogisk** - Lærer strukturering gradvis

**Forventninger:**

Alle UB-er vil ha:
- ✅ `00-handbok/` (formål, roller)
- ✅ `05-laering/` (læringslogger - KRITISK!)

De fleste vil ha:
- `02-marked/`, `03-prosjekter/`, `04-okonomi/`, `06-moter/`

Noen vil ha:
- `01-bedrift/`, `07-research/`, `08-ressurser/`

**Det er helt OK.** La bedriftene utvikle seg organisk.

---

## 🤝 Bidra

Fant du en forbedring?

1. Fork dette repoet
2. Lag en feature branch
3. Send pull request

**Spesielt ønsket:**
- Flere templates
- Bedre onboarding-instruksjoner
- Eksempler på AI-interaksjoner

---

## 📄 Lisens

MIT License - bruk fritt!

---

## ❓ FAQ

**Q: Må vi bruke AI-assistent?**
A: Nei! Les `ONBOARDING.md` for manuell tilnærming. Men AI gjør det mye enklere.

**Q: Hvorfor så få filer?**
A: Unngå støy. Lag kun det dere trenger.

**Q: Hva hvis vi allerede har dokumentasjon?**
A: Perfekt! AI-en hjelper med å strukturere det (se AGENTS.md scenario D).

**Q: Må vi følge 00-08 mappestrukturen?**
A: Anbefalt, men ikke påkrevd. Tilpass etter behov.

**Q: Hvor ofte skal vi skrive læringslogger?**
A: Minst ukentlig. Det er viktig for UB-karakter!

---

## 🎯 Oppsummering

**Denne templaten gir deg:**
- ✅ Minimal start (kun 15 filer)
- ✅ AI-drevet onboarding
- ✅ Progressive struktur
- ✅ Fokus på læring
- ✅ 9 battle-tested templates
- ✅ Ingen støy

**Start enkelt. Voks organisk. Dokumenter læringen. 🚀**

---

**Lykke til med ungdomsbedriften!**

_Laget med ❤️ for UB-programmet i Norge_
