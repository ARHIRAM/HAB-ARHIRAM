# HUB Catehetic Digital – Arhiepiscopia Râmnicului

## Structura proiectului
- `index.html` – pagina principală
- `abc-ul-credintei.html` – secțiunea ABC-ul credinței
- `teme.html` – catalogul celor 10 teme
- `cateheze/tema-01.html` ... `tema-10.html` – pagini individuale
- `assets/style.css` – design responsiv
- `assets/main.js` – funcții JavaScript minimale
- `resurse/pdf/` – locul recomandat pentru documentele PDF

## Publicare prin GitHub Pages
1. Deschideți depozitul GitHub în care doriți să publicați HUB-ul.
2. Încărcați conținutul acestui pachet în rădăcina depozitului (sau într-un director `docs`, dacă veți configura Pages să publice din acel director).
3. Verificați ca `index.html` să fie direct în rădăcina sursei de publicare.
4. În GitHub, intrați la **Settings → Pages**.
5. La **Build and deployment**, selectați **Deploy from a branch**.
6. Alegeți ramura `main` și folderul `/(root)` (sau ` /docs` dacă ați încărcat acolo), apoi apăsați **Save**.
7. După finalizarea publicării, accesați adresa afișată în secțiunea Pages.

## Cum adăugați un PDF
1. Încărcați fișierul în `resurse/pdf/`, de exemplu `tema-01-suport.pdf`.
2. Deschideți pagina catehezei, de exemplu `cateheze/tema-01.html`.
3. În secțiunea „Resurse PDF”, adăugați un link de forma:

   `<a href="../resurse/pdf/tema-01-suport.pdf" target="_blank" rel="noopener">Descarcă suportul PDF</a>`

4. Salvați modificarea și încărcați-o în GitHub. PDF-ul va putea fi deschis sau descărcat din pagina catehezei.

## Cum actualizați ulterior
- Pentru înlocuirea unui PDF cu o versiune nouă, încărcați fișierul cu același nume și confirmați înlocuirea.
- Pentru o resursă nouă, încărcați PDF-ul și adăugați un nou link în pagina catehezei.
- Pentru modificarea unui titlu sau text, editați fișierul HTML corespunzător.
- Orice modificare încărcată pe ramura și folderul configurate pentru Pages declanșează o nouă publicare. Actualizarea poate necesita câteva minute.

## Atenție la confidențialitate
GitHub Pages publică paginile pe internet. Nu încărcați documente cu date personale, informații confidențiale sau materiale pentru care nu aveți drept de publicare. Un depozit privat nu înseamnă automat că site-ul publicat este privat.

## Notă editorială
Cele zece teme sunt provizorii și nu reprezintă titluri validate. Conținutul teologic trebuie completat pe baza surselor aprobate de coordonatorul eparhial.
