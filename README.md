# Sebastians Notizen 📝

Dies ist der Quellcode für meinen persönlichen Blog **"Sebastians Notizen"**, der unter [sebastian.sanitz.net](https://sebastian.sanitz.net/) erreichbar ist.

Der Blog wurde auf **Hugo** (Static Site Generator) migriert und verwendet das **PaperMod** Theme.

## Voraussetzungen ⚙️

*   **Hugo:** Für die Erzeugung der Seite, siehe [Hugo Installationsanleitung](https://gohugo.io/getting-started/installing/).
*   **Git:** Zum Verwalten des Codes und der Submodule.

## Schnellstart 🚀

1.  **Repository klonen:**
    ```bash
    git clone --recursive https://github.com/sanitz/sebastians-sanitz-net.git
    cd sebastians-sanitz-net
    ```
    *Hinweis: Das `--recursive` Flag ist wichtig, um das Theme-Submodul mit herunterzuladen.*

2.  **Lokalen Server starten:**
    ```bash
    hugo server
    ```

3.  **Vorschau öffnen:**
    Besuche `http://localhost:1313` in deinem Browser.

## Projektstruktur 📂

*   `content/posts/`: Hier liegen die Blogartikel (jeder Artikel in einem eigenen Unterordner als "Page Bundle").
*   `hugo.toml`: Die zentrale Konfigurationsdatei.
*   `themes/PaperMod/`: Das verwendete Theme (eingebunden als Git Submodule).
*   `static/`: Statische Dateien (z.B. Profilbild, Favicon).

## Neuen Artikel anlegen ✍️

Um einen neuen Blogpost zu erstellen:

```bash
hugo new content posts/mein-neuer-artikel/index.md
```

Dies erstellt einen neuen Ordner mit einer vorformatierten Markdown-Datei.

## Deployment 🚀

  - TBD 🙄
