# Étteremek Borravaló Elemzése

## Projekt Leírása

Az éttermi borravalók adatainak elemzésével egy olyan adatvizualizációs portfóliót hoztam létre, amely különböző szempontok szerint mutat be érdekes összefüggéseket. A vizualizációk célja, hogy mélyebb betekintést nyújtsanak az éttermi borravalók és számlák alakulásába, és segítsenek az étterem tulajdonosoknak és menedzsereknek javítani szolgáltatásaikat és növelni bevételeiket. Az adatokat valós éttermi tranzakciókból gyűjtötték, és a projekt különösen hasznos lehet az éttermi működés optimalizálásában.

## Használt Adatok

Az elemzéshez használt adatok valós éttermi tranzakciókból származnak, és többek között tartalmazzák:
- Számla összege
- Borravaló összege
- Vendégek neme
- Dohányzási szokások
- Étkezés ideje (ebéd vagy vacsora)
- A hét napja

Ezek az adatok lehetővé teszik, hogy különböző szempontok szerint vizsgáljuk meg az éttermi költési szokásokat és a borravalók alakulását.

## Diagramok

### 1. Ábra: Összesített tippek időszak szerint (Oszlopdiagram)

Az oszlopdiagram az összesített számla összegeit mutatja a hét különböző napjain.

![1. Ábra](./images/chart1.png)

Az adatokból kiderül, hogy mely napokon keletkeznek a legmagasabb számlaösszegek. Ez az információ hasznos lehet az éttermek számára a forgalmas napok azonosítására, lehetővé téve a személyzet és a készletek megfelelő tervezését. A hétvégék (szombat és vasárnap) általában magasabb számlaösszegeket eredményeznek, ami arra utal, hogy ezek a napok a legforgalmasabbak az étterem számára.

### 2. Ábra: Nemek közötti különbségek a tippekben (Kördiagram)

A kördiagram a borravalók eloszlását mutatja férfiak és nők között.

![2. Ábra](./images/chart2.png)

Az eredmények alapján látható, hogy mindkét nem esetében hasonló a borravalók eloszlása, de a férfiak esetenként hajlamosabbak magasabb borravalót adni.

### 3. Ábra: Tippek és számlaösszegek közötti kapcsolat (Pontdiagram)

A pontdiagram a tippek összegét mutatja a számla összegének függvényében.

![3. Ábra](./images/chart3.png)

Látható, hogy a számla összegének növekedésével általában növekszik a borravaló összege is.

### 4. Ábra: Átlagos borravaló időszak szerint (Sávdiagram)

A sávdiagram az átlagos borravalót mutatja különböző időszakokban (ebéd és vacsora).

![4. Ábra](./images/chart4.png)

Látható, hogy a vacsoraidőszakban általában magasabb borravalók fordulnak elő, míg az ebédidőszakban alacsonyabbak.

### 5. Ábra: Átlagos borravaló dohányzó és nem dohányzó vendégek esetén (Kördiagram)

A kördiagram az átlagos borravalót mutatja dohányzó és nem dohányzó vendégek esetén.

![5. Ábra](./images/chart5.png)

A dohányzó vendégek által adott borravalók kissé alacsonyabbak a nem dohányzó vendégekéhez képest.

### 6. Ábra: Napi átlagos borravaló méret szerinti eloszlás (Hőtérkép)

A hőtérkép a napi átlagos borravalót mutatja különböző számlaméretek szerint.

![6. Ábra](./images/chart6.png)

A nagyobb számlaméretekhez magasabb átlagos borravalók társulnak, különösen a hétvégén.

## Következtetések

Az elemzés során feltárt összefüggések értékes betekintést nyújtanak az éttermek működésébe, segítve a szolgáltatások célzott fejlesztését és a bevételek növelését. A projekt skálázható és automatizálható, így további adatdimenziók és vizualizációk bevezetésével bővíthető, ami még mélyebb és részletesebb elemzéseket tesz lehetővé.


