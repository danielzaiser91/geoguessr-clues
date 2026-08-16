# Research log

Damit dieselbe Suche nicht zweimal läuft. Jede Websuche, die mehr liefert als die eine Zeile im
Dokument, kommt hierher — mit Datum, Quelle und Ergebnis. **Auch Fehlschläge**, sonst prüft man
dieselbe Quelle in drei Monaten erneut und kommt zum selben Nein.

## Trident-Masten — wo gibt es sie außer Uruguay? (16.08.2026, geklärt)

Alles direkt bei plonkit im Browser gelesen, Zitate wörtlich.

| Ort | Beleg |
|---|---|
| Uruguay | „One very common and useful one are the so-called trident poles" |
| **Brasilien, Rio Grande do Sul** | „Similar trident poles can be found in the neighbouring Brazilian state of Rio Grande do Sul" |
| **Indien**, landesweit | „The most common Indian utility pole is a concrete square pole with a trident pole top" |
| **Südafrika, KwaZulu-Natal** | „Trident pole tops are almost unique to KwaZulu-Natal" |
| **Australien, WA + VIC** | „A trident-like pole top can sometimes be seen in Western Australia and Victoria" |
| **Litauen** | „In some poletops, the insulators are arranged in a trident-like shape" |
| Australien, SA | Stobie-Mastköpfe sind „trident or rotated letter ‚E'" |

**Wichtigste Korrektur:** Die Learnable-Meta-Karte behauptet, Trident-Masten gebe es in Brasilien
nicht. plonkit widerspricht ausdrücklich für **Rio Grande do Sul** — genau die Grenzregion, in der
man den Hinweis brauchen würde. Steht so im Uruguay-Dokument.

**Bedingung, die den Hinweis in Australien kippt:** „For the meta to work, all 3 insulators must be
connected to the crossbar." Sitzt der mittlere Isolator am Mast statt am Querträger, ist es ein
anderer Mast.

**Der frühere Widerspruch war ein Suchmaschinen-Artefakt.** Beide Behauptungen stammten aus
generierten Zusammenfassungen, nicht aus gelesenen Quellen: Suche 2 bestritt Australien (falsch),
Suche 1 nannte Manipur und KwaZulu (KwaZulu richtig, Manipur nicht belegt — Indien hat den Masttyp
landesweit, nicht nur dort). Lehre: Suchzusammenfassungen sind kein Beleg, die Seite selbst schon.

## Quellenzugriff

- **`plonkit.net` nur im Browser lesbar.** Inhalt wird per JavaScript nachgeladen, WebFetch
  bekommt nur den Titel. `www.plonkit.net/<land>` leitet auf `de.plonkit.net/<land>` um. Vorgehen:
  Browser-Pane öffnen, dann `document.body.innerText` per `javascript_tool` durchsuchen — eine
  Seite hat 9.000–16.000 Zeichen, `indexOf` auf Stichwörter genügt. Braucht Daniels Zustimmung,
  weil eine fremde Seite geladen wird.
- **`geometas.com`** antwortet auf WebFetch mit HTTP 403.
- **`dingyiyi0226.github.io/geoguessr-note/docs/pole/`** — brauchbare Mastübersicht, kennt aber
  keine Trident-Masten.

## Baltikum — vollständig ausgelesen (16.08.2026)

Bollards, Chevrons, Kilometersteine, Schilderränder, Leitplanken-Reflektoren, Fußgängerschilder
und Masten für alle drei Länder stehen im Dokument. Plonkit verweist zusätzlich auf eine
Infografik zu baltischen und nordischen Bollards — noch nicht ausgewertet.

## Kanada — vollständig ausgelesen (16.08.2026)

Provinzmerkmale zu Schildern, Bollards, Masten, Fahrbahnmarkierung und der Nummerierung
ländlicher Straßen in AB und MB stehen im Dokument. Nicht übernommen: Landschaftsbeschreibungen
(Rocky Mountains, Prärie, Yukon) — die trennen keine Provinzen scharf, sondern nur grob West/Ost.

## Australien — vollständig ausgelesen (16.08.2026)

Schilder, Masten und Regionalmerkmale stehen im Dokument. Nicht übernommen, weil zu
kleinteilig für ein Nachschlagewerk: Regionalmerkmale einzelner Städte (Tom Price, Alice Springs,
Cairns, Mount Gambier, Grampians).
