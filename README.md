# Dorottya Duzsik – networking oldal

## Tartalom
- `index.html` – az oldal szövege (ezt szerkeszd a szövegcseréhez)
- `styles.css` – színek és betűk; a színek a fájl elején, a `:root` blokkban vannak
- `Dorottya-Duzsik-Resume.pdf` – a letölthető önéletrajz
- `img/` – képek (WebP). Csere: ugyanazzal a fájlnévvel töltsd fel az újat.
- `fonts/` – saját tárhelyről betöltött betűtípusok (Bricolage Grotesque, Nunito Sans; SIL OFL licenc)
- A „Hi, I am” felirat a saját kézírásod vektorizálva, az `index.html` elején (`class="hello"`). A színe a `styles.css`-ben a `--hand` változó.

## Portré hozzáadása
1. Készíts egy fotót: vállig érő, természetes fény, nyugodt háttér, lehetőleg ugyanaz, mint a LinkedIn-képed.
2. Vágd 4:5 arányra (pl. 1200 × 1500 px), mentsd WebP vagy JPG formátumban, kb. 300 KB alá.
3. Nevezd el `portrait.webp`-nek, és töltsd fel az `img` mappába. Ha JPG, az `index.html`-ben a `img/portrait.webp` szöveget írd át `img/portrait.jpg`-re.
Amíg nincs fotó, a „DD” monogramos csempe látszik.

## Előnézet
Dupla kattintással az `index.html` megnyílik, de a böngésző biztonsági okból így nem tölti be a háttérrajzot (és néha a betűket sem). A valós kép a GitHubon feltöltés után látszik.

## Publikálás GitHub Pages-re (kb. 15 perc)
1. github.com → Sign up. Felhasználónév javaslat: `dorottyaduzsik` (ez lesz a címben).
2. Jobb fent `+` → **New repository**. Név pontosan: `dorottyaduzsik.github.io` (ha más a felhasználóneved, azt írd). Láthatóság: **Public**. Create.
3. A repó oldalán: **uploading an existing file** → húzd be a mappa TELJES tartalmát (a `fonts` és `img` mappákkal együtt) → **Commit changes**.
4. **Settings → Pages** → Source: *Deploy from a branch*, Branch: `main`, mappa: `/ (root)` → Save.
5. 1–2 perc múlva nyisd meg telefonon: `https://dorottyaduzsik.github.io`

## Frissítés a korábbi verzióról
A GitHubon az `img` mappából TÖRÖLD a régi képeket (`bathroom-elevation.webp`, `benches.webp`, `thesis-courtyard.webp`, `thesis-courtyard-aerial.webp`, `thesis-gallery.webp`). Ha bent maradnak, közvetlen linkkel továbbra is elérhetők, akkor is, ha az oldal már nem mutatja őket.

## Frissítés: tiszta újrafeltöltés
Lásd a chatben leírt lépéseket (repó törlése és újra létrehozása ugyanazzal a névvel). Utána a teljes mappa tartalmát töltsd fel.

## FONTOS
- A repó nyilvános: ide csak az kerüljön, ami az oldalon is látszik. A régi (telefonszámos) CV, nyers portfólió PDF, munkahelyi anyagok NEM.
- Ne kapcsolj be analitikát vagy külső betűtípust: az oldal jelenleg semmilyen adatot nem küld harmadik félnek.
- November elején cseréld a Greenbuild-es záró mondatot (`index.html`, "Let's stay in touch" rész) örökzöld szövegre.
