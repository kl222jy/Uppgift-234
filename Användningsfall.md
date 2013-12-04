#Anv�ndningsfall

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

##AF2.2 - Hantera dokument
**Avgr�nsning:** System  
**Niv�:** Anv�ndarm�l  
**Prim�r akt�r:** Projektmedlem  
**Intressenter:**  
Projektledare: Vill snabbt kunna f� upp en organiserad bas f�r dokumentationen  
Projektmedlem: Vill kunna arbeta med systemet  

**F�rkrav:** Projektmedlemmen m�ste vara autentiserad  
**Efterkrav:** Dokumentet har skapats  
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

2h. Vald dokumenttyp �r anv�ndningsfall  
  1. Systemet applicerar mall f�r anv�ndningsfall  
  2. Anv�ndaren l�gger till inneh�ll i dokumentet  
  3. Systemet presenterar hj�lptext f�r aktuellt avsnitt  
  4. Anv�ndaren v�ljer att avsluta redigeringen  
  5. G� till 4  
  
  2ha. Om vald projekttyp �r iterativ, projektet �r i ett tidigt stadie och kravspecifikationen b�rjar bli v�l utf�rlig  
  ha1. Systemet varnar f�r tendenser mot vattenfallsmodellen  
  ha2. g� till 2h2  

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
