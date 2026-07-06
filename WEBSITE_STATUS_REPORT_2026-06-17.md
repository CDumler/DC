# Website Status Report (Stand: 2026-06-17)

## 1. Executive Summary

- Die Website ist heute deutlich weiter als im Report vom 2026-03-30.
- Aus dem frueheren visuellen Prototyp ist eine sehr weit entwickelte statische Marketing-Seite fuer `D.ONE` geworden.
- Die Positionierung ist klar: Boutique fuer die Besetzung von Fuehrungsrollen, mit Fokus auf Sorgfalt, Selektivitaet, persoenlicher Begleitung und tragfaehigen Entscheidungen.
- Die Startseite ist visuell hochwertig, responsiv und inzwischen an mehreren Stellen interaktiv.
- Die groessten offenen Punkte liegen nicht mehr im Grundlayout, sondern in operativen Details: Rechtstexte finalisieren, Branding konsistent abschliessen, fehlende Assets/Links ergaenzen, SEO ausbauen.

## 2. Delta Seit 2026-03-30

- Branding wurde weitgehend von `SDS` auf `D.ONE` umgestellt.
- `index.html` ist stark gewachsen: von 1,765 auf 3,069 Zeilen und von 57,289 auf 90,747 Bytes.
- `impressum.html` ist von 192 auf 306 Zeilen gewachsen.
- `datenschutz.html` ist von 238 auf 356 Zeilen gewachsen.
- Das Kontaktformular hat nicht mehr `action="#"`, sondern eine echte FormSubmit-Anbindung (`index.html:2545`).
- Die Bereiche `Ansatz` und `Werte` wurden um scroll-basierte sequenzielle Interaktionen erweitert.
- Die Rechtstext-Seiten haben jetzt sichtbares D.ONE-Branding, Ruecklinks oben und zusaetzliche Rueckkehr-Buttons am Seitenende.
- Der alte Report ging von einem sauberen Git-Status aus; aktuell ist der Worktree bewusst veraendert (`index.html`, `impressum.html`, `datenschutz.html`) und es gibt zusaetzlich diesen neuen Report als uncommittete Datei.

## 3. Projektueberblick

- Projektart: Statische Website ohne Framework, ohne Build-System, ohne Package-Setup.
- Branch: `main`
- Letzter Commit: `16151534b803a256d50319e1eafe67044aba90b5`
- Letzte Commit-Metadaten:
  - Datum: `2026-04-10 15:24:58 +0200`
  - Message: `b`
- Aktueller Git-Status: lokale Aenderungen in `index.html`, `impressum.html`, `datenschutz.html` sowie neuer Report `WEBSITE_STATUS_REPORT_2026-06-17.md`
- Projektdateien im Root:
  - `index.html`
  - `impressum.html`
  - `datenschutz.html`
  - `WEBSITE_STATUS_REPORT_2026-03-30.md`
  - `WEBSITE_STATUS_REPORT_2026-06-17.md`
- Asset-Ordner:
  - vorhanden: `assets/sds-wordmark.png`
  - referenziert aber nicht vorhanden: `assets/christian-dumler.jpg` (`index.html:2366`)

## 4. Dateistand

- `index.html`: 3,069 Zeilen, 90,747 Bytes
- `impressum.html`: 306 Zeilen, 8,047 Bytes
- `datenschutz.html`: 356 Zeilen, 10,406 Bytes
- `WEBSITE_STATUS_REPORT_2026-03-30.md`: 142 Zeilen
- `WEBSITE_STATUS_REPORT_2026-06-17.md`: dieser aktualisierte Report

## 5. Inhaltsarchitektur Der Website

### Vorhandene Seiten

1. `index.html`
2. `impressum.html`
3. `datenschutz.html`

### Struktur Der Startseite

1. Hero (`index.html:2123`)
2. Haltung (`index.html:2167`)
3. Ansatz (`index.html:2199`)
4. Werte (`index.html:2289`)
5. Ueber mich (`index.html:2359`)
6. Kennzahlen, aktuell versteckt (`index.html:2431`)
7. Referenzen, aktuell versteckt (`index.html:2460`)
8. Kontakt (`index.html:2495`)
9. Footer (`index.html:2653`)

## 6. Inhaltliche Beschreibung Pro Bereich

### 6.1 Hero

- Branding: D.ONE Wordmark als typografisches Logo (`index.html:2125`)
- Eyebrow: `Boutique der Fuehrungsbesetzung` (`index.html:2135`)
- Hauptclaim:
  - `Bessere Entscheidungen.`
  - `Sorgfaeltige Besetzungen.`
- Subline: persoenliche und selektive Begleitung bei Fuehrungsbesetzungen mit klarer Einschaetzung und direkter Ansprache (`index.html:2143-2149`)
- CTAs:
  - `Mandat besprechen`
  - `Ansatz ansehen`
- Zusaetzlicher Scroll-Hinweis zum naechsten Abschnitt (`index.html:2160`)

### 6.2 Haltung

- Kernthese: Fuehrungsbesetzung wird nicht als Prozess, sondern als Entscheidung mit Wirkung verstanden.
- Inhaltlicher Schwerpunkt:
  - selektives Arbeiten
  - wenige Mandate
  - persoenliche Begleitung
  - direkte, respektvolle Ansprache
  - Verantwortung gegenueber Unternehmen und Kandidat:innen
- Schlussgedanke: `Nicht jede Besetzung ist dringend. Aber jede verdient Sorgfalt.`

### 6.3 Ansatz

- Ueberschrift: `Fokus auf das, was entscheidend ist.`
- Logik: Besetzung folgt Verstaendnis, Einordnung und Entscheidung statt Standardprozess.
- 4 inhaltliche Schritte:
  1. `Verstaendnis & Einordnung`
  2. `Marktverstaendnis & gezielte Ansprache`
  3. `Bewertung & Passungsentscheidung`
  4. `Entscheidungsbegleitung`
- Jeder Schritt enthaelt eine kurze Beschreibung und ein explizites `Ergebnis`.
- Abschlusspunkt: Gute Besetzungen entstehen durch Klarheit in der Entscheidung, nicht durch Geschwindigkeit (`index.html:2277-2284`).

### 6.4 Werte

- Ueberschrift: `Grundsaetze der Zusammenarbeit.`
- 5 definierte Prinzipien:
  1. `Selektivitaet`
  2. `Ehrlichkeit`
  3. `Naehe`
  4. `Urteilskraft`
  5. `Verbindlichkeit`
- Jedes Prinzip hat eine kurze Leitthese plus einen zweiten Absatz mit praktischer Bedeutung.
- Die Werte machen die inhaltliche Positionierung sehr konkret und sind eine gute Basis fuer spaetere Marken-, Sales- und Messaging-Arbeit.

### 6.5 Ueber Mich

- Bereich ist persoenlich und nah formuliert.
- Kernperson: `Christian Dumler` (`index.html:2378`)
- Rollenbeschreibung: `Inhaber & persoenlicher Ansprechpartner bei D.ONE.` (`index.html:2388`)
- Schwerpunkt: IT- und Marketing-Fuehrungsbesetzungen (`index.html:2391-2392`)
- Studium / Hintergrund: wirtschaftlicher Hintergrund mit Fokus auf Informatik (`index.html:2394-2396`)
- Arbeitsweise: nah, direkt, verbindlich und persoenlich (`index.html:2398-2400`)
- Gruendungsgedanke: D.ONE entstand aus dem Wunsch nach ruhigeren, persoenlicheren und verantwortlicheren Besetzungen (`index.html:2406-2409`)
- Vision: Unternehmen und Kandidat:innen so zusammenbringen, dass daraus tragfaehige Entscheidungen werden.

### 6.6 Kennzahlen (Vorbereitet, Versteckt)

- Bereich ist vorhanden, aber durch `is-hidden-feature` deaktiviert.
- Inhalt:
  - `200+ erfolgreich begleitete Besetzungen`
  - `95 % nachhaltige Besetzungen`
  - `72h bis zur ersten qualifizierten Auswahl`
  - `18+ Jahre Erfahrung`
- Wirkung: potentiell starker Social-Proof-Block fuer spaeteres Go-Live, derzeit aber nicht sichtbar.

### 6.7 Referenzen (Vorbereitet, Versteckt)

- Bereich ist ebenfalls vorhanden, aber nicht sichtbar.
- Enthalten sind drei Testimonials aus:
  - Technologieunternehmen
  - Mittelstand / Personal
  - Finance / Kandidatin
- Wirkung: inhaltlich gut, aber noch bewusst deaktiviert.

### 6.8 Kontakt

- Ueberschrift: `Vertraulich austauschen.`
- Sichtbare Kontaktpunkte:
  - E-Mail: `kontakt@d.one` (`index.html:2504`)
  - Telefon: `+49 176 3457 6090`
  - Standort: `Frankfurt am Main`
- Kontaktformular:
  - 2 Anfragearten: `Unternehmen` und `Kandidat:in`
  - Unternehmensformular mit Firmenname, Kontaktperson, E-Mail, Nachricht
  - Kandidat:innen-Formular mit Name, E-Mail, Nachricht
  - Dateiupload fuer PDF, DOC, DOCX, TXT, RTF
  - sichtbarer Hinweis auf max. 2 MB

### 6.9 Footer

- Claim: `Besetzungen mit Verantwortung.`
- Copyright:
  - `© 2026 D.ONE Alle Rechte vorbehalten.`
- Links:
  - Impressum
  - Datenschutz
  - LinkedIn
- Der LinkedIn-Link ist aktuell noch ein Platzhalter (`index.html:2662`).

## 7. Rechtstext-Seiten

### 7.1 Impressum

- Titel: `Impressum | d.one` (`impressum.html:10`)
- Meta Description vorhanden (`impressum.html:8`)
- D.ONE Header-Branding vorhanden
- Ruecklink oben und zusaetzlicher Rueckkehr-Button am Seitenende
- Inhaltliche Bloecke:
  - Anbieter
  - Kontakt
  - Umsatzsteuer
  - Verantwortlich nach MStV
  - Hinweis zur Taetigkeit
  - EU-Streitschlichtung
  - Verbraucherstreitbeilegung

### 7.2 Datenschutz

- Titel: `Datenschutz | d.one` (`datenschutz.html:10`)
- Meta Description vorhanden (`datenschutz.html:8`)
- D.ONE Header-Branding vorhanden
- Ruecklink oben und zusaetzlicher Rueckkehr-Button am Seitenende
- Inhaltliche Bloecke:
  - Allgemeine Hinweise
  - Verantwortlicher
  - Erhebung und Speicherung personenbezogener Daten
  - Kontaktaufnahme
  - Weitergabe von Daten
  - Hosting
  - Ihre Rechte
  - Beschwerderecht
  - Speicherdauer
  - SSL/TLS
  - Stand

## 8. Design- Und UX-System

- Stilrichtung: hochwertig, ruhig, hell, boutique-artig
- Farbwelt: cremiger/beiger Hintergrund mit warmem Accent-Ton
- Typografie:
  - `Plus Jakarta Sans`
  - `Sora`
  - auf der Startseite zusaetzlich `Cormorant Garamond`
- Struktur:
  - starke Section-Rhythmen
  - grosszuegige Whitespaces
  - ruhige Karten- und Linienmotive
- Mobile UX:
  - eigenes Mobile-Menue mit Toggle
  - responsives Layout ueber mehrere Breakpoints
- Motion/Interaktion:
  - scroll-basierte Hero-Hintergrunddynamik
  - sequentielles Reveal fuer `Ansatz`
  - sequentielles Reveal fuer `Werte`
  - Upload-Dropzone mit Drag-and-Drop-State
  - `prefers-reduced-motion` wird beruecksichtigt

## 9. Technischer Stand

### Frontend-Architektur

- Komplett statisch
- CSS inline in jeder HTML-Datei
- JavaScript inline am Ende von `index.html` (`index.html:2667`)
- Kein bundling, kein transpiling, keine Dependencies im Projekt selbst

### Externe Abhaengigkeiten

- Google Fonts via `fonts.googleapis.com` und `fonts.gstatic.com`
- Externer Formularversand ueber FormSubmit (`index.html:2545`)

### Wichtige Interaktionen Im Code

- Mobile Navigation mit `#menuButton` und `#mobileMenu`
- Header wird scrollabhaengig ein- und ausgeblendet
- `Ansatz` und `Werte` haben eigene scrollgesteuerte Sequenz-Logiken
- Anfrage-Tabs schalten Formulargruppen dynamisch um
- Drag-and-Drop-Dateiupload mit Dateigroessenpruefung
- Inaktive Formularfelder werden sauber `disabled` gesetzt

## 10. Offene Luecken / Risiken (Priorisiert)

### Kritisch

1. Rechtliche Platzhalter sind noch nicht final ersetzt.
- `impressum.html:245` enthaelt `[E-Mail-Adresse]`
- `impressum.html:246` enthaelt `https://[deine-domain].de`
- `impressum.html:254` enthaelt Platzhaltertext zur Umsatzsteuer-ID
- `datenschutz.html:245` enthaelt `[Deine E-Mail-Adresse]`

2. Kontaktkanal ist inkonsistent.
- Sichtbar ist `kontakt@d.one` (`index.html:2504`)
- Das Formular sendet aber an `christian-dumler@web.de` (`index.html:2545`)
- Das kann bewusst sein, wirkt nach aussen aber inkonsistent und sollte entschieden werden.

### Hoch

3. Founder-Bild wird referenziert, ist aber nicht im Projekt vorhanden.
- Referenz: `index.html:2366`
- Tatsaechlich vorhanden im `assets`-Ordner ist nur `assets/sds-wordmark.png`
- Ergebnis: aktuell wird der `CD`-Fallback gezeigt.

4. LinkedIn-Link ist noch ein Platzhalter.
- `index.html:2662` nutzt `href="#"`

5. Branding ist weitgehend umgestellt, aber noch nicht komplett konsistent.
- Rechtstext-Titel verwenden `d.one` in Kleinschreibung (`impressum.html:10`, `datenschutz.html:10`)
- Das Asset heisst noch `assets/sds-wordmark.png`
- Das Asset wird derzeit offenbar nicht aktiv genutzt.

### Mittel

6. SEO ist weiterhin nur basal.
- Vorhanden:
  - `title`
  - `meta description`
- Fehlend:
  - `canonical`
  - Open Graph
  - Twitter Cards
  - strukturierte Daten / JSON-LD

7. Versteckte Sektionen sind inhaltlich vorbereitet, aber nicht in Nutzung.
- `Kennzahlen`
- `Referenzen`
- Das ist kein Bug, aber ein strategischer Zwischenstand.

8. Das Projekt ist technisch wartungsarm, aber inhaltlich monolithisch.
- `index.html` ist ueber 3,000 Zeilen gross.
- CSS, HTML und JS sind in einer Datei gebuendelt.
- Fuer schnelle Einzelanpassungen ist das okay, fuer laufende Weiterentwicklung wird es sperriger.

9. Es gibt keinen expliziten Datenschutz-/Einwilligungshinweis direkt am Kontaktformular.
- Das Formular ist funktional.
- Im direkten Formularbereich ist aber kein gesonderter Hinweis auf Datenverarbeitung oder ein Link auf die Datenschutzerklaerung eingebaut.

## 11. Go-Live-Reifegrad

- Reifegrad heute: sehr starker visueller und inhaltlicher Marketing-Auftritt mit klarer Positionierung.
- Nicht voll produktionsfertig wegen rechtlicher Restpunkte, Kontakt-Inkonsistenzen und einzelner Platzhalter.
- Im Vergleich zum alten Report ist die Seite naeher an einem Live-Stand, aber noch nicht "final abgeschlossen".

### Minimum Fuer Einen Sauberen Produktivstand

1. Platzhalter in Impressum und Datenschutz final ersetzen.
2. Entscheiden, welche E-Mail technisch und sichtbar verbindlich genutzt werden soll.
3. LinkedIn-Link mit echtem Profil hinterlegen.
4. `assets/christian-dumler.jpg` bereitstellen oder den Bereich bewusst ohne Foto finalisieren.
5. Branding-Namenskonvention fuer `D.ONE` vs. `d.one` vereinheitlichen.
6. SEO-Grundausstattung um `canonical`, OG und Twitter Meta erweitern.

## 12. Empfehlung Fuer Dein ChatGPT-Projekt

Das Projekt eignet sich sehr gut fuer ein laufendes ChatGPT-Workspace-Projekt, weil die Website statisch, ueberschaubar und inhaltlich bereits klar positioniert ist. Es braucht weniger "Produktneu-Erfindung" und mehr strukturierte Weiterentwicklung.

### Sinnvolle ChatGPT-Arbeitsstraenge

1. Marken- und Messaging-Arbeit
- Claim-Varianten
- LinkedIn-/Profiltexte
- About-/Founder-Texte
- Texte fuer Kontakt, Leistung, Referenzen

2. Go-Live-Polish
- rechtliche Finalisierung
- Brand-Konsistenz
- Link- und Asset-Finalisierung
- SEO-Metadaten

3. Conversion-Optimierung
- Hero-Varianten
- CTA-Hierarchie
- Formulartext / Vertrauenssignale
- Referenzen und Kennzahlen aktivieren oder ueberarbeiten

4. Technische Weiterentwicklung
- HTML aufraeumen
- CSS/JS modularisieren
- Formular sauber an finalen Mail-Flow anpassen
- spaeter evtl. Deployment-/Hosting-Checkliste

## 13. Kurzbriefing Fuer ChatGPT (Copy-Paste)

"Ich habe eine statische Marken-Website fuer D.ONE mit drei HTML-Dateien (`index.html`, `impressum.html`, `datenschutz.html`) ohne Framework und ohne Build-System. Die Website ist visuell weit entwickelt, responsiv und enthaelt bereits mehrere scroll-basierte Interaktionen. Inhaltlich positioniert sich D.ONE als Boutique fuer die Besetzung von Fuehrungsrollen mit Fokus auf Sorgfalt, Selektivitaet, persoenlicher Begleitung und tragfaehigen Entscheidungen. Die Startseite hat die Bereiche Hero, Haltung, Ansatz, Werte, Ueber mich, Kontakt sowie vorbereitete, aber versteckte Bereiche fuer Kennzahlen und Referenzen. Ein Kontaktformular mit Anfragearten-Umschaltung und Dateiupload ist integriert und nutzt FormSubmit. Offene Punkte sind: rechtliche Platzhalter in Impressum/Datenschutz, Inkonsistenz zwischen sichtbarer E-Mail und Formular-Zieladresse, fehlendes Founder-Foto, Platzhalter-Link fuer LinkedIn, unvollstaendige SEO-Metadaten und kleinere Brand-Konsistenzfragen (`D.ONE` vs. `d.one`, altes Asset `sds-wordmark.png`). Ich moechte dieses Projekt nun mit ChatGPT Schritt fuer Schritt weiter ausarbeiten, priorisieren und produktionsreif machen."
