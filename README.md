# Kytara – trénink stupnic

Webová aplikace (PWA) pro Android tablet Galaxy Tab S11: hmatník kytary ve skutečné velikosti
(Schecter PT SLS Evil Twin – menzura 648 mm), na kterém se trénuje poloha tónů ve stupnicích.

**Spuštění:** https://mjandlik.github.io/kytara/

- tablet na šířku, texty čitelné od levé hrany (od brnkací oblasti)
- režim 1 ruka / 2 ruce, slide, pull-off, hammer-on
- moll pentatonika + blues, boxy E D C A G, obrys boxu přes krajní tóny
- mapa krku, metronom, nastavení ladění, menzury a kalibrace velikosti

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
- bez zvuku

Verze: `kviz.html` je vždy aktuální, `kviz_vNN.html` jsou uložené jednotlivé verze.
