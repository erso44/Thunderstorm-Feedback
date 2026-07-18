# Thunderstorm — Alpha-Testanleitung für Creator

**Thunderstorm ist die Live-Shopping-Plattform für Creator.** Geh live, zeig dein Produkt und verkauf in Echtzeit – deine Community, dein Shop und deine Live-Streams an einem Ort.

Willkommen beim Alpha-Test! 🎉 Du gehörst zu den allerersten Creators, die Thunderstorm ausprobieren dürfen. Dein Feedback fließt direkt in das Produkt ein, bevor es offiziell startet. Danke, dass du dir die Zeit nimmst – jeder Fehler, den du findest, und jeder Eindruck, den du teilst, hilft uns wirklich weiter.

**Status**: Alpha · **Gestartet**: Mai 2026 · **Version**: 2.1 (deutsche Fassung)

> **ALPHA-HINWEIS** — Thunderstorm wird gerade aktiv entwickelt. Funktionen können sich ändern, Daten können zurückgesetzt werden, und manches ist noch nicht fertig. Bitte nutze die Plattform in der Testphase nicht für echte Geschäfte und verwende nur Test-Zahlungsdaten (siehe [Abschnitt 7](#7-zahlungstests)).

---

## Schnellstart (2 Minuten)

1. **Öffnen**: [https://ek-thunderstorm.com](https://ek-thunderstorm.com)
2. **Als Creator registrieren**: Geh auf `https://ek-thunderstorm.com/registration/creator` und folge der Anmeldung in 4 Schritten.
3. **Shop einrichten**: Nach der Anmeldung führt dich ein Assistent durch die Einrichtung – Profil, Shop-Daten, Zahlungs-Setup und dein erstes Produkt.
4. **Erkunden**: Schau dir dein **Dashboard** an, öffne deinen **Shop**, stöbere im **Forum** und wirf einen Blick in den **Live**-Bereich.
5. **Einen Fehler gefunden?** Melde ihn über [GitHub Issues](https://github.com/erso44/Thunderstorm-Feedback/issues/new/choose) mit den vorbereiteten Vorlagen.

> **💡 Wichtig – bitte kurz lesen:**
> **Einige Communities sind schon mit Beispiel-Daten gefüllt.** Wundere dich nicht, wenn du fertige Communities mit Inhalten siehst – das ist **Absicht**, damit die Plattform nicht leer wirkt.
> **So testest du richtig:** Erstelle als **Creator** deine **eigene** Community und teste dort alles. Möchtest du auch die Sicht eines **Mitglieds** sehen? Melde dich mit einem **zweiten Konto** (andere E-Mail) an und tritt deiner eigenen Community bei. So erlebst du **beide Seiten**.

---

## Was ist neu

| Datum | Update |
|-------|--------|
| Juni 2026 | Anleitung v2.1 — komplett auf Deutsch, in einfacher Sprache und mit Fokus auf Creator. |
| Mai 2026 | Anleitung v2.0 — neu ausgerichtet auf Creator. Alpha startet für die ersten eingeladenen Creator. |

*Dieser Abschnitt wird aktualisiert, sobald wir auf Basis deines Feedbacks Verbesserungen ausliefern.*

---

## Inhaltsverzeichnis

1. [Willkommen](#1-willkommen)
2. [Erste Schritte](#2-erste-schritte)
3. [Bereiche der Plattform](#3-bereiche-der-plattform)
4. [Funktionen & Test-Szenarien](#4-funktionen--test-szenarien)
5. [Nutzerrollen](#5-nutzerrollen)
6. [Abo-Pläne](#6-abo-pläne)
7. [Zahlungstests](#7-zahlungstests)
8. [Deine Daten & Datenschutz](#8-deine-daten--datenschutz)
9. [Verhaltenskodex für Alpha-Tester](#9-verhaltenskodex-für-alpha-tester)
10. [Probleme melden](#10-probleme-melden)
11. [Fehlerbehebung](#11-fehlerbehebung)
12. [Erfahrungen teilen](#12-erfahrungen-teilen)
13. [Häufige Fragen (FAQ)](#13-häufige-fragen-faq)
14. [Kontakt](#14-kontakt)

---

## 1. Willkommen

**Thunderstorm ist die Live-Shopping-Plattform für Creator in Deutschland.** Sie bringt Live-Shopping, Community und deinen eigenen Online-Shop an einem Ort zusammen: Du gehst live, verkaufst Produkte, baust eine Community auf – und behältst dein Publikum und deine Einnahmen. Die Plattform ist von Grund auf für Europa gebaut: Daten werden ruhend in Deutschland gespeichert (einzelne US-Dienstleister wie Cloudflare und Google verarbeiten begrenzte Daten unter EU-Standardvertragsklauseln – siehe [Abschnitt 8](#8-deine-daten--datenschutz)), DSGVO- und BGB-konform, mit täglichen Euro-Auszahlungen über Stripe Connect.

Als Creator kannst du eine Community aufbauen, einen Shop betreiben, deinen Bestand verwalten, live senden und deine Statistiken sehen – alles über ein einziges Dashboard. Mitglieder treten deiner Community bei, machen im Forum mit, stöbern in deinem Shop und schauen deine Streams.

**Was bedeutet Alpha-Test?** Du gehörst zu den ersten Creators von außerhalb, die Thunderstorm ausprobieren. Die Plattform ist schon so weit, dass echte Creator-Abläufe komplett funktionieren – Registrierung, Community aufbauen, Produkte einstellen, live gehen. Aber es ist Vor-Start-Software. Rechne mit kleinen Ecken und Kanten – und damit, dass wir auf Basis deiner Meldungen schnell nachbessern.

### Was wir dich bitten

- **Erste Runde**: Nimm dir 30–60 Minuten Zeit und probiere die Plattform aus, am besten anhand der [Test-Szenarien](#4-funktionen--test-szenarien).
- **Komm wieder**: Nachdem wir auf Basis deines Feedbacks Updates ausgeliefert haben, laden wir dich vielleicht zum erneuten Testen ein. So prüfen wir, ob die Lösungen wirklich funktionieren.
- **Melde Probleme**: Nutze die [Vorlagen](#10-probleme-melden) – je mehr Details, desto schneller können wir helfen.
- **Bleib erreichbar**: Wenn wir bei etwas nachfragen, hilft uns eine kurze Antwort sehr.
- **Sei ehrlich**: Kritisches Feedback ist das wertvollste.

### Was wir besonders lernen möchten

- Sind die Registrierung und das Creator-Onboarding klar und einfach?
- Findest du dich auf der Plattform gut zurecht?
- Fühlt sich das Einrichten eines Shops und das Einstellen eines Produkts intuitiv an?
- Gibt es verwirrende, kaputte oder „tote" Bildschirme?

### Zeitplan der Alpha

| Phase | Zeitraum | Was passiert |
|-------|----------|--------------|
| **Alpha** (aktuell) | Mai 2026 | Erste eingeladene Creator erkunden die Plattform, melden Fehler und geben Feedback. |
| **Fehlerbehebung & Iteration** | Laufend | Wir beheben gemeldete Probleme und liefern Updates aus. |
| **Beta** | Wird noch bekannt gegeben | Breiterer Test mit mehr Nutzern und mehr Funktionen. |
| **Öffentlicher Start** | Wird noch bekannt gegeben | Die Plattform öffnet sich für alle. |

### Anerkennung für Tester

Creator, die aktiv mitmachen und gutes Feedback geben, werden in unseren Start-Credits genannt und bekommen neue Funktionen früher als die Öffentlichkeit.

---

## 2. Erste Schritte

### Adresse der Plattform

**[https://ek-thunderstorm.com](https://ek-thunderstorm.com)**

### Unterstützte Umgebungen

| Browser | Status | Hinweise |
|---------|--------|----------|
| Google Chrome (aktuell) | Empfohlen | Haupt-Testbrowser |
| Mozilla Firefox (aktuell) | Unterstützt | Voll funktionsfähig |
| Microsoft Edge (aktuell) | Sollte funktionieren | Nicht aktiv getestet |
| Safari (aktuell) | Sollte funktionieren | Nicht aktiv getestet |

**Gerät**: Die Plattform ist für Desktop-Browser gemacht. Auf dem Handy kann die Darstellung in der Alpha noch unterschiedlich sein.

**Sprache**: Die Oberfläche ist auf **Deutsch**. Oben im Navigationsbereich gibt es einen Sprachumschalter.

### Als Creator registrieren

Mit einem Creator-Konto kannst du eine Community verwalten, einen Shop betreiben, Produkte verkaufen, live senden, deinen Bestand verwalten und Statistiken sehen.

1. Geh auf `https://ek-thunderstorm.com/registration/customer`.
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

> **💡 Tipp für Tester**: Wähle beim **Verkäufer-Status** „**Privatverkäufer**", wenn du nur testest. Die Schritte nur für Gewerbliche (Verpackungsregistrierung, Bevollmächtigter) werden dann automatisch übersprungen – sie brauchen echte Registrierungsnummern, die du für ein Testkonto nicht hast.

> **💳 Zahlungs-Setup ist wichtig**: Die Kasse deines Shops funktioniert erst, wenn das **Stripe-Connect**-Zahlungs-Setup abgeschlossen ist. Nutze dafür Testdaten – siehe [Abschnitt 7](#7-zahlungstests).

> **🌍 Region**: Das Creator-/Verkäufer-Onboarding unterstützt aktuell **nur Deutschland**. Wenn du von außerhalb Deutschlands testest, brauchst du für den Zahlungs-Schritt eine deutsche Adresse und deutsche Test-Bankdaten.

### Als Mitglied registrieren (optional)

Du kannst auch ein **Mitglieds-Konto** anlegen, um die Plattform aus Sicht eines Käufers zu testen – Communities ansehen, im Forum mitmachen, einkaufen und Streams schauen. Ein Mitglieds-Konto entsteht, indem du einer **Community beitrittst**:

1. Geh auf `https://ek-thunderstorm.com/registration/user`.
2. Wähle eine Community aus (am besten deine eigene) und gib deine E-Mail-Adresse ein.

> **So testest du beide Seiten:** Lege **ein Creator-Konto** und **ein Mitglieds-Konto** mit **unterschiedlichen E-Mail-Adressen** an. Tritt mit dem zweiten Konto deiner **eigenen** Community bei – so siehst du sowohl die Creator- als auch die Mitglieder-Sicht. (Die schon vorhandenen Beispiel-Communities sind nur zur Veranschaulichung da.)

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

## 4. Funktionen & Test-Szenarien

Zu jeder Funktion gibt es ein kleines Test-Szenario. Folge den Schritten und vergleiche mit dem erwarteten Ergebnis. Weicht etwas ab, melde es bitte als Problem.

### 4.1 Deine Community

Deine Community ist dein Zuhause – sie entsteht bei der Registrierung.

**Test-Szenario: Community prüfen**
1. Öffne dein **Dashboard**.
2. Prüfe, ob Name und Angaben deiner Community stimmen.
3. Öffne **Entdecken** und finde deine Community in der Creator-Liste.
4. **Erwartet**: Deine Community erscheint mit Name, Beschreibung und Mitgliederzahl.

### 4.2 Shop & Produkte

Richte deinen Shop ein und sieh ihn dir an.

**Test-Szenario: Produkt anlegen und ansehen**
1. Beim Onboarding legst du ein erstes Produkt an – oder öffne deinen **Shop** und erstelle ein weiteres.
2. Fülle Name, Beschreibung, Preis (in Euro) und ein Bild aus.
3. Speichere das Produkt und öffne deinen **Shop** so, wie ihn ein Besucher sieht.
4. **Erwartet**: Dein Produkt erscheint im Shop mit Preis in Euro und einer Produktseite.

### 4.3 Bestandsverwaltung

Behalte die Lagerbestände deiner Produkte im Blick.

**Test-Szenario: Bestand ansehen**
1. Öffne den Tab **Inventar**.
2. **Erwartet**: Die Bestandsübersicht zeigt deine Produkte mit Mengen und eventuellen Warnungen.

### 4.4 Analytik

Sieh, wie sich deine Community und dein Shop entwickeln.

**Test-Szenario: Statistiken ansehen**
1. Öffne den Tab **Analytik**.
2. **Erwartet**: Es laden Kennzahlen-Karten zu Community und Shop.
3. Probiere die Zeitfilter und den Knopf **Exportieren** aus.

### 4.5 Live-Streaming

Schau dir den Live-Bereich an.

**Test-Szenario: Live-Bereich durchstöbern**
1. Öffne den Tab **Live**.
2. **Erwartet**: Die Seite lädt mit Suche, Sortierung und Status-Filtern. Wenn gerade niemand sendet, ist die Liste leer – das ist normal.

### 4.6 Forum / Diskussionen

Starte und beteilige dich an Diskussionen.

**Test-Szenario: Forenbeitrag erstellen**
1. Öffne den Tab **Forum** in deiner Community.
2. Wähle eine Kategorie und klicke auf **Neuer Beitrag**.
3. Gib Titel und Text ein. Probiere die Editor-Werkzeuge (Fett, Kursiv, Listen).
4. Klicke auf **Absenden**.
5. **Erwartet**: Dein Beitrag erscheint in der Kategorie, du kannst ihn ansehen und beantworten.

### 4.7 Einstellungen & Profil

Aktualisiere deine Konto-Einstellungen.

**Test-Szenario: Profil aktualisieren**
1. Öffne **Einstellungen** über dein Profilmenü.
2. Ändere deine Profilangaben (z. B. Beschreibung, Anzeigename).
3. Klicke auf **Änderungen speichern**.
4. **Erwartet**: Die Änderungen werden gespeichert und eine Erfolgsmeldung erscheint.

### 4.8 Abo-Zahlung

Teste die Abo-Zahlung während der Creator-Registrierung.

**Test-Szenario: Abo-Zahlung abschließen**
1. Wähle im Schritt **Plan** der Registrierung einen **kostenpflichtigen Plan** (Pro oder Business) – der kostenlose Starter-Plan hat keinen Zahlungsschritt.
2. Gib die Testkarten-Nummer `4242 4242 4242 4242` ein (siehe [Abschnitt 7](#7-zahlungstests)).
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

**Für den Alpha-Test** empfehlen wir, dich als **Owner** zu registrieren (über `/registration/customer`), um das volle Creator-Erlebnis zu testen. Zusätzlich kannst du dich als **User** registrieren (über `/registration/user`), um die Mitglieder-Sicht zu sehen.

---

## 6. Abo-Pläne

Bei der Creator-Registrierung wählst du einen dieser Pläne:

| Funktion | Starter | Pro | Business |
|----------|---------|-----|----------|
| **Preis pro Monat** | Kostenlos | 29,99 € | 59,99 € |
| **Preis pro Jahr** | Kostenlos | 287,99 € | 575,99 € |
| Community-Mitglieder | 500 | 2.000 | 15.000 |
| Produkt-Einträge | 50 | 250 | 3.000 |
| Speicher | 2 GB | 15 GB | 20 GB |
| Live-Streaming | 720p · 15 Std/Monat | 1080p · 80 Std/Monat | 1080p · 150 Std/Monat |
| Gleichzeitige Streams | 1 | 2 | 3 |
| Zuschauer pro Stream | 50 | 200 | 500 |
| Forenkategorien | 10 | 25 | 100 |
| Moderatoren | 3 | 10 | 25 |
| Aufzeichnungen (VOD) | 14 Tage | 30 Tage | 45 Tage |
| Live-Commerce (im Stream verkaufen) | — | Ja | Ja |
| Lagerverwaltung (WMS) | — | Lite | Full |
| Analytik | — | Ja | Ja |
| Eigene Domain | — | — | — |
| API-Zugriff | — | — | — |

**Für den Alpha-Test**: Alle Pläne funktionieren mit Test-Zahlungskarten – es wird **kein echtes Geld** abgebucht. Der kostenlose Starter-Plan hat keinen Zahlungsschritt; wähle Pro oder Business, wenn du die Abo-Zahlung testen möchtest. Die aktuell gültigen Plan-Details stehen immer auf der Preis-Seite der Plattform.

---

## 7. Zahlungstests

Thunderstorm nutzt Stripe im **Sandbox- (Test-) Modus** für die Alpha. Es wird **kein echtes Geld** abgebucht.

> ⚠️ **Gib niemals echte Zahlungsdaten ein.** Verwende nirgends eine echte Kredit-/EC-Karte, eine echte IBAN oder echte Bankdaten – weder an der Abo-Kasse noch beim Stripe-Connect-Zahlungs-Setup. Nutze nur die Testdaten unten.

### Test-Karten fürs Abo

| Kartennummer | Ergebnis |
|--------------|----------|
| `4242 4242 4242 4242` | Zahlung gelingt |
| `4000 0000 0000 0002` | Zahlung wird abgelehnt |

Für alle Testkarten:
- **Ablaufdatum**: ein beliebiges Datum in der Zukunft (z. B. `12/30`)
- **CVC**: beliebige 3 Ziffern (z. B. `123`)
- **PLZ**: beliebige 5 Ziffern (z. B. `12345`)

### Stripe-Connect-Einrichtung (Zahlungs-Setup)

Beim Creator-Onboarding öffnet der Schritt **Zahlungs-Setup** das sichere Formular von Stripe, damit du ein Auszahlungskonto verbindest. Im Testmodus erwartet Stripe **Testdaten** – niemals echte persönliche oder Bankdaten. Typische Stripe-Testwerte:

- **Telefon**: `000 000 0000`
- **Geburtsdatum**: ein Datum, das dich über 18 macht (z. B. `01/01/1990`)
- **Test-IBAN (Deutschland)**: `DE89 3704 0044 0532 0130 00`

> Falls ein Feld diese Werte ablehnt, schau in die aktuelle Stripe-Testdokumentation – Stripe ändert die Testdaten gelegentlich. Denk daran: Das Creator-/Verkäufer-Onboarding unterstützt aktuell **nur Deutschland**.

Alle Preise auf der Plattform werden in **Euro (EUR)** angezeigt.

---

## 8. Deine Daten & Datenschutz

Dies ist eine kurze Zusammenfassung für Alpha-Tester. Das vollständige, maßgebliche Dokument ist die **Datenschutzerklärung** unter [https://ek-thunderstorm.com/privacy-terms](https://ek-thunderstorm.com/privacy-terms).

**Verantwortlicher.** ThunderLabs UG, Baumensteinstr. 2, 89134 Blaustein, Deutschland – Verantwortlicher im Sinne von Art. 4 Nr. 7 DSGVO. Vollständige Angaben findest du im Impressum unter [https://ek-thunderstorm.com/legal-notice](https://ek-thunderstorm.com/legal-notice).

**Was wir während der Alpha verarbeiten.**
- **Kontodaten** – deine E-Mail-Adresse, dein Benutzername und dein Passwort. Dein Passwort wird nie im Klartext gespeichert, sondern nur als gesalzener Hash.
- **Aktivitätsdaten** – wie du die Plattform nutzt, zu Test- und Verbesserungszwecken.
- **Inhalte** – Communities, Beiträge, Kommentare oder Produkte, die du erstellst.

**Rechtsgrundlagen.** Die Verarbeitung für deine Teilnahme am Alpha-Test stützt sich auf die Durchführung der Testvereinbarung; Aktivitäts-/Nutzungsdaten verarbeiten wir auf Grundlage unseres berechtigten Interesses am Betrieb, an der Sicherheit und an der Verbesserung der Plattform; wo das Gesetz es verlangt (z. B. bei nicht notwendigen Cookies), stützen wir uns auf deine Einwilligung.

**Zahlungsabwicklung.** Karten- und Auszahlungsdaten, die du eingibst, werden von **Stripe**, unserem Zahlungsdienstleister, im Testmodus verarbeitet.

**US-Dienstleister (Drittlandübermittlung).** Deine Konto- und Kaufdaten werden ruhend in der EU (Hetzner, Falkenstein/Nürnberg) gespeichert. Wenige namentlich genannte US-Anbieter verarbeiten begrenzte Daten auf Grundlage der EU-Standardvertragsklauseln: **Cloudflare** (Edge-Sicherheit und DNS – verarbeitet technische Daten wie deine IP-Adresse) und **Google** (E-Mail-Versand). KI-Funktionen nutzen, sofern aktiviert, **OpenAI**.

**Aufbewahrung.** Kontodaten werden für die Lebensdauer deines Kontos und 30 Tage nach einem Löschantrag aufbewahrt. Nutzungs- und Analysedaten werden innerhalb von 90 Tagen aggregiert oder anonymisiert. Steuerlich relevante Unterlagen werden 10 Jahre aufbewahrt, wo das Gesetz es verlangt (§147 AO). Wir kontaktieren alle Tester, bevor am Ende der Alpha Daten geändert werden.

**Deine Rechte.** Nach der DSGVO hast du das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung, Datenübertragbarkeit und Widerspruch gegen die Verarbeitung. Außerdem hast du das Recht, dich bei der zuständigen Aufsichtsbehörde zu beschweren – für die ThunderLabs UG ist das die *Landesbeauftragte für den Datenschutz und die Informationsfreiheit Baden-Württemberg* (LfDI Baden-Württemberg). Um eines dieser Rechte auszuüben oder die Löschung deines Kontos zu beantragen, schreib an **ekthunderstorminfo@gmail.com**.

Mit der Teilnahme an diesem Alpha-Test bestätigst du diese Zusammenfassung und die vollständige Datenschutzerklärung.

---

## 9. Verhaltenskodex für Alpha-Tester

Mit der Teilnahme an diesem Alpha-Test erklärst du dich einverstanden:

1. **Nutze Testdaten für sensible Felder.** Eine echte E-Mail-Adresse ist für die Registrierung nötig und wird wie in [Abschnitt 8](#8-deine-daten--datenschutz) beschrieben verarbeitet. Bei optionalen Freitextfeldern (z. B. Beschreibung oder Adresse) vermeide echte persönliche Daten. **Gib niemals echte Karten-, IBAN- oder Bankdaten ein** – Stripe ist im Testmodus; nutze die Testdaten aus [Abschnitt 7](#7-zahlungstests). Gib niemals die echten Daten einer anderen Person ein.
2. **Bleib angemessen.** Poste keine beleidigenden, schädlichen oder unangemessenen Inhalte in Foren, Communities oder Produkten.
3. **Halte öffentliche Bewertungen bis zum Start zurück.** Fehlermeldungen und Feedback in diesem Repository sind genau das, was wir uns wünschen – bitte mach das. Was wir dich bitten zurückzuhalten: öffentliche Bewertungen, Rezensionen oder Social-Media-Beiträge über die Plattform. Sie ist Vor-Start-Software und ändert sich schnell – dein öffentliches Urteil hören wir gern, sobald wir bereit sind.
4. **Kein automatisiertes Testen.** Führe kein automatisches Scannen, keine Lasttests, keine Penetrationstests und kein API-Fuzzing durch.
5. **Melde Sicherheitsprobleme vertraulich.** Wenn du eine Sicherheitslücke findest, schick sie uns direkt per E-Mail (siehe [Abschnitt 14](#14-kontakt)) – poste sie nicht in einem öffentlichen Issue, nutze sie nicht aus und teile sie nicht mit anderen. Gutgläubige Hinweise auf Dinge, die dir bei normaler Nutzung auffallen, sind willkommen und werden dir nie zum Nachteil ausgelegt; die Einschränkung gilt nur für *aktives* Ausnutzen oder Scannen.
6. **Respektiere andere Tester.** Greife nicht auf Konten, Communities oder Inhalte anderer Tester zu, ändere oder lösche sie nicht.
7. **Bleib erreichbar.** Wenn wir zu einer Meldung von dir nachfragen, antworte bitte, wenn du kannst – das hilft uns, Probleme schneller zu lösen.

---

## 10. Probleme melden

Etwas kaputt, verwirrend oder unerwartet? Bitte melde es!

### Wo melden

Geh auf [**New Issue**](https://github.com/erso44/Thunderstorm-Feedback/issues/new/choose) und wähle die passende Vorlage:

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
A: Nein. Stripe ist in der Alpha im Testmodus. Solange du die Testdaten aus [Abschnitt 7](#7-zahlungstests) nutzt, gibt es keine echte Zahlung.

**F: Warum ist die Plattform auf Deutsch?**
A: Thunderstorm richtet sich an den deutschsprachigen Markt. Oben im Navigationsbereich gibt es einen Sprachumschalter.

**F: Ich sehe die Tabs Dashboard, Analytik oder Inventar nicht.**
A: Diese sind nur für Creator-/Owner-Konten sichtbar. Registriere dich über `/registration/customer`, um sie zu sehen.

**F: Die Kasse in meinem Shop funktioniert nicht.**
A: Die Kasse deines Shops funktioniert erst, wenn du das **Stripe-Connect**-Zahlungs-Setup im Creator-Onboarding abgeschlossen hast. Siehe [Abschnitt 2](#2-erste-schritte).

**F: Kann ich von außerhalb Deutschlands testen?**
A: Die Plattform kannst du von überall ansehen, aber das Creator-/Verkäufer-Onboarding unterstützt aktuell **nur Deutschland** – du brauchst eine deutsche Adresse und deutsche Test-Bankdaten für den Zahlungs-Schritt.

**F: Was passiert mit meinen Daten nach der Alpha?**
A: Nach der Alpha kannst du dein Konto und deine Daten behalten oder die vollständige Löschung beantragen. Wir kontaktieren alle Tester, bevor etwas geändert wird. Siehe [Abschnitt 8](#8-deine-daten--datenschutz).

**F: Kann ich die Plattform auf dem Handy nutzen?**
A: Die Plattform ist für Desktop-Browser gemacht. Auf dem Handy kann die Darstellung in der Alpha noch unterschiedlich sein.

**F: Woher weiß ich, wann es Updates gibt?**
A: Wir aktualisieren den Abschnitt [Was ist neu](#was-ist-neu) oben auf dieser Seite und melden uns bei größeren Änderungen ggf. per E-Mail.

---

## 14. Kontakt

Für Fragen, Probleme oder Feedback:

- **GitHub Issues**: [erso44/Thunderstorm-Feedback](https://github.com/erso44/Thunderstorm-Feedback/issues) — für Fehler, Feedback und Funktionswünsche.
- **E-Mail**: ekthunderstorminfo@gmail.com — für Sicherheitsmeldungen, Konto-Löschung, Datenschutz-Anfragen oder Fragen außerhalb von GitHub.
- **Antwortzeit**: innerhalb von 48 Stunden.

---

Danke, dass du Teil der Thunderstorm-Alpha bist! Deine Zeit und dein Feedback bedeuten uns wirklich viel. Jede Meldung, jeder Vorschlag und jeder Eindruck hilft uns, eine bessere Plattform für Creator und ihre Communities zu bauen. 🚀
