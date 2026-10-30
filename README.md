# BikeRc Siła – trening ze sztangą z kamerą telefonu

Aplikacja w przeglądarce (telefon, tablet, komputer) do oceny techniki ćwiczeń ze sztangą. Ten sam silnik i wygląd co BikeRc Rehab: MediaPipe Pose działa na urządzeniu, obraz i filmy nie są nigdzie wysyłane.

Ćwiczenia (MVP): przysiad, martwy ciąg, wyciskanie żołnierskie, wyciskanie leżąc.

## Co robi

- **Kamera na żywo** albo **film z galerii** („Analizuj film”).
- Kontrola ustawienia telefonu (zielona ramka, gdy widać całą sylwetkę z boku).
- Liczy powtórzenia i ocenia każde z nich kolorem (zielone / żółte / czerwone), podpowiedź głosem po każdym powtórzeniu.
- **Tor gryfu względem środka stopy** w centymetrach. Pozycja gryfu z sylwetki albo – dokładniej – ze **śledzenia talerza** („Zaznacz talerz”: środek, potem krawędź; średnica 45 cm daje skalę).
- Reguły techniki dla każdego ćwiczenia (głębokość przysiadu, gryf blisko nóg, biodra i barki razem, wyprost, łokcie, miejsce dotknięcia klatki…), prędkość gryfu i spadek prędkości w serii.
- **Raport**: ocena serii, najważniejsza uwaga, propozycja ciężaru na następną serię, szacowany 1RM, wykres toru gryfu i prędkości, tabela powtórzeń, zdjęcie najlepszego i najsłabszego powtórzenia, wskazówki.
  Eksport: „Udostępnij raport” (plik HTML, np. dla trenera), „PDF / drukuj”, „Dane CSV”.
- Historia serii i postępy na urządzeniu (eksport / import JSON).

Kryteria techniki to nasze własne streszczenie zasad metody „Zacznij od siły” (M. Rippetoe), do uzgodnienia z trenerem. Pomiar 2D z jednej kamery – wartości orientacyjne.

## Uruchomienie

Kamera w przeglądarce wymaga **https**. Najprościej GitHub Pages:

1. Na GitHubie: **Settings → Pages**.
2. „Source”: *Deploy from a branch*, gałąź **main**, folder **/ (root)** → Save.
3. Po minucie aplikacja jest pod adresem `https://wwieczor-commits.github.io/ci-ary-/`.
4. Na iPhonie: otwórz w Safari → Udostępnij → „Do ekranu początkowego”.

Wszystko jest w jednym pliku `index.html`.
