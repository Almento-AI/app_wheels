# app_wheels

Repozytorium publikuje wlasne wheel-e Python

## Struktura

- `packages/` - pliki `.whl`
- `simple/` - indeks zgodny z `pip` (PEP 503)
- `.github/workflows/pages.yml` - automatyczny deploy na GitHub Pages

## Uzycie

Instalacja pakietu z tego indeksu:

```bash
pip install --index-url https://almento-ai.github.io/app_wheels/simple/ *
```


## Publikacja nowego wheel-a

1. Dodaj plik `.whl` do `packages/`.
2. Zaktualizuj odpowiedni `simple/<nazwa-pakietu>/index.html`.
