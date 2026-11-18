# Programy lekowe NFZ — pacjenci i wydatki płatnika

Statyczny dashboard (HTML + JS, bez serwera i bazy danych) z liczbą pacjentów i wydatkami NFZ w wybranych programach lekowych: B.6, B.44, B.59, B.75, B.88, B.101, B.125, B.128, B.129, B.156, B.157, B.159, B.162, B.163.FM, B.169, B.170 oraz RDTL (wskazania spoza programów).

- Pacjenci na terapii w kwartałach od I kw. 2024 do II kw. 2026, w podziale na kraj, województwo, miasto i ośrodek, z mapą ośrodków i zmianami kw/kw.
- Wydatki NFZ na leki w programach w półroczach od 2016 r.
- Wersja polska: `index.html`; wersja angielska: `en/`.

## Źródła

- NFZ: pliki „Realizacja programów lekowych” (liczba osób, jednostki i kwoty refundacji wg województw i półroczy).
- Otwarte Dane NFZ: liczba pacjentów z rozpoznaniem ICD-10, u których zastosowano lek o danym kodzie EAN (kroczące okna 4-kwartalne, wartości 1–4 utajnione jako „<5”).
- NFZ: raport „Programy lekowe” (przypisanie EAN do programów, kody ICD-10, umowy ośrodków).

Liczby dla ośrodków to szacunki skalibrowane do realizacji NFZ na poziomie województw. Metodologia jest opisana na dole strony.

## Publikacja (GitHub Pages)

*Settings → Pages → Source: Deploy from a branch → main / (root)*. Strona będzie dostępna pod `https://<login>.github.io/<nazwa-repozytorium>/`.
