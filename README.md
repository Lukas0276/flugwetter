# 🪂 Kann ich hier fliegen? – Flugwetter-Check

Eine schlanke Web-App für Gleitschirmflieger: **Ort eingeben → sofort sehen, ob es passt.**

👉 **Live:** https://lukas0276.github.io/flugwetter/

## Features
- **Flugwetter-Score** (0–100) mit Begründung
- **Aktuelle Bedingungen:** Temperatur, Wind & Richtung, Böen, Thermik (CAPE), Föhnrisiko, Luftfeuchte, Nullgradgrenze
- **Startplätze in der Umgebung** mit geeigneten Windrichtungen, Höhe, Thermik-/Soaring-Flags und Live-Urteil
- **Wind-Kompass**, **Topo-Karte** mit farbcodierten Markern, **Tagesverlauf** mit bestem Zeitfenster
- **Detailansicht je Startplatz:** Höhenwind-Profil, passende Startrichtungen, Föhn, Direktlinks
- **Webcams & Live-Windkarte**

## Datenquellen (alle frei, kein API-Key)
- Wetter & Geocoding: [Open-Meteo](https://open-meteo.com)
- Startplätze: [OpenStreetMap](https://www.openstreetmap.org) / Overpass & [Paragliding Earth](https://www.paraglidingearth.com)
- Karte: OpenTopoMap · Windkarte: [Windy](https://www.windy.com)

## ⚠️ Sicherheitshinweis
Entscheidungshilfe, **keine Flugfreigabe.** Die Werte sind automatisierte Schätzungen aus öffentlichen Modellen und ersetzen keinen offiziellen Wetter-/Bergwetterbericht, keine Föhndiagnose, keine Luftraumprüfung und keine Beurteilung vor Ort. Fliege nur im Rahmen deiner Ausbildung, Lizenz und der lokalen Regeln. Im Zweifel: am Boden bleiben.

---
*Eine einzelne `index.html` – kein Build, keine Abhängigkeiten zum Hosten.*
