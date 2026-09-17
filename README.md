# Webbureau Bouwpakket: skills voor Claude

Dit zijn de skills die horen bij het Webbureau Bouwpakket van ZakelijkGroeien.nl. Een skill is een set instructies die je in Claude installeert, waarna je hem start met een slash-commando, bijvoorbeeld `/contextdocument`.

## Wat zit erin

| Skill | Commando | Wat het doet |
|---|---|---|
| Context-skill | `/contextdocument` | Stelt in zes korte blokken vragen over je bedrijf, doelgroep, bestaand materiaal, stijl en onderscheid. Resultaat: één `contextdocument.md`, de basis voor Claude Design en je webteksten. |

## Installeren (eenmalig, 2 minuten)

Open Claude Code (de Code-tab in de Claude-app op je computer, of `claude` in de terminal) en typ de volgende twee commando's, één voor één:

```
/plugin marketplace add zakelijkgroeien/webbureau-bouwpakket
```

```
/plugin install contextdocument@webbureau-bouwpakket
```

Klaar. Typ daarna `/contextdocument` in een nieuw gesprek om te starten. Doe dit in de map van je websiteproject, want daar wordt `contextdocument.md` opgeslagen.

## Updates

Komt er een nieuwe versie van een skill, dan haal je die op met:

```
/plugin marketplace update webbureau-bouwpakket
```

## Handmatig installeren (als de commando's hierboven niet werken)

1. Download deze map als zip (groene knop "Code" op GitHub, dan "Download ZIP") en pak hem uit.
2. Kopieer de map `plugins/contextdocument/skills/contextdocument` naar `~/.claude/skills/` op je computer. Op een Mac vind je die map via Finder: druk Cmd+Shift+G en plak `~/.claude/skills`. Bestaat de map `skills` nog niet, maak hem dan aan.
3. Start Claude Code opnieuw. `/contextdocument` staat nu in de lijst.

## Vragen

Stel ze in het wekelijkse Bouwuur.
