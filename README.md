# SP-2024

## Cel projektu
Celem projektu jest opracowanie, implementacja i analiza algorytmów rejestracji obiektów trójwymiarowych, z naciskiem na dokładność i efektywność. Projekt koncentruje się szczególnie na rejestracji obrazów medycznych, które mają kluczowe znaczenie w diagnostyce i leczeniu, zwłaszcza w kontekście detekcji chorób i zmian nowotworowych.

## Oczekiwane rezultaty
- Opracowanie algorytmów rejestracji obiektów 3D - metody liniowe oraz nieliniowe
- Analiza skuteczności w różnych warunkach, zwłaszcza w przypadku dużych i nieregularnych zbiorów danych, takich jak obrazy mikroskopowe.

## Zakres problemu
Rejestracja obrazów 3D jest procesem dopasowania dwóch lub więcej obrazów tej samej sceny w celu poprawy ich analizy. Ma szerokie zastosowanie w:
- medycynie - rejestracja obrazów z różnych modalności, takich jak MRI, CT, PET, czy USG, w celu uzyskania kompleksowego obrazu narządów.
- geodezji - analiza zmian w terenie na podstawie obrazów satelitarnych.
- astronomii - porównywanie obrazów nieba z różnych przedziałów czasowych.

## Metodyka
Projekt zakłada zastosowanie transformacji liniowych (np. przesunięć, rotacji, skalowania) i nieliniowych (np. swobodnych deformacji). Kluczowe metody obejmują:

Liniowe:
- Transformacje sztywne (Rigid Registration, Euler Transform).
- Transformacje afiniczne (Affine Registration).
- Skalowanie i translacje (Similarity Transform, Translation Transform).

Nieliniowe:
- Swobodne deformacje (FFD, Multilevel FFD).
- Elastyczne rejestracje dla lokalnych deformacji.

## Wymagania

- Python 3.8 lub nowszy
- [Anaconda](https://www.anaconda.com/) lub [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

## Instalacja i konfiguracja

Aby skonfigurować środowisko potrzebne do uruchomienia projektu, wykonaj poniższe kroki:

### 1. Klonowanie repozytorium
Najpierw sklonuj to repozytorium:
```bash
git clone <git repository url>
cd repo-name
```
### 2. Utworzenie środowiska z pliku environment.yml
Użyj Condy, aby stworzyć środowisko na podstawie pliku environment.yml:
```bash
Skopiuj kod
conda env create -f environment.yml
```
### 3. Aktywacja środowiska
Aktywuj utworzone środowisko:
```bash
Skopiuj kod
conda activate sitkpy
```
Uwaga: Nazwa środowiska jest określona w pliku environment.yml. Zazwyczaj znajdziesz ją w nagłówku pliku w sekcji name:.

### 4. Uruchomienie projektu
Po aktywacji środowiska możesz uruchomić projekt. Przechodząc do sekcji Notebook znajdziesz pliki Jupyter Notebook, które możesz wykorzystać do testowanai metod.
