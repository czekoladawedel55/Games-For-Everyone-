# 🧱 BTBlocks — Games for Everyone

## 🪟 [Otwórz stronę BTBlocks — Windows 7 Aero](https://czekoladawedel55.github.io/Games-For-Everyone-/)

## 🚀 Najnowsza wersja: BTBlocks v1.7 Enhanced

**[⬇ Pobierz oficjalny instalator BTBlocks v1.7 Enhanced — EXE](https://drive.google.com/file/d/1PqT_FkYE3FVnFzqG_HW6cx5eEYW1gaWd/view?usp=drivesdk)**

Nowa edycja Enhanced: minigry **Orbital Escape**, **Circuit Master** i **Pulse Perfect**, zmodernizowane menu i systemy gry. Kafelkowy Labirynt i misja Inspirona 620 nie należą do zamierzonego zakresu v1.7; zamiast misji pozostaje pamiątkowa grafika obudowy.

Instalator został dostarczony przez autora i opublikowany na Google Drive. **Nie przeprowadzono niezależnego testu działania EXE w Windows ani pełnego audytu jego spakowanej zawartości.**

## 📱 BTBlocks v1.8 Mobile LS2208 Code128 Beta — Android APK

**[⬇ Pobierz BTBlocks v1.8 Mobile LS2208 Code128 Beta (DEBUG APK)](https://drive.google.com/file/d/1yPmSEsQ4Asy-eFSoJf4P8CkNZqcMIcNu/view?usp=drivesdk)**

Android działa **tylko w poziomie (landscape)**; zawiera mały interfejs, joystick do minigier i sterowanie FPS/Zombie Survival dwoma palcami.

### BTBlocks DevLink — czytnik USB Symbol LS2208

Nowy PC DevLink wspiera skaner **Symbol LS2208-SR20007R-UR** działający jako klawiatura USB. Model rozpoznaje **Code 128 (1D), ale nie odczytuje QR**. W ustawieniach Androida można wyświetlić duży kod kreskowy na całym ekranie; pierwotne parowanie wymaga zeskanowania **4 części Code 128**, a kolejne odblokowanie — **1 kodu**. Program PC automatycznie przyjmuje odczyty również bez końcowego Enter. QR nadal jest dostępny dla kamery komputera.

Parowanie wiąże telefon z **tajnym kluczem zapisanym w sparowanym PC**, a nie z numerem seryjnym skanera. Sam odczyt jednorazowego kodu przez obcy skaner nie odblokuje panelu. **Nie udostępniaj czterech kodów pierwszego parowania** — zawierają sekret.

**Uwaga sprzętowa:** LS2208 to stary laserowy skaner; odczyt kodów kreskowych **bezpośrednio z wyświetlacza telefonu nie jest gwarantowany**. W razie problemów spróbuj wydruku Code 128 albo pozostawionego trybu QR z kamerą. Kod można też przepisać do programu PC.

Deweloperskie funkcje BTBlocks: FPS, jakość grafiki 3D, czułość kamery, martwa strefa joysticka, ograniczenie animacji, diagnostyka i eksport JSON. Nie są to systemowe opcje programisty Androida.

- [Publiczny folder wydań APK](https://drive.google.com/drive/folders/17gEckRqCa2WdFG3y2oYN5YuH8UnzPvFN)
- [Archiwum starszych APK (w tym wcześniejszej DevLink QR Beta)](https://drive.google.com/drive/folders/18I-5pohGKzwpUes4RskVZASI31dkqB2L)
- [Kompilacja Android GitHub Actions](https://github.com/czekoladawedel55/BTBlocks-Mobile-PRIVATE/actions/runs/43291448230) (prywatny projekt)
- SHA-256 APK: `c69cf42f08792eab32b7b0ac3f9f73cdeb4d4d4dfadf62993a2ef1c90e8b614c`
- PC EXE pozostaje narzędziem prywatnym. Kompilacja GitHub Actions przeszła pomyślnie.
- Weryfikacja laboratoryjna: kody Code 128 zostały odczytane przez dekoder; **fizyczny LS2208, Windows 7 i Android nie były jeszcze testowane razem**.

To **testowe APK DEBUG**, nie produkcyjne wydanie stabilne. Windows EXE **BTBlocks v1.7 Enhanced** pozostaje niezależnym wydaniem PC.

## ⚠️ Uwaga o skrótach starszych instalatorów

W starszych EXE (m.in. v1.4 i v1.5) skróty na pulpicie mogły mieć tę samą nazwę **BTBlocks** i wskazywać ten sam katalog instalacyjny. Instalacja nowszej wersji mogła więc zastąpić pliki starszej, przez co skrót v1.4 otwierał v1.5. **Wersje EXE w archiwum są oryginalnymi, nieprzebudowanymi instalatorami.** Nie zmieniliśmy ich zawartości.

Przygotowano poprawione prywatne BuildKity v1.4 Original, v1.4 Tile Maze, v1.5 oraz v1.6, z unikalnymi nazwami skrótów, osobnymi katalogami i identyfikatorami instalacji. Trzeba z nich ponownie skompilować i przetestować EXE przed podmienieniem publicznych plików. Nie usuwać plików z katalogu poprzedniej instalacji bez kopii danych.

**Poprawione paczki developerskie dla wcześniejszych wersji są zachowane.** v1.7 Enhanced jest oficjalnym wydaniem Windows, a v1.8 Mobile jest dostępny wyłącznie jako testowa Beta Android.

## 📁 Poprzednie wersje (EXE)

- **[v1.5 Christmas — Inspiron 620 Tribute](https://drive.google.com/file/d/1NIsA4JbjmLpiS4HRg8abveJIuGhEdyB_/view?usp=drivesdk)**
- **[v1.4 Christmas + Kafelkowy Labirynt](https://drive.google.com/file/d/1LEDSQbtDgdGUWsGZfwFnYnSY4MFmMmK-/view?usp=drivesdk)**
- [v1.4 Christmas Original, bez labiryntu](https://drive.google.com/file/d/1dfKcGXOCyDXvSMeBSUTDf5Ev3UmZKw1Y/view?usp=drivesdk)
- [v1.3](https://drive.google.com/file/d/1UYH18dH5nfyBhhsiaHZjmY4161xGmSVP/view?usp=drivesdk)
- [Folder Archive - Old Versions](https://drive.google.com/drive/folders/1oTz7OIb2q6pUFwwtqRCIo9Wvi-bj0iZr)

## 💻 Zgodność

Docelowo: Windows 7–11 64-bit, Electron 22. Windows XP/Vista nie są obsługiwane przez ten instalator.

## 🔐 Prywatność kodu

Publiczne repozytorium zawiera stronę pobierania i opisy wydań. **Kod źródłowy gry i BuildKit są przechowywane prywatnie**, nie są publikowane tutaj.

## 🛠️ Zgłoszenia i historia

[Zgłoś błąd](../../issues) · [Changelog](CHANGELOG.md) · [Archiwum](archive/README.md)
