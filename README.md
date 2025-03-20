# World Cup Football

Match fixtures & results for all world cups (1930 to 2022) 
incl. goal scorers, lineups, penalty shootouts, sent offs, and more
using the Football.TXT format.

Example - [worldcup/2022_worldcup.txt](worldcup/2022_worldcup.txt):


```
» Final
Sun Dec/18 @ Lusail Stadium › Lusail, Qatar
  Argentina v France  3-3 [aet; 4-2 on pens]
    Lionel Messi 23'(p) Ángel Di María 36' Lionel Messi 108';
    Kylian Mbappé 80'(p) Kylian Mbappé 81' Kylian Mbappé 118'(p)

Argentina: Emiliano Martínez, Nicolás Tagliafico (120+1' Paulo Dybala), 
   Cristian Romero, Nicolás Otamendi, 
   Nahuel Molina (91' Gonzalo Montiel), 
   Rodrigo De Paul (102' Leandro Paredes), 
   Alexis Mac Allister (116' Germán Pezzella), Enzo Fernández, 
   Julián Álvarez (102' Lautaro Martínez), Lionel Messi, 
   Ángel Di María (64' Marcos Acuña)
France: Hugo Lloris, Raphaël Varane (113' Ibrahima Konaté), 
   Jules Koundé (120+1' Axel Disasi), Dayot Upamecano, 
   Théo Hernandez (71' Kingsley Coman), 
   Antoine Griezmann (71' Eduardo Camavinga), Aurélien Tchouaméni, 
   Adrien Rabiot (96' Youssouf Fofana), 
   Olivier Giroud (41' Marcus Thuram), Kylian Mbappé, 
   Ousmane Dembélé (41' Randal Kolo Muani)

Penalties: Lionel Messi, Paulo Dybala, Leandro Paredes, Gonzalo Montiel;
           Kylian Mbappé, Kingsley Coman (X), Aurélien Tchouaméni (X), Randal Kolo Muani
```



## Bonus - Tips & Tricks

Tip - You can use the [`fbtxt2json` command-line tool](https://github.com/sportdb/footty/tree/master/fbtxt2json) to convert any file in the Football.TXT format to JSON. 

Let's try to convert the World Cup 2020
in the Football.TXT format (see [`worldcup/2022_worldcup.txt`](https://github.com/openfootball/worldcup.more/blob/master/worldcup/2022_worldcup.txt)) to JSON:

```
$ fbtxt2json worldcup/2022_worldcup.txt 
```








---

NOTE - For the "original" (football.db) and alternative world cup dataset
using the Football.TXT format, 
see [openfootball/worldcup](https://github.com/openfootball/worldcup).



