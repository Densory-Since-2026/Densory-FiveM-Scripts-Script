# Template Script — FiveM Scripts

![Aktuelle Version: v1.5.0](https://img.shields.io/badge/Aktuelle_Version%3A_v1.5.0-555) ![Self-Hosted](https://img.shields.io/badge/Self--Hosted-555) ![ESX](https://img.shields.io/badge/ESX-555) ![QBCore](https://img.shields.io/badge/QBCore-555) ![Standalone](https://img.shields.io/badge/Standalone-555)

![Template Script](docs/assets/hero-de.png)

> FiveM Script Template mit integriertem Densory Lizenzsystem – fertig zum Anpassen und Verkaufen.

Das Template Script ist die Basis fuer alle FiveM Scripts auf der Densory Plattform. Es enthaelt ein vollstaendiges Lizenzsystem mit Hardware-Bindung (cfx.re Server-ID), automatische Settings-Verteilung ueber die API, Update-Erkennung und einen beispielhaften /ping Command. Perfekt als Ausgangspunkt fuer eigene Script-Entwicklung.

### 🛒 Im Densory-Shop erhältlich

**[Template Script — Im Shop ansehen](https://densory.com/shop/template-script)**

## Funktionen

- **Ultra-Low Resmon** — Optimiert auf unter 0.05ms Idle — bleibt unsichtbar auf deinem Server.
- **ESX & QBCore** — Adapter für beide Frameworks im Lieferumfang — sauber abstrahiert.
- **Multi-Locale** — DE/EN/FR Strings out-of-the-box, eigene Sprachen einfach ergänzbar.
- **Anti-Cheat Hooks** — Integrierte Exploit-Erkennung mit konfigurierbaren Reaktions-Stufen.
- **MySQL & Redis** — Native Adapter für persistente Daten und Realtime-Caches.
- **Event-Bus** — Saubere Modul-Architektur — Features als Plugins anhängbar.

## Voraussetzungen

- FiveM Server mit txAdmin oder direktem Konsolen-Zugang
- Zugang zur server.cfg fuer Convar-Konfiguration
- Grundkenntnisse in Lua und FiveM Resource-Struktur

## Einrichtung

1. **Script herunterladen**
   Lade das ZIP-Archiv ueber den Download-Button im Dashboard oder Shop herunter.
2. **Resource installieren**
   Entpacke den Ordner nach server-data/resources/ auf deinem FiveM Server.
3. **Lizenzschluessel konfigurieren**
   Fuege in deine server.cfg ein: set densory_template-script "DEIN-LIZENZSCHLUESSEL" und ensure template-script.
4. **Server starten und testen**
   Starte deinen FiveM Server neu. Die Lizenz wird automatisch validiert und Settings werden ueber die API geladen. Teste mit /ping im Chat.

## Framework-Kompatibilität

Dieses Script ist mit den folgenden Frameworks kompatibel:
- ESX
- QBCore
- Standalone

## Konfiguration

Die vollständige Einstellungs-Referenz findest du in [docs/configuration.md](docs/configuration.md).

## Changelog

Siehe [CHANGELOG.md](CHANGELOG.md) und den GitHub-Releases-Tab für die vollständige Versions-Historie.

## Support & Links

- 🛒 [Shop](https://densory.com/shop/template-script)
- 💬 [Discord](https://densory.com/discord)
- ⚙️ [Control Center](https://densory.com/dashboard)

---

_Verwaltet mit dem Densory Control Center: [https://densory.com/dashboard](https://densory.com/dashboard). Erhältlich unter [https://densory.com/shop/template-script](https://densory.com/shop/template-script)._
