#Speedtests#

| **Linkscars.com**   | **laddningstid/antal resurser**  |
|----------|:-------------:|------:|
| mobil: 64/100 dator:85/100 |  25 sec 400 bilder/giffar 15.8 Mb  |
| flik **about**: mobil 54/100 dator: 67/100 |    22 sec 300 bilder/giffar 8Mb |
| flik **fun stuff**: mobil: 55/100 dator:69/100 | 20 sec 280 bilder/giffar 6Mb |
| flik **quotes/ orders** mobil:58/100 dator: 73/100 | 15 sec 270 requests 6Mb |

Förbättrning: Mindre giffar och bilder vilket fyller ut hela skärmen i nuläget.  Komprimera flera objekt till en enda bild. Reducera antalet page requests på första sidan.

| **Python.org**   | **laddningstid/antal resurser**  |
|----------|:-------------:|------:|
| home 55/100 dator 75/100 |  3sec 30 req 771 Kb  |
| **documentation**  mobil: 60/100 dator 76/100 |    0.67 sec 14 req 153 Kb |
| **jobs** mobil: 64/100 dator: 80/100 | 0.67 sec 14 req 153 Kb |

Snygg design för sitt ändamål  och bra navigation.
Förbättring: Ta bort javascript och Css-kod som blockerar rendering  och innehåll ovanför mitten. En navigationsbar försvinner när man studerar sidan via mobilen och skulle kunna appliceras via de flikar som  redan nu finns inlagda.


| **Microsoft**   | **laddningstid/antal resurser**  |
|----------|:-------------:|------:|
| **home** mobil: 58/100 dator: 74/100 |  11.7 sec 66 req 2 mb  |
| **windows**: mobil: 49/100 dator: 68/100 |    23 sec 160 req  9mb |
| **support**:  58/100 dator: 78/100 | 15 sec 85 req 3.3 mb |

Förbättring: Ta bort javascript och Css-kod som blockerar rendering  och innehåll ovanför mitten. Något för mycket många och stora bilder. Endast två bilder i nuvarande bildspelet , kan använda sig av två stillabilder endast då antalet bilder är så pass lågt. Vi misstänker att antalet kan flukturera.

| **W3school**   | **laddningstid/antal resurser**  |
|----------|:-------------:|------:|
| **Home** mobil: 84/100 dator: 87/100 |  1.9 sec 29 req 1 mb  |
| **HTML Examples:** mobil: 83/100 dator:88/100 68/100 |    10 sec(förutom ads) 140 req 3.5 mb |
| **color Tutorial**	mobil: 82/100 dator: 90/100 | 10 sec 100 req 3.3 mb |

Förbättringar: Lite för mycket reklam på ett få antal sider samt de använder sig av en mediaspelare som kräver mycket. Html sidan har inte all plats utnyttjats och det finns gott om utryme att komprimera informationen på.

Sammanfattning: Ta bort javascript och Css-kod som blockerar rendering  och innehåll ovanför mitten. Sedan reducera antalet bilder som kan förekomma och förminska javscript och css kod.
Våran snitt laddningstid är 12.23 sec  vilket skulle få oss alla i gruppen att tappa intresse redan innan sidan laddat. Om inte något spännande skulle ladda först då kan vi spendara ytterligare några få seckunder i förväntan. Den absoluta gränder bör enligt oss ligga vid 6 sekunder.
Våra utvaldda sidor klarade inte våra förväntningar och skulle avfärdas på grund av deras laddningstid. Vi tror att vi tog ganska krävande sidor så som enorma företag och utbildningssidor vilket då laddninstiden kan vara förståligt eftersom att de måste meddela mycket information.

Oliver Bergman, Alexey Vorobyev, Daniel Hägg, Johan Liljeberg.
