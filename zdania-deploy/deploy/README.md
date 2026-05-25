# Zdania z Klocków

Interaktywna aplikacja do nauki języka angielskiego dla uczniów klas 1–7. Uczeń czyta polskie zdanie i buduje jego angielskie tłumaczenie, dotykając kolejnych kafelków ze słowami.

## Funkcje

- **2400 zdań** podzielonych na 7 poziomów klas (1–7)
- **Wymowa angielska** (Web Speech API) — przycisk głośnika odtwarza całe zdanie, dotknięcie kafelka odtwarza pojedyncze słowo
- **Tryb jasny / ciemny** z automatycznym wykrywaniem preferencji systemowych
- **Zapis postępów** w przeglądarce (localStorage) — każda klasa osobno
- **Bez konta, bez instalacji** — działa w przeglądarce, online i offline po pierwszym załadowaniu
- **Pojedynczy plik HTML** — można wysłać e-mailem, działa lokalnie

## Poziomy

- **Klasa 1** — Pierwsze słowa: imiona, liczby do 10, kolory, zwierzęta, „I have", „I like"
- **Klasa 2** — Pytania i czynności: liczby do 20, „What/Where/Who", 3 osoba, „There is/are", przyimki
- **Klasa 3** — Pierwsze kroki: „to be", „have got", kolory i zwierzęta
- **Klasa 4** — A1: Present Simple, „can", do/does, przyimki
- **Klasa 5** — A1+/A2: Present Continuous, Past Simple regularny, stopniowanie, „going to"
- **Klasa 6** — A2: Past Simple nieregularny, modalne, 1. tryb warunkowy, Present Perfect
- **Klasa 7** — A2+/B1: Present Perfect Continuous, Past Continuous, Past Perfect, 2. tryb warunkowy, strona bierna, mowa zależna

## Technologia

- Czysty HTML, CSS i JavaScript — bez frameworków, bez procesu budowania
- Web Speech API do syntezy mowy (en-GB)
- View Transitions API dla płynnych animacji
- Fonts: Fraunces (serif) + Manrope (sans) z Google Fonts

## Uruchomienie lokalne

Otwórz plik `index.html` w przeglądarce. To wszystko.

## Wdrożenie

Aplikacja to pojedynczy plik statyczny — można ją hostować na dowolnej platformie obsługującej pliki statyczne (Vercel, Netlify, GitHub Pages, Cloudflare Pages).
