# GerDA - German Data Assistant

**Deutsche Sprachausgabe für EDDI (Elite Dangerous Data Interface)**

GerDA bietet eine umfassende deutsche Übersetzung der EDDI-Sprachausgabe-Skripte, damit deutschsprachige Commanders ein vollständig lokalisiertes Erlebnis im Cockpit genießen können.

## 🎯 Was ist GerDA?

GerDA (German Data Assistant) ist ein vollständig übersetzter EDDI-Personality-Charakter, der:
- ✅ Ca. 85% aller EDDI-Events auf Deutsch ansagt
- ✅ Natürliche deutsche Formulierungen verwendet
- ✅ Kontinuierlich von der Community erweitert wird
- ✅ Kompatibel mit der aktuellen EDDI-Version ist

## 📥 Installation

### Voraussetzungen
- [EDDI](https://github.com/EDCD/EDDI) muss installiert sein
- Windows Text-to-Speech deutsche Stimme (z.B. Hedda, Katja)

### Schritt-für-Schritt Anleitung

1. **GerDA.json herunterladen**
   - Lade die `GerDA.json` aus diesem Repository herunter

2. **EDDI-Personalities-Ordner öffnen**
   - Standardpfad: `%APPDATA%\EDDI\personalities\`
   - Oder über EDDI: Settings → Speech → Manage Personalities

3. **GerDA.json kopieren**
   - Kopiere die heruntergeladene Datei in den `personalities` Ordner

4. **GerDA aktivieren**
   - Öffne EDDI
   - Gehe zu Settings → Speech → Personality
   - Wähle "GerDA" aus der Liste
   - Wähle eine deutsche TTS-Stimme

5. **Fertig!** 🎉
   - EDDI spricht jetzt Deutsch

## 🎤 Empfohlene Stimmen

**Windows 10/11 (kostenlos):**
- Katja (Standard deutsche Stimme)
- Hedda (österreichisches Deutsch)

**Premium-Optionen:**
- [Voxygen](https://voxygen.fr/) - Hochwertige TTS-Stimmen
- [CereProc](https://www.cereproc.com/) - Professionelle Stimmen

## 📝 Übersetzungsstatus

| Kategorie | Status | Fortschritt |
|-----------|--------|-------------|
| Docking & Navigation | ✅ Vollständig | 100% |
| Combat | ✅ Vollständig | 100% |
| Trading | ✅ Vollständig | 100% |
| Exploration | ✅ Vollständig | 100% |
| Community Goals | ✅ Vollständig | 100% |
| Missions | 🔄 In Arbeit | ~80% |
| Engineering | 🔄 In Arbeit | ~70% |
| Powerplay | ⏳ Geplant | ~40% |
| Selten genutzte Events | ⏳ Geplant | ~30% |

**Gesamt:** ~85% übersetzt

## 🤝 Beitragen

Wir freuen uns über jede Hilfe! Du kannst auf verschiedene Arten beitragen:

### Issues melden
- Fehler in Übersetzungen
- Unnatürliche Formulierungen
- Fehlende Übersetzungen

### Pull Requests
1. Forke dieses Repository
2. Erstelle einen Branch (`git checkout -b verbesserung-xyz`)
3. Bearbeite `GerDA.json`
4. Committe deine Änderungen (`git commit -m "Übersetzung für XYZ verbessert"`)
5. Push den Branch (`git push origin verbesserung-xyz`)
6. Erstelle einen Pull Request

### Übersetzungs-Guidelines
- Verwende natürliches, gesprochenes Deutsch
- Vermeide direkte Wort-für-Wort-Übersetzungen
- Behalte EDDI-Variablen unverändert (z.B. `{event.shipname}`)
- Teste deine Änderungen im Spiel!

## 📖 Cottle-Syntax

GerDA verwendet die Cottle-Template-Sprache. Hier ein kurzes Beispiel:

```cottle
{- Kommentar: Dies ist eine bedingte Ansage -}
{if event.station:
  Willkommen auf {event.station}
|else:
  Willkommen, Commander
}
```

[Vollständige Cottle-Dokumentation](https://github.com/r3c/cottle)

## 👥 Credits

**GerDA wurde entwickelt von:**
- **CMDR Flitzipaldi (nepomuk16321)** - Hauptentwickler & Übersetzer
- **CMDR Homunk** - Motivation & Unterstützung
- **CMDR Darkcyde** - Ideen aus dessen Personality

**Basierend auf EDDI von:**
- T'kael (EDCD)
- CMDR VerticalBlank (EDCD)
- Hoodathunk (EDCD) †

**Dank an:**
- Die gesamte EDDI-Community
- Die EDCD (Elite Dangerous Community Developers)
- Alle Tester und Feedback-Geber

## 📜 Lizenz

Dieses Projekt steht unter der MIT-Lizenz - siehe [LICENSE](LICENSE) für Details.

## 🔗 Links

- [EDDI Hauptprojekt](https://github.com/EDCD/EDDI)
- [EDDI Dokumentation](https://github.com/EDCD/EDDI/wiki)
- [Elite Dangerous](https://www.elitedangerous.com/)
- [EDSM](https://www.edsm.net/) - Elite Dangerous Star Map
- [Inara](https://inara.cz/) - Elite Dangerous Companion

## 💬 Support & Community

**Fragen? Probleme? Vorschläge?**
- Öffne ein [Issue](../../issues)
- Diskutiere im [EDDI Discord](https://discord.gg/y8rDhw7DhM)

---

**o7 Commanders! Fly safe!** 🚀
