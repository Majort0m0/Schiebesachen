# Schiebesachen

**Zuordnungsübungen ganz einfach** – ein Editor für interaktive Drag-and-Drop-Übungen (ähnlich H5P „Drag and Drop“) für den Unterricht, z. B. für ByCS mebis/Moodle.

**▶ Direkt im Browser starten:** https://majort0m0.github.io/Schiebesachen/

**⬇ Herunterladen:** [Schiebesachen.html](https://github.com/Majort0m0/Schiebesachen/releases/latest/download/Schiebesachen.html) (eine einzige Datei, läuft offline – einfach doppelklicken)

- Mehrseitige Übungen: mehrere Seiten mit „Weiter“/„Zurück“ und Gesamtergebnis (auch in SCORM und im PDF)
- Neue Übungen aus Übungsformaten – Bild und Wort, Oberbegriffe sortieren, Artikel (der, die, das), Reihenfolge, Paare, Bild beschriften, Buchstabieren, Silbenlesen: nur die Begriffe aufschreiben oder von einer KI vorschlagen lassen, Anordnung, Design und Piktogramme macht Schiebesachen
- Texte, Bilder (Upload, ARASAAC, Wikimedia Commons) und Töne (Upload oder Aufnahme) als Zuordnungselemente
- Hintergrund als Bild, Farbe oder frei gestaltet im Editor – mit Texten, Bildern, Tönen und eigenen Zeichnungen
- Lösungsbereiche sichtbar, als Punkt, als Pfeil, in Elementgröße oder unsichtbar
- Vorlesen per Sprachausgabe oder eigener Aufnahme, gut lesbare Schriften (u. a. Atkinson Hyperlegible, Andika)
- Export als HTML-Datei (auch zum Einbetten per iframe), SCORM-1.2-Paket mit Bewertung oder PDF-Arbeitsblatt mit Lösung
- Keine Anmeldung, kein Server, keine Cookies – siehe [Datenschutz](DATENSCHUTZ.md)

## Lizenz

Schiebesachen – Lizenz: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de) Lernsachen.blog ([https://lernsachen.blog](https://lernsachen.blog))

Du darfst Schiebesachen kopieren, weitergeben und verändern – auch in deiner Schule und im Kollegium –, solange du Lernsachen.blog als Urheber nennst, auf die Lizenz verweist, es nicht kommerziell nutzt und Veränderungen unter derselben Lizenz weitergibst. Die Übungen, die du damit erstellst, gehören dir; für darin verwendete Bilder und Töne gelten deren eigene Lizenzen.

Enthaltene Bausteine: [Preact](https://preactjs.com), [Immer](https://immerjs.github.io/immer/), [Excalidraw](https://excalidraw.com) (MIT-Lizenz); [Anthropic TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) für die KI-Schnittstelle ([Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)); Schriften Lexend, Nunito, Atkinson Hyperlegible, Andika, Merriweather, Caveat (SIL Open Font License 1.1). Bilder aus der Suche behalten ihre eigenen Lizenzen (ARASAAC: CC BY-NC-SA 4.0). Silbentrennung (Silben rot und blau): [Hypher](https://github.com/bramstein/hypher) (© 2011 Bram Stein, BSD-3-Clause) mit den deutschen TeX-Trennmustern dehyphn-x-2011-06-01 (© 2007–2011 Werner Lemberg, [LaTeX Project Public License 1.3c](https://www.latex-project.org/lppl/)), von Bram Stein ins Hypher-Format umgewandelt (npm-Paket hyphenation.de 0.2.1); die Silbenregeln für Sprechsilben kommen danach dazu. Die Autoren der Trennmuster sind für diese App nicht verantwortlich. Unverändertes Original: [tex-hyphen](https://github.com/hyphenation/tex-hyphen) (hyph-de-1996.tex, Stand 2011-06-01) bzw. CTAN (hyph-utf8).

<details><summary>Lizenztext von Hypher (BSD-3-Clause)</summary>

```
Copyright (c) 2011, Bram Stein
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

 1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
 2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.
 3. The name of the author may not be used to endorse or promote products
    derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE AUTHOR "AS IS" AND ANY EXPRESS OR IMPLIED
WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT,
INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY
OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE,
EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

</details>

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
6. **Testen und speichern** – oben auf „Testen“ klicken und die Übung selbst ausprobieren. Dann „Speichern“: als HTML-Datei (auch zum Einbetten in mebis), als SCORM-Paket für mebis mit Bewertung oder als PDF-Arbeitsblatt.

> **Tipp:** Schneller geht es mit einem **Übungsformat**: Bild und Wort, Oberbegriffe, Artikel, Reihenfolge, Paare, Bild beschriften, Buchstabieren oder Silbenlesen – du schreibst nur die Begriffe auf (oder lässt sie von einer KI vorschlagen), den Rest baut Schiebesachen. Siehe [Neue Übung: Formate & KI](#neue-übung-formate--ki).

> **Tipp:** Deine Arbeit wird automatisch im Browser gespeichert. Sichere wichtige Übungen trotzdem zusätzlich als Datei (Ordner-Symbol oben rechts → „Als HTML-Datei speichern“) – siehe [Speichern & Weiterbearbeiten](#speichern--weiterbearbeiten).

### So ist der Editor aufgebaut

- **Obere Leiste:** Titel der Übung, Rückgängig/Wiederholen, Umschalter „Bearbeiten“/„Testen“, Datei-Menü (Ordner-Symbol), Anleitung, Datenschutz und „Speichern“.
- **Schrittleiste** (links, auf dem Smartphone unten): die fünf Arbeitsschritte. Ein roter Punkt zeigt an, dass dort noch etwas fehlt (z. B. der Titel).
- **Seitenleiste:** alle Einstellungen des gewählten Schritts bzw. des ausgewählten Elements oder Bereichs.
- **Arbeitsfläche:** zeigt die Übung so, wie die Lernenden sie sehen. Hier verschiebst und vergrößerst du Elemente und Bereiche direkt mit der Maus oder dem Finger.
- **Seitenleiste unter der Arbeitsfläche:** die Seiten der Übung – eine Übung kann mehrere Seiten haben (siehe [Mehrere Seiten](#mehrere-seiten)).

## Neue Übung: Formate & KI

Beim ersten Start und bei „Neue Übung“ (Ordner-Symbol) fragt Schiebesachen, womit du anfangen möchtest: mit einer **leeren Übung** oder mit einem **Übungsformat**. Bei einem Format schreibst du nur die Begriffe auf – Anordnung, Bereiche, Überschriften und Bilder macht Schiebesachen. *(neu)*

### Die Übungsformate

| Format | So schreibst du es | Was entsteht |
|---|---|---|
| **Bild und Wort** | `Igel` – ein Wort pro Zeile | Zu jedem Wort ein Bild, darunter ein Bereich. Umschalter: „Wörter zu den Bildern“ oder „Bilder zu den Wörtern“ (dann werden die Bilder gezogen). 2 bis 8 Wörter. |
| **Oberbegriffe sortieren** | `# Säugetier`, darunter die Karten | Eine Spalte je Oberbegriff (2 bis 4), jede Spalte nimmt mehrere Karten auf. Bis zu 16 Karten. |
| **Artikel: der, die, das** | `der Tisch` | Drei Spalten in den Artikelfarben (der blau, die rot, das grün); auf der Karte steht nur das Nomen. 3 bis 15 Nomen. |
| **Reihenfolge** | `1. Ei` – die Schritte in der richtigen Reihenfolge (Nummern sind freiwillig) | Nummerierte Bereiche 1., 2., 3. … 2 bis 8 Schritte. |
| **Paare zuordnen** | `Deutschland = Berlin` | Links der feste Begriff, rechts ein Bereich für die passende Karte. 2 bis 8 Paare. |
| **Bild beschriften** | `Blüte` – ein Begriff pro Zeile | Bereiche am linken und rechten Rand, Ablage rechts. Danach wählst du im Schritt „2 Hintergrund“ das Bild und schiebst die Bereiche an die passenden Stellen. 2 bis 10 Begriffe. |
| **Buchstabieren** *(neu)* | `Hund` – ein Wort pro Zeile | Jedes Wort bekommt eine eigene **Seite**: das Bild zum Wort groß in der Mitte, darunter ein Kästchen für jeden Buchstaben; die Buchstaben liegen gemischt in der Ablage. Kommt ein Buchstabe doppelt vor („Ball“), passt jeder in beide Kästchen. Ablenker: `- x q` (auf jeder Seite). Bis zu 20 Wörter, je 2 bis 14 Buchstaben – so, wie du sie schreibst, auch in Großbuchstaben. |
| **Silbenlesen** *(neu)* | `Banane` – ein Wort pro Zeile, eigene Trennung mit `Ba-na-ne` | Schiebesachen zerlegt jedes Wort in Silben (Silbenmethode). Bis zu 4 Wörter pro **Seite**, je eine Reihe: links die Hilfe, daneben ein Kästchen für jede Silbe; die Silben liegen gemischt in der Ablage und werden der Reihe nach hineingezogen. Als Hilfe wählst du „Bild“ (das Bild zum Wort, eigenes Suchwort mit `[Bild: …]`), „Wort“ (das Wort geschrieben) oder „Hören“ (ein Ohr – ein Tipp darauf liest das Wort vor). „Silben blau und rot“ färbt die Silben wie bei der Silbenmethode. Ablenker: `- mo ri` (einzelne Silben, auf jeder Seite). Bis zu 24 Wörter mit 2 bis 6 Silben. |

Für alle Formate gilt:

- `Titel: Tiere im Wald` – der Titel der Übung (freiwillig).
- `Hund [Bild: Dackel]` – am Ende einer Zeile: Suchwort für ein Piktogramm (ARASAAC). Bei „Bild und Wort“ wird ohne Angabe zum Wort selbst gesucht.
- `- Fisch` – ein **Ablenker**: eine Karte, die nirgends hingehört (nicht bei „Reihenfolge“; bei „Buchstabieren“ einzelne Buchstaben, bei „Silbenlesen“ einzelne Silben). Mit Ablenkern passen höchstens 20 Karten in die Ablage.

„Beispiel“ setzt das Beispiel des Formats ein, „So geht's“ zeigt die Schreibweise. Rechts siehst du sofort eine **Vorschau** der fertigen Übung – graue Felder sind Platzhalter für die Bilder.

### Design

Sechs Designs legen Hintergrundfarbe, Karten, Schrift und Farben fest: „Klar“, „Himmel“, „Wiese“, „Sonne“, „Fibel“ (Andika, etwas größer, für Leseanfänger) und „Gut lesbar“ (Atkinson Hyperlegible, etwas größer). Schiebesachen merkt sich das zuletzt gewählte Design.

### Bilder automatisch suchen

Ist „Bilder automatisch suchen“ eingeschaltet, sucht Schiebesachen beim Erstellen zu jedem Suchwort das erste passende Piktogramm bei ARASAAC (Lizenz CC BY-NC-SA 4.0, steht als Bildnachweis am Bild). Findet ein eigenes Suchwort nichts, wird das Wort der Karte versucht. Wörter ohne Treffer zeigt Schiebesachen danach an – dort fügst du die Bilder selbst ein. Dafür braucht es Internet; ohne Bilder geht alles auch offline.

### Aus einer Wortliste

Bei „Bild und Wort“, „Oberbegriffe sortieren“, „Buchstabieren“ und „Silbenlesen“ setzt „Aus Wortliste …“ Wörter aus den Listen von Lernsachen-Heft ein: „Erste Wörter“ (lautgetreu), den „Grundwortschatz Bayern 1/2“ (LehrplanPLUS, nach Rechtschreibschwerpunkten) und „Deutsch als Zweitsprache“ (nach Themen). Ganze Abschnitte oder einzelne Wörter antippen, Listen lassen sich mischen. Jedes Wort bringt sein geprüftes Piktogramm mit (`Uhu [Bild: #24905]` – eine Nummer ist ein bestimmtes ARASAAC-Piktogramm, es wird nicht gesucht). Bei „Oberbegriffe sortieren“ wird jeder gewählte Abschnitt eine Spalte, z. B. „Wörter mit ei“ und „Wörter mit eu“.

### Mit einer KI

„Mit KI erstellen …“ öffnet einen Dialog für das gewählte Format: Thema, optional Material oder Stichpunkte, Anzahl, Zielgruppe und – je nach Format – Oberbegriffe, Ablenker, Bilder und weitere Wünsche (bei „Buchstabieren“: Anzahl der Wörter und höchstens wie viele Buchstaben). Die Auswahl merkt sich Schiebesachen für das nächste Mal. Dann gibt es zwei Wege:

- **Über einen KI-Chat:** Klicke eine KI-Anwendung an (z. B. AIS.chat, ByLKI, Duck.ai, ChatGPT). Der fertige Prompt mit deiner Auswahl wird automatisch übernommen: in die Zwischenablage (dort mit Strg+V einfügen), bei ChatGPT, Claude und Mistral zusätzlich direkt ins Eingabefeld. Für jede andere KI gibt es „Andere KI (Zwischenablage)“. Die Antwort der KI kopieren und nach „Ergebnis einfügen …“ ins Textfeld einfügen – auch mit dem Begleittext der KI; Schiebesachen liest nur den Block zwischen ```` ``` ````.
- **Über eine API-Schnittstelle:** mit einem eigenen API-Schlüssel (Claude von Anthropic oder ein Dienst mit OpenAI-kompatibler Schnittstelle wie OpenAI, Mistral, Gemini, OpenRouter) oder einer **lokalen KI** (Ollama, LM Studio – ohne Schlüssel). „Übung erzeugen“ schickt den Prompt direkt ab; das Ergebnis steht danach im Textfeld. Den Schlüssel speichert Schiebesachen nur, wenn du das einschaltest.

> **Achtung:** Gib keine personenbezogenen Daten von Schülerinnen und Schülern in eine KI ein und prüfe die Übung vor dem Einsatz.

### Danach

„Übung erstellen“ ersetzt die aktuelle Übung (nach einer Sicherheitsabfrage – sichere sie vorher als Datei, wenn du sie behalten möchtest). Die neue Übung ist eine ganz normale Übung: Texte, Bilder, Bereiche, Hintergrund und Ablauf lassen sich in den fünf Schritten ändern.

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
- **Lexend** – besonders leicht lesbar, mit weiten Buchstaben
- **Atkinson Hyperlegible** – barrierefreie Schrift mit besonders gut unterscheidbaren Buchstaben (z. B. bei Sehbeeinträchtigung oder Lese-Rechtschreib-Schwierigkeiten)
- **Andika** – für Leseanfänger, mit einstöckigem „a“
- **Merriweather** – mit Serifen
- **Caveat** – Handschrift

Dazu kommen Größe, Farbe, fett, kursiv und Ausrichtung. Alle Schriften sind in die Übung eingebettet und sehen überall gleich aus.

**Silben rot und blau** (rot-blauer Silben-Knopf): Die Wörter erscheinen in Sprechsilben, abwechselnd blau und rot (Silbenmethode) – statt der Schriftfarbe, auf einer weißen Hinterlegung, damit sie auf bunten Karten und Hintergründen gut lesbar bleiben.

**Zuletzt gewählte Schrift** : Schiebesachen merkt sich die Schrift, die du zuletzt gewählt hast – egal ob beim Titel, bei einem Element, bei einer Beschriftung oder bei einem Text im Hintergrund. Neue Texte und Titel sind dann gleich auf diese Schrift voreingestellt, auch der Titel einer „Neuen Übung“. So bleibt deine Übung einheitlich. Größe, Farbe und die übrigen Einstellungen änderst du wie gewohnt für jeden Text einzeln. Die Schrift wird in deinem Browser gemerkt (siehe Datenschutz) und gilt auch, wenn du Schiebesachen später wieder öffnest.

### Bild-Elemente

Klicke auf „Bild“ und wähle ein Bild wie beim Hintergrund (Hochladen, Hineinziehen, Einfügen, ARASAAC, Wikimedia Commons). Optional steht eine „Beschriftung“ unter dem Bild. Mit „Bild ändern“ tauschst du das Bild aus, ohne Größe und Zuordnung zu verlieren.

### Ton-Elemente

1. Klicke auf „Ton“. Im Reiter „Hochladen“ wählst du eine Tondatei (MP3, M4A, OGG, WAV oder WebM) oder ziehst sie hinein.
2. Im Reiter „Aufnehmen“ nimmst du direkt mit dem Mikrofon auf: auf das Mikrofon klicken, deutlich sprechen, mit Stopp beenden (höchstens 5 Minuten). Der Browser fragt beim ersten Mal, ob er das Mikrofon verwenden darf.
3. **Mikrofon nur einmal freigeben** : Nach der ersten Aufnahme bleibt das Mikrofon für diese Sitzung freigegeben – du musst nicht vor jeder Aufnahme neu zustimmen (das gilt für Töne und eigene Vorlese-Aufnahmen). Solange es freigegeben ist, zeigt dein Browser das Mikrofon-Symbol. Mit „Mikrofon trennen“ gibst du es sofort frei; spätestens beim Schließen der Seite passiert das automatisch. Aufgenommen wird nur, während die Aufnahme läuft. Auf dem iPad, dem iPhone und am Mac mit Safari wird es nach jeder Aufnahme gleich wieder freigegeben (ein offenes Mikrofon macht dort alle Töne leiser); Safari fragt dann meist trotzdem nicht neu.
4. **Zuschneiden** : Danach siehst du die Wellenform des Tons. Ziehe die Griffe an Anfang und Ende, um Stille oder Versprecher abzuschneiden. Mit „Auswahl anhören“ prüfst du den markierten Teil, mit „Alles anhören“ den ganzen Ton.„Stille automatisch entfernen“ schneidet leise Stellen am Anfang und Ende ab, „Zurücksetzen“ nimmt wieder den ganzen Ton. Nur der markierte Teil wird übernommen. (Tastatur: Griff anwählen, mit den Pfeiltasten verschieben.)
5. **Klang verbessern** : Unter der Wellenform machst du den Ton vor dem Übernehmen besser: „Lautstärke angleichen“ (leise Aufnahmen werden lauter, alle Töne klingen etwa gleich laut – bei neuen Aufnahmen schon an, das Gerät merkt sich deine Wahl), „Stimme klarer“, „Rauschen in Pausen leiser“ und „Lange Pausen kürzen“; „Verbessert anhören“ spielt das Ergebnis vorher vor.
6. „Übernehmen“ klicken. In der Übung erscheint ein runder Abspiel-Knopf; eine optionale Beschriftung steht darunter. Während der Aufnahme geht es mit „Stopp und übernehmen“ gleich weiter. Klappt das Zuschneiden oder Verbessern einmal nicht, kommt der Ton trotzdem hinein – ohne die Verbesserung oder so, wie du ihn aufgenommen hast; ein kurzer Hinweis sagt dir, was gefehlt hat. Eine neue Aufnahme geht nicht durch einen Klick neben das Fenster verloren: Beim Schließen wirst du gefragt, ob du sie verwerfen willst.

> **Tipp:** Kurze Töne (wenige Sekunden) halten die Datei klein. Lange Aufnahmen machen die Übung schnell mehrere Megabyte groß.

Gib Ton-Elementen am besten eine „Beschriftung“: Dann klappt auch das PDF-Arbeitsblatt – dort steht statt des Tons die Beschriftung (siehe [PDF](#pdf-arbeitsblatt-und-lösung)).

### Vorlesen und eigene Aufnahme

1. Schalte bei einem Element unter „Vorlesen“ den „Vorlesen-Button anzeigen“ ein. Auf der Karte erscheint oben rechts ein kleiner Lautsprecher – er sitzt wie ein Abzeichen auf der Ecke und verdeckt keinen Text.
2. Sollen alle Elemente vorgelesen werden, klicke direkt darunter auf „Für alle Elemente einschalten“ *(neu)* – das spart viele Klicks. Elemente ohne Text bleiben aus. Genauso geht „Für alle Elemente ausschalten“, und bei Lösungsbereichen und Hintergrund-Elementen gibt es das ebenfalls. Ein Klick auf Rückgängig nimmt alles auf einmal zurück.
3. Ohne eigene Aufnahme liest die **Computerstimme des Geräts** den Text vor (deutsche Stimme des Browsers). Mit „Probehören“ testest du sie.
4. Für eine **eigene Aufnahme** klicke auf „Eigene Aufnahme verwenden“, nimm auf (oder lade eine Datei hoch) und schneide sie zu. Sie wird dann statt der Computerstimme abgespielt – z. B. für Fremdsprachen, Dialekt oder Lautieren.

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

## Mehrere Seiten

Eine Übung kann mehrere **Seiten** haben – z. B. ein Wort pro Seite beim Buchstabieren oder mehrere Bilder zum Beschriften. Die Lernenden blättern mit „Weiter“ und „Zurück“; am Ende gibt es ein Ergebnis für alle Seiten zusammen. *(neu)*

### Seiten anlegen und ordnen

- Die **Seitenleiste** unter der Arbeitsfläche zeigt die Seiten. Tippe eine Nummer an, um diese Seite zu bearbeiten.
- „+ Seite“ fügt nach der gezeigten Seite eine leere Seite ein, „Verdoppeln“ eine Kopie mit Hintergrund, Elementen und Bereichen – praktisch, wenn alle Seiten gleich aufgebaut sein sollen.
- Mit den Pfeilen verschiebst du die gezeigte Seite nach vorne oder hinten, mit dem Papierkorb löschst du sie (Rückgängig holt sie zurück).
- Jede Seite hat ihren eigenen **Hintergrund**, ihre **Elemente** und **Bereiche**. **Titel**, **Format** und **Ablauf** gelten für alle Seiten.
- Rückgängig und Wiederholen zeigen jeweils die Seite, auf der sich etwas geändert hat. Die Checkliste nennt die Seite mit.

### So sehen es die Lernenden

- In der Leiste unter der Übung stehen „‹“, die Seitenzahl (z. B. „2 / 5“) und „Weiter“. Ist eine Seite fertig, wird „Weiter“ hervorgehoben. Jede Seite merkt sich ihren Stand, auch beim Zurückblättern.
- Unter dem Ergebnis einer Seite steht, welche Seiten noch offen sind – sind alle fertig, die Punkte **aller Seiten zusammen**.
- **SCORM (mebis):** gemeldet werden die Punkte aller Seiten zusammen, sobald jede Seite bearbeitet ist; der Fortschritt jeder Seite wird gespeichert.
- **PDF:** erst das Arbeitsblatt jeder Seite, danach die Lösungen.
- **Im Lernsachen-Heft** kommt die ganze Übung auf eine Heft-Seite; geblättert wird in der Übung.

## Testen

1. Klicke oben auf „Testen“. Die Übung startet genau so, wie die Lernenden sie sehen – bei mehreren Seiten auf der Seite, die du gerade bearbeitest („Neu starten“ beginnt bei Seite 1).
2. Ziehe Elemente, probiere Vorlese-Buttons und Töne aus, werte aus und teste „Nochmal“ und „Lösung anzeigen“.
3. „Neu starten“ beginnt von vorn, „Zurück zum Bearbeiten“ (oder „Bearbeiten“ oben) führt zurück in den Editor.

> **Tipp:** Teste auch auf einem Smartphone oder Tablet: Speichere dazu die HTML-Datei und öffne sie auf dem Gerät. Ziehen funktioniert mit Finger, Maus, Stift und Tastatur.

## Speichern und teilen

Klicke oben rechts auf „Speichern“ (dafür braucht die Übung einen Titel). Hast du noch Hinweise in der Checkliste, zeigt der Dialog sie an – speichern kannst du trotzdem.

### HTML-Datei

Eine einzelne Datei, die in jedem Browser läuft – auch ohne Internet. Zum Verschicken per E-Mail oder Messenger, zum Ablegen auf dem Schulserver oder in mebis als Material „Datei“. Ergebnisse werden dabei nicht gespeichert. Dieselbe Datei ist auch deine Arbeitsdatei: Über „Öffnen …“ lädst du sie wieder in Schiebesachen und bearbeitest sie weiter – mit allen Bildern, Tönen und Zeichnungen.

### HTML-Datei in mebis/Moodle einbetten (iframe) 

So erscheint die Übung direkt in mebis – auch mitten in einem Textfeld, auf einer Textseite oder in der Abschnittsbeschreibung. Nach dem Herunterladen der HTML-Datei zeigt der Export-Dialog dir dafür die Anleitung „In mebis/Moodle einbetten“. Du kannst sie auch ohne Download über den Link „Einbetten in mebis/Moodle“ bei der HTML-Datei öffnen.

1. Klicke bei „HTML-Datei (speichern und weitergeben)“ auf „Herunterladen“. Die Datei landet in deinem Download-Ordner, der Dialog wechselt zu „In mebis/Moodle einbetten“.
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
| Später weiterbearbeiten, teilen mit Kolleginnen und Kollegen | HTML-Datei („Speichern“) |

## Speichern & Weiterbearbeiten

### Automatisch im Browser

Jede Änderung wird nach kurzer Zeit automatisch **in deinem Browser** gespeichert (oben steht „Automatisch gespeichert“). Öffnest du Schiebesachen später im selben Browser auf demselben Gerät wieder, ist deine Übung noch da.

> **Achtung:** Der Browser-Speicher ist kein Archiv: Er gilt nur für diesen Browser auf diesem Gerät, und er geht verloren, wenn du die Browserdaten löschst oder im privaten Modus arbeitest. Es gibt immer nur **eine** aktuelle Übung.

### Als Datei sichern

1. Klicke oben rechts auf das Ordner-Symbol → „Als HTML-Datei speichern“.
2. Du bekommst eine HTML-Datei, z. B. „Der, die oder das (Schiebesachen).html“. Sie landet in deinem Download-Ordner. Bewahre sie z. B. in deinem Schul-Cloudspeicher auf.

Die Datei ist zugleich die fertige Übung: Sie läuft in jedem Browser und lässt sich in Lernsachen-Heft einfügen. Am Namen erkennst du, aus welcher App eine Datei stammt: „(Schiebesachen)“, „(Quizsachen)“, „(Textsachen)“ oder „(Heft)“ für Lernsachen-Heft.

### Öffnen

Ordner-Symbol → „Öffnen …“ lädt eine gespeicherte oder exportierte HTML-Übung wieder in den Editor (auch ältere JSON-Dateien). Die aktuelle Übung wird dabei ersetzt – sichere sie vorher, wenn du sie behalten möchtest. Öffnest du die Datei einer anderen App, sagt dir Schiebesachen, wohin sie gehört.

Zeichnungen aus HTML-Dateien älterer Versionen (vor 1.7) kannst du danach nur noch verschieben, vergrößern und löschen, aber nicht mehr weiterzeichnen – diese Dateien enthalten die Zeichen-Daten noch nicht.

### Neue Übung

Ordner-Symbol → „Neue Übung“ beginnt mit einer leeren Übung oder einem Übungsformat (siehe [Neue Übung: Formate & KI](#neue-übung-formate--ki)); die bisherige Übung wird nach einer Sicherheitsabfrage ersetzt. Die zuletzt gewählte Schrift bleibt erhalten – der neue Titel beginnt gleich in ihr.

### Im Lernsachen-Heft

Im Lernsachen-Heft öffnet die Vorlage „Zuordnungen“ Schiebesachen direkt im Heft. Oben rechts stehen dann „Ins Heft übernehmen“ und „Abbrechen“. Bis die Übung im Heft ist, speichert Schiebesachen sie als eigenen Entwurf – getrennt von der Übung, an der du sonst in Schiebesachen arbeitest. Wurde das Heft zwischendurch geschlossen, bietet Schiebesachen bei der nächsten neuen Übung an, den Entwurf fortzusetzen.

Weil die Seiten im Heft quer sind, gibt es dort nur Querformate – und zwar die, die zur Startposition der Elemente passen: mit der Ablage unten 2:1 oder 16:9, mit der Ablage rechts 4:3 oder 1:1, frei auf der Fläche 16:9, 4:3 oder 2:1.

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

Schicke ihr die gespeicherte HTML-Datei. Sie lässt sich in Schiebesachen über „Öffnen …“ wieder bearbeiten.

Brauche ich Internet?

Nur für die Bildsuche (ARASAAC, Wikimedia Commons). Alles andere – auch Zeichnen (samt Schriften), Aufnehmen und Speichern – funktioniert offline. Gespeicherte Übungen laufen ebenfalls ohne Internet.

Kann ich Schiebesachen wie eine App speichern?

Ja: Füge die Datei zum Startbildschirm hinzu (iPad/iPhone: Teilen → „Zum Home-Bildschirm“) oder lege ein Lesezeichen an. Am einfachsten speicherst du die HTML-Datei von Schiebesachen auf deinem Rechner und öffnest sie per Doppelklick.

Weitere Ideen und Materialien findest du auf [Lernsachen.blog](https://lernsachen.blog).
