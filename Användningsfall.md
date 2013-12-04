#Användningsfall

##AF1.1 Skapa projekt
Projektledaren väljer att skapa ett projekt, systemet ber projektledaren välja namn på projektet, projektledaren väljer namn och systemet skapar sedan ett projekt med detta namn.
Systemet visar sedan en överblickssida av projektet.

##AF1.2 Lägga till projektmedlemmar
Projektledaren väljer att lägga till projektmedlemmar, systemet frågar efter namn. Projektledaren väljer ett eller flera namn och medlemmen/medlemmarna läggs sedan till i projektet.

##AF1.3 Ta bort projektmedlemmar
Projektledaren väljer att ta bort projektmedlemmar, systemet presenterar projektets medlemmar. Projektledaren väljer ett eller flera namn och medlemmen/medlemmarna läggs sedan till i projektet.

##AF1.4 Ställa in vilken information som är tillgänglig för kund
Projektledaren väljer att ställa in information som ska vara tillgänglig för kund, systemet presenterar möjliga alternativ, projektledaren väljer ibland alternativen, datalagringen sparar valda inställningar

##AF2.1 - Lägga till dokument
**Avgränsning:** System  
**Nivå:** Användarmål  
**Primär aktör:** Projektmedlem  
**Intressenter:**  
Projektledare: Vill snabbt kunna få upp en organiserad bas för dokumentationen  
Projektmedlem: Vill kunna arbeta med systemet  

**Förkrav:** Projektmedlemmen måste vara autentiserad  
**Efterkrav:** Dokumentet har skapats  
**Huvudscenario:**  
1. Projektmedlemmen väljer att skapa ett nytt dokument  
2. Systemet frågar efter namn och dokumenttyp  
3. Projektmedlemmen väljer namn  
4. Systemet skapar filen och presenterar den  
5. Gå till AF2.2 - Hantera dokument

**Alternativt scenario:**  
4a. Namnet används redan  
  4a1. gå till steg 2  

##AF2.2 - Hantera dokument
**Avgränsning:** System  
**Nivå:** Användarmål  
**Primär aktör:** Projektmedlem  
**Intressenter:**  
Projektledare: Vill snabbt kunna få upp en organiserad bas för dokumentationen  
Projektmedlem: Vill kunna arbeta med systemet  

**Förkrav:** Projektmedlemmen måste vara autentiserad  
**Efterkrav:** Dokumentet har skapats  
**Huvudscenario:**  
1. Projektmedlemmen väljer hantera ett dokument  
2. Systemet presenterar dokumentet 
3. Användaren lägger till innehåll i dokumentet
4. Datalagringen sparar dokumentet och dess innehåll

**Alternativt scenario:**  
2a. Vald dokumenttyp är vision  
  1. Systemet applicerar mall för vision  
  2. Användaren lägger till innehåll i dokumentet  
  3. Systemet presenterar hjälptext för aktuellt avsnitt  
  4. Användaren väljer att avsluta redigeringen  
  5. Gå till 4  

2b. Vald dokumenttyp är kravspecifikation  
  1. Systemet applicerar mall för kravspecifikation  
  2. Användaren lägger till innehåll i dokumentet  
  3. Systemet presenterar hjälptext för aktuellt avsnitt  
  4. Användaren väljer att avsluta redigeringen  
  5. Gå till 4  

2c. Vald dokumenttyp är krav  
  1. Systemet applicerar mall för krav  
  2. Användaren lägger till innehåll i dokumentet  
  3. Systemet presenterar hjälptext för aktuellt avsnitt  
  4. Användaren väljer att avsluta redigeringen  
  5. Gå till 4  

2d. Vald dokumenttyp är projektplan  
  1. Systemet applicerar mall för projektplan  
  2. Användaren lägger till innehåll i dokumentet  
  3. Systemet presenterar hjälptext för aktuellt avsnitt  
  4. Användaren väljer att avsluta redigeringen  
  5. Gå till 4  

2e. Vald dokumenttyp är iterationsplan  
  1. Systemet applicerar mall för iterationsplan  
  2. Användaren lägger till innehåll i dokumentet  
  3. Systemet presenterar hjälptext för aktuellt avsnitt  
  4. Användaren väljer att avsluta redigeringen  
  5. Gå till 4  

2f. Vald dokumenttyp är ordlista  
  1. Systemet applicerar mall för ordlista  
  2. Användaren lägger till innehåll i dokumentet  
  3. Systemet presenterar hjälptext för aktuellt avsnitt  
  4. Användaren väljer att avsluta redigeringen  
  5. Gå till 4  

2g. Vald dokumenttyp är testspecifikation  
  1. Systemet applicerar mall för testspecifikation  
  2. Användaren lägger till innehåll i dokumentet  
  3. Systemet presenterar hjälptext för aktuellt avsnitt  
  4. Användaren väljer att avsluta redigeringen  
  5. Gå till 4  

2h. Vald dokumenttyp är testrapport  
  1. Systemet applicerar mall för testrapport  
  2. Användaren lägger till innehåll i dokumentet  
  3. Systemet presenterar hjälptext för aktuellt avsnitt  
  4. Användaren väljer att avsluta redigeringen  
  5. Gå till 4  

2h. Vald dokumenttyp är användningsfall  
  1. Systemet applicerar mall för användningsfall  
  2. Användaren lägger till innehåll i dokumentet  
  3. Systemet presenterar hjälptext för aktuellt avsnitt  
  4. Användaren väljer att avsluta redigeringen  
  5. Gå till 4  
  
  2ha. Om vald projekttyp är iterativ, projektet är i ett tidigt stadie och kravspecifikationen börjar bli väl utförlig  
  ha1. Systemet varnar för tendenser mot vattenfallsmodellen  
  ha2. gå till 2h2  

##AF2.3 - Lägga till händelse
En projektmedlem väljer att lägga till en händelse, systemet efterfrågar namn, datum och beskrivning. D

##AF2.4 - Kommunicera med enskild projektmedlem
En projektmedlem väljer att skicka ett meddelande till en specifik medlem, om användaren är inloggad presenteras meddelandet för denna annars visas det vid nästa inloggning

##AF2.5 - Kommunicera med samtliga projektmedlemmar
En projektmedlem väljer att skicka ett meddelande till samtliga medlemmar, systemet presenterar meddelandet för samtliga användare

##AF2.6 - Lägga till idé
En projektmedlem väljer att lägga till en idé, systemet lagrar denna och presenterar tillsammans med resterande idéer

##AF2.7 - Ta bort dokument  
En projektmedlem väljer att ta bort ett dokument, om ingen arbetar med dokumentet exkluderar systemet denna från systemet och mellanlagrar den i ett arkiv

##AF2.8 - Ta bort idé  
En projektmedlem väljer att ta bort en idé, systemet tar bort idén

##AF2.9 - Ta bort händelse  
En projektmedlem väljer att ta bort en händelse, systemet tar bort händelsen
