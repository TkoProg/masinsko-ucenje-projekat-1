# Computer Hardware ML

Projekat 1 iz predmeta **Masinsko ucenje** na PMF-u.

## Opis projekta

Cilj projekta je predvidjeti performanse racunarskog hardvera na osnovu njegovih tehnickih karakteristika.

Koristi se **Computer Hardware** dataset, koji sadrzi podatke o razlicitim racunarskim sistemima i njihovim performansama.

## Sta projekat radi?

U projektu se prolazi kroz osnovne korake masinskog ucenja:

- ucitavanje i pregled podataka
- imenovanje kolona
- analiza numerickih i kategorijskih atributa
- provjera outliera
- priprema podataka za treniranje
- treniranje regresionih modela
- evaluacija modela pomocu metrika
- poredjenje rezultata modela

## Koristeni modeli

U projektu se porede dva modela:

- Ridge Regression
- Random Forest Regressor

## Koristene biblioteke

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Struktura projekta

```text
computer-hardware-ml/
├── data/
│   └── machine.data
├── main.ipynb
├── requirements.txt
└── README.md
