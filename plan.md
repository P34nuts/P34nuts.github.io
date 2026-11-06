# P34nuts Root Pages – Entwickler-Startseite

## Umsetzung

Die Root-URL `https://p34nuts.github.io/` ist eine eigenständige, statische Entwickler-Startseite. Sie stellt P34nuts als Entwickler, Artist und Autor vor und führt über einzelne Projektkarten zu Musik, Apps, Spielen und Büchern.

Die bisherige React-/Artist-Website wird im Pages-Workflow mit `VITE_BASE_PATH=/artist/` gebaut und unter `/artist/` veröffentlicht. Die bestehende CarLoMind-Seite bleibt unter `/CarLoMind/`. Der Root-Wrapper liefert die Landingpage, Styles und das Routenmanifest direkt.

## Gestaltung

Die Grundästhetik bleibt eine reduzierte Editorial-/Studio-Oberfläche: Papierfläche, tiefes Schwarz, Signalrot und ein blasses Blaugrün. Große typografische Überschriften, nummerierte Projektkader und pillenförmige Direktlinks verbinden die drei Arbeitsfelder Code, Klang und Geschichten.

Die Projektkarten verwenden zusätzlich eigene Produktwelten, damit die Darstellung nicht wie ein neutrales Portfolio-Raster wirkt:

- **P34nuts Musik:** dunkle Nachtfläche, rote Platten-/Signalformen und Waveform-Motive.
- **CarLoMind:** helles Navigationsgrün, Parkplatzraster, Kartenpin und „Save / Find / Return“-Sprache.
- **MindFox:** violette Neon-Quizshow, leuchtende Fox-Augen und Bluff-/Vote-/Reveal-Motive.
- **FlipVoice:** dunkle Cyan-/Pink-Audiofläche, Waveform und Reverse-Pfeil.
- **Resonanzfall:** tiefer Weltraum, Planet, Orbit und warme Signalfarbe.
- **Emil entdeckt die Welt:** Himmel, Sonne, Wolken und eine gestrichelte Entdeckerroute.

Die Gestaltung verwendet ausschließlich CSS-Illustrationen und vorhandene Schrift-/Browsermittel; neue externe Infrastruktur oder Bildabhängigkeiten sind nicht erforderlich. Die Produktkarten bleiben semantisch als Artikel strukturiert, keyboard-bedienbar und auf mobilen Geräten untereinander lesbar.

## Links und Sichtbarkeit

MindFox verweist auf das inzwischen private Repository, den Closed-Test-Einstieg und die öffentliche Datenschutzseite. FlipVoice verweist auf das private Hauptrepository und die öffentliche Datenschutzseite. Nicht verifizierte öffentliche Play-Store-Links werden nicht als verfügbar dargestellt.
