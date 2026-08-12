# Utility Permitting Legal Portal

Intern juridisk kunskapsportal för miljö- och planrättsliga avgöranden med relevans för storskalig solkraft och energilagring.

## Funktioner

- Fritextsökning och filtrering
- Ämnen och taggar
- Centrala domar
- Detaljkort och relaterade avgöranden
- Trendvy
- Länkar till originaldomar i SharePoint

Portalen är skrivskyddad. `data/judgments.json` är den enda datakällan; administrationsläge, lokal redigering, lokal lagring och JSON-export/import ingår inte.

## Uppdatera domar

1. Redigera `data/judgments.json`.
2. Kontrollera att JSON-filen är giltig.
3. Lägg in filen i GitHub-repot och gör en commit.
4. Vänta tills GitHub Pages-publiceringen är klar.

## GitHub Pages

Publicera från den branch som repots Pages-inställning använder, med mappen `/(root)`. Om den befintliga webbplatsen publiceras från `develop`, behåll den inställningen när filerna ersätts. Då behålls samma URL:

`https://evelinasveasolar.github.io/utility-permitting-legal-portal/`
