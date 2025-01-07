# SP-2024

Opis krótki projektu, jego celu i głównych funkcji.

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
