# Pixel Mapping Tool for Pixera

Double-click `pixel-mapping-tool-for-pixera.html` to open the tool in your browser.  
No installation, no server, no internet required.

---

## Polska wersja

### Co to jest
Narzędzie do szybkiego przygotowania pliku CSV do **Pixel Based Video Mapping** w **Pixerze**.  
Zamiast ustawiać wszystko ręcznie w programie, wpisujesz liczby, sprawdzasz podgląd i pobierasz gotowy plik.

Oficjalna dokumentacja Pixera:  
<https://help.pixera.one/livetab/pixel-based-video-mapping>

### Jak uruchomić
Kliknij dwa razy plik `pixel-mapping-tool-for-pixera.html`.

### Jak używać
1. Ustaw **Source Canvas** i **Destination Canvas**.
2. Dodaj mapowanie.
3. Wpisz pozycję i rozmiar regionu.
4. Ustaw matrycę: kolumny, wiersze, krok kolumny `X/Y`, krok wiersza `X/Y`.
5. Sprawdź podgląd.
6. Kliknij **Pobierz CSV**.

### Najważniejsze pola
- **Source**: skąd pobierany jest obraz.
- **Destination**: gdzie obraz ma trafić.
- **Region**: pojedynczy prostokąt.
- **Matrix**: powielenie regionu w siatkę.
- **Krok kolumny X/Y**: przesunięcie następnej kolumny.
- **Krok wiersza X/Y**: przesunięcie następnego wiersza.

### Dodatkowe informacje
- Ustawienia zapisują się automatycznie w przeglądarce.
- Możesz użyć **Import JSON** i **Eksport JSON**, żeby przenosić ustawienia między komputerami.

---

## English Version

### What it is
A simple tool for generating a CSV file for **Pixel Based Video Mapping** in **Pixera**.  
Instead of setting everything by hand inside Pixera, you enter values, check the preview, and download the result.

Official Pixera documentation:  
<https://help.pixera.one/livetab/pixel-based-video-mapping>

### How to start
Double-click `pixel-mapping-tool-for-pixera.html`.

### How to use it
1. Set **Source Canvas** and **Destination Canvas**.
2. Add a mapping.
3. Enter the region position and size.
4. Set the matrix: columns, rows, column step `X/Y`, row step `X/Y`.
5. Check the preview.
6. Click **Download CSV**.

### Main fields
- **Source**: where pixels come from.
- **Destination**: where pixels should go.
- **Region**: one rectangle.
- **Matrix**: repeats the region in a grid.
- **Column step X/Y**: offset of the next column.
- **Row step X/Y**: offset of the next row.

### Extra notes
- Settings are saved automatically in the browser.
- You can use **Import JSON** and **Export JSON** to move settings between machines.
