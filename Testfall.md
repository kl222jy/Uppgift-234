#Testfall
<!--
	##AF1.1 Skapa projekt
	Projektledaren v�ljer att skapa ett projekt, systemet ber projektledaren v�lja namn p� projektet, projektledaren v�ljer namn och systemet skapar sedan ett projekt med detta namn.
	Systemet visar sedan en �verblickssida av projektet.

	##AF1.2 L�gga till projektmedlemmar
	Projektledaren v�ljer att l�gga till projektmedlemmar, systemet fr�gar efter namn. Projektledaren v�ljer ett eller flera namn och medlemmen/medlemmarna l�ggs sedan till i projektet.

	##AF1.3 Ta bort projektmedlemmar
	Projektledaren v�ljer att ta bort projektmedlemmar, systemet presenterar projektets medlemmar. Projektledaren v�ljer ett eller flera namn och medlemmen/medlemmarna l�ggs sedan till i projektet.

	##AF1.4 St�lla in vilken information som �r tillg�nglig f�r kund
	Projektledaren v�ljer att st�lla in information som ska vara tillg�nglig f�r kund, systemet presenterar m�jliga alternativ, projektledaren v�ljer ibland alternativen, datalagringen sparar valda inst�llningar

	##AF2.1 - L�gga till dokument
	**Avgr�nsning:** System  
	**Niv�:** Anv�ndarm�l  
	**Prim�r akt�r:** Projektmedlem  
	**Intressenter:**  
	Projektledare: Vill snabbt kunna f� upp en organiserad bas f�r dokumentationen  
	Projektmedlem: Vill kunna arbeta med systemet  

	**F�rkrav:** Projektmedlemmen m�ste vara autentiserad  
	**Efterkrav:** Dokumentet har skapats  
	**Huvudscenario:**  
	1. Projektmedlemmen v�ljer att skapa ett nytt dokument  
	2. Systemet fr�gar efter namn och dokumenttyp  
	3. Projektmedlemmen v�ljer namn  
	4. Systemet skapar filen och presenterar den  
	5. G� till AF2.2 - Hantera dokument

	**Alternativt scenario:**  
	4a. Namnet anv�nds redan  
	  4a1. g� till steg 2  
	  
	  
	  
	  
	  
	  
	  
	  
	  
	  
	  
	  
	  
	  
-->
##TF AF2.2 - Hantera textbaserade dokument
M�let f�r detta testfall �r att unders�ka att det g�r att hantera ett dokument.

###F�rkrav
Inloggad, projekt skapat, dokumentet "vision"
###Efterkrav
Kontrollera att inneh�llet sparats korrekt

###Scenario
1. "�verblick":"�ppna dokument":"vision"  
2. Systemet presenterar dokumentet "vision" av typen "vision"  
3. L�gg till detta projektets vision i dokumentet  
4. Systemet presenterar hj�lp f�r vardera avsnitt  
5. Spara dokumentet och avsluta  
6. Systemet presenterar "�verblick"  

3a. Skriv in information som inte st�mmer �verens med ett avsnitt
  1. Kontrollera att varning och hj�lp visas  


3b. St�ng f�nstret under p�g�ende inmatning
  1. Kontrollera att den inmatade informationen finns kvar
  2. Spara och avsluta
  3. Kontrollera att den inmatade informationen sparats
  
  2a. Avbryt dokumentredigeringen  
  <p>1. Kontrollera att ingen av �ndringarna sparats</p>


5a. V�lj att avbryta redigeringen av dokumentet
  1. Kontrollera att �ndringarna inte har sparats  


<!--















1a. "�verblick":"�ppna dokument":"test-vision"  
  1. Dokumentet "test-vision" av typen "vision" presenteras  
  2. L�gg till testdata i form av lorem ipsum paragrafer p� samtliga avsnitt  
  3. g� till steg 4  

1b. "�verblick":"�ppna dokument":"test-kravspecifikation"  
  1. Dokumentet "test-kravspecifikation" av typen "kravspecifikation" presenteras  
  2. L�gg till testdata i form av lorem ipsum paragrafer p� samtliga avsnitt  
  3. g� till steg 4  

1c. "�verblick":"�ppna dokument":"test-krav"  
  1. Dokumentet "test-krav" av typen "krav" presenteras  
  2. L�gg till testdata i n�gra celler 
  3. g� till steg 4  

1d. "�verblick":"�ppna dokument":"test-projektplan"  
  1. Dokumentet "test-projektplan" av typen "projektplan" presenteras  
  2. L�gg till testdata i form av lorem ipsum paragrafer p� samtliga avsnitt  
  3. g� till steg 4  

1e. "�verblick":"�ppna dokument":"test-iterationsplan"  
  1. Dokumentet "test-iterationsplan" av typen "iterationsplan" presenteras  
  2. L�gg till testdata i form av lorem ipsum paragrafer p� samtliga avsnitt  
  3. g� till steg 4  

1f. "�verblick":"�ppna dokument":"test-ordlista"  
  1. Dokumentet "test-ordlista" av typen "ordlista" presenteras  
  2. L�gg till n�gra ord och definitioner i ordlistan  
  3. g� till steg 4  

1g. "�verblick":"�ppna dokument":"test-testspecifikation"  
  1. Dokumentet "test-testspecifikation" av typen "testspecifikation" presenteras  
  2. L�gg till testdata i form av lorem ipsum paragrafer p� samtliga avsnitt  
  3. g� till steg 4  

1h. "�verblick":"�ppna dokument":"test-testrapport"  
  1. Dokumentet "test-testrapport" av typen "testrapport" presenteras  
  2. L�gg till testdata i form av lorem ipsum paragrafer p� samtliga avsnitt  
  3. g� till steg 4  

1i. "�verblick":"�ppna dokument":"test-anv�ndningsfall"  
  1. Dokumentet "test-anv�ndningsfall" av typen "anv�ndningsfall" presenteras  
  2. L�gg till n�gra korta anv�ndningsfall  
  3. g� till steg 4  






 ##AF2.2 - Hantera dokument
**Avgr�nsning:** System  
**Niv�:** Anv�ndarm�l  
**Prim�r akt�r:** Projektmedlem  
**Intressenter:**  
Projektledare: Vill snabbt kunna f� upp en organiserad bas f�r dokumentationen  
Projektmedlem: Vill kunna arbeta med systemet  

**F�rkrav:** Projektmedlemmen m�ste vara autentiserad  
**Efterkrav:** Dokumentet har sparats  
**Huvudscenario:**  
1. Projektmedlemmen v�ljer hantera ett dokument  
2. Systemet presenterar dokumentet 
3. Anv�ndaren l�gger till inneh�ll i dokumentet
4. Datalagringen sparar dokumentet och dess inneh�ll

**Alternativt scenario:**  
2a. Vald dokumenttyp �r vision  
  1. Systemet applicerar mall f�r vision  
  2. Anv�ndaren l�gger till inneh�ll i dokumentet  
  3. Systemet presenterar hj�lptext f�r aktuellt avsnitt  
  4. Anv�ndaren v�ljer att avsluta redigeringen  
  5. G� till 4  

2b. Vald dokumenttyp �r kravspecifikation  
  1. Systemet applicerar mall f�r kravspecifikation  
  2. Anv�ndaren l�gger till inneh�ll i dokumentet  
  3. Systemet presenterar hj�lptext f�r aktuellt avsnitt  
  4. Anv�ndaren v�ljer att avsluta redigeringen  
  5. G� till 4  
  
  2ba. Om vald projekttyp �r iterativ, projektet �r i ett tidigt stadie och kravspecifikationen b�rjar bli v�l utf�rlig  
  ba1. Systemet varnar f�r tendenser mot vattenfallsmodellen  
  ba2. g� till 2b2  

2c. Vald dokumenttyp �r krav  
  1. Systemet applicerar mall f�r krav  
  2. Anv�ndaren l�gger till inneh�ll i dokumentet  
  3. Systemet presenterar hj�lptext f�r aktuellt avsnitt  
  4. Anv�ndaren v�ljer att avsluta redigeringen  
  5. G� till 4  

2d. Vald dokumenttyp �r projektplan  
  1. Systemet applicerar mall f�r projektplan  
  2. Anv�ndaren l�gger till inneh�ll i dokumentet  
  3. Systemet presenterar hj�lptext f�r aktuellt avsnitt  
  4. Anv�ndaren v�ljer att avsluta redigeringen  
  5. G� till 4  

2e. Vald dokumenttyp �r iterationsplan  
  1. Systemet applicerar mall f�r iterationsplan  
  2. Anv�ndaren l�gger till inneh�ll i dokumentet  
  3. Systemet presenterar hj�lptext f�r aktuellt avsnitt  
  4. Anv�ndaren v�ljer att avsluta redigeringen  
  5. G� till 4  

2f. Vald dokumenttyp �r ordlista  
  1. Systemet applicerar mall f�r ordlista  
  2. Anv�ndaren l�gger till inneh�ll i dokumentet  
  3. Systemet presenterar hj�lptext f�r aktuellt avsnitt  
  4. Anv�ndaren v�ljer att avsluta redigeringen  
  5. G� till 4  

2g. Vald dokumenttyp �r testspecifikation  
  1. Systemet applicerar mall f�r testspecifikation  
  2. Anv�ndaren l�gger till inneh�ll i dokumentet  
  3. Systemet presenterar hj�lptext f�r aktuellt avsnitt  
  4. Anv�ndaren v�ljer att avsluta redigeringen  
  5. G� till 4  

2h. Vald dokumenttyp �r testrapport  
  1. Systemet applicerar mall f�r testrapport  
  2. Anv�ndaren l�gger till inneh�ll i dokumentet  
  3. Systemet presenterar hj�lptext f�r aktuellt avsnitt  
  4. Anv�ndaren v�ljer att avsluta redigeringen  
  5. G� till 4  
  
##AF2.3 - L�gga till h�ndelse
En projektmedlem v�ljer att l�gga till en h�ndelse, systemet efterfr�gar namn, datum och beskrivning. D

##AF2.4 - Kommunicera med enskild projektmedlem
En projektmedlem v�ljer att skicka ett meddelande till en specifik medlem, om anv�ndaren �r inloggad presenteras meddelandet f�r denna annars visas det vid n�sta inloggning

##AF2.5 - Kommunicera med samtliga projektmedlemmar
En projektmedlem v�ljer att skicka ett meddelande till samtliga medlemmar, systemet presenterar meddelandet f�r samtliga anv�ndare

##AF2.6 - L�gga till id�
En projektmedlem v�ljer att l�gga till en id�, systemet lagrar denna och presenterar tillsammans med resterande id�er

##AF2.7 - Ta bort dokument  
En projektmedlem v�ljer att ta bort ett dokument, om ingen arbetar med dokumentet exkluderar systemet denna fr�n systemet och mellanlagrar den i ett arkiv

##AF2.8 - Ta bort id�  
En projektmedlem v�ljer att ta bort en id�, systemet tar bort id�n

##AF2.9 - Ta bort h�ndelse  
En projektmedlem v�ljer att ta bort en h�ndelse, systemet tar bort h�ndelsen

##AF2.10 - Hantera tabellbaserat dokument  
AF2.2 med l�mpliga variationer

##AF2.11 - Hantera listbaserat dokument  
AF2.2 med l�mpliga variationer
-->
