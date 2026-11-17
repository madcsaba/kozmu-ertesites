# Közmű-kimaradási értesítés (K1)

Szabványtervezet, petíció a közműszolgáltatókhoz és szakpolitikai javaslat ahhoz, hogy az áram-,
víz-, gáz- és távhőszolgáltatók **egyféle, géppel olvasható, aláírt** formában közöljék a
kimaradásokat — a lakos pedig a saját helyeire szűrve, a saját nyelvén tudja meg, miért nincs áram
vagy víz.

**Elérhető (GitHub Pages):** https://madcsaba.github.io/kozmu-ertesites/

## Oldalak

| Fájl | Tartalom |
|---|---|
| [`index.html`](index.html) | Kezdőlap: a probléma, az öt alapelv, az anyagok jegyzéke, a 2026. novemberi felmérés |
| [`peticio.html`](peticio.html) | Petíció a szolgáltatókhoz (kattintással másolható szöveggel) |
| [`javaslat.html`](javaslat.html) | Szakpolitikai javaslat a minisztériumoknak és a MEKH-nek, a K1 rövid szabványjavaslata, nemzetközi példák és források |
| [`szabvany.html`](szabvany.html) | A teljes műszaki szabvány: alapelvek, kódlisták, JSON- és SMS-forma, terjesztés, RSS, adatvédelem, bevezetés |
| [`minta/`](minta/) | Mintafájlok (JSON, RSS, tömör forma, szolgáltatói jegyzék) kitalált adatokkal |

## Forrásfájlok (markdown)

- [`kozmu-ertesites.md`](kozmu-ertesites.md) – a műszaki szabvány eredeti szövege
- [`peticio-szolgaltatok.md`](peticio-szolgaltatok.md) – a petíció eredeti szövege
- [`szakpolitikai-javaslat.md`](szakpolitikai-javaslat.md) – a szakpolitikai javaslat eredeti szövege

Az HTML-oldalak ezekből készültek, tartalmilag változtatás nélkül. A fájlok korábban a
`madcsaba/felkeszules-kezikonyv` repó `docs/` mappájában voltak; 2026 novemberében ide költöztek,
a kézikönyv csak hivatkozik rájuk.

## Kapcsolódó oldalak

- **Működő bemutató:** https://madcsaba.github.io/felkeszules-kezikonyv/app/ – a Felkészülés mobilapp
  „Helyben” képernyője a szabványos, aláírt értesítés megjelenését mutatja (mintaadatokkal).
- **Felkészülési kézikönyv:** https://madcsaba.github.io/felkeszules-kezikonyv/

## Futtatás

Nincs build-lépés: statikus HTML, a `main` ág gyökeréből szolgálja ki a GitHub Pages.
Helyben: `python3 -m http.server 8000`, majd <http://localhost:8000/>.

## Megjegyzés

Tervezet, 2026. november — szakmai vitaanyag, nem hivatalos szolgáltatás. A mintaadatok kitaláltak.
