# MK Transport & Logistik GmbH — Flotten- & Liefermanagement

Interaktive Konzept-Demo eines Dispositions- und Flottenmanagement-Dashboards für eine
mittelständische Spedition. Eine einzelne, eigenständige HTML-Datei — kein Build, kein Backend,
kein Framework.

**▶ Live-Demo: https://haydarkozat.github.io/mk-logistik-demo/**

---

## Überblick

Disposition, Fahrer und Kunden brauchen dieselben Informationen — aber in sehr
unterschiedlicher Form. Die Demo zeigt eine Oberfläche, die genau das leistet: ein dichtes
Leitstand-Dashboard für die Disposition und daneben eine radikal reduzierte Fahreransicht
(„Glance & Go"), die im Fahrerhaus mit einem Blick erfassbar bleibt.

Umgesetzt für **MK Transport & Logistik GmbH** — Spedition & Nahverkehr seit 2011,
Ehningen in der Region Stuttgart.

## Funktionen

- **Live-Flottenkarte** — alle Fahrzeuge mit Position und Status; ein Klick auf einen Lkw
  öffnet die Fahrzeugdetails (Fahrer, Ladung, Gewicht, Tempo, Tankfüllung).
- **Sendungsverwaltung & Tracking** — Sendungen nach Status: unterwegs, verspätet,
  am Hub-Punkt.
- **Fahreransicht „Glance & Go"** — reduzierte Oberfläche für Navigation und Nachrichten
  an die Disposition, ohne Ablenkung am Steuer.
- **Kennzahlen** — aktive Fahrzeuge, Pünktlichkeitsquote, Sendungen pro Tag,
  gefahrene Kilometer, Zustellungen der Woche.
- **Echtzeit-Transparenz für Kunden** — Sendungsstatus ohne Rückfrage per Telefon.

### Demo-Bereiche

| Bereich | Inhalt |
| --- | --- |
| Karte | Flottenkarte mit anklickbaren Fahrzeugen |
| Sendungen | Sendungsliste mit Status und Kunde |
| Fahrer | Fahreransicht inkl. Nachrichten an die Disposition |
| Unternehmen | Leistungen, Ausstattung & Qualität, Kontakt |

Abgebildete Leistungen: Nahverkehr & Regionalverteilung, Stückgut & Teilladung,
Be- & Entladung (Hebebühne & Hubwagen serienmäßig), Echtzeit-Tracking.
Ausstattung: eigener Fuhrpark von 7,5 t bis 40 t, Gefahrgut nach ADR, EU-Lizenz.

## Technik

Eine Datei, `index.html`, mit eingebettetem CSS und JavaScript — Vanilla, ohne Abhängigkeiten.
Grafiken sind als Data-URI eingebettet, Karte und Icons sind Inline-SVG. Einzige externe
Ressource sind die Schriften von Google Fonts (Plus Jakarta Sans, JetBrains Mono);
ohne Internetverbindung greift der System-Font-Stack. Ausgelegt für Desktop und Mobil.

## Lokal starten

Die Datei kann direkt im Browser geöffnet werden:

```bash
git clone https://github.com/haydarkozat/mk-logistik-demo.git
cd mk-logistik-demo
open index.html          # macOS · Linux: xdg-open · Windows: start
```

## Hinweis

Konzept-Demo zur Veranschaulichung der Oberfläche. Alle Fahrzeuge, Sendungen, Fahrernamen
und Kennzahlen sind Beispieldaten; es besteht keine Anbindung an ein Telematik-, ERP- oder
Tracking-System.

---

Konzipiert & entwickelt von **Haydar Kozat**
