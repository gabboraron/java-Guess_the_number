# java-Guess_the_number
# Feladat (A GTNGame osztály)
- Az osztály a jól ismert (“Guess the number”) számkitalálos játékot valósítja meg.
- A főprogram parancssori argumentumként egy pozitív maxNum számot vár a felhasználótól, ami a megoldás felső korlátját jelenti majd.
- Amennyiben a felhasználó megfelelő számú argumentumot ad meg, vagy nem egy pozitív számot ad, a program írjon ki üzenetet.
- Ezután a program “gondoljon” egy számra 1 és maxNum között (használható a java.util.Random osztály nextInt metódusa).
- Ezt követően ciklusban kérjen be számokat a felhasználótól.
- - Amennyiben a felhasználó eltalálja melyik számra gondolt a program, a program lépjen ki a ciklusból és írjon ki gratuláló üzenetet.
- - Amennyiben a felhasználó nem egy pozitív számot ad, írjon ki üzenetet, majd kérjen be újra számot.
- - Amennyiben a felhasználó valid számot ad meg, de nem azt, amelyikre gondolt a program, írja ki, hogy kisebb vagy nagyobb volt a tipp a megoldásnál.
- Rajzold meg az osztály vezérlésfolyam-gráfját.
- Teszteld fehérdoboz-teszteléssel a GTNGame osztályt.
- Törekedj a következő metrikák maximalizálására:
- - Metódusok lefedettsége
- - Elágazások lefedettsége (döntési pontok mindkét ága)
- - Feltételek lefedettsége (részfeltételek a logikai kifejezésekben)
- - Ciklusok lefedettsége (ciklusok, 0, 1, 2 iterációra)
