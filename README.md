#Internetové stránky - Zahradnické služby#
##HTML a CSS##
Kód pro stránky jsem psala v html a nastylovala v css

##Struktura stránek a šablona##
Stránky jsou založeny na jednotné šabloně (ve složce _includes)

Použila jsem šablonovací engine nunjucks (njk) a generátor statických webů eleventy/11ty 

##Netlify##
Vzhledem k použití šablony jsem místo GitHub Pages využila pro publikování stránek službu Netlify 

##Responzivita##
Rozložení stránek a menu je responzivní (pomocí @media) s využitím gridu

##Barvy a písmo##
Použité barvy jsem uložila do proměnných, abych je v případě potřeby mohla snadno změnit

Pro podbarvení tlačítek a pozadí jednotlivých vtipů jsem použila selektor :nth-child()

Pro podbarvení v menu dle aktuální stránky jsem v šabloně použila podmínku {{ 'menu__item--active' if page.fileSlug==='...' }}

Čitelnost barvy písma vzhledem k pozadí tlačítek jsem ověřila pomocí contrast checkeru

Font pro písmo jsem vybrala Work Sans na Google Fonts

##Favicon##
Vektorový obrázek pro favicon jsem nadesignovala a sestavial ve vektorovém editoru Vectr

Pro vygenerování faviconu jsem následně použila RealFaviconGenerator
