# World of Warcraft

my WoW Addons and Settings Export

## Addons 

### Baganator - Categories

Bag Addon - [Baganator](https://www.curseforge.com/wow/addons/baganator)

```json
{"categories":[{"source":"23","name":"Gegenstandsaufwertung","search":"#Gegenstandsaufwertung|Tapferkeitsstein|Vorbotenwappen|Wachsklumpen"},{"source":"11","name":"Dunkelmond-Jahrmarkt","search":"Dunkelmond-Jahrmarkt|Dunkelmond-Spielpreis|Dunkelmond-Ticket"},{"source":"12","name":"Items","search":"!war within&!Dunkelmond&!Goblingleiter"},{"source":"13","name":"Seelengebunden","search":"seelengebunden&#rüstung&#ausrüstung&>400"},{"source":"17","name":"Beim Anlegen gebunden","search":"!seelengebunden&#rüstung&#ausrüstung&>400"},{"source":"27","name":"Schlüsselstein","search":"Schlüsselstein&Seelengebunden&Mythische"},{"source":"8","name":"Wappenröcke","search":"Wappenrock"},{"source":"14","name":"Kampfhaustiere","search":"#kamphaustier|#Haustier"},{"source":"15","name":"Kochen","search":"fleisch|fisch|kochkunst|Portioniertes Steak"},{"source":"25","name":"Beim Anlegen gebunden","search":"!seelengebunden&(einhändig|zweihändig|wurfwaffe|schildhand|nebenhand|köcher)&>400"},{"source":"4","name":"Optionales Handwerksmaterial","search":"optionale reagenzien|Funke der Omen"},{"source":"1","name":"Monfest","search":"Mondfest"},{"source":"5","name":"Ingenieurskunst","search":"teile"},{"source":"3","name":"Juwelierskunst","search":"juwelierskunst&!Rüstung&!Anlegen"},{"source":"2","name":"Verzauberkunst","search":"verzauberkunst"},{"source":"19","name":"Kürschnerei","search":"leder&!Rüstung&!Anlegen"},{"source":"18","name":"Fertigungsreagenzien","search":"fertigungsreagenzien|#reagenz"},{"source":"7","name":"Bergbau","search":"metalle steine"},{"source":"6","name":"Inschriftenkunde","search":"inschriftenkunde"},{"source":"9","name":"Schneiderei","search":"stoffe|faden|#handwerksmaterial&Band|Schneiderei"},{"source":"24","name":"Seelengebunden","search":"seelengebunden&(einhändig|zweihändig|wurfwaffe|schildhand|nebenhand|köcher)&>400"},{"source":"16","name":"Kräuterkunde","search":"kräuter"},{"source":"26","name":"Steinmetzkunst","search":"gewichtsstein|schleifstein"},{"source":"20","name":"Berufswissen","search":"wissen&studieren"},{"source":"21","name":"Truhen und Geldbeutel","search":"Truhe|Geldbeutel"},{"source":"22","name":"Braufest","search":"Braufest"},{"source":"10","name":"Kampfkuriosität","search":"Kuriosität"}],"version":1,"order":["27","21","default_hearthstone","default_potion","default_food","default_consumable","10","----","_Berufe","5","2","9","19","16","7","3","6","15","4","18","default_tradegoods","default_reagent","default_gem","default_recipe","20","__end","----","_Rüstung","17","13","8","default_profession","default_auto_equipment_sets","default_armor","__end","_Waffen","24","25","26","__end","----","default_container","default_questitem","default_key","default_miscellaneous","23","14","default_battlepet","default_toy","default_other","default_junk","default_special_empty","----","_Feiertag","11","1","22","__end","----","_Alte Erweiterungen","12","__end"],"modifications":[{"showGroupPrefix":true,"source":"27","priority":3},{"source":"9","priority":0},{"showGroupPrefix":true,"source":"23","priority":0},{"showGroupPrefix":true,"source":"22","priority":3},{"showGroupPrefix":true,"source":"21","priority":3},{"showGroupPrefix":true,"source":"20","priority":3},{"showGroupPrefix":true,"source":"26","priority":3},{"source":"8","priority":3},{"source":"15","priority":0},{"source":"default_hearthstone","priority":3},{"showGroupPrefix":true,"source":"25","priority":0},{"source":"default_tradegoods","priority":-1},{"items":[116406],"source":"default_food"},{"items":[221763,213611],"source":"18","priority":0},{"source":"default_battlepet","priority":3},{"items":[228414,228956],"source":"5","priority":0},{"items":[21100],"source":"1","priority":0},{"showGroupPrefix":true,"source":"default_key","priority":-1},{"items":[211806],"source":"3","priority":0},{"source":"2","priority":0},{"items":[222649,224807],"source":"19","priority":0},{"source":"4","priority":0},{"items":[222553],"source":"7","priority":0},{"source":"6","priority":0},{"source":"14","priority":3},{"showGroupPrefix":true,"source":"24","priority":0},{"source":"16","priority":0},{"source":"17","priority":3},{"showGroupPrefix":true,"source":"13","priority":3},{"showGroupPrefix":true,"source":"12","group":"expansion","priority":2},{"items":[92794,72018],"source":"11","priority":0},{"source":"10","priority":0}],"hidden":[]}
```

## Macros

### Priest - Mount and Angelic Feather

Change the mount and spellnames to your used ones

```
/cast [nocombat,swimming]Dunkelwasserrochen;[nocombat,outdoors,flyable]Leuchtender Sternensucher;[nocombat,outdoors]Erneuerter Protodrache;[nocombat,outdoors,noflyable]Schecke;[nocombat,nostance,@player][combat,@player]Engelsfeder;[@player]Engelsfeder
```

## Weak Auras

### Fishing - Wiederverwendbarer übergroßer Schwimmer

Displays an icon that shows the remaining duration of the ![reusable oversized bobber](https://wow.zamimg.com/images/wow/icons/large/achievement_profession_fishing_outlandangler.jpg) [reusable oversized bobber](https://www.wowhead.com/de/item=202207/wiederverwendbarer-%C3%BCbergro%C3%9Fer-schwimmer) and casts the fishing rod when clicked.

> [!WARNING]
> This Weak Aura uses [Secure Frames](https://github.com/WeakAuras/WeakAuras2/wiki/protected-frames)

```
!WA:2!fw1tVTrru844iHyRq0gAsAdvOvb1qsPK2K(NuQuLQxh7Mao2H1o02dG9S7o27qwpZYmZ68hqO2CQhr(ax4MpuXb4I)cakFcgzvXhGEGpa5la8MzTtBdiHpSEE)zM379B(9EtMIt2EYGjdE2c9i(mAvwc3hFPXgGsKHmELyjHrfZ(N9ejEJe(jh5(XyxcnorYte41Wc)WUTtIKKicfhYdWnrG04RSdEFhjEpP7UKazywVimTLmCkhkQn2PgyOlS9sgLHQjCBXzjX90gttJmh6ZIIqXcCO6mz7d(MFKmNY2eZBbgEB32iFot9oQP6grAtK1GKZHYO4UMZtl6jiTJJW9djbyxmdsqEdhb5a8u9rbFtIqId2eT34VsGqhNVFLMnfy563VXtg7jJngyL6dqYwmcv6LVq5AfCh4ZyrbSDPv3LeJBC0iXcbqM5OXZghk5KwTWCXhmpF4YNRbTYqv2OlkHJ01RywVB8PRENvw1f3bdh)6yuKm8LaOBK3IJBs2ZT6wfkv6qrmokAJaH1jMRM0em3VE(CvRvVATCU1CsOePxCeAFm31ealaF1rBLEbypWFnSWxVqPTkUDPUj0HPM18Ql)C1eQBOwsDn1IQROUUAz1NyP(y1vvZ3qTIL6JMn(8FEegqsUnG8HyQTdorIv3uDl1TTIphYxs6GRLEGBYcW)6yhdqgMtrrFjaeah6NFzmN1IJfI0l6RCPXgVRah10aUkBihfijKTsCOM55IBPzE3DA1edarpK)o67wAWZoF8KAcwDrica(hLELLj(IgLMpnz82iWHHluZ09eBZDzr8zFTTdSlg)ZYKjt2xMQDug5KB7AvIFpJsOXGbNdX)HAoTtoq840ar2dhyu(0bPuLhpmDoYyxtTin3hQootcvMM)7uUs5cQj4qrP9PNXrFtAKf(1DyfqLXNTiNCG9xKGcaubzxR2Bu4JI0aJUDbg(d5O4dF4WfPjqhIGaTGngwZVgDo(CBuUCb36ovQvRYMUB8G1Rn4Kqxf6tU4Wk6rVrC0wn8OkBxR0gLl8xdAfX2Tih)TjyQ)(BnX1xALBLwDAdhP)SM(wfUmZEOwsV7bEjsjJwPdMd81EA1PJeMQVE9OsRRwi)jqZrqp0dgPj045jjN5Kdj(7qbgwwZgR6JIWzD0ldnkkbtQeNZenhZaHqVqmPvO8PormuqN(ejUnuiqFDWSxy8F)xogcy9xtzONeosQCAxZKpREA7(S2EizORFesiMwrTCGUvF9c17R)gFwWRCdNYyg6eEAveAypUHVRbh1hUscjOFK3QRSXDEmPYQD6IOK2gi82UcjIllEegjWvLCdO9wq37mdcgIY11tQ5cmmjkqCO2pZHoJtBeHwuTVXB1bQVt99Qz8AsOer4Pv3NqtBDGZZIV3WPI)Xx9c1yWpUUDh6nVTApl1py5ahHC(UbS6(qbXA3Wl9)9Y81KM2uM0wpeQoM2zP0RDBjmbXYg(fXG7iBU99ELlP4GX6P329SZZXqxuromDBH5CmAN7Q2ZLhsMe45Lrk4GUQy)eooNjttnuddpiaBFUfTTTW0alRtfG7wflZffzApelS4)YSEKeCJXlY45JaQMyH5kHBktp91G3a05YR0SD8Cl(Fgcjm5feHsqFvP3Kz(o49)J7PUDv7LVXY3C1BUOZbmw7m9BQHdGlaZiY2tY87KoW9cz(T(Zrc8YrBHJOXtAEkn9TkycTlaenCrrXHOSQZS(936D)7FeUApoTN3GWMxrRM3TqHYEazQjP10QPMwzn4A(iH0UjWBi0wCcvhqm0aCsJA85h9QOEG3AebcMbfe2ttjjgQJ1HJ8OXX7GXX509msxnHlCsH3TwA5vxA5j78Ih9pd
```
### Wago.io Links

- [https://wago.io/TamasTheWarWithinHelper](https://wago.io/TamasTheWarWithinHelper)
- [Myu's Knowledge Points Tracker](https://wago.io/L7lpDrqUO/10)
- [Luxthos WeakAuras](https://www.luxthos.com/)


