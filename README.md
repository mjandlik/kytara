# Kytara – trénink stupnic

Webová aplikace (PWA) pro Android tablet Galaxy Tab S11: hmatník kytary ve skutečné velikosti
(Schecter PT SLS Evil Twin – menzura 648 mm), na kterém se trénuje poloha tónů ve stupnicích.

**Spuštění:** https://mjandlik.github.io/kytara/

- tablet na šířku, texty čitelné od levé hrany (od brnkací oblasti)
- režim 1 ruka / 2 ruce, slide, pull-off, hammer-on
- moll pentatonika + blues, boxy E D C A G, obrys boxu přes krajní tóny
- mapa krku, metronom, nastavení ladění, menzury a kalibrace velikosti
- v Nastavení odkazy na ostatní stránky (mapa, kvíz na boxy, tóny na hmatníku)

Verze: `index.html` je vždy aktuální, `kytara_vNN.html` jsou uložené jednotlivé verze.

## Mapa pentatoniky

**Spuštění:** https://mjandlik.github.io/kytara/mapa.html

- jen zobrazení, bez zvuku; telefon nebo tablet na výšku
- celý krk 0–24, nultý pražec nahoře, krk uprostřed
- krk vpravo; vlevo nahoře tlačítka ve dvou sloupcích: tónina, boxy E D C A G (víc najednou), bluesové tóny zap/vyp, tóny všechny / jen v boxech, akord
- pod tlačítky teorie o intervalech (zobrazí se v režimu Akord 1 b3 5)
- základní tóny s písmenem, písmeno boxu vpravo od krku v barvě rámečku
- značky na hmatníku (3, 5, 7, 9, 12, 15, 17, 19, 21, 24) a čísla těchto pražců vlevo od krku
- tlačítko Akord (vyp / 1 b3 5 / názvy): tóny mollového akordu tóniny ve vybraných boxech jako kroužek v barvě boxu s popiskem vpravo nahoře; plný kroužek = hmat akordu (tvar Em, Dm, Cm, Am, Gm), čárkovaný = jiný tón akordu v boxu
- tlačítko Stránky: odkazy na trenažér, kvíz na boxy a tóny na hmatníku, pod nimi číslo verze

Verze: `mapa.html` je vždy aktuální, `mapa_vNN.html` jsou uložené jednotlivé verze.

## Kvíz na boxy

**Spuštění:** https://mjandlik.github.io/kytara/kviz.html

- kartičky na zkoušení boxů mollové pentatoniky (6 strun, bez bluesových tónů), tvary E D C A G
- box přes celou obrazovku: jen pražce daného boxu, stejně široké, bez čísel pražců a bez tóniny; tečky na všech tónech boxu ve stejné barvě
- telefon na výšku i tablet na šířku, všude stejný pohled: krk vodorovně, hlava vlevo, tlustá struna E dole
- na výšku má krk 60 % dostupné výšky a je svisle uprostřed, aby měl proporce kytary
- odpověď: ťuknout na tečky se základními tóny (reaguje tečka a úzký lem kolem ní) a vybrat tvar; Zkontrolovat ukáže správné řešení, tvar a základní tóny se hodnotí zvlášť
- kolo má 10 kartiček, v každém kole všech pět tvarů; tvary s chybami se vracejí častěji; pokrok se ukládá v zařízení
- kartičky jdou náhodně a nečíslují se (nahoře je jen počet správných); tlačítka s písmeny tvarů se u každé kartičky zamíchají
- tlačítko Ukázat odpověď odhalí tvar i základní tóny bez odpovídání, počítá se jako chyba
- druhý režim **Bez hmatníku**: otázky jen textem, odpověď tlačítky; v menu tři volby: Box → struny, Struny → boxy, Mix obou
  - Box → struny: na kterých strunách má box základní tóny (tlačítka E A D G H e, E = tlustá, e = tenká)
  - Struny → boxy: které boxy mají základní tón na uvedených strunách; otázka uvede náhodně 1 až všechny struny boxu a označují se všechny boxy, které sedí
  - tlačítka Ukázat box (bez základních tónů) a Box i základní tóny, obě se počítají jako chyba; po odpovědi se box ukáže vždy
  - úspěšnost se vede zvlášť pro oba typy otázek
- v menu odkazy na trenažér, mapu a tóny na hmatníku
- bez zvuku

Verze: `kviz.html` je vždy aktuální, `kviz_vNN.html` jsou uložené jednotlivé verze.

## Tóny na hmatníku

**Spuštění:** https://mjandlik.github.io/kytara/tony.html

- kvíz na polohu tónů na krku: zadání je jeden tón, na krku se označí na všech šesti strunách (struna + pražec)
- všech 12 tónů, názvy jako v mapě: C, C#, D, Eb, E, F, F#, G, Ab, A, B, H
- krk je jedna oktáva: pražce 1–12, bez prázdných strun; v tomto rozsahu je každý tón na každé struně právě jednou
- telefon na výšku: krk přes celou výšku, hlava nahoře, tělo dole, tlustá struna E vlevo; pražce se k tělu zužují jako na skutečném krku
- značky na hmatníku (3, 5, 7, 9, 12) a čísla těchto pražců vlevo od krku, názvy strun u hlavy
- vlevo od krku zadání (tón), nad ním menu, celá obrazovka a počet správných, pod ním tlačítka Ukázat odpověď a Zkontrolovat
- dotyk: reaguje celé políčko struna × pražec; na struně je nejvýš jedna značka, ťuknutí na jiný pražec ji přesune, ťuknutí na značku ji zruší
- Zkontrolovat jde dát kdykoli (stačí jedna značka); neoznačená nebo špatně označená struna je chyba; po kontrole se ukáže správné řešení
- tlačítko Ukázat odpověď odhalí polohy bez odpovídání, počítá se jako chyba
- kolo: všech 12 tónů v náhodném pořadí; tón určený špatně se v kole vrátí znovu (nejdřív po dvou jiných otázkách, nejvýš dvakrát)
- otázky se nečíslují (je vidět jen počet správných); menu se statistikou po tónech, výsledek kola, pokrok se ukládá v zařízení
- v menu odkazy na trenažér, mapu a kvíz na boxy a číslo verze
- bez zvuku

Verze: `tony.html` je vždy aktuální, `tony_vNN.html` jsou uložené jednotlivé verze.
