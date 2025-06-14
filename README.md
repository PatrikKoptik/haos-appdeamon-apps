# 🏠 Nützliche AppDaemon-Skripte für Home Assistant

Dies ist eine Sammlung von nützlichen **AppDaemon**-Skripten für die Heimautomatisierung mit [Home Assistant](https://www.home-assistant.io/).  
Die Skripte helfen dabei, alltägliche Automatisierungen effizienter, flexibler und intelligenter zu gestalten.

## 📦 Inhalt

Diese Sammlung enthält:

- 🔔 **Benachrichtigungen**: z. B. bei Bewegung, Geräusch, oder Gerätezustand  
- 🕒 **Zeitbasierte Automatisierungen**: wie z. B. Beleuchtung abhängig von Sonnenstand oder Uhrzeit  
- 📉 **Sensor-Überwachung**: Trigger bei Grenzwerten, z. B. Temperatur, Luftfeuchtigkeit, Stromverbrauch  
- 🔄 **Logik für smarte Routinen**: Szenenwechsel, Wenn-Dann-Kaskaden etc.

Die Skripte sind modular aufgebaut und lassen sich leicht anpassen.

## 🛠️ Voraussetzungen

- [AppDaemon](https://appdaemon.readthedocs.io/en/latest/) installiert und in Home Assistant integriert
- Grundkenntnisse in Python und YAML
- `apps.yaml` konfiguriert

## 📁 Verzeichnisstruktur

```plaintext
apps/
├── solmate-mqtt-client.py
└── ...
apps.yaml
```

## 🔗 Inspiration & Quellen

Einige der Skripte in diesem Repository basieren auf Ideen oder Code aus der Home Assistant Community und anderen Open-Source-Projekten.  
Vielen Dank an alle Entwickler:innen, die ihre Lösungen teilen! 🙌

### Repositories & Quellen:

- [https://github.com/home-assistant/example-appdaemon-apps](https://github.com/MatthiasKrt/home-assistant-eet-solmate-mqtt) – MQTT Client für die EET Solmate Photovoltaik Anlage mit Speicher von [MatthiasKrt](https://github.com/MatthiasKrt/home-assistant-eet-solmate-mqtt/commits?author=MatthiasKrt)

Wenn du dein Skript auf einem fremden Projekt basiert hast, ergänze die Liste bitte entsprechend oder öffne ein Pull Request.


## 📄 Lizenz

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Die Inhalte dieses Repositories stehen unter der Lizenz [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
Das bedeutet: Du darfst die Skripte frei verwenden, anpassen und weiterverbreiten – auch für kommerzielle Zwecke – **sofern** du eine angemessene Namensnennung vornimmst.  
Bitte verweise bei Weiterverwendung auf dieses Repository oder den ursprünglichen Autor.

