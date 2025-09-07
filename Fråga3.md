# Pull requests, branches & merge

När man jobbar som ett team i GitHub har man en *main* branch där själva projektet sparas online. Härifrån kan alla delaktiga spara filer lokalt, samt ladda upp från sin dator (lokalt) och lägga det online (GitHub). Utöver *main*-branchen kan man också skapa nya branches, om man till exempel jobbar på en specifik feature för projektet. I denna branch kan man göra ändringar i koden utan att det påverkar materialet som finns i *main*.
Detta är otroligt viktigt för att säkerställa att man inte gör oönskade ändringar som påverkar hela projektet, utan man kan testa, iterera och göra ändringar som **SEDAN** uppdateras i *main-branch.*

Om man gjort en ändring i en branch (till exempel en ny feature) kan det vara bra att någon annan i teamet går igenom, felsöker och testar dina ändringar, då kan man göra en så kallad *pull request*.  
**Exempel:** Jag har gjort ändringar för en ny funtkion i ett projekt, men behöver att någon granskar och testar min kod. Då kan jag göra en pull request där jag anger vilka/vem jag vill ska testa koden, och den kommer då att bli synlig för dessa utvalda personer.
När personerna testat och godkänt ändringarna kan jag *pusha* dem till main så att det sparas i projektet.

Rent praktiskt så ansöker jag om att merge:a ändringar **(commits)** FRÅN min branch TILL *main.*
