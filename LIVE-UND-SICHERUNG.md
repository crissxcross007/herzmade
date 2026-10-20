# Herzmade – Livebetrieb und Sicherung

Veröffentlicht am 20.10.2026 unter https://herzmade.de.
Pages CMS: https://app.pagescms.org – Repository crissxcross007/herzmade, Branch main.
Die Testumgebung bleibt crissxcross007/herzmade-relaunch.

## Alte Website wiederherstellen

Unveränderter Sicherungszweig: sicherung-vor-relaunch-2026-10-20
Commit: 9bfa157bd124154d0457ee2151ca8a371a205748
Tree: a1eeefd97f373f8882921bafb76b2d60ecfd1d38
ZIP: https://github.com/crissxcross007/herzmade/archive/refs/heads/sicherung-vor-relaunch-2026-10-20.zip

Für die Rückkehr den vollständigen Tree des Sicherungsstands als neuen Commit auf main übernehmen und die Pages-Veröffentlichung abwarten. Kein Force-Push erforderlich. Laufende CMS-Builds vorher abwarten oder abbrechen und neuere Inhaltsänderungen sichern. Die Domain-Zuordnung und CNAME bleiben herzmade.de; DNS und Microsoft-365-Mail-Einstellungen nicht verändern.

## Pflege

Nach Änderungen in Pages CMS baut .github/workflows/pages-cms.yml HTML-Seiten, optimierte Bilder, Sitemap und robots.txt automatisch neu. Der Builder erkennt die Live-Domain an CNAME und gibt öffentliche Seiten zur Indexierung frei. Interne Prüf- und Bestätigungsseiten bleiben noindex.

Formspree verwendet weiter https://formspree.io/f/xeeropko. Die E-Mail-Zustellung ist mit einer echten Testnachricht zu prüfen; Kontoeinstellungen und Domain-Beschränkung liegen bei Formspree.
