# Semnalistică SSM și PSI

Site static cu indicatoare SSM și PSI în format PNG/PDF, pregătit pentru publicare prin GitHub Pages.

## Publicare pe GitHub Pages

1. Verifică local pagina deschizând fișierul `index.html` în browser.
2. Adaugă fișierele în repository:

   ```bash
   git add .
   git commit -m "Adauga pagina pentru semnalistica SSM si PSI"
   git push
   ```

3. În GitHub, intră în repository și mergi la `Settings` -> `Pages`.
4. La `Build and deployment`, selectează:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` sau `master`, în funcție de branch-ul repository-ului
   - folder: `/ (root)`
5. Apasă `Save`.
6. După publicare, GitHub va afișa URL-ul site-ului în aceeași pagină `Settings` -> `Pages`.

## Structura fișierelor

- `index.html` - pagina web principală.
- `*.png` - imaginile indicatoarelor afișate în pagină.
- `*.pdf` - fișierele descărcabile pentru indicatoare și instrucțiuni.

## Actualizare conținut

Pentru a adăuga un indicator nou, copiază imaginea și PDF-ul în rădăcina repository-ului, apoi adaugă o secțiune nouă în `index.html` după modelul indicatoarelor existente.
