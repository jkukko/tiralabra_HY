# Määrittelydokumenttatio

## Minkä ongelman ratkaisen

Sovelluksen tarkoitus on verrata reittihakualgortimien tehokkuutta. Toteutan Leveyshaku (BFS), A* ja Jump Point Search (JPS) . Tarkoituksena on hyödyntää joukkoliikenteen reittejä.

## Algoritmit ja tietorakenteet

Käytän BFS, A* ja JPS algoritmiä.

### BFS 

Algoritmi, joka löytää lyhimmän reitin painotetussa verkossa. Algoritmi voidaan toteuttaa jonona.

### A*

Algoritmi, joka on tehostettu versio Dijkstran algoritmissä. Siinä hyödynnetään heuristiikkaa funktiota, jonka avulla voidaan arvioida käsiteltävien solmujen etäisyyttä loppuun.

### JPS

Algoritmi on A* muunnelma. Sen pitäisi olla huomattavasti tehokkaampi kuin A*.

## Syötteet

Ohjelma saa syötteenä kartan ja haettava alku- ja loppupisteen. Ohjelmassa on valmiiksi joukko karttoja.

## Aikavaatimus

Dikkstran algoritmin aikavaatimus on O(n + m log n) ja A* ja JPS algoritmin aikavaatimus on O(n). n on solmujen lkm ja m on kaarien lukumäärä

## Yleistä

* Opinto-ohjelma: tietojenkäsittelytieteen kandidaatti (TKT)
* Dokumentaatiossa käytetty kieli: Suomi
* Ohjelmointikieli: Java

## Lähteet

[Dijkstra's algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)

[Introduction to A*](http://theory.stanford.edu/~amitp/GameProgramming/AStarComparison.html)

[Jump Point Search](https://en.wikipedia.org/wiki/Jump_point_search)
