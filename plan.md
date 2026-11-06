# P34nuts Root Pages – Studio Board

Die Root-Seite positioniert P34nuts als unabhängiges Studio für sechs eigenständige Projektwelten:

1. Artist und Songwriter P34nuts mit Spotify, Suno und der ausführlichen Artist-Seite.
2. CarLoMind als praktische Android-Parkplatz-App mit Bluetooth-Automatik, manuellen Standorten, Karten-, Kalender- und Widget-Funktionen.
3. MindFox als lokales Android-Partyspiel für 2–8 Spieler mit Bluff-, Voting-, Reveal- und Scoreboard-Runden.
4. FlipVoice als mobile-first Partyspiel-PWA/Android-Hülle mit Pass & Play, WLAN-Lobby, QR-Code, Audio-Reverse und Buzzer.
5. Resonanzfall / Protokoll I als Science-Fiction-Thriller.
6. Emil entdeckt die Welt als sechsteilige Kinderbuchserie.

## Designsystem

Jede Karte folgt einer eigenen visuellen Produktlogik: Audio-Signal und dunkle Konzertfarben für Musik, Kartenraster und Türkis für CarLoMind, Neon-Violett und Augenmotiv für MindFox, Audio-Wellen und Cyan/Magenta für FlipVoice, Orbit/Planet und Nachtfarben für Resonanzfall sowie Himmel, Sonne und Route für Emil. Die gemeinsame Studio-Klammer bleibt eine redaktionelle Typografie, nummerierte Kapitel und klare pillenförmige Links.

## Inhaltliche Erweiterung

Die Karten enthalten nun Positionierung, Funktionsbeschreibung, Zielgruppen-/Format-Hinweise, technische Schlagworte, Status und direkte Links. Die Texte wurden gegen die lokalen README- und Übergabedokumente der Projekte abgeglichen; nicht bestätigte Store- oder Releasebehauptungen wurden vermieden.

## QA

- HTML/CSS lokal mit `git diff --check` und Parser-Smoke prüfen.
- Alle sechs Projektanker und externen Direktlinks prüfen.
- Root, `/artist/` und `/CarLoMind/` nach dem Pages-Deploy per HTTP prüfen.
- Responsive Darstellung für Desktop und Mobil kontrollieren.
