# project-Makao

**Sadržaj**
  1. Makao – pravila Igre	
  2. Opis	
  3. Deljenje	
  4. Igra	
  5. Jake karte	
  6. Bodovanje	
  7. Zahtevi	
  
**Makao – pravila Igre**
> Opis

  Makao (Mau mau, Uno) je veoma popularna kartaška igra na prostorima Balkana koja ima relativno laka pravila koja se vrlo            brzo savladaju. Kada jednom savladate pravila Mau Mau-a,  biće vam teško da se okrenete nekoj drugoj kartaškoj igri.

> Deljenje
 
  Igra se sa dva standardna špila od po 52 karte. Igra se u smeru kazaljke na satu. Delilac prvo daje igraču iza sebe da preseče. Ako je presečena karta 'jaka' igrač koji je sekao ima pravo da je zadrži za sebe i da stavi na talon sledeću. Ukoliko su nakon sečenja dve ili tri karte u nizu 'jake' igrač koji je presekao ima pravo da ih zadrži dok ukoliko je i četvrta jaka ona se stavlja na talon licem na gore. Igrač koji seče ne mora da uzme karte za sebe, to je samo njegova odluka. Potom se svakom igraču deli po 6 karata i to po tri u dva kruga. Ostatak špila se ostavlja pored presečene karte odakle će igrači kasnije uzimati karte.

> Igra

  **_Igrači izbacuju karte na talon licem na gore i to, ili istu kartu (isti broj) ili kartu u istom znaku, u odnosu na onu koja je poslednja izbačena na talon - to su odgovarajuće karte za izbacivanje._** Ukoliko nemaju odgovarajuću kartu dužni su da uzmu jednu kartu iz špila. Ako ta karta odgovara kriterijumu od malopre igrač može da je izbaci i red prelazi na sledećeg igrača. Ukoliko ni ona ne odgovara, igrač samo kaže 'Dalje' i red prelazi na sledećeg. Međutim igrač može i namerno da uzme kartu sa špila iako ima kod sebe odgovarajuću kartu za izbacivanje ukoliko želi da taktizira. Pobednik partije je onaj koji prvi izbaci sve karte. Kada igrač ostane sa dve karte u ruci, pre nego što izbaci pretposlednju dužan je da naglas kaže „Makao“ („Mau Mau“). Ukoliko to ne učini a neko od protivnika mu to sugeriše dužan je da po kazni uzme još dve karte iz špila.

> Jake karte

  Jake karte su sledeće:
  - kečevi
  - mala dvojka (dvojka tref)
  - sedmice
  - osmice
  - žandari (pubovi)
  
**Kec** - kada igač izbaci keca ima pravo (mora) da izbaci još jenu odgovarajuću kartu. Ako je ta karta opet kec postupak je isti. Ukoliko igrač po izbacivanju keca kod sebe nema odgovarajuću kartu kojom bi opet odigrao mora da povuče jednu sa špila i ukoliko je ona odgovarajuća može (ne mora ako taktizira) da je baci. Ukoliko ni ona nije odgovarajuća (ili jeste ali igrač taktizira) dužan je da kaže 'Dalje' i sledeći igrač je na potezu.

**Mala dvojka** - ukoliko igrač izbaci malu dvoju igrač pre njega je dužan da povuče 4 karte sa špila.

**Sedmice** - ukoliko igrač izbaci sedmicu, sledeći koji je na potezu je dužan da vuče 2 karte sa špila ukoliko pre toga kod sebe i on nema sedmicu. Ukoliko je ima, može (ne mora) da je izbaci pa onda igrač posle njega mora da vuče 4 karata. Ako i taj igrač izbaci sedmicu onda sledeći vuče 6, itd. sve dok jedan od igrača nema sedmicu kod sebe da odgovri i on vuče sa špila. Napomena: Ako igrač koji vuče 2,4,6.. karata jer kod sebe nema sedmicu i u tom povlačenju sa špila izvuče sedmicu i baci je, sledeći igrač vuče samo 2 karte (prvo kolo je završeno, počinje drugo). Znači, sabiranje sedmica važi sve dok jedan od igrača ne pokupi odgovarajući broj karata sa špila.

**Osmice** - osmicom se preskače sledeći igrač, odnosno ukoliko igrač koji je na potezu baci osmicu, preskače igrača koji je sledeći na potezu (na redu je drugi igrač od njega). Taj drugi igrač naravno takođe može baciti osmicu jer je to odgovarajuća karta i time preskočiti sledećeg igrača.

**Žandari** - žandar menja znak. Jedino za žandare ne važi pravilo odgovarajuće karte za izbacivanje, jer se on može baciti na bilo koju kartu u bilo kom znaku (iako on nije u tom znaku) i time promeniti znak u neki drugi (ukoliko igrač želi može zadržati postojeći znak).

> Bodovanje

  Žandar se boduje sa 25 poena. Ostale 'jake' karte se boduju sa po 10 poena. Sve druge karte se boduju sa onoliko poena koliko na njima piše. Kralj se boduje sa 10 poena. Pobednik partije dobija -40 poena. U slučaju da je poslednja karta pobednika žandar svi poeni se dupliraju. Pobednik nosi -80, ako je igrač ima kralja i peticu umesto 15 nosi 30 poena.

> Zahtevi

  Implementirati opisanu igru tako da podržava isključivo dva igrača. Prilikom implementacije igra mora da implementira interfejse zadate u TIG.AV.Karte.dll. Implementacija ispunjava minimalni uslov ako vraća ispravan potez.
  



  
  > FAZE

          Opis                                                                                           Rok za predaju

Faza 1 

          Implementirati minimalno Alfa-Beta algoritam. Potraga kreće pozivom metode BeginBestMove.      30.11.2018. 23:59
          Najbolji potez mora bti smešten u properti BestMove. Pretraga se završava pozivom metode 
          EndBestMove. Ove metode ne pozivate lokalno, njih isključivo poziva eksterni sistem.

Faza 2 

          Unapređenje algoritma pretrage, upotreba Transpozicionih tabela i sl.                          30.12.2018. 23:59
          VERZIJA IZ FAZE 2 JE ZVANICNA VERZIJA KOJA CE SE TAKMICITI.
          
Faza 3 

          Grafički interfejs za igru jednog igrača i računara.                                           13.01.2019. 23:59
          
          
:exclamation: **Implementacija mora biti imenovana kao broj_indeksa.exe/dll
Npr. 12345.exe ili 12345.dll**

Za vise informacija idi na [Katedru za racunarstvo](https://cs.elfak.ni.ac.rs/nastava/course/view.php?id=110)
