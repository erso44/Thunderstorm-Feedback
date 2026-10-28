# Thunderstorm — Creator-Anleitung & Feedback

**Thunderstorm ist die Live-Shopping-Plattform für Creator.** Geh live, zeig dein Produkt und verkauf in Echtzeit – deine Community, dein Shop und deine Live-Streams an einem Ort.

Willkommen! 🎉 Die Alpha-Phase ist abgeschlossen – Thunderstorm ist **live**. Diese Anleitung zeigt dir, wie du als Creator startest, und dieses Repository bleibt der Ort für dein Feedback: Jeder Fehler, den du findest, und jeder Eindruck, den du teilst, fließt direkt in die Weiterentwicklung ein.

> **💬 DEIN FEEDBACK GEHÖRT INS ISSUE BOARD** — Feedback, Anregungen, Wünsche und Fehlermeldungen sammeln wir im [**Issue Board**](https://github.com/erso44/Thunderstorm-Feedback/issues). Dort kannst du bestehende Einträge lesen, mit 👍 unterstützen und kommentieren – oder mit [**New Issue**](https://github.com/erso44/Thunderstorm-Feedback/issues/new/choose) etwas Neues einreichen. Bitte schreib uns Feedback nicht per Chat oder E-Mail, damit nichts verloren geht (Ausnahme: Sicherheitslücken, Konto-Löschung und Zahlungsprobleme, siehe [Abschnitt 14](#14-kontakt)).

**Status**: Live · **Alpha**: Mai 2026 (abgeschlossen) · **Version**: 3.0 (deutsche Fassung)

> **ZAHLUNGEN SIND ECHT** — Die Plattform läuft im Live-Betrieb. Abo-Zahlungen, Käufe und Auszahlungen über Stripe sind **echtes Geld**; Testkarten funktionieren nicht mehr (siehe [Abschnitt 7](#7-zahlungen)). Funktionen werden weiter laufend verbessert.

---

## Schnellstart (2 Minuten)

1. **Öffnen**: [https://ek-thunderstorm.com](https://ek-thunderstorm.com)
2. **Als Creator registrieren**: Geh auf `https://ek-thunderstorm.com/registration/creator` und folge der Anmeldung in 4 Schritten.
3. **Shop einrichten**: Nach der Anmeldung führt dich ein Assistent durch die Einrichtung – Profil, Shop-Daten, Zahlungs-Setup und dein erstes Produkt.
4. **Erkunden**: Schau dir dein **Dashboard** an, öffne deinen **Shop**, stöbere im **Forum** und wirf einen Blick in den **Live**-Bereich.
5. **Feedback, Idee, Wunsch oder Fehler?** Trag es im [**Issue Board**](https://github.com/erso44/Thunderstorm-Feedback/issues) ein ([New Issue](https://github.com/erso44/Thunderstorm-Feedback/issues/new/choose) mit vorbereiteten Vorlagen). Schau vorher kurz, ob es schon einen Eintrag gibt, und unterstütze ihn mit 👍.

> **💡 Wichtig – bitte kurz lesen:**
> **Einige Communities sind schon mit Beispiel-Daten gefüllt.** Wundere dich nicht, wenn du fertige Communities mit Inhalten siehst – das ist **Absicht**, damit die Plattform nicht leer wirkt.
> **So startest du richtig:** Erstelle als **Creator** deine **eigene** Community und probiere dort alles aus. Möchtest du auch die Sicht eines **Mitglieds** sehen? Melde dich mit einem **zweiten Konto** (andere E-Mail) an und tritt deiner eigenen Community bei. So erlebst du **beide Seiten**.

---

## Was ist neu

| Datum | Update |
|-------|--------|
| Oktober 2026 | Anleitung v3.0 — **Alpha beendet, Thunderstorm ist live.** Alpha-Texte entfernt, **Zahlungen laufen jetzt im Live-Modus (echtes Geld, keine Testkarten mehr)**, Plan-Tabelle auf den aktuellen Stand gebracht (Limits, Provisionen; „Eigene Domain“ und „API-Zugriff“ sind entfallen), Registrierungs-Links korrigiert. |
| Juni 2026 | Anleitung v2.1 — komplett auf Deutsch, in einfacher Sprache und mit Fokus auf Creator. |
| Mai 2026 | Anleitung v2.0 — neu ausgerichtet auf Creator. Alpha startet für die ersten eingeladenen Creator. |

*Dieser Abschnitt wird aktualisiert, sobald wir auf Basis deines Feedbacks Verbesserungen ausliefern.*

---

## Inhaltsverzeichnis

1. [Willkommen](#1-willkommen)
2. [Erste Schritte](#2-erste-schritte)
3. [Bereiche der Plattform](#3-bereiche-der-plattform)
4. [Funktionen & Szenarien](#4-funktionen--szenarien)
5. [Nutzerrollen](#5-nutzerrollen)
6. [Abo-Pläne](#6-abo-pläne)
7. [Zahlungen](#7-zahlungen)
8. [Deine Daten & Datenschutz](#8-deine-daten--datenschutz)
9. [Verhaltenskodex](#9-verhaltenskodex)
10. [Probleme melden](#10-probleme-melden)
11. [Fehlerbehebung](#11-fehlerbehebung)
12. [Erfahrungen teilen](#12-erfahrungen-teilen)
13. [Häufige Fragen (FAQ)](#13-häufige-fragen-faq)
14. [Kontakt](#14-kontakt)

---

## 1. Willkommen

**Thunderstorm ist die Live-Shopping-Plattform für Creator in Deutschland.** Sie bringt Live-Shopping, Community und deinen eigenen Online-Shop an einem Ort zusammen: Du gehst live, verkaufst Produkte, baust eine Community auf – und behältst dein Publikum und deine Einnahmen. Die Plattform ist von Grund auf für Europa gebaut: Daten werden ruhend in Deutschland gespeichert (Details zu Dienstleistern und Übermittlungen siehe [Abschnitt 8](#8-deine-daten--datenschutz)), DSGVO- und BGB-konform, mit regelmäßigen Euro-Auszahlungen über Stripe Connect.

Als Creator kannst du eine Community aufbauen, einen Shop betreiben, deinen Bestand verwalten, live senden und deine Statistiken sehen – alles über ein einziges Dashboard. Mitglieder treten deiner Community bei, machen im Forum mit, stöbern in deinem Shop und schauen deine Streams.

**Wo stehen wir?** Die Alpha-Phase (ab Mai 2026) ist abgeschlossen, Thunderstorm ist live. Die Creator-Abläufe funktionieren komplett – Registrierung, Community aufbauen, Produkte einstellen, live gehen. Einzelne Funktionen werden weiter ausgebaut; sollte dir etwas auffallen, melde es bitte, wir bessern schnell nach.

### Was wir dich bitten

- **Probiere aus und melde**: Wenn dir etwas kaputt, verwirrend oder unvollständig vorkommt, nutze die [Vorlagen](#10-probleme-melden) – je mehr Details, desto schneller können wir helfen.
- **Bleib erreichbar**: Wenn wir bei etwas nachfragen, hilft uns eine kurze Antwort sehr.
- **Sei ehrlich**: Kritisches Feedback ist das wertvollste.

### Was wir besonders lernen möchten

- Sind die Registrierung und das Creator-Onboarding klar und einfach?
- Findest du dich auf der Plattform gut zurecht?
- Fühlt sich das Einrichten eines Shops und das Einstellen eines Produkts intuitiv an?
- Gibt es verwirrende, kaputte oder „tote" Bildschirme?

### Meilensteine

| Phase | Zeitraum | Stand |
|-------|----------|-------|
| **Alpha** | Mai 2026 | Abgeschlossen – erste eingeladene Creator haben die Plattform getestet. |
| **Live** | Aktuell | Die Plattform ist im Live-Betrieb, Zahlungen sind echt. |
| **Weiterentwicklung** | Laufend | Wir beheben gemeldete Probleme und liefern Updates aus. |

---

## 2. Erste Schritte

### Adresse der Plattform

**[https://ek-thunderstorm.com](https://ek-thunderstorm.com)**

### Unterstützte Umgebungen

| Browser | Status | Hinweise |
|---------|--------|----------|
| Google Chrome (aktuell) | Empfohlen | Haupt-Browser |
| Mozilla Firefox (aktuell) | Unterstützt | Voll funktionsfähig |
| Microsoft Edge (aktuell) | Sollte funktionieren | Nicht aktiv getestet |
| Safari (aktuell) | Sollte funktionieren | Nicht aktiv getestet |

**Gerät**: Die Plattform ist für Desktop-Browser gemacht. Auf dem Handy kann die Darstellung noch unterschiedlich sein.

**Sprache**: Die Oberfläche ist auf **Deutsch**. Oben im Navigationsbereich gibt es einen Sprachumschalter.

### Als Creator registrieren

Mit einem Creator-Konto kannst du eine Community verwalten, einen Shop betreiben, Produkte verkaufen, live senden, deinen Bestand verwalten und Statistiken sehen.

1. Geh auf `https://ek-thunderstorm.com/registration/creator`.
2. Durchlaufe die Anmeldung in 4 Schritten:
   - **Los geht's** — gib deine E-Mail-Adresse ein, um zu starten.
   - **Community** — wähle Name, Art und Sichtbarkeit deiner Community.
   - **Konto** — wähle deinen Benutzernamen und dein Passwort.
   - **Plan** — wähle einen Abo-Plan (siehe [Abschnitt 6](#6-abo-pläne)).
3. Danach geht es in den **Creator-Einrichtungs-Assistenten**, der dir beim Aufbau deines Shops hilft (siehe unten).

### Creator-Einrichtung (Onboarding)

Nach der Registrierung führt dich der Assistent durch die Einrichtung deines Shops. Er hat mehrere Schritte:

1. **Profil einrichten**
2. **Verkäufer-Status angeben** (Händler-Erklärung)
3. **Verpackungsregistrierung (LUCID)** – für gewerbliche Verkäufer
4. **Bevollmächtigter** – für gewerbliche Verkäufer
5. **Zahlungs-Setup (Stripe Connect)** – Auszahlungskonto verbinden
6. **Rechtliche & steuerliche Angaben**
7. **Benutzernamen wählen**
8. **Erstes Produkt anlegen**
9. **Shop veröffentlichen**

> **💡 Hinweis zum Verkäufer-Status**: Gib bei **Verkäufer-Status** wahrheitsgemäß an, ob du privat oder gewerblich verkaufst. Die Schritte nur für Gewerbliche (Verpackungsregistrierung, Bevollmächtigter) brauchen echte Registrierungsnummern und entfallen bei Privatverkäufern.

> **💳 Zahlungs-Setup ist wichtig**: Die Kasse deines Shops funktioniert erst, wenn das **Stripe-Connect**-Zahlungs-Setup abgeschlossen ist. Das Zahlungs-Setup läuft über Stripe im **Live-Modus** – du gibst dort echte Angaben ein, siehe [Abschnitt 7](#7-zahlungen).

> **🌍 Region**: Das Creator-/Verkäufer-Onboarding unterstützt aktuell **nur Deutschland**. Für den Zahlungs-Schritt brauchst du eine deutsche Adresse und ein echtes deutsches Bankkonto; Stripe prüft deine Angaben real. Creator außerhalb Deutschlands können das Onboarding aktuell nicht abschließen.

### Als Mitglied registrieren (optional)

Du kannst auch ein **Mitglieds-Konto** anlegen, um die Plattform aus Sicht eines Käufers zu testen – Communities ansehen, im Forum mitmachen, einkaufen und Streams schauen. Ein Mitglieds-Konto entsteht, indem du einer **Community beitrittst**:

1. Geh auf `https://ek-thunderstorm.com/registration/member`.
2. Wähle eine Community aus (am besten deine eigene) und gib deine E-Mail-Adresse ein.

> **So siehst du beide Seiten:** Lege **ein Creator-Konto** und **ein Mitglieds-Konto** mit **unterschiedlichen E-Mail-Adressen** an. Tritt mit dem zweiten Konto deiner **eigenen** Community bei – so siehst du sowohl die Creator- als auch die Mitglieder-Sicht. (Die schon vorhandenen Beispiel-Communities sind nur zur Veranschaulichung da.)

### Passwort-Anforderungen

| Anforderung | Regel |
|-------------|-------|
| Länge | 12–128 Zeichen |
| Großbuchstabe | Mindestens 1 (A–Z) |
| Kleinbuchstabe | Mindestens 1 (a–z) |
| Ziffer | Mindestens 1 (0–9) |
| Sonderzeichen | Mindestens 1 (z. B. `! @ # $ % & *`) |

### Mehrere Konten

Du kannst sowohl ein Creator- als auch ein Mitglieds-Konto anlegen, um beide Erlebnisse zu testen. Jedes Konto braucht eine **eigene E-Mail-Adresse**.

### Sitzung (Login)

Deine Anmeldung bleibt aktiv und wird etwa eine Woche lang automatisch verlängert. Falls sie abläuft, melde dich einfach erneut an.

---

## 3. Bereiche der Plattform

Die wichtigsten Bereiche im Überblick:

- **Dashboard** – Übersicht mit Zahlen und schnellen Aktionen (nur für Creator).
- **Forum** – Diskussionen und Beiträge der Community (für alle).
- **Shop** – Produkte ansehen und kaufen (für alle).
- **Live** – Live-Streams (für alle).
- **Inventar** – Bestände, Umlagerungen und Warnungen (nur für Creator).
- **Lager** – Lagerverwaltung (nur für Creator).
- **Analytik** – Kennzahlen zu Community und Shop (nur für Creator).
- **Warenkorb** – deine ausgewählten Produkte vor dem Kauf.
- **Benachrichtigungen** – Hinweise zu Aktivitäten rund um dein Konto.
- **Einstellungen** – Profil und Konto anpassen.
- **Sammlungen** – Merklisten / Wunschlisten.
- **Kasse** – Bezahlvorgang.
- **Meine Bestellungen** – deine Käufe und deren Status.
- **Entdecken** – Communities und Creator finden.

---

## 4. Funktionen & Szenarien

Zu jeder Funktion gibt es ein kleines Szenario. Folge den Schritten und vergleiche mit dem erwarteten Ergebnis. Weicht etwas ab, melde es bitte als Problem.

### 4.1 Deine Community

Deine Community ist dein Zuhause – sie entsteht bei der Registrierung.

**Szenario: Community prüfen**
1. Öffne dein **Dashboard**.
2. Prüfe, ob Name und Angaben deiner Community stimmen.
3. Öffne **Entdecken** und finde deine Community in der Creator-Liste.
4. **Erwartet**: Deine Community erscheint mit Name, Beschreibung und Mitgliederzahl.

### 4.2 Shop & Produkte

Richte deinen Shop ein und sieh ihn dir an.

**Szenario: Produkt anlegen und ansehen**
1. Beim Onboarding legst du ein erstes Produkt an – oder öffne deinen **Shop** und erstelle ein weiteres.
2. Fülle Name, Beschreibung, Preis (in Euro) und ein Bild aus.
3. Speichere das Produkt und öffne deinen **Shop** so, wie ihn ein Besucher sieht.
4. **Erwartet**: Dein Produkt erscheint im Shop mit Preis in Euro und einer Produktseite.

### 4.3 Bestandsverwaltung

Behalte die Lagerbestände deiner Produkte im Blick.

**Szenario: Bestand ansehen**
1. Öffne den Tab **Inventar**.
2. **Erwartet**: Die Bestandsübersicht zeigt deine Produkte mit Mengen und eventuellen Warnungen.

### 4.4 Analytik

Sieh, wie sich deine Community und dein Shop entwickeln.

**Szenario: Statistiken ansehen**
1. Öffne den Tab **Analytik**.
2. **Erwartet**: Es laden Kennzahlen-Karten zu Community und Shop.
3. Probiere die Zeitfilter und den Knopf **Exportieren** aus.

### 4.5 Live-Streaming

Schau dir den Live-Bereich an.

**Szenario: Live-Bereich durchstöbern**
1. Öffne den Tab **Live**.
2. **Erwartet**: Die Seite lädt mit Suche, Sortierung und Status-Filtern. Wenn gerade niemand sendet, ist die Liste leer – das ist normal.

### 4.6 Forum / Diskussionen

Starte und beteilige dich an Diskussionen.

**Szenario: Forenbeitrag erstellen**
1. Öffne den Tab **Forum** in deiner Community.
2. Wähle eine Kategorie und klicke auf **Neuer Beitrag**.
3. Gib Titel und Text ein. Probiere die Editor-Werkzeuge (Fett, Kursiv, Listen).
4. Klicke auf **Absenden**.
5. **Erwartet**: Dein Beitrag erscheint in der Kategorie, du kannst ihn ansehen und beantworten.

### 4.7 Einstellungen & Profil

Aktualisiere deine Konto-Einstellungen.

**Szenario: Profil aktualisieren**
1. Öffne **Einstellungen** über dein Profilmenü.
2. Ändere deine Profilangaben (z. B. Beschreibung, Anzeigename).
3. Klicke auf **Änderungen speichern**.
4. **Erwartet**: Die Änderungen werden gespeichert und eine Erfolgsmeldung erscheint.

### 4.8 Abo-Zahlung

Die Abo-Zahlung läuft während der Creator-Registrierung (echtes Geld, siehe Abschnitt 7).

**Szenario: Abo-Zahlung abschließen**
1. Der kostenlose **Starter**-Plan hat keinen Zahlungsschritt. Einen kostenpflichtigen Plan (Pro oder Business) buchst du nur, wenn du ihn wirklich nutzen willst – die Zahlung ist **echt** (siehe [Abschnitt 7](#7-zahlungen)).
2. Wählst du einen kostenpflichtigen Plan, gibst du deine Zahlungsdaten im sicheren Stripe-Formular ein.
3. Schließe die Zahlung ab.
4. **Erwartet**: Die Zahlung gelingt und du gelangst weiter ins Creator-Onboarding.

---

## 5. Nutzerrollen

| Rolle | Beschreibung | Zugriff |
|-------|--------------|---------|
| **Owner** | Community-Gründer mit voller Kontrolle | Alles – Dashboard, Forum, Shop, Inventar, Lager, Analytik, Live, Einstellungen |
| **Admin** | Erweiterte Verwaltung | Dashboard, Forum, Shop, Inventar, Analytik, Einstellungen |
| **Moderator** | Inhalte moderieren | Moderations-Werkzeuge im Forum, grundlegender Zugriff |
| **User** | Normales Mitglied | Forum, Shop, Live, Profil, Einstellungen |

Als Creator registrierst du dich über `/registration/creator` und wirst **Owner** deiner Community. Als Mitglied trittst du über `/registration/member` einer Community bei und bist **User**.

---

## 6. Abo-Pläne

Bei der Creator-Registrierung wählst du einen dieser Pläne:

| Funktion | Starter | Pro | Business |
|----------|---------|-----|----------|
| **Preis pro Monat** | Kostenlos | 29,99 € | 59,99 € |
| **Preis pro Jahr** | Kostenlos | 287,99 € | 575,99 € |
| **Provision pro Verkauf** | 7,5 % | 5 % | 3,5 % |
| Community-Mitglieder | 500 | 2.000 | 7.500 |
| Produkt-Einträge | 50 | 250 | 1.500 |
| Speicher | 1 GB | 5 GB | 10 GB |
| Live-Streaming | — | 80 Std/Monat | 150 Std/Monat |
| Gleichzeitige Streams | — | 1 | 2 |
| Zuschauer pro Stream | — | 100 | 150 |
| Forenkategorien | 10 | 25 | 100 |
| Moderatoren | 3 | 10 | 25 |
| Aufzeichnungen (VOD) | — | 14 Tage | 30 Tage |
| Live-Commerce (im Stream verkaufen) | — | Ja | Ja |
| Lagerverwaltung (WMS) | — | Lite | Full |
| Analytik | — | Ja | Ja |

Der kostenlose Starter-Plan hat keinen Zahlungsschritt; Pro und Business sind kostenpflichtig und werden **real abgebucht**. Die aktuell gültigen Plan-Details stehen immer auf der Preis-Seite der Plattform. Dort und im Bestellschritt stehen auch die Angaben zur Umsatzsteuer sowie zu Widerruf und Kündigung; maßgeblich sind die AGB und Widerrufsinformationen der Plattform.

---

## 7. Zahlungen

Thunderstorm läuft im **Live-Betrieb**, Stripe arbeitet im **Live-Modus**. Abo-Zahlungen, Käufe und Auszahlungen sind **echtes Geld**.

> ⚠️ **Testkarten funktionieren nicht mehr.** Stripe-Testdaten (z. B. `4242 …`) werden im Live-Modus abgelehnt. Umgekehrt wird eine echte Karte, die du eingibst, **wirklich belastet**. Buche einen kostenpflichtigen Plan (Pro/Business) nur, wenn du ihn tatsächlich nutzen willst; der Starter-Plan ist kostenlos und hat keinen Zahlungsschritt.

### Karten- und Bankdaten

Karten- und Bankdaten gibst du **ausschließlich in den sicheren Stripe-Formularen** ein – niemals in Beschreibungen, Foren, Issues oder per E-Mail an uns. Wir sehen deine vollständige Kartennummer nie. Poste auch in GitHub-Issues keine Zahlungsdaten, Screenshots davon oder Zahlungs-IDs mit persönlichen Daten.

### Stripe-Connect-Einrichtung (Auszahlungskonto)

Beim Creator-Onboarding öffnet der Schritt **Zahlungs-Setup** das sichere Formular von Stripe, damit du ein Auszahlungskonto verbindest. Stripe prüft dabei deine **echten** Angaben (Identität, Adresse, IBAN). Das Creator-/Verkäufer-Onboarding unterstützt aktuell **nur Deutschland**.

### Preise und Provision

Alle Preise auf der Plattform werden in **Euro (EUR)** angezeigt. Die Provision pro Verkauf hängt von deinem Plan ab (siehe [Abschnitt 6](#6-abo-pläne)). Bei Problemen mit einer Zahlung melde dich per E-Mail (siehe [Abschnitt 14](#14-kontakt)) – nicht über ein öffentliches Issue.

---

## 8. Deine Daten & Datenschutz

Dies ist eine kurze Orientierung. Das vollständige, maßgebliche Dokument ist die **Datenschutzerklärung** unter [https://ek-thunderstorm.com/privacy-terms](https://ek-thunderstorm.com/privacy-terms). Bei Abweichungen gilt immer die Datenschutzerklärung. Wer für die Verarbeitung verantwortlich ist, steht im Impressum unter [https://ek-thunderstorm.com/legal-notice](https://ek-thunderstorm.com/legal-notice).

**Was wir verarbeiten.**
- **Kontodaten** – deine E-Mail-Adresse, dein Benutzername und dein Passwort. Dein Passwort wird nie im Klartext gespeichert, sondern nur als gesalzener Hash.
- **Aktivitäts- und Zahlungsdaten** – wie du die Plattform nutzt sowie Abo-, Bestell- und Auszahlungsdaten.
- **Inhalte** – Communities, Beiträge, Kommentare oder Produkte, die du erstellst.

**Rechtsgrundlagen, Dienstleister, Übermittlungen in Drittländer und Aufbewahrungsfristen** (z. B. für Rechnungen und Buchungsbelege) stehen verbindlich in der Datenschutzerklärung. Wir wiederholen sie hier bewusst nicht, damit es keine abweichenden Fassungen gibt.

**Zahlungsabwicklung.** Karten- und Auszahlungsdaten, die du eingibst, werden von **Stripe**, unserem Zahlungsdienstleister, im Live-Modus verarbeitet (siehe [Abschnitt 7](#7-zahlungen)).

**Deine Rechte.** Nach der DSGVO hast du das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung, Datenübertragbarkeit und Widerspruch gegen die Verarbeitung sowie das Recht auf Beschwerde bei einer Datenschutz-Aufsichtsbehörde. Die zuständige Stelle und die Wege zur Ausübung deiner Rechte (u. a. Konto-Löschung in der Plattform) nennt die Datenschutzerklärung. Du kannst dich auch per E-Mail an **ekthunderstorminfo@gmail.com** wenden.

Maßgeblich ist immer die vollständige Datenschutzerklärung.

---

## 9. Verhaltenskodex

Mit der Nutzung dieses Repositories erklärst du dich einverstanden:

1. **Schütze sensible Daten.** Poste in GitHub-Issues keine Karten-, IBAN- oder Bankdaten, keine Passwörter und keine persönlichen Daten anderer Personen – auch nicht auf Screenshots. Zahlungsdaten gehören nur in die sicheren Stripe-Formulare (siehe [Abschnitt 7](#7-zahlungen)). Deine E-Mail-Adresse wird wie in [Abschnitt 8](#8-deine-daten--datenschutz) beschrieben verarbeitet.
2. **Bleib angemessen.** Poste keine beleidigenden, schädlichen oder unangemessenen Inhalte in Foren, Communities oder Produkten.
3. **Fair und sachlich bleiben.** Fehlermeldungen und kritisches Feedback in diesem Repository sind genau das, was wir uns wünschen. Beschreibe Probleme konkret und nachvollziehbar.
4. **Kein automatisiertes Testen.** Führe kein automatisches Scannen, keine Lasttests, keine Penetrationstests und kein API-Fuzzing durch.
5. **Melde Sicherheitsprobleme vertraulich.** Wenn du eine Sicherheitslücke findest, schick sie uns direkt per E-Mail (siehe [Abschnitt 14](#14-kontakt)) – poste sie nicht in einem öffentlichen Issue, nutze sie nicht aus und teile sie nicht mit anderen. Gutgläubige Hinweise auf Dinge, die dir bei normaler Nutzung auffallen, sind willkommen und werden dir nie zum Nachteil ausgelegt; die Einschränkung gilt nur für *aktives* Ausnutzen oder Scannen.
6. **Respektiere andere Nutzer.** Greife nicht auf Konten, Communities oder Inhalte anderer zu, ändere oder lösche sie nicht.
7. **Bleib erreichbar.** Wenn wir zu einer Meldung von dir nachfragen, antworte bitte, wenn du kannst – das hilft uns, Probleme schneller zu lösen.

---

## 10. Probleme melden

Etwas kaputt, verwirrend oder unerwartet? Bitte melde es!

### Wo melden

Alles läuft über das [**Issue Board**](https://github.com/erso44/Thunderstorm-Feedback/issues). Prüfe zuerst, ob es deinen Punkt schon gibt – dann gib ihm ein 👍 oder ergänze einen Kommentar. Sonst geh auf [**New Issue**](https://github.com/erso44/Thunderstorm-Feedback/issues/new/choose) und wähle die passende Vorlage:

| Vorlage | Wann nutzen |
|---------|-------------|
| **Bug Report** | Etwas funktioniert nicht richtig |
| **Feature Request** | Eine Verbesserung oder eine neue Idee |
| **General Feedback** | Dein Gesamteindruck oder deine Gedanken |
| **Security Concern** | Unkritische Sicherheits-/UX-Themen (Sicherheitslücken bitte direkt per E-Mail) |

**Antwortzeit**: Wir bestätigen jede Meldung innerhalb von **48 Stunden**.

### Vorlage für eine Fehlermeldung

Wenn du lieber selbst schreibst, gib bitte an:

```
**Titel**: [Kurze Beschreibung des Problems]

**Schritte zum Nachstellen**:
1. [Erster Schritt]
2. [Zweiter Schritt]
3. [Was passiert ist]

**Erwartetes Ergebnis**: [Was hätte passieren sollen]

**Tatsächliches Ergebnis**: [Was tatsächlich passiert ist]

**Browser & Gerät**: [z. B. Chrome 122 unter Windows 11]

**Screenshot**: [Wenn möglich anhängen]

**Dein Benutzername**: [Optional — hilft uns beim Prüfen der Server-Logs. Wenn du ihn nicht öffentlich posten möchtest, schick ihn uns per E-Mail.]
```

### Schweregrad-Leitfaden

| Schweregrad | Wann nutzen | Beispiel |
|-------------|-------------|----------|
| **Kritisch** | Eine Kernfunktion ist gar nicht nutzbar | Registrierung/Login nicht möglich, Seite stürzt ab |
| **Schwer** | Funktion kaputt, aber es gibt einen Umweg | Produkte lassen sich nicht filtern, aber durch Scrollen finden |
| **Gering** | Optischer oder nicht blockierender Fehler | Verrutschter Knopf, fehlende Übersetzung, langsames Laden |
| **Vorschlag** | Idee oder Verbesserung | „Schön wäre, wenn …" |

---

## 11. Fehlerbehebung

Bevor du ein Problem meldest, probiere diese schnellen Lösungen:

| Problem | Versuch das |
|---------|-------------|
| **Seite sieht kaputt oder veraltet aus** | Neu laden mit `Strg + Umschalt + R` (Windows/Linux) oder `Cmd + Umschalt + R` (Mac) |
| **Login klappt nicht** | Schreibweise des Benutzernamens prüfen (Groß-/Kleinschreibung beachten). Cookies für `ek-thunderstorm.com` löschen. |
| **Sitzung unerwartet abgelaufen** | Erneut anmelden. Sitzungen verlängern sich automatisch für etwa eine Woche. |
| **Knöpfe reagieren nicht** | Anderen Browser probieren (Chrome oder Firefox empfohlen). Browser-Erweiterungen deaktivieren, die stören könnten. |
| **Seite lädt, zeigt aber keinen Inhalt** | Ein paar Sekunden warten – manche Daten laden im Hintergrund. Nach ca. 10 Sekunden noch leer? Bitte melden. |
| **Fehler nach einem Update** | Wir liefern regelmäßig Updates. Browser-Cache leeren oder neu laden, um die neueste Version zu bekommen. |

Wenn nichts davon hilft, [melde das Problem bitte](#10-probleme-melden).

---

## 12. Erfahrungen teilen

Über Fehlermeldungen hinaus möchten wir von deinem Gesamteindruck hören – du musst keinen „Bug" finden, um wertvolles Feedback zu geben.

Öffne ein [**General Feedback**](https://github.com/erso44/Thunderstorm-Feedback/issues/new/choose)-Issue und teile deine Gedanken. Ein paar Anstöße:

- **Was war am verwirrendsten** bei der Nutzung?
- **Was fühlte sich gut gemacht oder intuitiv an?** Was funktionierte wie erwartet?
- **Welche Funktion würdest du am ehesten verbessern** wollen, bevor es öffentlich startet?
- **Wie war die Registrierung und das Onboarding?** Flüssig? Verwirrend? Zu viele Schritte?
- **Würdest du die Plattform einem anderen Creator empfehlen?** Warum oder warum nicht?
- **Hast du als Creator Funktionen erwartet, aber nicht gefunden?**

Jedes Feedback – positiv oder kritisch – hilft uns, die nächsten Schritte zu priorisieren.

---

## 13. Häufige Fragen (FAQ)

**F: Wird mir echtes Geld abgebucht?**
A: Ja, wenn du einen kostenpflichtigen Plan buchst oder etwas kaufst. Die Alpha ist vorbei, Stripe läuft im Live-Modus; Testkarten funktionieren nicht mehr. Der Starter-Plan ist kostenlos. Siehe [Abschnitt 7](#7-zahlungen).

**F: Warum ist die Plattform auf Deutsch?**
A: Thunderstorm richtet sich an den deutschsprachigen Markt. Oben im Navigationsbereich gibt es einen Sprachumschalter.

**F: Ich sehe die Tabs Dashboard, Analytik oder Inventar nicht.**
A: Diese sind nur für Creator-/Owner-Konten sichtbar. Registriere dich über `/registration/creator`, um sie zu sehen.

**F: Die Kasse in meinem Shop funktioniert nicht.**
A: Die Kasse deines Shops funktioniert erst, wenn du das **Stripe-Connect**-Zahlungs-Setup im Creator-Onboarding abgeschlossen hast. Siehe [Abschnitt 2](#2-erste-schritte).

**F: Kann ich von außerhalb Deutschlands testen?**
A: Die Plattform kannst du von überall ansehen, aber das Creator-/Verkäufer-Onboarding unterstützt aktuell **nur Deutschland** – du brauchst eine deutsche Adresse und ein echtes deutsches Bankkonto für den Zahlungs-Schritt (Stripe prüft die Angaben real).

**F: Kann ich meine Daten löschen lassen?**
A: Ja, du kannst die vollständige Löschung deines Kontos beantragen. Siehe [Abschnitt 8](#8-deine-daten--datenschutz).

**F: Kann ich die Plattform auf dem Handy nutzen?**
A: Die Plattform ist für Desktop-Browser gemacht. Auf dem Handy kann die Darstellung noch unterschiedlich sein.

**F: Woher weiß ich, wann es Updates gibt?**
A: Wir aktualisieren den Abschnitt [Was ist neu](#was-ist-neu) oben auf dieser Seite und melden uns bei größeren Änderungen ggf. per E-Mail.

---

## 14. Kontakt

Für Fragen, Probleme oder Feedback:

- **Issue Board** (bevorzugt): [erso44/Thunderstorm-Feedback](https://github.com/erso44/Thunderstorm-Feedback/issues) — für Fehler, Feedback, Anregungen und Funktionswünsche.
- **E-Mail**: ekthunderstorminfo@gmail.com — für Sicherheitsmeldungen, Konto-Löschung, Datenschutz-Anfragen oder Fragen außerhalb von GitHub.
- **Antwortzeit**: innerhalb von 48 Stunden.

---

Danke, dass du Teil von Thunderstorm bist! Deine Zeit und dein Feedback bedeuten uns wirklich viel. Jede Meldung, jeder Vorschlag und jeder Eindruck hilft uns, eine bessere Plattform für Creator und ihre Communities zu bauen. 🚀
