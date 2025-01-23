# __Markdown Cheat Sheet__

Köszönöm a látogatást [Markdown segédlet](https://www.markdownguide.org!)

Ez a leírás gyors áttekintést nyújt az összes Markdown szintaktikai elemről.Nem tud minden esetet lefedni, ezért ha további információra van szüksége ezen elemek bármelyikével kapcsolatban, tekintse meg a referencia útmutatókat [alapvető szintaxis](https://www.markdownguide.org/basic-syntax/) és [bővített szintaxis](https://www.markdownguide.org/extended-syntax/).

# Fejezetcímek
# H1
## H2
### H3
__Félkövér__
**félkövér szöveg**

**Dőlt**

*dőlt szöveg*
### **Bekezdés, sortörés**
Az elektromos áram munkáját a feszültség és az áramerősség értelmezése alapján számíthatjuk ki. **I** erősségű áramnál **t** idő alatt a vezetőn __I*t__ töltés halad át és a vezető végpontjai között **U** nagyságú FESZÜLTSÉG van. A végzett munka a töltésnek és a feszültségnek szorzata: 

**W=U*Q=U*I*t=P*t**

A váltakozó áram teljesítménye (látszólagos teljesítménye):

P=U<sub>eff</sub>*I<sub>eff</sub> (Ha szükséges a képletekbe behelyettesíthetjük Ohm törvényét: __U=R*I__).

 Ha a feszültséget **Volt**ban, az áramerősséget **Amper**ben adjuk meg, akkor az elektromos teljesítményt **Watt**ban kapjuk.
Tehát az átváltás: **1 Watt=1 Volt* 1 Amper**. (1 W=1 V* 1 A)

### Idézet
*Idézet szöveg dőlten*

### Számozás
1. Első elem
2. Második elem
3. Harmadik elem

### Felsorolás
- Első elem
- Második elem
- Harmadik elem

### Kód
`code`

### Vízszintes vonal
------
### Link
[segédlet](https://www.markdownguide.org)

### Kép

![Pingvin](https://www.markdownguide.org/assets/images/tux.png "Pingvin")

### Táblázat

|**Szintakszis**|Leírás|
|------------|--------|
|Fejléc| Cím|
|Bekezdés| Szöveg|
### Táblázat középre

|**Szintakszis**| Leírás|
|---------:|------:|
|Fejléc| Cím|
|Bekezdés |Szöveg|

### Kódblokk
```python
{
  "keresztnev": "János",
  "vezeteknev": "Szabó",
  "eletkor": 25
}
```
### Lábjegyzet

Itt van egy mondat lábjegyzettel.
Ez a lábjegyzet.[^1]

### Definiciós lista
fogalom
fogalom:leírása

### Áthúzás

~~The world is flat.~~

### Feladatlista

Megírni a sajtóközleményt

Frissíteni a weboldalt

Felvenni a kapcsolatot a médiával

### Emoji
Ez olyan vicces! :joy:

(Lásd még [Emoji másolás és beiilesztés](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

[^1]: Ez a lábjegyzet