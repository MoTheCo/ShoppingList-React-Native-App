# ShoppingList React Native App

## Überblick

**ShoppingList** ist eine React Native Anwendung zur Verwaltung einer Einkaufsliste. Mit dieser App können Sie Artikel zur Liste hinzufügen, bearbeiten, löschen und die Liste als CSV-Datei speichern oder laden. Die App unterstützt auch die Spracherkennung zur Eingabe von Artikeln.

## Funktionen

- **Artikel hinzufügen**: Fügen Sie neue Artikel zur Einkaufsliste hinzu.
- **Artikel bearbeiten**: Bearbeiten Sie bestehende Artikel in der Liste.
- **Artikel löschen**: Entfernen Sie Artikel aus der Liste.
- **CSV-Export/Import**: Speichern und laden Sie die Liste als CSV-Datei.
- **Spracherkennung**: Fügen Sie Artikel per Sprachbefehl hinzu (nur in unterstützten Browsern).

## Installation

1. **Voraussetzungen**: Stellen Sie sicher, dass Sie Node.js und npm installiert haben.
2. **Projekt einrichten**:
   ```bash
   npx create-react-native-app shopping-list
   cd shopping-list
   ```
3. **Notwendige Pakete installieren**:
   ```bash
   npm install papaparse
   ```

## Nutzung

1. **Starten der Anwendung**:
   ```bash
   npm start
   ```
2. Verwenden Sie einen Android/iOS-Emulator oder ein physisches Gerät zur Ausführung der App.

## Komponenten

- **TextInput**: Zum Eingeben von Artikelnamen.
- **Button**: Zum Hinzufügen, Bearbeiten und Löschen von Artikeln.
- **FlatList**: Zur Anzeige der Artikel in der Liste.
- **Spracherkennung**: Startet die Spracheingabe, um Artikel hinzuzufügen.

## Stile

Die Stile sind in der `StyleSheet`-API definiert und umfassen:

- **Container**: Zentriert die App-Inhalte.
- **Input**: Stil für das Texteingabefeld.
- **ItemContainer**: Layout für einzelne Artikel.
- **ButtonGroup**: Layout für die Schaltflächen „Edit“ und „Delete“.

## Anforderungen

- **Browser**: Für die Spracherkennung wird Chrome empfohlen.

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz.

## Kontakt

Bei Fragen oder Anmerkungen wenden Sie sich bitte an den Entwickler.
