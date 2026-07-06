# sonew2aosp

Ein .NET 8.x WinForms-Tool zur Umwandlung der Benutzeroberfläche Ihres Xperia-Geräts in ein AOSP (Android Open Source Project)-ähnliches Erlebnis.

## Funktionen
- **Kein Root/BLU erforderlich**: Verwendet ADB-Befehle, daher ist keine Gerätemodifikation notwendig.
- **Mehrsprachige Unterstützung**: Englisch, Japanisch und Deutsch als Sprachoptionen während der Einrichtung verfügbar.
- **AOSP UI-Transformation**: Ermöglicht AOSP-Stil Launcher 3, Einstellungen und Sperrbildschirm.
- **BigClock (Zweizeilige Uhr) Umschaltung**: Ermöglicht das Umschalten der Sperrbildschirmuhr auf den AOSP-Stil.
- **All-in-One AOSP-Modus**: Führt das Löschen des Launchers, die Aktivierung der AOSP-Einstellungen/des Launchers und die Hintergrundbildeinstellung in einem einzigen Vorgang aus.
- **Overlay-Manager**: Bietet eine GUI zur Verwaltung von Geräte-Overlays (aktivieren/deaktivieren/deinstallieren/neu installieren).

## Screenshots

### Logo
![sonew2aosp Logo](./sonew2aospApp/Resources/logo.png)

### Sperrbildschirm vor der AOSP-Transformation
![Sperrbildschirm vor der AOSP-Transformation](./images/lockscreen_before.png)

### Sperrbildschirm nach der AOSP-Transformation
![Sperrbildschirm nach der AOSP-Transformation](./images/lockscreen_after.png)

### Einstellungsbildschirm vor der AOSP-Transformation
![Einstellungsbildschirm vor der AOSP-Transformation](./images/settings_before.png)

### Einstellungsbildschirm nach der AOSP-Transformation
![Einstellungsbildschirm nach der AOSP-Transformation](./images/settings_after.png)

## Anforderungen
- Windows OS
- .NET 8.x Runtime
- ADB (Android Debug Bridge) aktivierte Umgebung
- Xperia-Gerät mit Android 12 oder höher (empfohlen)

## Verwendung
1. Aktivieren Sie "USB-Debugging" auf Ihrem Xperia-Gerät und verbinden Sie es mit Ihrem PC.
2. Starten Sie das Tool.
3. Wählen Sie Ihre Sprache und starten Sie die Einrichtung.
4. Klicken Sie auf die entsprechenden Schaltflächen, um die AOSP UI-Änderungen anzuwenden.
5. Der Overlay-Manager ermöglicht eine detaillierte Anpassung.
6. Beim Ausführen des All-in-One AOSP-Modus wird ein Bestätigungsdialog zum Löschen der Launcher-Daten angezeigt.

## Für Entwickler
Dieses Projekt wurde mit .NET 8.0 WinForms erstellt.
Um das Projekt zu erstellen, führen Sie den folgenden Befehl aus:
```bash
dotnet build
```

## Haftungsausschluss
- Kompatibel mit Carrier- und globalen Versionen, aber einige Funktionen funktionieren möglicherweise nicht auf allen Modellen.
- Die Verwendung dieses Tools erfolgt auf eigenes Risiko.
