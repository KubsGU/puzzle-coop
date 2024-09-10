# Puzzle Coop

Puzzle Coop to gra stworzona w Unreal Engine, która skupia się na kooperacyjnych zagadkach. Projekt jest dostępny na GitHubie i można go uruchomić lokalnie, korzystając z poniższych instrukcji.

## Spis treści

1. [Wymagania wstępne](#wymagania-wstępne)
2. [Instalacja](#instalacja)
3. [Konfiguracja Git LFS](#konfiguracja-git-lfs)
4. [Uruchamianie projektu](#uruchamianie-projektu)
5. [Kontrybucja](#kontrybucja)
6. [Licencja](#licencja)

## Wymagania wstępne

Przed rozpoczęciem upewnij się, że masz zainstalowane następujące narzędzia:

- [Unreal Engine](https://www.unrealengine.com/) (wersja 5.4.4)
- [Git](https://git-scm.com/)
- [Git LFS](https://git-lfs.github.com/)

Dodatkowo zaleca się posiadanie edytora kodu, np. [Visual Studio](https://visualstudio.microsoft.com/) lub [Visual Studio Code](https://code.visualstudio.com/).

## Instalacja

1. **Sklonuj repozytorium:**

   Otwórz terminal lub wiersz polecenia i wpisz:

   ```bash
   git clone https://github.com/KubsGU/puzzle-coop.git
   ```

2. **Przejdź do katalogu projektu:**

   ```bash
   cd puzzle-coop
   ```

## Konfiguracja Git LFS

Unreal Engine używa dużych plików binarnych, takich jak assety i modele. Aby upewnić się, że duże pliki są poprawnie pobierane, skonfiguruj Git LFS:

1. **Zainstaluj Git LFS, jeśli jeszcze tego nie zrobiłeś:**

   Pobierz i zainstaluj Git LFS z [oficjalnej strony](https://git-lfs.github.com/).

2. **Zainicjuj Git LFS w swoim środowisku:**

   ```bash
   git lfs install
   ```

3. **Pobierz duże pliki za pomocą Git LFS:**

   ```bash
   git lfs pull
   ```

## Uruchamianie projektu

1. **Otwórz projekt Unreal Engine:**

   Otwórz Unreal Engine i wybierz `File > Open Project`. Przejdź do katalogu projektu `RAK_V1` następnie `puzzle-coop` i wybierz plik `RAK_v1.uproject`.

2. **Skonfiguruj wymagania projektu:**

   Po otwarciu projektu, Unreal Engine może poprosić o zainstalowanie dodatkowych pakietów, np. brakujących pluginów. Zainstaluj je zgodnie z instrukcjami.

3. **Zbuduj projekt:**

   W menu `Build` wybierz `Build Solution` (jeśli używasz Visual Studio) lub kliknij `Compile` w Unreal Engine, aby zbudować projekt.

4. **Uruchom grę/aplikację:**

   Po zakończeniu kompilacji kliknij przycisk `Play`, aby uruchomić projekt.

## Kontrybucja

Jeśli chcesz przyczynić się do rozwoju projektu:

1. Sklonuj repozytorium i stwórz nową gałąź (`git checkout -b feature/nazwa-funkcji`).
2. Wprowadź swoje zmiany i zatwierdź je (`git commit -m 'Dodaj funkcję'`).
3. Wypchnij zmiany do gałęzi (`git push origin feature/nazwa-funkcji`).
4. Otwórz Pull Request na GitHubie.

## Licencja

Ten projekt jest objęty licencją MIT. Zobacz plik [LICENSE](LICENSE) po więcej szczegółów.

---

Dzięki za zainteresowanie projektem! W razie pytań lub problemów prosimy o otwarcie zgłoszenia na GitHubie.
