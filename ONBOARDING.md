# Onboarding Guide - Kom i gang! 🚀

Velkommen til din ungdomsbedrifts kunnskapsbase!

Denne guiden hjelper deg å komme i gang - enten du starter fra scratch eller har eksisterende dokumentasjon.

---

## 📋 Før du starter

**Du trenger:**
- [ ] [Obsidian](https://obsidian.md/) installert (gratis)
- [ ] Denne mappen åpnet som vault i Obsidian
- [ ] (Valgfritt) Tilgang til AI-assistent (Claude, ChatGPT, Cursor)

**Du trenger IKKE:**
- ❌ Å fylle ut alt på forhånd
- ❌ Å opprette alle mapper selv
- ❌ Å vite hvordan alt fungerer

> [!tip] Bruk AI-assistent!
> Denne kunnskapsbasen er designet for å brukes sammen med AI.
> AI-en vil hjelpe deg progressivt bygge strukturen etter hvert som dere trenger den.

---

## 🎯 Valg A: Med AI-assistent (ANBEFALT)

### Steg 1: Åpne i Obsidian + AI-verktøy

**Obsidian:**
1. Åpne Obsidian
2. `File → Open vault → Open folder as vault`
3. Velg denne mappen

**AI (velg en):**
- **Claude Desktop + MCP:** [Sett opp filesystem access](https://docs.claude.com/en/docs/claude-code)
- **Cursor:** Åpne denne mappen i Cursor
- **ChatGPT:** Ha vinduet åpent ved siden av

### Steg 2: Start samtalen

**Si til AI-assistenten:**

```
Hei! Jeg har åpnet en ny UB-kunnskapsbase basert på template.

Vi heter: [Bedriftsnavn]
Vi er i fase: [Ide/Oppstart/Aktiv/Levering]

[Valgfritt: Del eksisterende dokumentasjon]

Kan du hjelpe meg komme i gang?
```

**AI-en vil:**
1. Stille oppklarende spørsmål
2. Opprette mapper og filer etter behov
3. Fylle ut med faktisk informasjon
4. Guide deg gjennom prosessen

### Steg 3: Følg AI-ens veiledning

AI-en vil hjelpe deg med:
- ✅ Definere formål og mål
- ✅ Liste opp teammedlemmer
- ✅ Sette priser
- ✅ Dokumentere første møte
- ✅ Og mye mer!

**Du lærer underveis** - AI forklarer hva og hvorfor.

---

## 🔧 Valg B: Manuelt (uten AI)

### Steg 1: Definer grunnlaget

**Opprett første mappe:**
```
mkdir 00-handbok
```

**Bruk templates:**
1. Åpne `_templates/` mappen
2. Kopier relevant template
3. Fyll ut med deres informasjon

**Start med:**
1. `00-handbok/formaal-og-maal.md` - Hvorfor eksisterer vi?
2. `00-handbok/roller-og-ansvar.md` - Hvem gjør hva?
3. `02-marked/pris-og-tjenester.md` - Hva tilbyr vi?

### Steg 2: Dokumenter løpende

**Ved første lead:**
```
mkdir -p 02-marked
# Bruk _templates/kunde-intervju.md
```

**Ved første møte:**
```
mkdir -p 06-moter
# Bruk _templates/motenotat.md
```

**Ukentlig:**
```
mkdir -p 05-laering/laeringslogger
# Bruk _templates/laeringslogg.md
```

### Steg 3: Oppdater `index.md`

Hver gang du oppretter ny seksjon:
1. Åpne `index.md`
2. Legg til lenke i "Hovedseksjoner"
3. Oppdater "Første steg"

---

## 📚 Hva skal jeg faktisk lage?

### Minimum (Uke 1)

**Kritisk:**
- [ ] `00-handbok/formaal-og-maal.md`
- [ ] `00-handbok/roller-og-ansvar.md`
- [ ] `02-marked/pris-og-tjenester.md`
- [ ] `index.md` (oppdatert)

**Dette gir dere:**
- Klar retning (formål)
- Tydelig ansvar (roller)
- Grunnlag for salg (priser)

### Tidlig fase (Uke 2-4)

**Når relevant:**
- [ ] `02-marked/leads.md` (første lead)
- [ ] `06-moter/YYYY-MM-DD-mote.md` (første møte)
- [ ] `04-okonomi/budsjett.md` (budsjettplan)
- [ ] `05-laering/laeringslogger/YYYY-MM-DD-navn.md` (første refleksjon)

### Aktiv fase (Uke 4-8)

**Når dere får kunde:**
- [ ] `03-prosjekter/[kunde]/oversikt.md`
- [ ] `03-prosjekter/[kunde]/avtale.md`
- [ ] `03-prosjekter/[kunde]/leveranseplan.md`

**Løpende:**
- [ ] Møtenotater (hver uke)
- [ ] Læringslogger (hver fredag anbefalt!)
- [ ] Oppdater budsjett (ved inntekt/utgift)

---

## 🎓 Spesielt viktig for UB

### Læringslogger er KRITISK

Ungdomsbedrift handler om **læring**, ikke bare business.

**Skriv læringslogg:**
- ✅ Minst én gang i uka (fredager fungerer godt)
- ✅ Etter viktige hendelser (pitch, kundemøte, lansering)
- ✅ Når du lærer noe nytt

**Bruk template:**
`_templates/laeringslogg.md`

**Tips:**
- Vær konkret ("lærte Figma basics" > "lærte mye")
- Nevn både suksesser og feil
- Tenk på hva du vil gjøre annerledes

### Retrospektiver etter prosjekter

Når prosjekt er ferdig:
- ✅ Samle teamet
- ✅ Bruk `_templates/retrospektiv.md`
- ✅ Diskuter: Hva gikk bra? Hva kan forbedres?

---

## 🗺️ Progresjon - Hva er normalt?

### Uke 1-2: Grunnmur
```
Forvent å ha:
✅ Formål definert
✅ Roller fordelt
✅ Priser satt
✅ Kanskje første lead
```

### Uke 3-5: Aktivitet
```
Forvent å ha:
✅ 2-4 møtenotater
✅ 1-3 læringslogger
✅ Leads-liste med 3-5 potensielle kunder
✅ Budsjett opprettet
```

### Uke 6-10: Første kunde
```
Forvent å ha:
✅ Minst ett prosjekt i 03-prosjekter/
✅ 5-10 læringslogger
✅ Dokumenterte avtaler
✅ Oppdatert budsjett med faktiske tall
```

### Uke 11+: Modenhet
```
Forvent å ha:
✅ 2-3 fullførte prosjekter
✅ Retrospektiv etter prosjekter
✅ 15+ læringslogger
✅ Godt dokumentert økonomispor
```

**Husk:** Dette er veiledende - hver bedrift er unik!

---

## 💡 Beste praksis

### ✅ Gjør

- **Dokumenter løpende** - Ikke vent til slutten!
- **Skriv møtenotat UNDER møtet** - Du glemmer ellers
- **Læringslogg hver fredag** - Gjør det til en rutine
- **Bruk templates** - De sikrer konsistens
- **Lenk mellom dokumenter** - Bruk `[[filnavn]]` syntax
- **Spør AI om hjelp** - Den er der for deg!

### ❌ Ikke gjør

- **Opprett alle mapper på forhånd** - Lag etter behov
- **Skriv placeholder-tekst** - Vent til du har faktisk info
- **Dokumenter ALT** - Hold det enkelt og relevant
- **Vente med læringslogger** - Start tidlig!
- **Glemme å oppdatere** - Budsjett, leads osv. må holdes oppdatert

---

## 🆘 Hjelp og ressurser

### Intern dokumentasjon
- **STRUCTURE.md** - Forklarer mappestrukturen
- **AGENTS.md** - For AI-assistenter (les hvis du er nysjerrig!)
- **README.md** - Teknisk oversikt

### Eksempel
- **[lions-kristiansand](https://github.com/[org]/lions-kristiansand)** - Se et fullstendig utfylt eksempel

### Eksterne ressurser
- **[Obsidian Help](https://help.obsidian.md/)** - Lær Obsidian
- **[Markdown Guide](https://www.markdownguide.org/)** - Lær Markdown
- **[UE Norge](https://ue.no/ressurser)** - Ressurser for UB

### Kom ikke videre?

1. **Spør AI-assistenten** - Den kan hjelpe!
2. **Se lions-kristiansand** - Finn lignende eksempel
3. **Spør lærer/veileder** - De kjenner UB-programmet
4. **Start enkelt** - Ikke stress med å få alt perfekt

---

## 🎯 Din sjekkliste - Første time

- [ ] Obsidian installert og åpnet
- [ ] AI-assistent tilgjengelig (hvis du bruker)
- [ ] Bedriftsnavn bestemt
- [ ] Formål diskutert med teamet
- [ ] Roller fordelt

**Deretter:**
- [ ] Opprett `00-handbok/formaal-og-maal.md`
- [ ] Opprett `00-handbok/roller-og-ansvar.md`
- [ ] Diskuter og sett priser
- [ ] Opprett `02-marked/pris-og-tjenester.md`

**Du er i gang! 🎉**

---

## 📝 Siste tips

**For første gang med Obsidian:**
- Klikk `Ctrl/Cmd + P` for command palette (søk etter alt)
- Bruk `[[` for å lage lenker til andre filer
- Bruk `#` for overskrifter (# = H1, ## = H2, osv.)
- Bilder drar du bare inn i filen

**For første gang med AI-assistent:**
- Vær spesifikk: "Hjelp meg lage budsjett" > "Hjelp meg"
- Del kontekst: "Vi er 5 personer, fokuserer på nettsider"
- Spør når du ikke forstår: "Hvorfor trenger vi dette?"
- AI er der for å hjelpe - ikke vær redd for å spørre!

---

**Lykke til med ungdomsbedriften! 🚀**

Du har nå et solid fundament for å dokumentere reisen deres.
Husk: Dette handler om å **lære** entreprenørskap - ikke bare drive business.

Skriv læringslogger, reflekter over erfaringer, og ha det gøy! ❤️
