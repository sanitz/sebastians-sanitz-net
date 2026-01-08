---
title: "Migration Hugo 🛠️ Januar 2026"
date: 2026-01-07
draft: false
description: ""
tags: ["Blog"]
---

## Änderungen 🛠️

Der Blog ist komplett modernisiert und vereinfacht. Hier ist eine Übersicht der Anpassungen:

### Wechsel zu Hugo 🚀
Der Blog ist umgestiegen von [11ty (Eleventy)](https://www.11ty.dev/) auf [Hugo](https://gohugo.io/). Hugo ist schnell und sehr einfach zu installieren. Die  Pflege des Blogs in Zukunft sollte leichter sein.

### Aufräumen 🧹
Es wurde ausgemistet:
*   **Dateien gelöscht:** Tausende Dateien von Bildern und `node_modules` sowie alte Build-Skripte sind weg.
*   **Kein JavaScript-Chaos mehr:** Wir brauchen kein `npm` oder `package.json` mehr, um den Blog zu bauen.
*   **Struktur:** Das Projekt enthält nur noch das Nötigste: Die Artikel und die Konfiguration.

### Ordnung mit "Page Bundles" 📦
Früher lagen Bilder und Texte verstreut. Jetzt nutzt Hugo [Page Bundles](https://gohugo.io/content-management/page-bundles/). Damit hat jeder Artikel seinen eigenen Ordner.
*   Bilder zum Artikel liegen direkt neben dem Text.
*   Das macht es viel einfacher, Artikel zu verschieben oder zu bearbeiten.

### Theme "PaperMod" 🎨
Der Blog benutzt nutzt jetzt das [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod). Es ist schlicht und scheint schnell sein.

###  Konfiguration ⚙️
Alle Einstellungen stehen jetzt zentral in einer einzigen Datei (`hugo.toml`). Das ist viel übersichtlicher als viele verstreute Javascript-Dateien.

###  Deployment 🚀

Der Blog ist jetzt bei [Statichost.eu](https://statichost.eu/) gehostet und wird automatisch bei jedem Push ins Git-Repository neu gebaut.

[![statichost.eu status](https://builder.statichost.eu/sebastian-sanitz/status.svg)](https://builder.statichost.eu/sebastian-sanitz/)



**Fazit:** Der Blog ist jetzt aufgeräumter und einfacher zu ergänzen - der Code dazu liegt hier [https://github.com/sanitz/sebastians-sanitz-net](https://github.com/sanitz/sebastians-sanitz-net)! 🎉