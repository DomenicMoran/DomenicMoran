## Domenic Moran

**AI Product Engineer, Berlin.** Ich baue Produkte allein zu Ende: Architektur,
Code, Auslieferung, Betrieb und Recht.

Vier Systeme in Produktion, in vier Monaten neben einem Vollzeitjob entstanden.
Zwei davon mit Apps in beiden Stores, eines mit gesetzlich vorgeschriebener
Fiskalisierung nach § 146a AO, eines ein autonomer Agent.

→ **[domenicmoran.de](https://domenicmoran.de)** · [English](https://domenicmoran.de/en)

---

### Was ich veröffentliche

Die Produktivsysteme bleiben privat, sie tragen Kundendaten und lizenzierte
Inhalte. Öffentlich ist, was sich daraus herauslösen ließ.

| Repository | Worum es geht |
| :--- | :--- |
| **[verified-done](https://github.com/DomenicMoran/verified-done)** | Vier Claude-Code-Skills gegen die Behauptung ohne Beleg. Jeder stammt aus einem Fehler, der ausgeliefert wurde. |
| **[cron-last-due](https://github.com/DomenicMoran/cron-last-due)** | Wann war dieser Cron zuletzt fällig? Zeitzonenbewusst, für Watchdogs. 21 Tests, null Abhängigkeiten. |
| **[whisper-ggml-header](https://github.com/DomenicMoran/whisper-ggml-header)** | Prüft, ob whisper.cpp ein Modell überhaupt lädt. Fängt die verbreitete Fehlkonvertierung ab. |
| **[arabic-normalize](https://github.com/DomenicMoran/arabic-normalize)** | Normalisierung arabischer Schrift für den Vergleich. 23 Tests, null Abhängigkeiten. |
| **[portfolio](https://github.com/DomenicMoran/portfolio)** | Der Quellcode von domenicmoran.de. Next.js 16, dokumentierte Entscheidungen. |

---

### Geschrieben

Drei Fehler aus den eigenen Systemen, jeweils mit Ursache, Fix und Commit.

- [Warum ein kleineres Whisper-Modell mein größeres geschlagen hat](https://domenicmoran.de/artikel/kleineres-whisper-modell)
- [KassenSichV in der Praxis: was in der Dokumentation nicht steht](https://domenicmoran.de/artikel/kassensichv-in-der-praxis)
- [Alle Tests grün. Widget trotzdem leer auf dem echten Gerät.](https://domenicmoran.de/artikel/widget-leer-trotz-gruener-tests)

---

### Arbeitsweise

Ich arbeite seit über einem Jahr agentengestützt. Das komprimiert Lieferzeiten,
aber nur, weil um die Agenten herum ein System steht, das ihre Fehler abfängt.
Die wichtigste Regel darin ist die einfachste:

> „Sollte jetzt funktionieren“ ist kein Ergebnis. Jede Behauptung über den
> Systemzustand braucht einen Beleg: HTTP-Response, Datenbankabfrage,
> Screenshot vom echten Gerät, empfangene Mail, echte Cron-Ausführung.

Genau diese Regel ist als
[verified-done](https://github.com/DomenicMoran/verified-done) veröffentlicht.

---

### Womit

| Bereich | Werkzeuge |
| :--- | :--- |
| **Sprachen** | TypeScript, SQL, Swift, Kotlin, Python |
| **Web** | Next.js, React Server Components, Tailwind, Vercel |
| **Mobil** | React Native, Expo, Android TV, Wear OS, App Widgets, Live Activities |
| **Daten** | PostgreSQL, Supabase, Row Level Security, Migrationen |
| **KI** | llama.cpp und GGUF auf dem Gerät, Whisper, eigenes RAG |
| **Betrieb** | Docker, Hetzner, Coolify, Cloudflare, n8n, Playwright, Vitest |

---

**Kontakt** [domenicmoran@gmail.com](mailto:domenicmoran@gmail.com)
