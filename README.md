# Schiebesachen

**Zuordnungsübungen ganz einfach** – ein Editor für interaktive Drag-and-Drop-Übungen (ähnlich H5P „Drag and Drop“) für den Unterricht, z. B. für ByCS mebis/Moodle.

**▶ Direkt im Browser starten:** https://majort0m0.github.io/Schiebesachen/

**⬇ Herunterladen:** [Schiebesachen.html](https://github.com/Majort0m0/Schiebesachen/releases/latest/download/Schiebesachen.html) (eine einzige Datei, läuft offline – einfach doppelklicken)

- Texte, Bilder (Upload, ARASAAC, Wikimedia Commons) und Töne (Upload oder Aufnahme) als Zuordnungselemente
- Hintergrund als Bild, Farbe oder frei gestaltet im Editor – mit Texten, Bildern, Tönen und eigenen Zeichnungen
- Lösungsbereiche sichtbar, als Punkt, als Pfeil, in Elementgröße oder unsichtbar
- Vorlesen per Sprachausgabe oder eigener Aufnahme, gut lesbare Schriften (u. a. Atkinson Hyperlegible, Andika)
- Export als HTML-Datei (auch zum Einbetten per iframe), SCORM-1.2-Paket mit Bewertung oder PDF-Arbeitsblatt mit Lösung
- Keine Anmeldung, kein Server, keine Cookies – siehe [Datenschutz](DATENSCHUTZ.md)

## Lizenz

Schiebesachen – Lizenz: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de) Lernsachen.blog ([https://lernsachen.blog](https://lernsachen.blog))

Enthaltene Bausteine: [Preact](https://preactjs.com), [Immer](https://immerjs.github.io/immer/), [Excalidraw](https://excalidraw.com) (MIT-Lizenz); Schriften Nunito, Atkinson Hyperlegible, Andika, Merriweather, Caveat (SIL Open Font License 1.1). Bilder aus der Suche behalten ihre eigenen Lizenzen (ARASAAC: CC BY-NC-SA 4.0).

---

# Anleitung

Diese Anleitung steht auch in der App unter „Anleitung“.

## Schnellstart

Mit Schiebesachen erstellst du Zuordnungsübungen: Die Lernenden ziehen Texte, Bilder oder Töne auf die richtigen Stellen eines Hintergrunds – z. B. Begriffe an ein Bild einer Pflanze, Tiere in ihren Lebensraum oder Laute zu Bildern. Alles läuft direkt in deinem Browser, ohne Anmeldung.

### In 6 Schritten zur fertigen Übung

1. **Titel eingeben** – oben in der Leiste oder im Schritt „1 Grundlagen“. Wähle dort auch das Format (z. B. 16:9 quer).
2. **Hintergrund festlegen** – im Schritt „2 Hintergrund“ ein Bild hochladen bzw. suchen, einfach eine Farbe wählen oder im „Editor“ frei gestalten – mit Texten, Bildern, Tönen und eigenen Zeichnungen.
3. **Elemente anlegen** – im Schritt „3 Elemente“ auf „Text“, „Bild“ oder „Ton“ klicken. Viele Texte gehen am schnellsten mit „Mehrere Texte auf einmal“. Darunter legst du die „Startposition der Elemente“ fest: in einer Ablageleiste (unten oder rechts) oder frei auf der Fläche.
4. **Lösungsbereiche setzen** – im Schritt „4 Bereiche“ auf die passende Stelle des Hintergrunds klicken (oder ein Rechteck aufziehen) und darunter die richtigen Elemente abhaken.
5. **Ablauf einstellen** – im Schritt „5 Ablauf“: Sofort-Feedback oder „Überprüfen“-Button, Optionen wie „Reihenfolge mischen“, Bestehensgrenze. Die Checkliste zeigt, ob noch etwas fehlt.
6. **Testen und exportieren** – oben auf „Testen“ klicken und die Übung selbst ausprobieren. Dann „Exportieren“: als HTML-Datei (auch zum Einbetten in mebis), als SCORM-Paket für mebis mit Bewertung oder als PDF-Arbeitsblatt.

> **Tipp:** Deine Arbeit wird automatisch im Browser gespeichert. Sichere wichtige Übungen trotzdem zusätzlich als JSON-Datei (Ordner-Symbol oben rechts → „Als JSON speichern“) – siehe [Speichern & Weiterbearbeiten](#speichern--weiterbearbeiten).

### So ist der Editor aufgebaut

- **Obere Leiste:** Titel der Übung, Rückgängig/Wiederholen, Umschalter „Bearbeiten“/„Testen“, Datei-Menü (Ordner-Symbol), Anleitung, Datenschutz und „Exportieren“.
- **Schrittleiste** (links, auf dem Smartphone unten): die fünf Arbeitsschritte. Ein roter Punkt zeigt an, dass dort noch etwas fehlt (z. B. der Titel).
- **Seitenleiste:** alle Einstellungen des gewählten Schritts bzw. des ausgewählten Elements oder Bereichs.
- **Arbeitsfläche:** zeigt die Übung so, wie die Lernenden sie sehen. Hier verschiebst und vergrößerst du Elemente und Bereiche direkt mit der Maus oder dem Finger.

## 1 Titel & Format

### Titel

1. Gib einen **Titel** ein (Pflichtfeld) – z. B. „Die Teile einer Blume“. Er steht über der Übung und wird auch als Dateiname beim Export verwendet.
2. Unter „Titel“ stellst du **Schrift, Größe, Farbe**, fett/kursiv und die Ausrichtung ein. Die gewählte Schrift gilt danach auch für neue Texte (siehe [Schriften](#schriften)).
3. Mit „Vorlesen-Button anzeigen“ erscheint neben dem Titel ein Lautsprecher. Ein Tipp darauf liest den Titel (oder eine Arbeitsanweisung, die du hineinschreibst) vor – ideal für Kinder, die noch nicht sicher lesen. Statt der Computerstimme kannst du auch eine **eigene Aufnahme** verwenden (siehe [Vorlesen und eigene Aufnahme](#vorlesen-und-eigene-aufnahme)).

### Format der Arbeitsfläche

Das Format bestimmt das Seitenverhältnis des Hintergrunds. Wähle es am besten, bevor du Bilder einfügst.

| Format | Quer | Hochkant | Geeignet für |
|---|---|---|---|
| 16:9 (Breitbild) | 16 : 9 | 9 : 16 | Whiteboard, Laptop, Smartphone hochkant |
| 4:3 | 4 : 3 | 3 : 4 | Tablets, Fotos, Arbeitsblätter |
| Quadratisch | 1 : 1 (kein Hoch-/Querformat) | Piktogramme, Ablage unten oder rechts |
| 2:1  | 2 : 1 – flacher Panorama-Streifen | 1 : 2 – schmale Säule | quer mit Ablage unten, hochkant mit Ablage rechts |

Mit „Querformat“/„Hochformat“ drehst du das Format. Du kannst das Format jederzeit ändern: Elemente und Bereiche behalten ihre Lage (in Prozent), ein Hintergrundbild wird neu zugeschnitten. Prüfe danach kurz, ob alles noch an der richtigen Stelle sitzt und ob der Bildausschnitt im Schritt „Hintergrund“ passt.

> **Tipp:** Querformat passt gut auf Tablets und Whiteboards, Hochformat auf Smartphones. Für eine Ablage rechts neben dem Bild nimm ein Hochformat (z. B. 2:1 hochkant), für eine Ablage unten ein Querformat. Die Lage der Ablage stellst du im Schritt „Elemente“ ein (siehe [Startposition der Elemente](#startposition-der-elemente)).

## 2 Hintergrund

Unter „Art des Hintergrunds“ wählst du eine von drei Möglichkeiten: „Bild“, „Nur Farbe“ oder „Editor“. Zeichnungen fügst du im „Editor“ ein – so viele du willst (siehe [Zeichnungen einfügen](#zeichnungen-einfügen)). Die Hintergrundfarbe kannst du bei jeder Art zusätzlich einstellen. Wechselst du die Art, bleiben Bild und Editor-Inhalte erhalten – du kannst also gefahrlos zurückwechseln.

### Bild hochladen, hineinziehen oder einfügen

1. Wähle „Bild“ und klicke auf das Feld „Bild hierher ziehen oder klicken“.
2. Im Reiter „Hochladen“ hast du mehrere Wege:
   - eine Bilddatei auswählen (JPG, PNG, GIF, WebP oder SVG),
   - eine Datei aus dem Explorer/Finder auf das Feld ziehen,
   - ein Bild aus einem anderen Browserfenster direkt hineinziehen oder mit <kbd>Strg</kbd>+<kbd>V</kbd> (Mac: <kbd>⌘</kbd>+<kbd>V</kbd>) einfügen,
   - oder unter „Oder Bildadresse (URL) einfügen“ die Adresse eines Bildes angeben (klappt nur, wenn die Webseite das erlaubt).
3. Trage bei eigenen oder fremden Bildern unter „Quelle / Urheber“ ein, woher das Bild stammt. Das wird als Bildnachweis gespeichert.
4. Danach legst du den **Bildausschnitt** fest (siehe unten).

Große Fotos werden automatisch verkleinert und komprimiert, damit die Übung schnell lädt. Du musst sie vorher nicht bearbeiten.

### Bilder suchen: ARASAAC und Wikimedia Commons

- **ARASAAC (Piktogramme):** über 10.000 einheitliche, klare Piktogramme – ideal für Förderschule, DaZ und Grundschule. Suchbegriff auf Deutsch eingeben, z. B. „Hund“. Lizenz: CC BY-NC-SA 4.0 (nicht kommerziell, Namensnennung, Weitergabe unter gleichen Bedingungen). Der Pflicht-Bildnachweis wird automatisch gespeichert.
- **Wikimedia Commons:** Millionen freier Fotos, Zeichnungen und Karten mit unterschiedlichen Lizenzen. Klicke auf ein Bild, um „Lizenz“, „Urheber“ und Größe zu sehen; ein Doppelklick übernimmt es direkt. Urheber und Lizenz werden automatisch als Bildnachweis gespeichert. Die Suche antwortet manchmal etwas langsam – mit „Mehr anzeigen“ lädst du weitere Treffer.

> **Lizenzen beachten:** Verwende nur Bilder, die du selbst gemacht hast oder nutzen darfst. Die Bildnachweise stehen in der exportierten Übung unter „Bildnachweise“. Lösche sie nicht und prüfe vor dem Veröffentlichen, ob die Lizenz deine Nutzung erlaubt (z. B. „NC“ = nicht kommerziell).

### Zuschnitt: den Bildausschnitt festlegen

1. Nach dem Auswählen öffnet sich „Bildausschnitt festlegen“. Der helle Rahmen zeigt, was auf der Arbeitsfläche zu sehen ist.
2. Verschiebe das Bild mit der Maus/dem Finger und zoome mit dem Regler, dem Mausrad oder den Lupen-Knöpfen (Tastatur: Pfeiltasten verschieben, <kbd>+</kbd>/<kbd>−</kbd> zoomen).
3. „Ausfüllen“: Das Bild füllt die ganze Fläche (Ränder werden abgeschnitten). „Einpassen“: Das ganze Bild ist sichtbar, freie Flächen zeigen die Hintergrundfarbe.
4. „Übernehmen“ klicken. Später änderst du den Ausschnitt jederzeit mit „Anpassen“.

### Editor: Hintergrund aus Texten, Bildern, Tönen und Zeichnungen 

Mit der Art „Editor“ gestaltest du den Hintergrund direkt auf der Arbeitsfläche – ganz ohne Bildbearbeitung. Das ist ideal für Tabellen aus Überschriften, Wortkarten mit Bildern, Hörbeispiele oder eigene Skizzen.

1. Wähle „Editor“ und füge unter „Einfügen“ mit „Text“, „Bild“, „Ton“ oder „Zeichnung“Hintergrund-Bausteine hinzu. Für Fotos, die einen großen Teil der Fläche füllen, schalte vorher „Große Bilder (bis 2400 px)“ ein.
2. Verschiebe sie auf der Fläche und ändere ihre Größe an den Griffen – genau wie bei den Zuordnungselementen. Texte haben Schrift, Farbe, Größe und auf Wunsch einen Vorlese-Button; Karten sind zunächst durchsichtig und ohne Rahmen.
3. In der Übung sind diese Bausteine **fest**: Die Lernenden können sie nicht verschieben. Töne und Vorlese-Buttons bleiben aber anklickbar.
4. Die Bausteine liegen immer unter den Lösungsbereichen und den Zuordnungselementen. Untereinander legst du die Reihenfolge in der Liste „Auf dem Hintergrund“ mit den Pfeilen fest („Weiter nach vorne“/„Weiter nach hinten“).

### Zeichnungen einfügen 

Mit dem eingebauten Zeichenwerkzeug skizzierst du Tabellen, Zeitstrahle, Mengendiagramme, Schaubilder oder einfache Lagepläne. Jede Zeichnung ist ein eigener Baustein im Editor-Hintergrund – du kannst also mehrere Zeichnungen einfügen und jede für sich platzieren.

1. Wähle als Art des Hintergrunds „Editor“ und klicke unter „Einfügen“ auf „Zeichnung“. Das Zeichenwerkzeug „Neue Zeichnung“ öffnet sich bildschirmfüllend.
2. Zeichne Formen, Pfeile, Linien, Texte oder freie Skizzen. Über das Bild-Werkzeug fügst du auch Fotos ein. Oben findest du die Werkzeuge, links die Farben, Strichstärken und Schriften des gewählten Werkzeugs.
3. Klicke auf „Übernehmen“. Übernommen wird nur, was du zeichnest – der Hintergrund der Zeichnung ist durchsichtig, die Hintergrundfarbe und andere Bausteine scheinen also durch.
4. Die Zeichnung erscheint in der Mitte der Arbeitsfläche. Verschiebe sie und ändere ihre Größe an den Griffen – wie bei den anderen Bausteinen. Wirkt sie verzerrt, z. B. weil du nur die Breite geändert hast, stellt „Höhe an Zeichnung anpassen“ die Proportionen wieder her.

### Zeichnung nachträglich bearbeiten

Eine Zeichnung bleibt jederzeit veränderbar. Du öffnest sie auf drei Wegen:

- **Doppelklick** auf die Zeichnung auf der Arbeitsfläche (oder auswählen und <kbd>Enter</kbd> drücken),
- den Stift-Knopf „Zeichnung bearbeiten“ in der kleinen Leiste an der ausgewählten Zeichnung,
- den Knopf „Zeichnung bearbeiten“ in der Seitenleiste, wenn die Zeichnung ausgewählt ist.

Das Zeichenwerkzeug heißt dann „Zeichnung bearbeiten“. Nach „Übernehmen“ bleiben Lage und Maßstab auf der Fläche erhalten – auch wenn du die Größe vorher geändert hast. Was du ergänzt, kommt einfach dazu; die vorhandenen Striche bleiben, wo sie waren. Würde die Zeichnung danach über den Rand ragen, wird sie passend verschoben bzw. verkleinert. Mit „Abbrechen“ verwirfst du deine Änderungen (nach einer Rückfrage).

„Duplizieren“ legt eine unabhängige Kopie an – du kannst sie getrennt vom Original weiterzeichnen. In der Liste „Auf dem Hintergrund“ heißen Zeichnungen „Zeichnung 1“, „Zeichnung 2“ usw.

> **Ältere Übungen:** Übungen mit einem gezeichneten Hintergrund aus einer früheren Version werden beim Öffnen automatisch umgestellt: Sie bekommen die Art „Editor“ mit einer Zeichnung, die die ganze Fläche füllt. Du bearbeitest sie wie gewohnt im Rahmen „Übungsfläche“ und kannst weitere Texte, Bilder, Töne und Zeichnungen dazulegen.

### Nur Farbe

Ein einfarbiger Hintergrund – gut für reine Sortierübungen mit sichtbaren Bereichen (z. B. „Nomen“ | „Verben“). Setze die Bereiche dann mit Beschriftung, damit die Lernenden wissen, wohin.

## 3 Elemente

Elemente sind die Kärtchen, die die Lernenden verschieben. Lege sie im Schritt „3 Elemente“ an. Ein Klick auf ein Element (in der Liste oder auf der Arbeitsfläche) öffnet seine Einstellungen; mit den Pfeilen oben springst du zum vorherigen/nächsten Element.

### Text-Elemente

1. Klicke unter „Neues Element“ auf „Text“ und tippe den Text ein. Die Karte wächst automatisch mit.
2. **Mehrere Texte auf einmal:** Klicke auf „Mehrere Texte auf einmal“ und schreibe jeden Begriff in eine eigene Zeile (z. B. Wurzel, Stängel, Blatt, Blüte). Jede Zeile wird ein eigenes Element.

### Schriften

- **Nunito** – serifenlos und freundlich (beim ersten Start voreingestellt; danach beginnen neue Texte in der Schrift, die du zuletzt gewählt hast)
- **Atkinson Hyperlegible** – barrierefreie Schrift mit besonders gut unterscheidbaren Buchstaben (z. B. bei Sehbeeinträchtigung oder Lese-Rechtschreib-Schwierigkeiten)
- **Andika** – für Leseanfänger, mit einstöckigem „a“
- **Merriweather** – mit Serifen
- **Caveat** – Handschrift

Dazu kommen Größe, Farbe, fett, kursiv und Ausrichtung. Alle Schriften sind in die Übung eingebettet und sehen überall gleich aus.

**Zuletzt gewählte Schrift** : Schiebesachen merkt sich die Schrift, die du zuletzt gewählt hast – egal ob beim Titel, bei einem Element, bei einer Beschriftung oder bei einem Text im Hintergrund. Neue Texte und Titel sind dann gleich auf diese Schrift voreingestellt, auch der Titel einer „Neuen Übung“. So bleibt deine Übung einheitlich. Größe, Farbe und die übrigen Einstellungen änderst du wie gewohnt für jeden Text einzeln. Die Schrift wird in deinem Browser gemerkt (siehe Datenschutz) und gilt auch, wenn du Schiebesachen später wieder öffnest.

### Bild-Elemente

Klicke auf „Bild“ und wähle ein Bild wie beim Hintergrund (Hochladen, Hineinziehen, Einfügen, ARASAAC, Wikimedia Commons). Optional steht eine „Beschriftung“ unter dem Bild. Mit „Bild ändern“ tauschst du das Bild aus, ohne Größe und Zuordnung zu verlieren.

### Ton-Elemente

1. Klicke auf „Ton“. Im Reiter „Hochladen“ wählst du eine Tondatei (MP3, M4A, OGG, WAV oder WebM) oder ziehst sie hinein.
2. Im Reiter „Aufnehmen“ nimmst du direkt mit dem Mikrofon auf: auf das Mikrofon klicken, deutlich sprechen, mit Stopp beenden (höchstens 5 Minuten). Der Browser fragt beim ersten Mal, ob er das Mikrofon verwenden darf.
3. **Mikrofon nur einmal freigeben** : Nach der ersten Aufnahme bleibt das Mikrofon für diese Sitzung freigegeben – du musst nicht vor jeder Aufnahme neu zustimmen (das gilt für Töne und eigene Vorlese-Aufnahmen). Solange es freigegeben ist, zeigt dein Browser das Mikrofon-Symbol. Mit „Mikrofon trennen“ gibst du es sofort frei; spätestens beim Schließen der Seite passiert das automatisch. Aufgenommen wird nur, während die Aufnahme läuft.
4. **Zuschneiden** : Danach siehst du die Wellenform des Tons. Ziehe die Griffe an Anfang und Ende, um Stille oder Versprecher abzuschneiden. Mit „Auswahl anhören“ prüfst du den markierten Teil, mit „Alles anhören“ den ganzen Ton.„Stille automatisch entfernen“ schneidet leise Stellen am Anfang und Ende ab, „Zurücksetzen“ nimmt wieder den ganzen Ton. Nur der markierte Teil wird übernommen. (Tastatur: Griff anwählen, mit den Pfeiltasten verschieben.)
5. „Übernehmen“ klicken. In der Übung erscheint ein runder Abspiel-Knopf; eine optionale Beschriftung steht darunter.

> **Tipp:** Kurze Töne (wenige Sekunden) halten die Datei klein. Lange Aufnahmen machen die Übung schnell mehrere Megabyte groß.

Gib Ton-Elementen am besten eine „Beschriftung“: Dann klappt auch das PDF-Arbeitsblatt – dort steht statt des Tons die Beschriftung (siehe [PDF](#pdf-arbeitsblatt-und-lösung)).

### Vorlesen und eigene Aufnahme

1. Schalte bei einem Element unter „Vorlesen“ den „Vorlesen-Button anzeigen“ ein. Auf der Karte erscheint oben rechts ein kleiner Lautsprecher – er sitzt wie ein Abzeichen auf der Ecke und verdeckt keinen Text.
2. Ohne eigene Aufnahme liest die **Computerstimme des Geräts** den Text vor (deutsche Stimme des Browsers). Mit „Probehören“ testest du sie.
3. Für eine **eigene Aufnahme** klicke auf „Eigene Aufnahme verwenden“, nimm auf (oder lade eine Datei hoch) und schneide sie zu. Sie wird dann statt der Computerstimme abgespielt – z. B. für Fremdsprachen, Dialekt oder Lautieren.

Vorlesen gibt es auch für den Titel, für Bild-Elemente mit Beschriftung, für Texte im Hintergrund-Editor und für Beschriftungen von Lösungsbereichen.

### Größe und Karte

- Ziehe auf der Arbeitsfläche an den Griffen eines ausgewählten Elements, oder stelle unter „Größe & Aussehen“ Breite und Höhe ein. „Größe an Text anpassen“ bzw. „Höhe an Bild anpassen“ macht die Karte wieder passend.
- Alle Elemente sind gleich behandelt: In der Ablage hat jede Karte dieselbe Größe wie auf der Fläche.
- „Hintergrund der Karte“ (Farbe oder durchsichtig) und „Rahmen anzeigen“ bestimmen das Aussehen der Karte.

### Richtige Bereiche und Ablenker

Unter „Richtig in diesen Bereichen“ hakst du ab, wohin das Element gehört – es darf auch in mehrere Bereiche passen. Ein Element **ohne Haken** ist ein **Ablenker**: Es passt nirgends hin und bringt keine Punkte. Ablenker machen eine Übung anspruchsvoller.

Elemente kopierst du mit „Duplizieren“ oder <kbd>Strg</kbd>+<kbd>D</kbd>, löschen geht mit „Löschen“ bzw. dem Papierkorb oder <kbd>Entf</kbd>.

### Startposition der Elemente 

Wo die Elemente zu Beginn der Übung liegen, stellst du direkt im Schritt „3 Elemente“ ein – in der Liste gleich unter „Neues Element“ (früher stand das im Schritt „Ablauf“). Solange die Einstellungen eines Elements offen sind, ist der Abschnitt ausgeblendet; schließe sie, um ihn wieder zu sehen.

- **„Ablageleiste“**: Die Elemente liegen ordentlich in einer Leiste unter oder neben der Arbeitsfläche. Unter „Lage der Ablage“ wählst du „Unter dem Bild“ oder „Rechts daneben“. Auf schmalen Bildschirmen (z. B. Smartphone) rückt die Ablage automatisch unter das Bild.
- **„Frei auf der Fläche“**: Die Elemente starten dort, wo du sie im Editor hinlegst – z. B. für Übungen, in denen Dinge auf einer Karte verschoben werden. Beim Umschalten verteilt Schiebesachen übereinanderliegende Elemente am rechten und unteren Rand. Mit „Elemente neu anordnen“ machst du das jederzeit erneut.

Rechts passt am besten ein Hochformat, unten ein Querformat. Passt das Format nicht zur Lage der Ablage, erscheint ein Hinweis mit dem Knopf „Format passend wählen (…)“ – ein Klick stellt ein passendes Format ein (z. B. 2:1 hochkant für die Ablage rechts). Prüfe danach kurz, ob Bereiche und Hintergrund noch passen.

**Viele Elemente:** Die Ablage wächst nicht mit, sondern wird scrollbar – unten waagerecht, rechts senkrecht. Pfeile am Rand zeigen, dass es weitere Elemente gibt. Ziehen klappt auch aus der scrollenden Ablage heraus.

## 4 Lösungsbereiche

Lösungsbereiche sind die Stellen, an denen Elemente abgelegt werden können.

### Bereiche anlegen

1. Wechsle in den Schritt „4 Bereiche“. **Klicke** auf eine Stelle des Hintergrunds – dort entsteht ein Bereich. Oder **ziehe ein Rechteck auf**, um Lage und Größe gleich festzulegen.
2. Verschiebe den Bereich und ändere seine Größe an den Griffen. Unter „Lage & Größe“ (bei „Nur Punkt“ und „Pfeil“: „Lage & Trefferfläche“) kannst du die Werte auch genau eintippen.
3. Schnell: „Für jedes Element einen Bereich anlegen“ erzeugt passende Bereiche für alle Elemente, die noch keinen haben.

### Darstellung

| Sichtbar | gestrichelter Rahmen mit leichter Füllung – die Lernenden sehen, wo etwas hingehört. |
|---|---|
| Nur Punkt | nur ein kleiner Ring in der Mitte; die (unsichtbare) Trefferfläche ist das ganze Rechteck. Gut für Beschriftungen an Bildern. |
| Pfeil  | Punkt mit Pfeil: Das Element rastet am Punkt ein, der Pfeil zeigt auf die passende Stelle im Bild. Praktisch zum Beschriften von Bildteilen – siehe [Pfeil-Bereiche](#pfeil-bereiche-bildteile-beschriften). |
| Größe wie Element | sichtbarer Rahmen in genau der Größe des richtigen Elements – das Element „passt hinein“. |
| Unsichtbar  | In der Übung ist nichts zu sehen, die Trefferfläche ist aber aktiv (im Editor schwach gestrichelt). Die Lernenden müssen die richtige Stelle im Bild selbst finden – nutze das nur mit einem aussagekräftigen Hintergrund. |

Die Darstellung wählst du beim ausgewählten Bereich unter „Darstellung“. „Darstellung neuer Bereiche“ legt fest, wie neu angelegte Bereiche aussehen.

### Pfeil-Bereiche: Bildteile beschriften 

Mit der Darstellung „Pfeil“ beschriften die Lernenden Bilder wie in einem Schulbuch: Neben dem Bild liegt ein Punkt, von dem ein Pfeil auf die gemeinte Stelle zeigt – z. B. auf das Blatt einer Pflanze. Das abgelegte Element verdeckt den Punkt, der Pfeil ragt darunter hervor.

1. Lege den Bereich dort an, wo das Element später liegen soll (z. B. neben dem Bild), und wähle unter „Darstellung“ die Option „Pfeil“. Sollen alle neuen Bereiche Pfeile bekommen, stelle „Darstellung neuer Bereiche“ auf „Pfeil“.
2. Auf der Arbeitsfläche sitzt an der Pfeilspitze ein runder Griff. **Ziehe ihn mit der Maus oder dem Finger** an die Stelle im Bild, auf die der Pfeil zeigen soll – der Pfeil passt sich an. Mit der Tastatur: Bereich auswählen, mit <kbd>Tab</kbd> den Griff „Pfeilspitze verschieben“ ansteuern und mit den Pfeiltasten verschieben (mit <kbd>Umschalt</kbd> in größeren Schritten).
3. Im Abschnitt „Pfeil“ der Seitenleiste wählst du die „Farbe des Pfeils“ (z. B. Weiß auf dunklen Fotos). Unter „Spitze links“ und „Spitze oben“ tippst du die Lage der Spitze auch genau ein (in Prozent der Fläche).
4. Verschiebst du den Bereich, bleibt die Pfeilspitze, wo sie ist – nur der Punkt wandert mit. Beim „Duplizieren“ wandert die Spitze der Kopie mit. „Pfeil zurücksetzen“ stellt Spitze und Farbe wieder auf den Anfang.

Liegt die Spitze zu nah am Punkt, ist kein Pfeil zu sehen; die Seitenleiste weist dich dann darauf hin. Getroffen wird wie bei „Nur Punkt“ das ganze (unsichtbare) Rechteck des Bereichs. Auch auf dem PDF-Arbeitsblatt erscheinen die Pfeile.

### Beschriftung und Vorlesen

Unter „Name des Bereichs“ gibst du einen Namen ein (z. B. „Wurzel“). Er hilft dir beim Zuordnen. Mit „Beschriftung anzeigen“ sehen ihn auch die Lernenden oben links im Bereich.  Zusätzlich kannst du für die Beschriftung einen **Vorlese-Button** einschalten (Computerstimme oder eigene Aufnahme) – z. B. für Oberbegriffe in einer Sortierübung.

### Richtige Elemente zuordnen

- **Per Häkchen:** Wähle den Bereich aus und hake unter „Richtige Elemente“ alle Elemente an, die hierhin gehören. (Umgekehrt geht es im Schritt „Elemente“ unter „Richtig in diesen Bereichen“.)
- **Per Ziehen aus der Ablage:** Bei der Startposition „Ablageleiste“ ziehst du ein Element aus der Ablage unter (bzw. neben) der Arbeitsfläche auf einen Bereich. Damit wird es dort als richtig markiert – ein zweites Ziehen entfernt die Markierung wieder.
- **Alt-Ziehen bei freier Anordnung:** Liegen die Elemente „Frei auf der Fläche“, halte <kbd>Alt</kbd> (Mac: <kbd>⌥</kbd>) gedrückt, während du ein Element auf einen Bereich ziehst. Das Element wird als richtig markiert (oder die Markierung entfernt) und springt an seinen Startplatz zurück.

### Nur ein Element

Mit „Nur ein Element erlaubt“ nimmt ein Bereich höchstens ein Element auf – ist er belegt, kann nichts weiter abgelegt werden. Sonst rasten mehrere Elemente ordentlich nebeneinander bzw. untereinander ein. Gehören mehrere Elemente hinein, aber nur eines passt, gilt jedes davon als richtig.

> **Achtung:** Ein Bereich ohne richtiges Element nimmt nichts richtig auf. Die Checkliste im Schritt „Ablauf“ weist dich darauf hin.

## 5 Ablauf & Feedback

### Rückmeldung

- **Sofort-Feedback:** Rückmeldung bei jedem Ablegen. Falsche Elemente springen zurück und können neu versucht werden. Punkte gibt es nur, wenn ein Element **beim ersten Versuch** richtig abgelegt wurde.
- **Überprüfen-Button:** Erst alle Elemente zuordnen, dann mit „Überprüfen“ auswerten. Richtige und falsche Elemente werden markiert; die Lernenden können Fehler korrigieren.

Die „Startposition der Elemente“ (Ablageleiste oder frei) und die „Lage der Ablage“ stellst du jetzt im Schritt „Elemente“ ein – siehe [Startposition der Elemente](#startposition-der-elemente).

### Optionen

- „Reihenfolge mischen“: Die Elemente liegen bei jedem Start anders in der Leiste (nur bei der Ablageleiste).
- „Bereiche beim Ziehen hervorheben“: zeigt beim Ziehen, wo etwas abgelegt werden kann.
- „„Nochmal“-Button“: Die Übung kann neu begonnen werden.
- „„Lösung anzeigen“-Button“: Nach dem Auswerten kann die richtige Lösung eingeblendet werden.

### Bewertung

Jedes richtig zugeordnete Element gibt **einen Punkt**; Fehler kosten keine Punkte. Ablenker zählen nicht mit. Die **Bestehensgrenze** (in Prozent) legt fest, ab wann die Übung als bestanden gilt – wichtig für SCORM in mebis.

### Checkliste

Die Checkliste unten im Schritt „Ablauf“ prüft deine Übung: fehlender Titel, Elemente ohne Bereich, leere Bereiche, unsichtbare Bereiche auf einfarbigem Hintergrund, Ton-Elemente ohne Beschriftung (die das PDF verhindern) usw. Ein Klick auf einen Eintrag führt dich direkt zur Stelle. Steht dort „Alles bereit!“, kannst du testen.

## Testen

1. Klicke oben auf „Testen“. Die Übung startet genau so, wie die Lernenden sie sehen.
2. Ziehe Elemente, probiere Vorlese-Buttons und Töne aus, werte aus und teste „Nochmal“ und „Lösung anzeigen“.
3. „Neu starten“ beginnt von vorn, „Zurück zum Bearbeiten“ (oder „Bearbeiten“ oben) führt zurück in den Editor.

> **Tipp:** Teste auch auf einem Smartphone oder Tablet: Exportiere dazu die HTML-Datei und öffne sie auf dem Gerät. Ziehen funktioniert mit Finger, Maus, Stift und Tastatur.

## Exportieren

Klicke oben rechts auf „Exportieren“ (dafür braucht die Übung einen Titel). Hast du noch Hinweise in der Checkliste, zeigt der Dialog sie an – exportieren kannst du trotzdem.

### Projektdatei (JSON)

Die Arbeitsdatei zum **Weiterbearbeiten** in Schiebesachen – mit allen Bildern und Tönen. Damit sicherst du Übungen, gibst sie an Kolleginnen und Kollegen weiter oder bearbeitest sie auf einem anderen Gerät weiter. Für Lernende ist sie nicht gedacht.

### HTML-Datei

Eine einzelne Datei, die in jedem Browser läuft – auch ohne Internet. Zum Verschicken per E-Mail oder Messenger, zum Ablegen auf dem Schulserver oder in mebis als Material „Datei“. Ergebnisse werden dabei nicht gespeichert. Tipp: Eine exportierte HTML-Datei kannst du über „Öffnen …“ auch wieder in Schiebesachen laden und weiterbearbeiten.

### HTML-Datei in mebis/Moodle einbetten (iframe) 

So erscheint die Übung direkt in mebis – auch mitten in einem Textfeld, auf einer Textseite oder in der Abschnittsbeschreibung. Nach dem Herunterladen der HTML-Datei zeigt der Export-Dialog dir dafür die Anleitung „In mebis/Moodle einbetten“. Du kannst sie auch ohne Download über den Link „Einbetten in mebis/Moodle“ bei der HTML-Datei öffnen.

1. Klicke bei „HTML-Datei (eigenständig)“ auf „Herunterladen“. Die Datei landet in deinem Download-Ordner, der Dialog wechselt zu „In mebis/Moodle einbetten“.
2. In mebis im Kurs „Bearbeiten“ einschalten und die **HTML-Datei hochladen** – z. B. als Material „Datei“ mit der Anzeige „Eingebettet“ oder im Texteditor eines Textfelds bzw. einer Seite über „Link“ oder „Medien“ → „Datei hochladen“. Als Material „Datei“ mit „Eingebettet“ sehen die Lernenden die Übung schon dort – dann bist du fertig. Die nächsten Schritte brauchst du nur für ein Textfeld oder eine Seite.
3. **Link der Datei kopieren:** Klicke mit der rechten Maustaste auf den Dateinamen der hochgeladenen Datei und wähle „Link-Adresse kopieren“. Der Link beginnt meist mit https://mebis.bycs.de/ und enthält „pluginfile.php“.
4. Füge den Link im Export-Dialog in das Feld „Link der HTML-Datei“ ein. Der „iframe-Code“ darunter ist dann fertig – mit passender Höhe für deine Übung. Klicke auf „Code kopieren“.
5. In mebis den Texteditor des Textfelds öffnen, auf die HTML-Ansicht umschalten (Atto: Symbol `</>` in der erweiterten Werkzeugleiste; TinyMCE: „Quellcode“ bzw. `<>`), den Code einfügen und speichern.

- Hast du versehentlich den Link zur Material-Seite statt zur Datei kopiert, oder endet der Link nicht auf .html, weist dich das Feld darauf hin. Ein angehängtes `forcedownload` entfernt Schiebesachen selbst, damit die Übung angezeigt statt heruntergeladen wird.
- Die Höhe ist geschätzt. Ist unten etwas abgeschnitten oder bleibt zu viel Platz, ändere im Code den Wert bei `height`. Die Breite passt sich automatisch an (100 %).
- Du kannst den Code auch ohne Link kopieren und später `HIER-DEN-LINK-ZUR-HTML-DATEI-EINFUEGEN` durch den Link ersetzen.

> **Keine Ergebnisse:** Eine eingebettete HTML-Datei speichert keine Ergebnisse. Für Punkte in der Bewertungsübersicht von mebis nimm das [SCORM-Paket](#scorm-paket-mebis-als-lernpaket).

### SCORM-Paket (mebis als „Lernpaket“)

Mit SCORM landen die Ergebnisse in der Bewertungsübersicht von mebis.

1. Im Export-Dialog das SCORM-Paket (ZIP-Datei) herunterladen – nicht entpacken.
2. In mebis im Kurs „Bearbeiten“ einschalten → „Aktivität oder Material anlegen“ → „Lernpaket (SCORM)“.
3. Namen eingeben und die ZIP-Datei in das Feld „Paketdatei“ ziehen.
4. Unter „Bewertung“ und „Versuchsverwaltung“ festlegen, wie Punkte gewertet werden (z. B. höchste Bewertung) und wie viele Versuche erlaubt sind. Speichern – fertig.

**Bewertung:** Übertragen werden Punkte, Prozent und „bestanden“/„nicht bestanden“ (nach deiner Bestehensgrenze). **Wiederaufnahme:** Verlassen Lernende eine angefangene Übung, geht es beim nächsten Öffnen an derselben Stelle weiter.

### PDF: Arbeitsblatt und Lösung

- „Zum Ausschneiden“: Arbeitsblatt mit nummerierten, leeren Bereichen und den Kärtchen zum Ausschneiden und Aufkleben.
- „Mit Nummern zuordnen“: Neben jedem Kärtchen steht ein Kästchen „Bereich ☐“, in das die Lernenden die Nummer des Bereichs schreiben.
- „Lösungsblatt anhängen“ fügt eine Seite mit der richtigen Lösung hinzu.

**PDF mit Tönen** : Papier kann nichts abspielen, ein PDF klappt aber trotzdem:

- Ton-Elemente mit Beschriftung erscheinen als Kärtchen mit ihrer Beschriftung und einem kleinen Lautsprecher-Symbol.
- Eigene Vorlese-Aufnahmen (bei Titel, Texten, Bildern und Bereichsbeschriftungen) und Vorlese-Buttons werden einfach weggelassen – der Text steht ja da.
- Töne auf dem Hintergrund (Editor) erscheinen mit ihrer Beschriftung; ohne Beschriftung werden sie weggelassen.

Nur ein **Ton-Element ohne Beschriftung** verhindert das PDF – sein Kärtchen bliebe auf Papier leer. Der Export-Dialog und die Checkliste nennen dann das betroffene Element (z. B. „Element 3“); ein Klick in der Checkliste öffnet es. Gib ihm eine „Beschriftung“, dann klappt auch der PDF-Export.

### Welcher Export wofür?

| Ziel | Export |
|---|---|
| Übung in mebis mit Bewertung | SCORM-Paket |
| Übung in mebis mitten im Text | HTML-Datei hochladen + iframe-Code („Einbetten in mebis/Moodle“) |
| Verschicken, Schulserver, offline | HTML-Datei |
| Ausdrucken | PDF |
| Später weiterbearbeiten, teilen mit Kolleginnen und Kollegen | JSON (oder HTML-Datei) |

## Speichern & Weiterbearbeiten

### Automatisch im Browser

Jede Änderung wird nach kurzer Zeit automatisch **in deinem Browser** gespeichert (oben steht „Automatisch gespeichert“). Öffnest du Schiebesachen später im selben Browser auf demselben Gerät wieder, ist deine Übung noch da.

> **Achtung:** Der Browser-Speicher ist kein Archiv: Er gilt nur für diesen Browser auf diesem Gerät, und er geht verloren, wenn du die Browserdaten löschst oder im privaten Modus arbeitest. Es gibt immer nur **eine** aktuelle Übung.

### Als JSON sichern

1. Klicke oben rechts auf das Ordner-Symbol → „Als JSON speichern“.
2. Die Datei landet in deinem Download-Ordner. Bewahre sie z. B. in deinem Schul-Cloudspeicher auf.

### Öffnen

Ordner-Symbol → „Öffnen …“ lädt eine JSON-Datei **oder eine exportierte HTML-Übung** wieder in den Editor. Die aktuelle Übung wird dabei ersetzt – sichere sie vorher, wenn du sie behalten möchtest.

Zeichnungen aus einer exportierten HTML-Übung kannst du danach nur noch verschieben, vergrößern und löschen, aber nicht mehr weiterzeichnen – die Zeichen-Daten stecken nur in der JSON-Datei. Sichere deshalb immer auch die JSON-Datei.

### Neue Übung

Ordner-Symbol → „Neue Übung“ beginnt mit einer leeren Übung (nach einer Sicherheitsabfrage). Die zuletzt gewählte Schrift bleibt erhalten – der neue Titel beginnt gleich in ihr.

### Rückgängig und Wiederholen

Mit den Pfeilen oben oder <kbd>Strg</kbd>+<kbd>Z</kbd> machst du Schritte rückgängig, mit <kbd>Strg</kbd>+<kbd>Umschalt</kbd>+<kbd>Z</kbd> oder <kbd>Strg</kbd>+<kbd>Y</kbd> stellst du sie wieder her. Auch gelöschte Bilder oder Elemente holst du so zurück.

## Tastenkürzel

Auf dem Mac nimmst du statt <kbd>Strg</kbd> die Befehlstaste <kbd>⌘</kbd> und statt <kbd>Alt</kbd> die Taste <kbd>⌥</kbd>.

| <kbd>Strg</kbd>+<kbd>Z</kbd> | Rückgängig |
|---|---|
| <kbd>Strg</kbd>+<kbd>Umschalt</kbd>+<kbd>Z</kbd> oder <kbd>Strg</kbd>+<kbd>Y</kbd> | Wiederholen |
| <kbd>Tab</kbd>, dann <kbd>Enter</kbd> | auf der Arbeitsfläche zu Elementen und Bereichen springen und auswählen |
| <kbd>Enter</kbd> oder Doppelklick | ausgewählte Zeichnung im Editor-Hintergrund bearbeiten |
| Pfeiltasten | ausgewähltes Element/Bereich verschieben (mit <kbd>Umschalt</kbd> in größeren Schritten) |
| <kbd>Tab</kbd>, dann Pfeiltasten | bei einem ausgewählten Pfeil-Bereich: zum Griff der Pfeilspitze springen und nur die Spitze verschieben |
| <kbd>Entf</kbd> / <kbd>⌫</kbd> | Auswahl löschen |
| <kbd>Strg</kbd>+<kbd>D</kbd> | Auswahl duplizieren |
| <kbd>Esc</kbd> | Auswahl aufheben, Ziehen abbrechen, Dialog schließen |
| <kbd>Alt</kbd> + Ziehen | bei freier Anordnung: Element in einem Bereich als richtig markieren |
| <kbd>Strg</kbd>+<kbd>V</kbd> | im Bild-Dialog: Bild aus der Zwischenablage einfügen |

## Barrierefreiheit

Die fertigen Übungen lassen sich vollständig mit der Tastatur bedienen – wie bei H5P:

1. Mit <kbd>Tab</kbd> ein Element ansteuern.
2. Mit <kbd>Leertaste</kbd> oder <kbd>Enter</kbd> das Element „aufnehmen“.
3. Mit <kbd>Tab</kbd> oder den Pfeiltasten einen Bereich wählen.
4. Mit <kbd>Leertaste</kbd>/<kbd>Enter</kbd> ablegen. <kbd>Esc</kbd> bricht ab.

Bildschirmleser bekommen Ansagen wie „Element … aufgenommen“, „abgelegt in Bereich 2“ und das Ergebnis.

### So machst du Übungen zugänglicher

- Barrierefreie Schrift (Atkinson Hyperlegible) oder Andika für Leseanfänger wählen, Schrift ausreichend groß einstellen.
- Vorlese-Buttons für Titel, Elemente und Bereichsbeschriftungen einschalten – eigene Aufnahmen klingen oft natürlicher.
- Starke Kontraste verwenden (dunkle Schrift auf hellen Karten).
- Bereiche lieber sichtbar und beschriftet anlegen; „Unsichtbar“ nur, wenn das Finden selbst Teil der Aufgabe ist.
- Bilder mit Beschriftung versehen, damit sie auch ohne Bild verständlich sind.

## Tipps & häufige Fragen

Darf ich jedes Bild aus dem Internet verwenden?

Nein. Nutze eigene Bilder, ARASAAC oder Wikimedia Commons und beachte die Lizenz. Bei ARASAAC und Wikimedia Commons speichert Schiebesachen den Bildnachweis automatisch; bei eigenen Uploads trägst du ihn unter „Quelle / Urheber“ ein. Fotos von Schülerinnen und Schülern nur mit Einwilligung!

Die Datei ist sehr groß – was tun?

Bilder werden schon automatisch verkleinert. Groß werden Übungen vor allem durch lange Töne und viele Fotos. Schneide Aufnahmen auf das Nötige zu, nutze Piktogramme statt Fotos und lösche nicht mehr benötigte Bilder. Der Export-Dialog zeigt die ungefähre Dateigröße an. mebis hat für Uploads eine Größenbegrenzung.

Im iframe wird die Übung heruntergeladen statt angezeigt – oder es erscheint eine mebis-Seite.

Wahrscheinlich ist im Code der Link zur Material-Seite statt zur Datei. Öffne das Material, klicke mit der rechten Maustaste auf den Dateinamen, wähle „Link-Adresse kopieren“ und füge diesen Link im Export-Dialog unter „Einbetten in mebis/Moodle“ neu ein (siehe [Einbetten](#html-datei-in-mebismoodle-einbetten-iframe)).

Im iframe ist unten etwas abgeschnitten oder es bleibt zu viel Platz.

Die Höhe im iframe-Code ist geschätzt. Öffne im Texteditor die HTML-Ansicht und ändere im Code den Wert bei `height` (z. B. von 600 auf 700). Die Breite passt sich von selbst an.

Warum kann ich kein PDF erstellen?

Mindestens ein Ton-Element hat keine Beschriftung – auf Papier bliebe sein Kärtchen leer. Der Export-Dialog und die Checkliste nennen das Element. Gib ihm eine Beschriftung, dann klappt das PDF. Alle anderen Töne und eigenen Aufnahmen stören nicht (siehe [PDF](#pdf-arbeitsblatt-und-lösung)).

Der Ton bzw. das Vorlesen ist stumm.

Prüfe die Lautstärke und ob das Gerät stummgeschaltet ist (bei iPhone/iPad auch den Stumm-Schalter). Die Computerstimme hängt vom Gerät ab: Manche Geräte haben keine deutsche Stimme – dann hilft eine eigene Aufnahme.

Das Mikrofon funktioniert nicht.

Erlaube den Zugriff: Klicke in der Adresszeile auf das Schloss- bzw. Mikrofon-Symbol und erlaube das Mikrofon. Ein anderes Programm (z. B. eine Videokonferenz) kann das Mikrofon blockieren. Hast du das Mikrofon gewechselt, klicke auf „Mikrofon trennen“ – die nächste Aufnahme fragt dann neu nach.

Warum ist das Mikrofon nach der Aufnahme noch an?

Damit du nicht vor jeder Aufnahme neu zustimmen musst (Chrome fragt bei einer geöffneten Datei sonst jedes Mal), bleibt das Mikrofon für diese Sitzung freigegeben. Aufgenommen wird nur, während die Aufnahme läuft, und nichts wird verschickt. Mit „Mikrofon trennen“ gibst du es sofort frei, beim Schließen der Seite automatisch.

Wie gebe ich eine Übung an eine Kollegin weiter?

Schicke ihr die JSON-Datei oder die exportierte HTML-Datei. Beide lassen sich in Schiebesachen über „Öffnen …“ wieder bearbeiten.

Brauche ich Internet?

Nur für die Bildsuche (ARASAAC, Wikimedia Commons). Alles andere – auch Zeichnen (samt Schriften), Aufnehmen und Exportieren – funktioniert offline. Exportierte Übungen laufen ebenfalls ohne Internet.

Kann ich Schiebesachen wie eine App speichern?

Ja: Füge die Datei zum Startbildschirm hinzu (iPad/iPhone: Teilen → „Zum Home-Bildschirm“) oder lege ein Lesezeichen an. Am einfachsten speicherst du die HTML-Datei von Schiebesachen auf deinem Rechner und öffnest sie per Doppelklick.

Weitere Ideen und Materialien findest du auf [Lernsachen.blog](https://lernsachen.blog).
