# Ungdomsbedrift - Kunnskapsbase Template

En minimal, ferdig strukturert kunnskapsbase for ungdomsbedrifter. Fork dette repoet og tilpass det til deres bedrift!

## 🎯 Hva er dette?

Dette er en **startpakke** for ungdomsbedrifter som vil:
- Holde god dokumentasjon fra dag 1
- Dokumentere læring og refleksjon
- Holde oversikt over prosjekter og økonomi
- Bruke AI-verktøy effektivt (ChatGPT, Claude, osv.)

## 🚀 Komme i gang (5 minutter)

### 1. Fork eller klon repoet

```bash
git clone https://github.com/[your-org]/ub-knowledge-base-template.git min-ub
cd min-ub
```

### 2. Åpne i Obsidian

1. Last ned [Obsidian](https://obsidian.md/) (gratis)
2. Åpne denne mappen som en vault: `File → Open vault → Open folder as vault`
3. Start med [[index|hovedsiden]]

### 3. Tilpass til deres bedrift

**Første time:**
- [ ] Endre "Ditt Bedriftsnavn" i `index.md` til deres faktiske navn
- [ ] Fyll ut [[00-handbok/formaal-og-maal|formål og mål]]
- [ ] Definer [[00-handbok/roller-og-ansvar|roller]] i teamet

**Første uke:**
- [ ] Sett [[02-marked/pris-og-tjenester|priser]]
- [ ] Lag [[04-okonomi/budsjett|budsjett]]
- [ ] Skriv [[01-bedrift/om-oss|om oss]]
- [ ] Dokumenter første [[06-moter/|teammøte]]

## 📂 Struktur

```
ub-knowledge-base-template/
├── _templates/          # 9 Obsidian templates for ulike dokumenttyper
├── 00-handbok/          # Regler, roller og beslutninger
├── 01-bedrift/          # Om dere
├── 02-marked/           # Salg og leads
├── 03-prosjekter/       # Kundeprosjekter
├── 04-okonomi/          # Budsjett og regnskap
├── 05-laering/          # Læringslogger og retrospektiver
├── 06-moter/            # Teammøter
├── 07-research/         # Markedsanalyse
└── 08-ressurser/        # Verktøy og guider
```

## 📋 9 Templates inkludert

Alle templates finnes i `_templates/`:

1. **motenotat.md** - Dokumenter alle møter
2. **prosjekt-oversikt.md** - Start nytt kundeprosjekt
3. **laeringslogg.md** - Ukentlig refleksjon (viktig for UB!)
4. **ukerapport.md** - Ukentlig statusoppdatering
5. **kunde-intervju.md** - Kartlegg kundebehov
6. **leveranseplan.md** - Planlegg leveranser
7. **beslutning.md** - Dokumenter viktige valg
8. **kreativ-brief.md** - Designoppdrag
9. **retrospektiv.md** - Team-refleksjon etter prosjekter

### Hvordan bruke templates i Obsidian

1. Installer "Templater" plugin (anbefalt) ELLER bruk innebygd "Templates" core plugin
2. Opprett ny fil
3. Bruk template-kommando (Cmd/Ctrl + P → "Insert template")

## 🎓 Pedagogisk fokus

Denne strukturen støtter **læring**, ikke bare forretning:

- **Læringslogger** (05-laering/) - Reflekter ukentlig over hva dere lærer
- **Retrospektiver** - Lær av hvert prosjekt
- **Beslutningslogg** - Forstå hvorfor dere tok visse valg
- **Møtenotater** - Tren på strukturert kommunikasjon

## 🤖 Bruk med AI-verktøy

Denne kunnskapsbasen er optimalisert for AI:

### Med Claude Desktop (MCP)
```bash
# Legg til i Claude Desktop config
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/min-ub"]
    }
  }
}
```

### Med ChatGPT
- Del relevante filer som kontekst
- Be ChatGPT hjelpe med å fylle ut templates
- La AI analysere budsjett, leads, osv.

### Med Cursor/Copilot
- Åpne vault i VS Code/Cursor
- Bruk AI til å skrive møtenotater, læringslogger, osv.

## 💡 Beste praksis

**Dokumenter løpende:**
- ✅ Skriv møtenotat UNDER møtet
- ✅ Skriv læringslogg hver fredag
- ✅ Oppdater leads-liste ukentlig
- ❌ IKKE vent til slutten av året!

**Hold det enkelt:**
- Start med det viktigste (handbok, budsjett, leads)
- Utvid etter behov
- Ikke dokumenter ALT

**Gjør det til en vane:**
- Ukentlig statusmøte → møtenotat
- Hver fredag → læringslogg
- Hver måned → oppdater budsjett

## 📚 Eksempel

Vil du se hvordan en fullstendig utfylt kunnskapsbase ser ut?

Se [lions-kristiansand](https://github.com/[your-org]/lions-kristiansand) - et komplett eksempel med:
- 1 fullført kundeprosjekt
- 3 læringslogger
- Flere møtenotater
- Komplett budsjett og salgshistorikk

## 🔗 Ressurser

**Ungdomsbedrift:**
- [UE Norge](https://ue.no/) - Offisielt UB-program
- [UE Ressursbank](https://ue.no/ressurser) - Guider og maler

**Obsidian:**
- [Obsidian Help](https://help.obsidian.md/)
- [Markdown Guide](https://www.markdownguide.org/)

**Git:**
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- [GitHub Desktop](https://desktop.github.com/) - Enklere enn kommandolinje

## ❓ FAQ

**Q: Må vi bruke Obsidian?**
A: Nei! Dette er vanlige Markdown-filer. Bruk VS Code, iA Writer, eller hvilken som helst teksteditor. Men Obsidian er optimalisert for denne type kunnskapsbase.

**Q: Må vi bruke Git?**
A: Nei, men det er sterkt anbefalt. Git gir versjonskontroll og backup. Bruk GitHub Desktop hvis kommandolinje er skummelt.

**Q: Hvor ofte skal vi oppdatere kunnskapsbasen?**
A: Minimum ukentlig (møtenotat + læringslogg). Ideelt: dokumenter ting når de skjer.

**Q: Hva hvis vi ikke har noe å skrive i en seksjon?**
A: Da lar du den stå tom! Ikke fyll ut noe bare for å fylle ut. Strukturen er der når dere trenger den.

**Q: Kan vi endre strukturen?**
A: Absolutt! Dette er en template, ikke en fasit. Tilpass til deres behov.

## 📄 Lisens

MIT License - bruk fritt!

## 🤝 Bidra

Fant du en forbedring? Send pull request!

---

**Laget for ungdomsbedrifter av [din organisasjon] ❤️**

God dokumentasjon → God læring → God ungdomsbedrift!
