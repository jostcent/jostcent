# Webinar: "Wie du mit KI-Agenten jede Software bauen kannst"

**Referent:** Leonard Schmedding, Everlast AI (Ulm)
**Datum:** 17.11.2026, 19:01–19:29
**Plattform:** WebinarJam
**Teilnehmende:** ca. 18'000
**Quelle:** 61 Screenshots, gesichert in Nextcloud (AgenticCode)

---

## Teil 1: Inhaltlicher Kern

### Vibe Coding vs. Agentic Coding

- **Vibe Coding:** Drauflos prompten, hoffen dass es klappt — fragile Ergebnisse
- **Agentic Coding:** Strukturierter Ansatz — du fuehrst die Agenten, nicht umgekehrt
- Motto: "Kontrolle statt Vibes"

### Empfohlene Projektstruktur

```
CLAUDE.md          (Projektkontext fuer den Agenten)
specs/             (Spezifikationen VOR dem Code)
.claude/agents/    (frontend-agent.md, backend-agent.md, security-review.md)
settings.json
src/
tests/
.env.example
```

### Drei Agenten-Stufen (nach Anthropic)

1. **Stufe 1:** Reines LLM — Frage rein, Antwort raus
2. **Stufe 2:** LLM + Werkzeuge — kann Dateien lesen, Code ausfuehren
3. **Stufe 3:** Agent — eigenstaendige Schleife mit Planung, Ausfuehrung, Korrektur

### Context Engineering (Andrej Karpathy, Juni 2025)

- Wichtiger als Prompt Engineering
- "The art of filling the context window with the right information"
- Entscheidet ueber die Qualitaet der Ergebnisse

### Produktions-Eisberg

- Ueber der Oberflaeche: die Demo, die in 5 Minuten funktioniert
- Darunter (80% der Arbeit): Tests, Monitoring, Auth, Security, Error Handling, Logging, Backups, CI/CD

### Quick-Win Tools

Claude, Google AI Studio, Lovable, Base44 — "Erste eigene App in Minuten, ohne eine Zeile Code"

### Weitere Referenzen

- Prof. Dr. Juergen Schmidhuber (KI-Pionier) — Autoritaetsverweis
- "Der Feuermacher" — Motivationsfolie vor dem Verkaufsteil

---

## Teil 2: Kursangebot — Agentic Coding Masterclass

### 8 Module, aufsteigend bepreist

| Modul | Titel | "Wert" | Inhalt |
|-------|-------|--------|--------|
| 01 | Einfuehrung & Grundlagen | 297 EUR | Mindset, Quick Wins, Vibe vs. Agentic trennen |
| 02 | App-Grundlagen | 297 EUR | Frontend/Backend/APIs, Datenbanken, Deployment, Auth |
| 03 | Tool-Landschaft | 297 EUR | Claude Code, Cursor, Codex, Gemini CLI, VS Code, Copilot, Lovable, Base44, GitHub, Supabase |
| 04 | Agentic AI Konzepte | 497 EUR | Agent-Harness, Kontextfenster, Token-Effizienz, Context-Management, Secrets/API-Keys |
| 05 | Praxis | 997 EUR | 6 Projekte: Website, Chrome Extension, Linktree-Klon, Projektmanagement-App, Leadscraper, Custom Dashboards |
| 06 | Workflows | 497 EUR | Spec-Driven Development, Multi-Agent-Orchestration, Agent-Loops, Browser-Use-Agents |
| 07 | Einordnung & Ausblick | 297 EUR | Sicherheit, Prompt Injections, Open-Source-Lizenzen |
| 08 | Bonus-Lernpfad | 297 EUR | Deep-Dive-Material, laufende Updates, 20h Extra |

**Summe "Werte":** 3'476 EUR
**Tatsaechlicher Preis:** 999 EUR

### Marktvergleich (Schmeddings Argumentation)

- Internationale Agentic-AI-Bootcamps: 5'000–15'000 EUR (fuer Entwickler)
- Deutsche KI-Weiterbildungen: ca. 6'200 EUR (10–12 Wochen)
- Udemy-Vibe-Coding-Kurse: 10–100 EUR (oberflaechlich)
- "Keins davon richtet sich an Nicht-Entwickler"

---

## Bewertung

### Fachlich korrekt

- Context Engineering > Prompt Engineering — aktueller Stand der Technik
- Drei Agenten-Stufen nach Anthropic — korrekte Darstellung
- Produktions-Eisberg — reale Problematik
- Spec-Driven Development — tatsaechlich best practice
- Tool-Auswahl (Claude Code, Cursor, Supabase) — alles relevante Tools

### Uebertrieben oder fragwuerdig

- "Wert"-Berechnung pro Modul ist reiner Anker-Effekt (Verkaufspsychologie)
- 100+ Apps als Credential — unklar, was darunter faellt
- Schmidhuber-Referenz dient der Legitimation, hat mit dem Kursinhalt nichts zu tun
- "Feuermacher"-Folie ist emotionale Manipulation vor dem Preisschild
- Marktvergleich vergleicht Aepfel mit Birnen (ML-Bootcamps vs. No-Code-Kurs)

### Persoenliche Einschaetzung: nicht kaufen

- Module 01–03 (Grundlagen, App-Basics, Tools): bereits in der Praxis mit Claude Code, Chartr, Symptome, Whisper-Pipeline
- Modul 04 (Konzepte): Context Engineering, CLAUDE.md, Agent-Harness bereits im Einsatz
- Modul 05 (Praxis-Projekte): Leadscraper und Linktree-Klon irrelevant fuer Gesundheitswesen
- Modul 07 (Sicherheit): Fuer Schweizer Gesundheitsdaten braucht es DSG/kantonale Expertise, nicht generische OWASP-Einfuehrung
- Was fehlt, ist domaenenspezifische Expertise (Schweizer Datenschutz, SASIS, KLV-Abrechnung) — kein 999-EUR-Online-Kurs liefert das
