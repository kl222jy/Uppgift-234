#Anv�ndningsfall

##AF1.1 Skapa projekt
Projektledaren v�ljer att skapa ett projekt, systemet ber projektledaren v�lja namn p� projektet, projektledaren v�ljer namn och systemet skapar sedan ett projekt med detta namn.
Systemet visar sedan en �verblickssida av projektet.

##AF1.2 L�gga till projektmedlemmar
Projektledaren v�ljer att l�gga till projektmedlemmar, systemet fr�gar efter namn. Projektledaren v�ljer ett eller flera namn och medlemmen/medlemmarna l�ggs sedan till i projektet.

##AF1.3 Ta bort projektmedlemmar
Projektledaren v�ljer att ta bort projektmedlemmar, systemet presenterar projektets medlemmar. Projektledaren v�ljer ett eller flera namn och medlemmen/medlemmarna l�ggs sedan till i projektet.

##AF1.4 St�lla in vilken information som �r tillg�nglig f�r kund
Projektledaren v�ljer att st�lla in information som ska vara tillg�nglig f�r kund, systemet presenterar m�jliga alternativ, projektledaren v�ljer bland alternativen, datalagringen sparar valda inst�llningar

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
4. Systemet skapar filen utifr�n dokumenttypens mall och presenterar den  
5. *G� till AF2.2 - Hantera dokument*

**Alternativt scenario:**  
4a. Namnet anv�nds redan  
  4a1. *g� till steg 2*  
  
##AF2.2 - Hantera textbaserat dokument
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
3. Projektmedlemmen l�gger till inneh�ll i dokumentet  
4. Systemet presenterar hj�lp f�r aktuell inmatning  
5. Projektmedlemmen v�ljer att verkst�lla �ndringarna  
6. Systemet sparar inneh�llet  

**Alternativt scenario:**  
*a Projektmedlemmen st�nger f�nstret eller n�got allvarligt fel intr�ffar  
  1. Systemet f�rs�ker spara all data  
  2. *Anv�ndarfallet avbryts*  

3a Projektmedlemmen matar in inneh�ll som inte st�mmer �verens med dokumenttypen och aktuellt avsnitt
  1. Systemet presenterar en varning och ett hj�lpavsnitt  
  2. *g� till steg 2*  
    
3b. Projektmedlemmen skriver f�r utf�rlig information i f�rh�llande till projektets fas, vald dokumenttyp och projektform  
  1. Systemet varnar f�r tendenser mot vattenfallsmodellen  
  2. *g� till steg 2*  

##AF2.3 - L�gga till h�ndelse
En projektmedlem v�ljer att l�gga till en h�ndelse, systemet efterfr�gar namn, datum och beskrivning.

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
