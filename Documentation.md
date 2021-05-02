# Dokumentation Projektarbete

Som vanligt så börjar jag med html dokumentet och gör alla grunddelarna såsom alla meta taggar och link till stylesheets.

Därefter lägger jag upp strukturen för det innehåll sidan skall ha och delar upp det i lämpliga sektioner som i grova drag är navigationsdelen, footern samt huvuddelen av innehållet i respektive sida.

I det här fallet så funderade jag först på att använda Bulma alternativt Bootstrap för meny delen men med tanke på att det bara är 2 sidor så gjorde jag det för hand mha en unordered list istället.

När allt innehåll är på plats så är det dags att titta på layouten.

Det såg lite andefatigt ust så jag gjorde en enkel png bestående av 3 fyrkanter med färger från den envisade paletten. På så sätt så livade det upp sidorna och navigationsbiten lite grand.

Här fanns det ingen modell eller ide vad det gäller utformningen så det finns inget att rita linjer på för grid system som jag gjorde i uppgift 2.

Vad det gäller reaktiviteten till Hem-sidan så finns det inte så mycket att göra här. Det är bara att hitta brytpunkter så småning om och anpassa
fontstorlekar och lite förändringar i padding.

För katalog-sidan fanns det lite mer att göra med table uppsättningen. Jag gjorde om tabellens kolumner till rader med tillhörande kolumnheading till varje element. Ganska OK lösaning när man inte kan använda JavaScript där man istället hade haft all data i json eller XML fil och injecerat den i lämplig form på lämpligt ställe i html DOMen. Brytningen här från vamnligt table kommer vid 900px all mindre representerar tabellen i rader.
Även i katalog-sidan så gäller det naturligtvis att anpassa storleken på fonter och padding så att det passar mellan de olika brytpunkterna.

Jag har använt mig av tre brytpunkter 900px, 640px och 420 samt bara för att det irriterade mig lite en sista vid 290px för hemsidan. H1 elementet i header taggen blev en aning för stort under 290px. Siten skall fungera ner till 280px smalare skärmar än så finns inte mycket ide att syssla med och det stog inget i kravspecifikationene om hur små skärmar som skulle stödjas. iPhone 4 är 320px och bör väl vara en rimlig nedre gräns om inga specifika önskemål framställs.

I övrigt så jobbar jag alltid med både html koden och stylesheet för att hitta den bästa och enklaste lösningen för att det skall se ut som jag hade tänkt mig.

Om det är något annat du vill veta som jag kanske inte tagit upp så förklarar jag gärna.

-Chris Johannesson
