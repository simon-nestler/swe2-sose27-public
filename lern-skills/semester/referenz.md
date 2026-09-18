# Referenz – Softwareentwicklung 2 (Begleitdatei zum Lernbegleiter, v1.2, 2026-09-18)

*Alles hier steht auch im Kursmaterial; das Folienskript bleibt die bindende Quelle. Diese Datei existiert, damit der Assistent mit den Festlegungen des Moduls arbeitet statt mit eigenen.*

## Die Semesterbewegung

Das Semester erzählt eine einzige Bewegung: vom Schreiben zum Verantworten. T01–T05 bauen das objektorientierte Denkgerüst, T06–T09 setzen es unter Last (der Blick wandert vom eigenen Code zum fremden), T10–T13 holen den Studiengang ab: Oberflächen, Reaktionsfähigkeit, KI-Verantwortung, großer Entwurf.

Das Semester ist auf 14 Wochen geplant, je nach Feiertagen eine Woche mehr oder weniger. T09 und T07 sind streichbar: Fällt eine Woche aus, findet T09 nicht als Termin statt, fallen zwei aus, auch T07. Der Stoff steht dann vollständig im Folienskript. Eine zusätzliche Woche wird Fragestunde. (Nachtrag 15.09.2026)

## Die 13 Themen mit Kernkonflikt und Lernzielen

| # | Thema | Kernkonflikt (ein Satz) | LZ |
|---|---|---|---|
| 1 | Auftakt: Klassen und Objekte | Jede Klasse dieses Semesters schreibt ein Sprachmodell in dreißig Sekunden – und trotzdem entscheidet am Ende ein Mensch, ob der Code stimmt. | 1, 2, 8 |
| 2 | Kapselung und Invarianten | Je weniger ein Objekt von sich zeigt, desto nützlicher ist es – Bequemlichkeit heute gegen Wartbarkeit in drei Wochen. | 2 |
| 3 | Vererbung als Vertrag | Wiederverwendung klingt nach geschenkter Arbeit – und bindet jede Unterklasse auf Dauer an die Entscheidungen der Oberklasse. | 1, 2 |
| 4 | Polymorphismus und Bindung | Polymorphismus macht Programme erweiterbar, indem er sie beim bloßen Lesen unvorhersehbar macht – wer die Bindung nicht versteht, liest jedes moderne Programm falsch. | 1, 3 |
| 5 | Anker 1: Vererbung oder Schnittstelle ⚓ | Vererbung oder Schnittstelle: zwei vertretbare Architekturen für denselben Fall – und die Entscheidung kostet in jedem Fall etwas, nur je etwas anderes. | 4, 2 |
| 6 | Exceptions und Fehlermeldungen | Programme zeigen ihren Charakter erst, wenn etwas schiefgeht – und die meiste Software behandelt genau diesen Moment am schlechtesten. | 6, 3 |
| 7 | Verkettete Listen | Eine verkettete Liste ist in fünf Zeilen erklärt – und fast jede Implementierung scheitert an denselben drei Sonderfällen. | 5, 3 |
| 8 | Rekursion und Binärbäume | Rekursion löst in drei Zeilen, was Schleifen verknoten – und produziert ohne Abbruchdenken die teuersten Fehler des Semesters. | 5 |
| 9 | Collections und Generics | Collections und Generics erledigen in einer Zeile, was T07 und T08 mühsam gebaut haben – wer aber nie gebaut hat, kann nicht beurteilen, was die eine Zeile kostet. | 5, 4, 3 |
| 10 | JavaFX und Ereignissteuerung | Erst wer die Ereignissteuerung versteht, weiß, warum sich ein Interface so verhält, wie es sich verhält. | 6, 2 |
| 11 | Event-Thread und Nebenläufigkeit | Ein Absturz ist ehrlich, eine eingefrorene Oberfläche lügt – und die Ursache liegt in einem einzigen blockierten Thread. | 6 |
| 12 | Anker 2: Audit-Werkstatt ⚓ | KI-Werkzeuge schreiben Java-Code mit über 70 Prozent Schwachstellenquote, löschen im Ernstfall Produktionsdatenbanken – und fühlen sich dabei schneller an, als sie sind. | 8, 3, 4 |
| 13 | Der große Entwurf ⚓ | Eine kleine App von der Anforderung bis zur robusten Oberfläche – mit allem Stoff des Semesters, aber ohne die Sicherheit, dass es eine richtige Lösung gibt. | 1–6 |

## Lernziele (Kurzform)

LZ1 Ablauf eines unbekannten Programms (Vererbung, Polymorphismus, dynamische Bindung) schriftlich vorhersagen und Zeile für Zeile begründen · LZ2 UX-nahes Problem in ein Klassenmodell zerlegen, zwei Entwurfsentscheidungen begründen · LZ3 plausibel wirkende, auch KI-erzeugte Lösung prüfen: Fehler finden, korrigieren, den entdeckenden Prüfschritt benennen · LZ4 zwischen zwei vertretbaren Entwürfen begründet entscheiden – mit benanntem Kriterium und benanntem Preis · LZ5 dynamische Datenstrukturen und einfache Sortieralgorithmen anwenden, Grenzfall benennen · LZ6 Laufzeitverhalten aus Benutzersicht erklären (blockierter Event-Thread, unbehandelte Exception) · LZ7 mittelschwere Aufgaben ohne KI-Werkzeug umsetzen und im Testat verantworten (Praktikum) · LZ8 mit KI-Werkzeug entwickeln, Ausgaben systematisch prüfen, Grenzen der Delegation benennen (Spalte 2, kein Prüfungsträger – die prüfbare Spur ist LZ3).

Prüfungsform: Kombination aus Klausur (schrP120, ohne Rechner) und Praktikum (PA, Zulassungsvoraussetzung).

## Sammelaufträge zwischen den Terminen (Stand 18.09.2026)

Zwischen Teil A und Teil B jedes Themas steht ein **freiwilliger Sammelauftrag** aufs Padlet: keine Moodle-Abgabe, keine Frist, keine Bewertung, und aus dem Auslassen folgt nichts. Abgaben in Moodle betreffen nur die sechs Praktikumsblätter. Jeder Teil B trägt sich über eigene Beispiele auf den Folien – überwiegend aus der Altvorlesung des Kurses; das Padlet ergänzt, es trägt nicht. Der Assistent stellt also **keine** Abgabefristen in Aussicht und behauptet keine Nachteile bei Nichtabgabe. (Stand bis 17.09.2026: Zwischenaufgaben mit Moodle-Abgabe bis zum Vorabend von Teil B.)

## Die zwei Räume und die vier KI-Rollen

**Vorlesung und Übung: mit KI** – Werkzeuge sind erlaubt und werden ernsthaft benutzt. **Praktikum und Klausur: ohne** – die sechs Blätter entstehen ohne KI, das Testat prüft das persönlich, die Klausur läuft ohne Rechner. Jede Einheit deklariert ihre KI-Rolle offen: **ausgeschlossen** (Tracing im Kopf ist die Kompetenz) · **Sparringspartner** (die Maschine erklärt, Sie prüfen die Erklärung) · **Prüfobjekt** (eine KI-Ausgabe liegt auf dem Seziertisch) · **Werkzeug** (die Maschine darf, soll, muss – und Sie verantworten das Ergebnis).

## Praktikum und Testate

Sechs Aufgabenblätter, ohne KI. Domäne aller Blätter: die fiktive Raumbuchung *Freiraum*, zu jedem Blatt gibt es einen Startstand. Blatt 1 Zeitfenster, Raum, Buchung – Git und Invarianten (nach T01–T02) · Blatt 2 Raumtypen und Buchungsterminal – `static`, Vererbung, Vertrag (nach T02–T03) · Blatt 3 Warteliste und Belegungskalender – Interface, eigene Exception, verkettete Liste, Baum (nach T07–T08) · Blatt 4 Sammlungen, Dateien, Rangliste – Collections, Comparator, Dateifehler (nach T08–T09) · Blatt 5 Oberfläche – JavaFX über der bestehenden Logik (nach T10) · Blatt 6 Import ohne Einfrieren – `Task`, Rückmeldung, Fehlerdialog (parallel zu T11–T13). Die Blätter sind chronologisch nummeriert (Neukonzept Praktikum, 15.09.2026). Die Vorlesung übt nicht, was die Blätter prüfen – sie liefert das Denkzeug.

**Testatmechanik:** Bearbeitungszeit 45 Minuten, maximal 40 Punkte, Beantwortung direkt im vorgesehenen Antwortfeld. Hinweis wörtlich: „Bitte verwenden Sie keine Hilfsmittel (Entwicklungsumgebung, ChatGPT, Google, Lösung, etc.), um eine realistische Bewertung Ihres Leistungsstandes zu erhalten." Danach Selbstbewertung im Rahmen der Besprechung: Lösung mit Musterlösung vergleichen und Punkte je Teilaufgabe vergeben (auch andere korrekte Implementierungen können die volle Punktzahl erhalten; entscheidend ist, ob die grundlegenden Konzepte korrekt umgesetzt wurden) · Punkte addieren · mit 2,5 multiplizieren = Prozentwert · Note aus der Notentabelle · Bestätigung per Namen in Druckbuchstaben: „fair und realistisch eingeschätzt".

## Notentabelle

| Note | von % | bis % |
|---|---|---|
| 1,0 | 96 | 100 |
| 1,3 | 91 | 95 |
| 1,7 | 86 | 90 |
| 2,0 | 81 | 85 |
| 2,3 | 76 | 80 |
| 2,7 | 70 | 75 |
| 3,0 | 65 | 69 |
| 3,3 | 60 | 64 |
| 3,7 | 55 | 59 |
| 4,0 | 50 | 54 |
| 5,0 | 0 | 49 |

## Fachliche Festlegungen (Auswahl, Fassung des Moduls)

- **Zwei Regeln der Bindung:** Regel 1 – Der statische Typ entscheidet, was *aufrufbar* ist. Regel 2 – Der dynamische Typ entscheidet, was *läuft*. Merksatz: „Auf dem Zettel steht der Typ, und das Verhalten steckt im Objekt." Für Referenzen aus T01: „Auf dem Zettel steht nur die Adresse, das Objekt liegt woanders im Speicher."
- **Zeitstrahl:** Übersetzungszeit: Überladung, Felder · Laufzeit: Überschreibung. Felder binden statisch, ausnahmslos. Es läuft immer die Fassung der echten Klasse.
- **These T04:** „Wer polymorph baut, sieht der Schleife nicht mehr an, was sie tut, und bekommt dafür den neuen Medientyp ohne eine geänderte Zeile."
- **Drei Erkennungsmerkmale einer belastbaren Erklärung:** konkrete Zeile statt Prosa · Regelverweis statt Analogie · Nachrechnen statt Nicken.
- **Drei Fragen jeder guten Fehlermeldung (T06):** Was ist passiert? · Was heißt das für mich? · Was kann ich jetzt tun?
- **Semesterformel:** Plausibel ist nicht korrekt.
- **Satz zu T11:** „Wer die Arbeit nicht in einen zweiten Thread auslagert, hat bei 40 Sekunden Wartezeit keine einzige Rückmeldungsstufe zur Wahl." Dazu die eiserne Regel: Die Oberfläche wird nur vom Event-Thread angefasst; aus dem Hintergrund melden Sie mit `updateProgress`, und das Framework reicht die Meldung weiter.
- **Satz zu T12:** „Wer Code einsetzt, ohne ihn zu prüfen, verantwortet ihn trotzdem" – handwerklich gemeint, nicht juristisch. Die Prüfschleife: Lesen → Testen → Grenzfälle provozieren → Verantworten.
- **Ein-Satz-Prüfung zu T08:** Erreicht jeder Eingabefall einen *richtigen* Basisfall?

> [Stand bis 17.09.2026: Merksatz zur Bindung „Der Zettel kennt den Typ, das Objekt kennt sein Verhalten."; These T04 „Unvorhersehbarkeit beim Lesen ist der Preis für Erweiterbarkeit beim Bauen."; Satz zu T11 „Nebenläufigkeit ist keine Technikfrage, sie ist die Voraussetzung dafür, dass es überhaupt etwas zu gestalten gibt."; Satz zu T12 „Es haftet, wer nicht geprüft hat." Die Decks führen die alten Fassungen jeweils in der Folien-Notiz.]

## Datierte Stände (Stand 2026-09-05 – vor Verlass prüfen)

- Veracode, *2025 GenAI Code Security Report*: über 70 Prozent Schwachstellenquote bei maschinell erzeugtem Java-Code (Bezugsrahmen von T12).
- Kurs-Fehlerbilder aus echten Läufen: JDK 21 (Temurin), javac mit englischer Meldungssprache; Zeilennummern der `java.base`-Frames hängen vom JDK ab, die der eigenen Klassen nicht.
- Literaturbasis: Ullenboom, *Java ist auch eine Insel*, 18. Auflage (aktuell zu Java 25); Mössenböck, *Sprechen Sie Java?*, 5. Auflage 2014.
- Prüfungssemester der Testatvorlagen: SoSe 2027; AWT/Swing ist gestrichen, JavaFX ist das GUI-Vehikel, JDBC entfällt, Thread-Synchronisation im Detail entfällt.
