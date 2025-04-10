# 🎬 Reactify your Movie App!

Ni har redan byggt en filmdatabas med HTML, CSS och JavaScript. Nu är det dags att ta det till nästa nivå – med **React**! Målet är att upptäcka fördelarna med ett ramverk, såsom komponenter, återanvändning och en bättre, tydligare struktur.

## 🧩 Uppgiften

Bygg en webbapp som liknar IMDB. Användare ska kunna:

- Se trailers och topplistan (via mitt API)
- Söka efter filmer (OMDB API)
- Klicka på en film för att få mer info
- Spara favoritfilmer

Startkod finns i mappen `template`. Den innehåller stil och struktur ni kan använda. Skapar ni eget, tänk på att matcha eller överträffa det visuella från template-versionen.

---

## ✅ Krav (för godkänt)

- Startsida med:
  - **5 slumpade trailers** (använd gärna Chad CN för att importera en redan färdig karussel)
  - **Topplista på våra rekommenderade filmer** (från mitt API)
- **Sökfunktion** som använder OMDB:s breda sökning:  
  `http://www.omdbapi.com/?apikey=[yourkey]&s=[söksträng]`
- Visa resultat som **kort eller lista** (titel + poster)
- Vid klick: gör en **specifik sökning** med imdbID:  
  `http://www.omdbapi.com/?apikey=[yourkey]&plot=full&i=[imdbID]`
- Visa mer detaljerad info om filmen (gärna på en egen sida/komponent)
- Spara filmer till en **favoritlista**
- **Användarvänlig design**: Här har ni chansen att skapa en egen design om ni inte gärna vill återanvända er gamla design
- Appen ska vara **responsiv**
- **Tillgänglighet**: alt-attribut, semantisk HTML, inga onödiga div:ar
- Använd **felhantering** vid API-anrop
- **Ren och läsbar kod**: rätt indentering, inga onödiga upprepningar

---

## 🔧 API-resurser

- Mitt API (trailers och topplista):  
  `https://santosnr6.github.io/Data/favoritemovies.json`
- OMDB API:
  - Bred sökning:  
    `http://www.omdbapi.com/?apikey=[yourkey]&s=[söksträng]`
  - Specifik sökning:  
    `http://www.omdbapi.com/?apikey=[yourkey]&plot=full&i=[imdbID]`
- Ni får gärna använda TMDB API istället om ni hellre vill det.

---

## 🧪 Tips

- Testa era API-anrop i **Postman** eller **Insomnia**
- Tänk på återanvändbara komponenter i React
- Reflektera över skillnaden mot er vanilla JS-version – vad blev enklare med React?
