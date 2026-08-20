## Domenic Moran

**AI Product Engineer, Berlin.** Ich baue Produkte allein zu Ende: Architektur,
Code, Auslieferung, Betrieb und Recht.

Sieben Systeme in Produktion, seit März 2026 neben einem Vollzeitjob entstanden,
zwei davon mit Apps in beiden Stores. Acht Store-Einträge sind öffentlich, drei
weitere Apps liegen in der Prüfung. Eines der Systeme trägt gesetzlich
vorgeschriebene Fiskalisierung nach § 146a AO, eines ist ein autonomer Agent,
eines eine Lernplattform mit Prüfung und Zertifikat.

→ **[domenicmoran.de](https://domenicmoran.de)** · [English](https://domenicmoran.de/en)

---

### Was läuft

| System | Was es ist | Wo |
| :--- | :--- | :--- |
| **Salati** | Gebets- und Koran-App über vier Geräteklassen, KI auf dem Gerät | [salati.pro](https://www.salati.pro) · [App Store](https://apps.apple.com/de/app/salati-gebetszeiten-koran/id6791867298) · [Play](https://play.google.com/store/apps/details?id=de.salatibox.de) |
| **MenuCloud Berlin** | Multi-Tenant-SaaS für Gastronomie mit Cloud-TSE nach § 146a AO | [menucloud-berlin.de](https://menucloud-berlin.de) |
| **NOURI** | Ernährung und Training auf einem Katalog aus 11.892 Rezepten | [nouri-fitness.de](https://www.nouri-fitness.de) · [Play](https://play.google.com/store/apps/details?id=app.nouri.mobile) |
| **BitDojo** | Deutschsprachige Lernplattform mit genau einer Lektionsbibliothek | [bitdojo.de](https://bitdojo.de) |
| **Dartile** | Dart-Counter, der jeden Pfeil einzeln aufnimmt statt der Summe | [dartile.de](https://dartile.de) |
| **LexiPulse** | Reader für EPUB, PDF und Web-Artikel: Wortstrom oder Fließtext, offline und offen lesbar | [lexipulse.de](https://lexipulse.de) · [Code](https://github.com/DomenicMoran/lexipulse) |
| **WohnungsJäger** | Autonomer Agent für den Berliner Wohnungsmarkt, Freigabe beim Menschen | im Eigenbetrieb |
| **Moran Fleet Control (MFC)** | Die eine Anwendung für den Builder-Alltag: Multi-LLM-Router, Agenten über die lokale Claude-CLI, elf Micro-SaaS-Werkzeuge, Projekte, Backlog, Marketing, Vault – Desktop für Windows/macOS/Linux plus Web | [mfc.domenicmoran.de](https://mfc.domenicmoran.de) |

Die Fallstudien mit Architekturdiagrammen stehen auf
[domenicmoran.de](https://domenicmoran.de/#work).

---

### Was gerade entsteht

Vier Apps, angelegt im August 2026. Alle vier sind am 20.08.2026 durch einen
vollständigen Emulator-Durchlauf gegangen – jeder Bildschirm angeklickt,
Verschlüsselung der Datenbank am Gerät nachgewiesen, zehn Fehler dabei gefunden
und behoben. Die Store-Einträge (Play) sind angelegt und mit Beschreibungen und
Ladenbildern befüllt; die Einreichung folgt mit den ersten Builds.

| Projekt | Was es ist | Stand |
| :--- | :--- | :--- |
| **Aegis** | Belege fotografieren, Gewährleistungs- und Garantiefristen überwachen, EÜR und Kontoauszug abgleichen. Alles auf dem Gerät, SQLCipher-verschlüsselt | Kern, Web und App gebaut. 304 Tests im Kern bei 92 % Anweisungsabdeckung, Emulator-Audit mit Belegen. Play-Eintrag steht |
| **Vesper** | Bewerbungen, Vorhaben und Kontakte auf einem Kanban-Brett, das den Rechner nicht verlässt, mit einem lokal laufenden Sprachmodell daneben | Emulator-Audit abgeschlossen (Sicherungs-Roundtrip verifiziert, Verschlüsselung belegt). Play-Eintrag steht |
| **Aether** | Der Tag als durchsuchbares Gedächtnis: Kontext und Notizen, auf dem Gerät ausgewertet | Emulator-Audit abgeschlossen (Verschlüsselung belegt, vier Erfassungsquellen geprüft). Play-Eintrag steht |
| **Synapse** | Aus PDFs und Notizen werden Lernkarten, wiederholt im Rhythmus von SM-2, offline | Emulator-Audit abgeschlossen (106 Screenshots, vier Fehler behoben, Verschlüsselung belegt). Play-Eintrag steht |

Die Fallstudie zu Aegis, mit Architekturbild und der Begründung, warum kein
Bildschirmfoto danebensteht, ist auf der Seite verlinkt.

---

### Was ich veröffentliche

Die Produktivsysteme bleiben privat, sie tragen Kundendaten und lizenzierte
Inhalte. Öffentlich ist, was sich daraus herauslösen ließ. Die fünf Pakete
stehen unter MIT; LexiPulse liegt vollständig offen, aber unter PolyForm
Noncommercial: lesbar und prüfbar, nicht zur gewerblichen Nutzung freigegeben.

| Repository | Worum es geht |
| :--- | :--- |
| **[lexipulse](https://github.com/DomenicMoran/lexipulse)** | Der ganze Reader. Engine, Parser und Bereinigung ohne DOM und ohne React Native, 561 Tests (am 19.08.2026 gemessen). |
| **[darts-checkout](https://github.com/DomenicMoran/darts-checkout)** | Die Checkout-Tafel aus Dartile. Auf 40 gibt es über achtzig richtige Wege und genau einen, den jemand wirft. 25 Tests, null Abhängigkeiten. |
| **[verified-done](https://github.com/DomenicMoran/verified-done)** | Vier Claude-Code-Skills gegen die Behauptung ohne Beleg. Jeder stammt aus einem Fehler, der ausgeliefert wurde. 16 Tests, null Abhängigkeiten. |
| **[cron-last-due](https://github.com/DomenicMoran/cron-last-due)** | Wann war dieser Cron zuletzt fällig? Zeitzonenbewusst, für Watchdogs. 23 Tests, null Abhängigkeiten. |
| **[whisper-ggml-header](https://github.com/DomenicMoran/whisper-ggml-header)** | Prüft, ob whisper.cpp ein Modell überhaupt lädt. Fängt die verbreitete Fehlkonvertierung ab. 17 Tests, null Abhängigkeiten. |
| **[arabic-normalize](https://github.com/DomenicMoran/arabic-normalize)** | Normalisierung arabischer Schrift für den Vergleich. 23 Tests, null Abhängigkeiten. |
| **[portfolio](https://github.com/DomenicMoran/portfolio)** | Der Quellcode von domenicmoran.de. Next.js 16, dokumentierte Entscheidungen. |
| **[Zertifikate](https://github.com/DomenicMoran/certificates)** | Zehn Kurszertifikate von Meta, LearnQuest und Udemy. Jedes beim Aussteller nachprüfbar. |

---

### Geschrieben

Sechs Fehler aus den eigenen Systemen, jeweils mit Ursache, Fix und Commit.
Einen davon hatte monatelang niemand bemerkt, einen zweiten über Wochen.

- [Achtzehn Wege über das Bull, und der Test sah nur den letzten Pfeil](https://domenicmoran.de/artikel/achtzehn-wege-ueber-das-bull)
- [Der gestrichelte Kreis kam nicht aus der Schrift](https://domenicmoran.de/artikel/gestrichelter-kreis-kam-nicht-aus-der-schrift)
- [„Published“ ist kein Beleg. Meine Updates kamen nie an.](https://domenicmoran.de/artikel/published-ist-kein-beleg)
- [Alle Tests grün. Widget trotzdem leer auf dem echten Gerät.](https://domenicmoran.de/artikel/widget-leer-trotz-gruener-tests)
- [KassenSichV in der Praxis: was die Dokumentation auslässt](https://domenicmoran.de/artikel/kassensichv-in-der-praxis)
- [Warum ein kleineres Whisper-Modell mein größeres schlug](https://domenicmoran.de/artikel/kleineres-whisper-modell)

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
| **KI** | Antwortsuche auf dem Gerät über eigenem Korpus, Whisper-Spracherkennung |
| **Betrieb** | Docker, Hetzner, Coolify, Cloudflare, n8n, Playwright, Vitest |

---

**Kontakt** [kontakt@domenicmoran.de](mailto:kontakt@domenicmoran.de)
