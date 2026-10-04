# Freigaben

Zeitlich begrenzte Freigaben aus Daily (Reisetage mit Bildern) und der Reisekarte (Orte).

- Jede Freigabe ist ein Ordner `<Ablaufdatum>_<id>` mit verschlüsselten Dateien (AES-GCM): `data.bin` (Inhalt), `t*.bin` (Vorschaubilder), `p*.bin` (Bilder in voller Größe).
- Der Schlüssel steht nur im Link hinter dem `#` und wird nie an einen Server geschickt. Ohne Link sind die Dateien nicht lesbar.
- `index.html` ist die Ansicht (GitHub Pages). Ab dem Tag nach dem Ablaufdatum zeigt sie nur noch „abgelaufen“; Daily löscht abgelaufene Ordner beim nächsten Start.
- Erstellt und beendet werden Freigaben in Daily unter Einstellungen → Reisen freigeben.
