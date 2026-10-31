# Dein KI-Betriebssystem

Das ist die Ordnerstruktur, mit der ich selbst arbeite, als leere Vorlage für dich.
Die Idee: Deine KI (Claude Code oder Codex) kennt dein Wissen, deine Abläufe und deine Tools.
Dann musst du nicht jedes Mal von vorne erklären, wer du bist und wie du arbeitest.

## In 3 Schritten starten

1. **Ordner entpacken**, zum Beispiel nach `Dokumente/KI-Betriebssystem`.
2. **Claude Code oder Codex in diesem Ordner öffnen.**
   - Claude Code: Terminal öffnen, `cd` in den Ordner, `claude` eingeben.
   - Codex: In der Codex-App den Ordner als Projekt öffnen, oder im Terminal `codex` eingeben.
3. **Schreib: `Richte mein KI-Betriebssystem ein.`**
   Die KI interviewt dich ein paar Minuten und füllt danach `wissen/` mit deinen Antworten.

Danach arbeitest du einfach in diesem Ordner. Je mehr drin liegt, desto besser werden die Antworten.

## Was wo liegt

| Ordner | Was rein gehört | Beispiel |
|---|---|---|
| `wissen/` | Alles, was die KI über dich und dein Business wissen soll | Über dich, deine Firma, Kunden, Notizen aus Büchern |
| `ablaeufe/` | Schritt-für-Schritt-Anleitungen für Dinge, die du öfter machst | Offerte schreiben, Wochenrückblick, Rechnungen sammeln |
| `tools/` | Kleine Skripte, die die KI für dich baut und immer wieder nutzt | PDF umbenennen, Daten aus Excel holen |
| `projekte/` | Ein Unterordner pro laufendem Projekt | `projekte/website-relaunch/` |
| `entscheidungen/` | Was du entschieden hast und warum | «Ab jetzt Offerten nur noch als PDF» |
| `.claude/skills/`, `.agents/skills/` | Fertige Fähigkeiten für Claude Code und Codex (gleicher Inhalt) | siehe unten |

## Die fertigen Skills

Du musst keinen Befehl auswendig lernen. Sag einfach, was du willst, die KI wählt den passenden Skill selbst.

| Skill | Sag zum Beispiel |
|---|---|
| **einrichten** | «Richte mein KI-Betriebssystem ein.» |
| **merk-dir** | «Merk dir: Kunde Meier will Rechnungen immer per Post.» |
| **ablauf-bauen** | «Das mache ich jede Woche. Mach daraus einen Ablauf.» |
| **erst-fragen** | «Bau mir ein Dashboard für meine Leads.» (Die KI stellt zuerst Fragen, statt drauflos zu bauen.) |
| **rotstift** | «Prüf diese Mail, bevor ich sie abschicke.» |
| **wochenrueckblick** | «Mach meinen Wochenrückblick.» |

## Drei Regeln, die dir Ärger sparen

1. **Passwörter und API-Schlüssel nie in normale Dateien.** Sie gehören in `.env` (Vorlage: `.env.example`). Diese Datei teilst du nie.
2. **Die KI fragt, bevor sie etwas sendet, löscht oder bezahlt.** Das steht in `CLAUDE.md` und `AGENTS.md`. Lass es drin.
3. **Klein anfangen.** Ein Ablauf, der läuft, bringt mehr als zehn halbe.

Viel Spass beim Bauen. Fragen? Stell sie in der Automatisierbar-Community auf Skool.
