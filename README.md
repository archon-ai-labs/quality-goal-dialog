# Quality Goal Dialog

A structured, conversational prompt that guides you through the discovery
of quality goals for a software system.

**[Deutsche Version weiter unten](#qualitätsziel-dialog)**

---

## What it does

The prompt leads you step by step through a dialog with an AI. It asks
targeted questions about your system – its type, purpose, stakeholders,
and risks – and derives between three and five prioritized quality goals from your
answers. Each goal is described in one to three sentences and assigned
to a quality attribute.

The result is a table ready to use in your architecture documentation.

## How to use it

1. Open `prompt_en.md`
2. Copy the full content
3. Paste it as first message into your AI tool of choice
   (e.g. Claude, ChatGPT, or another LLM)
4. Answer the questions the AI asks – one at a time
5. Receive your prioritized quality goals as a table

## Example output

| # | Goal                      | Quality Attribute | Description |
|---|---------------------------|-------------------|-------------|
| 1 | Available around the clock | Reliability       | The system is available 24/7 ... |
| 2 | User data is protected    | Security          | All user data is protected ... |
| 3 | Easy to get started       | Usability         | New users can ... |

## Quality agttributes

The prompt uses a curated set of quality attributes based on
**LASR** (© Stefan Toth & Stefan Zörner, CC BY-SA 4.0), covering areas
such as performance, maintainability, security, usability, and more.

See [LASR Quality Model](https://www.lasr-reviews.org/quality-model/) for details.

## License

© 2026 embarc GmbH – Licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

Authors: Alexander Kaserbacher, Stefan Zörner

You are free to share and adapt this prompt as long as you give
appropriate credit and distribute your contributions under the same license.

---

# Qualitätsziel-Dialog

Ein strukturierter, dialogbasierter Prompt zur Erarbeitung von
Qualitätszielen für ein Softwaresystem.

## Was er tut

Der Prompt führt Dich Schritt für Schritt durch ein Gespräch mit einer KI.
Er stellt gezielte Fragen zu Deinem System – Art, Zweck, Stakeholder und
Risiken – und leitet daraus drei bis fünf priorisierte Qualitätsziele ab.
Jedes Ziel wird in ein bis drei Sätzen beschrieben und einem
Qualitätsmerkmal zugeordnet.

Das Ergebnis ist eine Tabelle, die direkt in die Architekturdokumentation
übernommen werden kann.

## Nutzung

1. `prompt_de.md` öffnen
2. Den gesamten Inhalt kopieren
3. Als erste Nachricht in ein KI-Tool einfügen
   (z.B. Claude, ChatGPT oder ein anderes LLM nach Wahl)
4. Die Fragen der KI beantworten – eine nach der anderen
5. Die priorisierten Qualitätsziele als Tabelle erhalten

## Beispiel-Ergebnis

| # | Ziel                       | Qualitätsmerkmal  | Beschreibung |
|---|----------------------------|-------------------|--------------|
| 1 | Rund um die Uhr verfügbar  | Zuverlässigkeit   | Das System ist 24/7 verfügbar ... |
| 2 | Nutzerdaten sind geschützt | Sicherheit        | Alle Nutzerdaten sind geschützt ... |
| 3 | Einfacher Einstieg         | Benutzbarkeit     | Neue Nutzer können ... |

## Qualitätsmerkmale

Der Prompt verwendet einen kuratierten Vorrat an Qualitätsmerkmalen auf
Basis von **LASR** (© Stefan Toth & Stefan Zörner, CC BY-SA 4.0), der
Bereiche wie Performanz, Wartbarkeit, Sicherheit, Benutzbarkeit und
weitere abdeckt.

Siehe [LASR-Qualitätsmodell](https://www.lasr-reviews.org/de/quality-model/) für Details dazu.

## Lizenz

© 2026 embarc GmbH – Veröffentlicht unter
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

Autoren: Alexander Kaserbacher, Stefan Zörner

Du darfst diesen Prompt teilen und anpassen, solange Du die Quelle nennst
und Deine Beiträge unter derselben Lizenz weitergibst.
