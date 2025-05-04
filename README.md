Maak een TCP-server "Hoger/Lager" die met integers in network-byte-order werkt.

Vraag 1
TCP SOCKETS correct : het aanmaken, verbinden en opruimen van sockets
Vraag 2
CLIENT to SERVER COMMUNICATION correct : TCP-client stuurt correcte integers in network-byte-order en worden juist ontvangen door TCP-server en vergeleken met het te raden getal dat genereert wordt tijdens connectie (tussen 0 en 1 000 000)
Vraag 3
SERVER to CLIENT COMMUNICATION correct : elke gok wordt beantwoord met "Hoger", "Lager" of "Correct" afhankelijk van het te raden getal en de gok.
Vraag 4
CLOSING CONNECTION correct : de TCP-server sluit de connectie als eerste indien de gok "Correct" was, maar ook de TCP-client kan elk moment de connectie sluiten om te stoppen met spelen. Alle handlers en geheugen wordt proper opgeruimd.
Vraag 5
CONTINOUS correct : TCP-server en TCP-client moeten niet herstarten om een volgende ronde te kunnen spelen en er wordt een nieuw random nummer gekozen.
Vraag 6
MULTIPLE CLIENTS correct : TCP-server kan meerdere simultane TCP-clients tegelijk bedienen met elk hun getal.
Vraag 7
MULTIPLE CLIENTS clean & correct : er is geen nutteloze overhead bij meerdere clients, er wordt gewerkt met Synchronous I/O Multiplexing, i.e. poll() of select()
Vraag 8
CLEAN CODE : (Eens alles juist werkt) TCP-server en TCP-client code zijn volgens industriestandaard geschreven in handelbare functies en geen globale variabelen.
Vraag 9
EXTRA : (Eens alles juist werkt) bijvoorbeeld : high-score met IP en poort, logging to files met IP en poort, gaming AI-client, ...
Vraag 10
PROFESSIONAL : Code staat op GitHub, i.e. enkel juiste bestanden, meerdere nuttige commits en uitleg
