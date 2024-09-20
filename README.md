Feladat: Kocsmai szimuláció többszálúság használatával

Készíts egy Java programot, amely egy kocsmába sörözni menő embereket szimulál. A kocsmának van egy maximális kapacitása, tehát egyszerre csak egy bizonyos számú ember lehet bent. Az emberek a következő szabályok szerint viselkednek:

Belépés a kocsmába: Egy ember akkor tud bemenni a kocsmába, ha bent nincs több ember, mint a kocsma maximális kapacitása. Ha tele van a kocsma, akkor várnia kell.
Bent tartózkodás: Amikor egy ember bejutott, bizonyos időt tölt a kocsmában, ami véletlenszerű (pl. söröznek). Ez az idő egy véletlenszerű érték 1 és 10 másodperc között.
Kilépés: Miután az ember eleget volt bent, kimegy a kocsmából egy időre, mondjuk pisilni. A kilépés után felszabadít egy helyet, és egy másik ember bemehet helyette.
Újra próbálkozik: Miután pisilni ment, egy idő után újra be akar menni a kocsmába.
További követelmények:

Használj Java többszálúságot (pl. Thread vagy Runnable osztályok), hogy az embereket külön szálak szimulálják.
A szinkronizációt kezeld megfelelően, például Semaphore vagy más szinkronizációs eszköz használatával.
A kocsma kapacitása egy konstans érték legyen (például 5 fő).
Legalább 10 ember próbáljon meg bejutni a kocsmába, de egyszerre maximum 5-en lehetnek bent.
Kimenet:

A program logolja, amikor egy ember próbál bejutni, sikeresen bejut, bent sörözik, majd távozik pisilni.
A program folyamatosan figyelje, hogy hány ember van a kocsmában, és kezelje a belépéseket, kilépéseket.
