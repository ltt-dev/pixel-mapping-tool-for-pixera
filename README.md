# Pixel Mapping Tool for Pixera

Simple offline CSV generator for Pixera pixel mapping.

## Polska wersja

### Co to jest
To proste narzędzie pomaga przygotować plik CSV do **Pixel Based Video Mapping** w **Pixerze**.  
Zamiast ustawiać każdy obszar ręcznie w programie, wpisujesz liczby w formularzu, sprawdzasz podgląd i pobierasz gotowy plik.

Oficjalna dokumentacja Pixera:  
<https://help.pixera.one/livetab/pixel-based-video-mapping>

### Dla kogo
Dla osób pracujących z:
- ekranami LED,
- projekcją,
- niestandardowymi powierzchniami,
- instalacjami, gdzie wiele fragmentów obrazu trzeba rozmieścić ręcznie.

### Najważniejsze zalety
- działa jako **jeden plik HTML**,
- nie wymaga instalacji,
- działa **offline**,
- pokazuje podgląd Source i Destination,
- eksportuje CSV zgodny z Pixera.

### Jak uruchomić
Po prostu otwórz plik `pixel-mapping-tool-for-pixera.html` w przeglądarce.

Przykłady:

```bash
open pixel-mapping-tool-for-pixera.html
xdg-open pixel-mapping-tool-for-pixera.html
start pixel-mapping-tool-for-pixera.html
```

Możesz też po prostu kliknąć plik dwa razy.

### Jak używać
1. Ustaw **Canvas Source** i **Canvas Destination**.
2. Dodaj mapowanie.
3. Wpisz pozycję i rozmiar regionu.
4. Ustaw matrycę:
   kolumny, wiersze, krok kolumny `X/Y`, krok wiersza `X/Y`.
5. Sprawdź podgląd.
6. Kliknij **Pobierz CSV**.

### Co oznaczają najważniejsze pola
- **Source**: skąd pobierany jest obraz.
- **Destination**: gdzie obraz ma trafić.
- **Region**: pojedynczy prostokąt.
- **Matrix**: powielenie regionu w siatkę.
- **Krok kolumny X/Y**: o ile przesuwa się następna kolumna.
- **Krok wiersza X/Y**: o ile przesuwa się następny wiersz.

### Dodatkowe informacje
- Ustawienia zapisują się automatycznie w przeglądarce.
- Możesz użyć **Import JSON** i **Eksport JSON**, aby przenosić konfiguracje.
- `warp.CSV` to plik referencyjny używany do sprawdzania zgodności eksportu.

---

## English Version

### What it is
This tool helps you generate a CSV file for **Pixel Based Video Mapping** in **Pixera**.  
Instead of setting every region by hand inside Pixera, you enter values in a form, check the preview, and download a ready-to-use file.

Official Pixera documentation:  
<https://help.pixera.one/livetab/pixel-based-video-mapping>

### Who it is for
For people working with:
- LED walls,
- projection setups,
- custom surfaces,
- installations where many image regions must be placed manually.

### Main benefits
- works as a **single HTML file**,
- no installation required,
- works **offline**,
- shows Source and Destination preview,
- exports Pixera-compatible CSV.

### How to start
Open `pixel-mapping-tool-for-pixera.html` in your browser.

Examples:

```bash
open pixel-mapping-tool-for-pixera.html
xdg-open pixel-mapping-tool-for-pixera.html
start pixel-mapping-tool-for-pixera.html
```

You can also just double-click the file.

### How to use it
1. Set **Source Canvas** and **Destination Canvas**.
2. Add a mapping.
3. Enter the region position and size.
4. Set the matrix:
   columns, rows, column step `X/Y`, row step `X/Y`.
5. Check the preview.
6. Click **Download CSV**.

### What the main fields mean
- **Source**: where pixels come from.
- **Destination**: where pixels should go.
- **Region**: one rectangle.
- **Matrix**: repeats the region in a grid.
- **Column step X/Y**: how much the next column moves.
- **Row step X/Y**: how much the next row moves.

### Extra notes
- Settings are saved automatically in the browser.
- You can use **Import JSON** and **Export JSON** to move configurations between machines.
- `warp.CSV` is the reference file used to verify export compatibility.
