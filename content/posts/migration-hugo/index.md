---
title: "Umstieg auf Hugo Januar 2026 🛠️"
date: 2026-01-07
draft: false
description: ""
tags: ["Blog"]
cover:
    image: "muellfisch.jpg"
    alt: "Bild eines Müllfisches aus Stahl am Strand mit leeren Plastikflaschen"
    caption: "Müllfische am Strand"
    relative: true
---

## Änderungen 🛠️

Nach langem Stillstand habe ich mich mal wieder mit diesem Blog beschäftigt, ihn aufgeräumt, im Erstellungsprozess und im Aussehen vereinfacht und insgesamt modernisiert. Hier ist eine Übersicht der Anpassungen:

### Wechsel zu Hugo 🚀
Für die Erzeugung der Seiten des Blogs verwende ich nicht mehr [11ty (Eleventy)](https://www.11ty.dev/) in der inzwischen obsoleten Variante  [eleventy-high-performance-blog
](https://github.com/google/eleventy-high-performance-blog). Jetzt wird  [Hugo](https://gohugo.io/) verwendet. Hugo ist schnell und sehr einfach zu installieren. Auch die Pflege des Blogs in Zukunft sollte leichter sein.

### Aufräumen 🧹
Es wurde ausgemistet:
*   **Dateien gelöscht:** Tausende Dateien, Bilder, Verzeichnisse wie `node_modules` sowie Build-Skripte werden nicht mehr benötigt.
*   **Kein JavaScript-Chaos mehr:** Tools wie `npm` oder `package.json` sind nicht mehr  notwendig, um den Blog zu bauen.
*   **Struktur:** Das Projekt enthält nur noch das Nötigste: Die Texte und Bilder für die Artikel sowie die Konfiguration.

### Ordnung mit "Page Bundles" 📦
Früher lagen Bilder und Texte verstreut. Jetzt nutzt Hugo [Page Bundles](https://gohugo.io/content-management/page-bundles/). Damit hat jeder Artikel seinen eigenen Ordner.
*   Bilder zum Artikel liegen direkt neben dem Text.
*   Artikel zu verschieben oder zu bearbeiten ist einfacher

### Theme "PaperMod" 🎨
Der Blog nutzt jetzt das [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod). Es ist schlicht und scheint schnell zu sein.

### Konfiguration ⚙️
Alle Einstellungen stehen jetzt zentral in einer einzigen Datei (`hugo.toml`). Das ist viel übersichtlicher als viele verstreute JavaScript-Dateien.

### Deployment 🚀

Der Blog ist jetzt bei [statichost.eu](https://statichost.eu/) gehostet und wird automatisch bei jedem Push ins Git-Repository neu gebaut.

[![statichost.eu status](https://builder.statichost.eu/sebastian-sanitz/status.svg)](https://builder.statichost.eu/sebastian-sanitz/)

**Fazit:** Der Blog ist jetzt aufgeräumter und einfacher zu ergänzen. Der Code dazu liegt hier [https://github.com/sanitz/sebastians-sanitz-net](https://github.com/sanitz/sebastians-sanitz-net)! 🎉