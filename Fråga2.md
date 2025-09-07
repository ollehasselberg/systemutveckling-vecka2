**2. Vad är ett Git-commit och varför är det viktigt?**

När man arbetar flera i ett projekt är det viktigt att ha olika
branches. Detta är för att undvika oönskade ändringar som ännu inte
granskats/testats av teamet. När man ändrat i koden och gjort en
*commit* så kommer ditt arbete sparas som en milstolpe i projektet. Du
kan sedan gå tillbaka och kolla tidigare commits för att så att säga
"backa i tiden" och se när och var dessa commits har gjorts. På så sätt
kan du lättare back-tracka i projektet om du stöter på problem senare.

**Exempel:** Vi jobbar i ett team som ska skapa en hemsida och vi vill
lägga till en funktion/knapp på hemsidan. Någon lägger till en knapp i
koden och gör en commit med meddelandet "Added a button to the home
page".

Om det senare skulle visa sig bli problem med den knappen, till exempel
att den inte funkar i mobilversion eller appversion, så kan vi tack vare
*commit-funktionen* gå tillbaka i projektet och leta upp när den
ändringen gjordes och börja felsöka.