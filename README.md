# VELTRIX — Local Vault

**Deine Dateien. Deine Kontrolle.**

## Website lokal starten
Öffne `index.html` in einem aktuellen Browser. Für die zuverlässigste Web-Crypto-Unterstützung empfiehlt sich GitHub Pages oder `http://localhost`.

## Auf GitHub Pages veröffentlichen
Lade die Dateien `index.html`, `style.css`, `app.js`, `README.md` und `VELTRIX-Programm.zip` in das Stammverzeichnis deines Repositorys. Aktiviere anschließend unter **Settings → Pages** die Veröffentlichung aus deinem Branch.

## Funktionen
- Datei verschlüsseln und als `.vltx` herunterladen
- `.vltx`-Datei mit Passwort entschlüsseln
- Separater Tresor: Dateien werden vor dem Speichern mit AES-256-GCM verschlüsselt und lokal in IndexedDB abgelegt
- Tresor-Einträge entschlüsseln/herunterladen oder löschen
- Kein Datei-Upload an einen VELTRIX-Server

## Hinweise
Der Tresor ist an den Browser und das jeweilige Gerät gebunden. Wenn Browserdaten gelöscht werden, können die lokalen Tresordateien verloren gehen. Sichere wichtige Dateien zusätzlich separat. Das Projekt ist ein Prototyp und wurde nicht unabhängig sicherheitsgeprüft.
