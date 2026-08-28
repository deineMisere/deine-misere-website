# CMS für deine Misere!

Die Oberfläche liegt unter `/admin/`. Sie nutzt die GitHub Contents API und aktualisiert `content.json`.

## Einrichtung
1. Repository mit dieser Website auf GitHub anlegen.
2. Fine-grained GitHub Token erstellen: Zugriff nur auf dieses Repository, Berechtigung **Contents: Read and write**.
3. Website über Vercel mit dem Repository verbinden.
4. Unter `/admin/` Owner, Repository, Branch und Token eingeben.

Der Token wird nicht gespeichert. Änderungen an `content.json` lösen bei einer GitHub/Vercel-Verknüpfung einen neuen Deployment-Lauf aus.

## Musik verwalten
Unter **Musik / Veröffentlichungen** können neue Veröffentlichungen mit Titel, Jahr, Streaming-/Album-Link und optionalem Albumcover angelegt werden. Cover werden unter `assets/music/` gespeichert.

Zusätzlich zeigt die Musik-Sektion eine Spotify-Einbindung der Band, über die die aktuell bei Spotify verfügbaren Veröffentlichungen inklusive Cover und Namen sichtbar sind.

## Fotos verwalten
Unter **Fotos / Impressionen** können JPG-, PNG- oder WebP-Dateien hochgeladen und mit einer Bildunterschrift versehen werden. Die Bilder werden unter `assets/photos/` gespeichert.

Wichtig: Der Bandname wird im CMS und auf der Website fest auf **deine Misere!** normalisiert.

Website-Deployment wird vorbereitet.
