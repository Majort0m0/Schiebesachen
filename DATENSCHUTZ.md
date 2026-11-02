# Datenschutz

Diese Hinweise stehen auch in der App unter „Datenschutz“.

**Kurz gesagt:**

- Schiebesachen hat keinen Server. Alles läuft lokal in deinem Browser.
- Deine Übungen werden nur auf deinem Gerät gespeichert.
- Keine Anmeldung, keine Cookies, kein Tracking, keine Analyse, keine Werbung.
- Verbindungen ins Internet gibt es nur, wenn du die Bildsuche (ARASAAC, Wikimedia Commons) benutzt, bei einer neuen Übung Bilder automatisch suchen lässt oder eine Bildadresse (URL) einfügst – siehe Punkt 4 –, und wenn du eine KI über eine API-Schnittstelle nutzt – siehe Punkt 8.

### 1. Alles läuft lokal in deinem Browser

Schiebesachen ist eine einzelne HTML-Datei. Alles, was du tust – Bilder einfügen und zuschneiden, zeichnen, Töne aufnehmen, Übungen exportieren –, berechnet dein Browser selbst auf deinem Gerät. Es gibt **keinen Server von Schiebesachen**, an den Daten geschickt werden. Wir sehen weder deine Übungen noch deine Bilder oder Aufnahmen.

Wenn du Schiebesachen von einer Webseite aus aufrufst, ruft dein Browser die Datei von dem Webserver ab, auf dem sie liegt. Dabei verarbeitet der Betreiber dieses Webservers technisch notwendige Daten (z. B. IP-Adresse, Zeitpunkt). Dafür gilt die Datenschutzerklärung der jeweiligen Webseite. Öffnest du die heruntergeladene Datei direkt von deinem Rechner, entfällt auch das.

### 2. Speicherung nur auf deinem Gerät

Damit nichts verloren geht, speichert Schiebesachen die aktuelle Übung automatisch im Speicher deines Browsers (IndexedDB) – nur auf diesem Gerät, nur in diesem Browser. Niemand sonst hat Zugriff darauf. Du löschst diese Daten, indem du eine „Neue Übung“ beginnst oder in deinem Browser die Website-Daten löschst.

Öffnest du Schiebesachen im Lernsachen-Heft, liegt der Entwurf getrennt davon und wird gelöscht, sobald die Übung im Heft ist oder du abbrichst. Die Übung gibt Schiebesachen dabei nur an das Heft in deinem Browser weiter – sie verlässt dein Gerät nicht.

Außerdem merkt sich Schiebesachen im lokalen Speicher deines Browsers (localStorage) die **zuletzt gewählte Schrift**, damit neue Texte gleich in dieser Schrift beginnen. Gespeichert wird nur der Name der Schrift, keine Inhalte. Dieser Eintrag bleibt auch bei einer „Neuen Übung“ erhalten; du löschst ihn, indem du in deinem Browser die Website-Daten löschst.

Ebenso merkt sich Schiebesachen dort das **zuletzt gewählte Design** für neue Übungen und die **Einstellungen des KI-Dialogs** (Thema, Zielgruppe usw. – den API-Schlüssel nur, wenn du das einschaltest, siehe Punkt 8).

Dateien wie JSON, HTML, SCORM-Pakete oder PDF entstehen ebenfalls nur lokal und werden in deinem Download-Ordner gespeichert. Was du damit machst (z. B. in mebis hochladen), entscheidest du.

### 3. Keine Cookies, kein Tracking

Schiebesachen setzt keine Cookies, verwendet keine Analyse- oder Statistikdienste, keine Werbung und keine Social-Media-Plugins. Alle Programmteile und Schriften – auch die des Zeichenwerkzeugs – sind in der Datei enthalten; es wird nichts aus dem Internet nachgeladen.

### 4. Externe Verbindungen: nur bei Bildsuche und Bildadresse

Nur wenn du im Bild-Dialog **selbst** eine Suche startest oder ein Suchergebnis übernimmst, verbindet sich dein Browser direkt mit dem jeweiligen Dienst:

| Dienst | Adressen | Datenschutz |
|---|---|---|
| **ARASAAC** (Regierung von Aragón, Spanien) | `api.arasaac.org`, `static.arasaac.org` | [Datenschutzerklärung von ARASAAC](https://arasaac.org/privacy-policy) |
| **Wikimedia Commons** (Wikimedia Foundation, USA) | `commons.wikimedia.org`, `upload.wikimedia.org`, `thumb.wikimedia.org` | [Datenschutzrichtlinie der Wikimedia Foundation](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy/de) |

Dabei werden **deine IP-Adresse**, der **Suchbegriff** und übliche technische Angaben deines Browsers (z. B. Browsertyp, Sprache) an diesen Dienst übermittelt – so wie beim Besuch der jeweiligen Webseite. Schiebesachen schickt keine weiteren Daten mit, insbesondere nicht deine Übung. Gib deshalb keine personenbezogenen Daten als Suchbegriff ein. Die Wikimedia Foundation sitzt in den USA; Daten können dorthin übertragen werden.

Erstellst du eine „Neue Übung“ aus einem Übungsformat und ist „Bilder automatisch suchen“ eingeschaltet, sucht dein Browser beim Klick auf „Übung erstellen“ bei ARASAAC nach den Wörtern bzw. Suchwörtern der Karten – dabei gilt dasselbe wie bei der Bildsuche. Schalte die Bildsuche aus, wenn das nicht passieren soll.

Fügst du unter „Oder Bildadresse (URL) einfügen“ eine Adresse ein oder ziehst ein Bild aus einer anderen Webseite hinein, lädt dein Browser das Bild von dieser Webseite – auch dabei erfährt deren Betreiber deine IP-Adresse.

Links in Bildnachweisen, in dieser Hilfe oder zu Lizenzen öffnen sich erst, wenn du sie anklickst, in einem neuen Tab.

### 5. Mikrofon und Aufnahmen

Auf das Mikrofon greift Schiebesachen nur zu, wenn du eine Aufnahme startest **und** deinem Browser die Erlaubnis gibst. Die Aufnahme bleibt lokal: Sie wird nur in deiner Übung gespeichert und nirgendwohin hochgeladen oder verschickt.

Damit du nicht vor jeder Aufnahme neu zustimmen musst, bleibt das Mikrofon nach der ersten Aufnahme **für diese Sitzung** freigegeben – nur solange die Seite geöffnet ist. Aufgenommen wird dabei nur, während eine Aufnahme läuft. Mit „Mikrofon trennen“ gibst du das Mikrofon sofort frei; beim Schließen oder Verlassen der Seite gibt Schiebesachen es automatisch frei. Die Erlaubnis selbst verwaltet dein Browser (Schloss- bzw. Mikrofon-Symbol in der Adresszeile).

### 6. Sprachausgabe (Vorlesen)

Die Vorlese-Funktion nutzt die Sprachausgabe deines Geräts bzw. Browsers. Schiebesachen schickt dafür selbst nichts ins Internet. **Hinweis:** Manche Browser (z. B. Google Chrome oder Microsoft Edge) bieten zusätzlich Online-Stimmen an. Wird eine solche Stimme verwendet, übermittelt der Browser den vorzulesenden Text an den Anbieter der Stimme (z. B. Google oder Microsoft). Darauf hat Schiebesachen keinen Einfluss. Wenn du das vermeiden möchtest, nutze eigene Aufnahmen oder einen Browser mit lokalen Stimmen (z. B. Safari oder Firefox).

### 7. Exportierte Übungen

Exportierte Übungen (HTML-Datei – auch eingebettet per iframe –, SCORM-Paket, PDF) enthalten alles, was sie brauchen – Bilder, Töne, Schriften und das Programm. Sie **laden nichts aus dem Internet nach**, setzen keine Cookies und enthalten keine Tracker. Für das Vorlesen gilt Punkt 6 auf dem Gerät der Lernenden.

Ein **SCORM-Paket** meldet Punkte, Fortschritt, „bestanden“/„nicht bestanden“ und den Bearbeitungsstand (zum Fortsetzen) ausschließlich an die Lernplattform, in die du es hochgeladen hast (z. B. mebis). Dort gelten die Datenschutzbestimmungen dieser Plattform bzw. deiner Schule.

### 8. Personenbezogene Daten und KI

Du entscheidest, was in einer Übung steht. Bitte verwende **keine personenbezogenen Daten von Schülerinnen und Schülern** (z. B. Namen, Noten, Fotos, Stimmaufnahmen) ohne Einwilligung bzw. ohne Rechtsgrundlage. Das gilt besonders, wenn du Übungen weitergibst oder veröffentlichst. Beachte auch Urheber- und Persönlichkeitsrechte bei Bildern.

**KI-Chat:** Beim Weg „Über einen KI-Chat“ (bei „Neue Übung“ → „Mit KI erstellen …“) schickt Schiebesachen selbst nichts an eine KI – du kopierst nur einen Text (den Prompt) in die Zwischenablage und fügst ihn selbst in eine KI-Anwendung deiner Wahl ein. Dort gelten die Bedingungen dieses Anbieters.

**API-Schnittstelle:** Nur wenn du „Über eine API-Schnittstelle“ wählst und auf „Übung erzeugen“ klickst, schickt dein Browser den Prompt (Thema, Material, deine Auswahl) direkt an den eingestellten Dienst – an Anthropic, an den gewählten Anbieter oder an eine lokale KI auf deinem Rechner bzw. im Schulnetz. Dabei erfährt der Dienst auch deine IP-Adresse. Es gelten die Bedingungen des Anbieters; die Kosten richten sich nach deinem Vertrag. Den API-Schlüssel speichert Schiebesachen nur in deinem Browser und nur, wenn du „Schlüssel in diesem Browser speichern“ einschaltest. In exportierte Übungen gelangen weder Schlüssel noch Einstellungen.

Gib in keine KI personenbezogene Daten von Schülerinnen und Schülern ein.

### 9. Verantwortlich

Schiebesachen wird von [Lernsachen.blog](https://lernsachen.blog) bereitgestellt. Da das Werkzeug selbst keinen Server hat, werden durch Schiebesachen keine personenbezogenen Daten an Lernsachen.blog übermittelt oder dort gespeichert. Für Fragen zum Datenschutz erreichst du uns über [lernsachen.blog](https://lernsachen.blog); dort findest du auch das Impressum.
