# Countryballs Adventure — strona pod GitHub Pages

Minimalna, ładna strona HTML5/CSS z:
- lewym „image buttonem” **Changelog**, który się powiększa na hover i rozwija panel,
- trzema przyciskami na środku (pierwszy prowadzi do `download.html`, pozostałe „Wkrótce”),
- podpisem na środku dołu: `2024-2025 Countryballs Adventure`.

## Szybki start (GitHub Pages)
1. Utwórz repo, np. `countryballs-adventure-site`.
2. Skopiuj tu pliki (lub rozpakuj ZIPa).
3. W ustawieniach repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, ustaw `branch: main`, `folder: / (root)`.
4. Wejdź na wygenerowany adres strony (np. `https://twoja-nazwa.github.io/countryballs-adventure-site/`).

## Gdzie wstawić build gry?
- Podmień linki/kafelki w `download.html` na prawdziwe URL-e ZIP/EXE (np. z `Releases`).
- Jeśli chcesz, dodaj `releases/` i trzymaj tam pliki — i podlinkuj je.

## Customizacja
- Kolory i promienie: w `:root` w `styles.css`.
- Zmiany changeloga: sekcja `<ul>` w `index.html`.
- Ikona przy changelogu: `assets/changelog-ball.svg` (możesz wymienić na własną).
