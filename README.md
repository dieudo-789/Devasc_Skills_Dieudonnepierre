aak 1

>Task name: GitHub



Taakvoorbereiding:

Maak een map genaamd "Devasc_Skills" op je DEVASC virtuele machine.
Initialiseer een Git-repository binnen deze map.
Maak een online repository op GitHub genaamd "Devasc_Skills_YourInitals".
Koppel je lokale Git-repository aan de online repository.
Taakimplementatie:

Voor elke taak, sla het corresponderende script op in de "Devasc_Skills" map.
Voer de standaard Git-opdrachten uit: git add ., git commit -m "Toevoegen script voor Task X", git push origin master (of de relevante taknaam).


Taakproblemen en -oplossingen:

Problemen met git clone het werkte niet dus heb ik chat gpt gebruikt


Taakverificatie:
Bekijk de GitHub-repository om te controleren of de bestanden zijn georganiseerd per taak met de juiste tags.
folder goed upgeload




taak 2
task ansible


Taakvoorbereiding:

Toegang tot DEVASC Virtual Machine:

Zorg ervoor dat je toegang hebt tot je DEVASC Virtual Machine.

Taakimplementatie:

Maak een Ansible Playbook:

Maak een nieuw bestand genaamd ios_facts.yml voor het Ansible Playbook.




Uitvoeren van het Playbook:

Open een terminal op je DEVASC Virtual Machine.

Taakprobleem:

Verbindingsproblemen met Ansible:
Tijdens het uitvoeren van het Ansible Playbook ondervind ik een verbindingsprobleem met de virtuele router. het kqn dat  de router niet correct herkend of is de SSH-connectiviteit niet goed geconfigureerd. 

Taakverificatieprobleem:

Fout in IOS Versie Verzameling:
Bij het inspecteren van de uitvoer van het playbook merk ik op dat de verzamelde IOS-versie-informatie leeg is of niet correct is weergegeven. Dit kan te wijten zijn aan een fout in de ios_command-module of een onjuiste interpretatie van de uitvoer. 






Taak 3

Task 3 -- Docker


Taaknaam: Creatie van Docker-image voor Apache-webserver

Taakvoorbereiding:

Installeer Docker op je machine als dit nog niet is gedaan.
Maak jezelf vertrouwd met de structuur en vereisten van de verstrekte Ansible playbook.
Taakuitvoering:

Creatie van Dockerfile:

Analyseer de Ansible playbook en vertaal dit naar een Dockerfile. Voeg de nodige commando's toe voor het installeren van Apache, het inschakelen van mod_rewrite, het configureren van Apache-poorten en het kopiëren van het homepage-bestand.
Maak een bestand met de naam Dockerfile in de projectdirectory.
Taakverificatie:

Controleer Apache-webserver:
Voer het bash-script uit (./run_apache.sh) om het Docker-image te bouwen en de Docker-container uit te voeren.
Open een webbrowser en ga naar http://localhost:8080 om te controleren of de Apache-webserver draait.
Maak screenshots van de draaiende container en de webpagina.

Taakproblemen en -oplossingen:

Problemen bij het bouwen van het Docker-image: Zorg ervoor dat alle vereiste stappen in de Dockerfile correct zijn. Controleer op foutmeldingen tijdens het bouwen.
Problemen bij het starten van de Docker-container: Controleer of de poorten correct zijn toegewezen en of er geen conflicten zijn met andere actieve containers op dezelfde poort.

Taak 6

Taakvoorbereiding:

Webex Teams API Token verkrijgen:
Ga naar developer.webex.com en verkrijg een API-token voor Webex Teams.
Python-scriptomgeving opzetten:
Zorg ervoor dat Python op je systeem is geïnstalleerd.
Installeer eventueel ontbrekende pakketten met pip install requests.


Taakuitvoering (Python-code):

Webex Teams Space maken:
geen probleem gehad
Taakverificatie:
Na het uitvoeren van de Python-scriptcode, controleer in de Webex Teams-client of de ruimte is gemaakt en of het bericht succesvol is verzonden. Je kunt ook screenshots van de Webex Teams-client toevoegen als bewijs.


taak 10
Taakvoorbereiding:

Toegang tot DEVASC Virtual Machine:

Zorg ervoor dat je toegang hebt tot je DEVASC Virtual Machine.
Python-omgeving en Bibliotheekinstallatie:

Zorg ervoor dat Python is geïnstalleerd op je DEVASC Virtual Machine.
Installeer de vereiste bibliotheek requests indien deze nog niet is geïnstalleerd. Dit kan worden gedaan met het commando pip install requests.
Toegang tot het Cisco DNA Center (DNAC):

Zorg ervoor dat je toegang hebt tot een Cisco DNA Center-instantie. In het script wordt uitgegaan van het gebruik van 'sandboxdnac.cisco.com'. Als je een andere DNAC-instantie gebruikt, vervang dan de relevante parameters.
Webex Teams-toegang (voor vervolgopdrachten):

Als je van plan bent om de Webex Teams-gerelateerde taken uit te voeren, zorg er dan voor dat je toegang hebt tot een Webex Teams-account en de nodige rechten hebt om ruimtes te maken en berichten te verzenden.




Taakimplementatie:

Python Script en Aanpassingen:

Kopieer het gegeven DNAC-script naar je Python-omgeving.
Vervang de XXXXXXXX-elementen in het script door de juiste parameters, variabelen en sleutels zoals aangegeven in de taakbeschrijving.
Voer het aangepaste script uit en controleer of de gewenste output wordt gegenereerd.


Taakverificatie:

alle data werden goed veranderd
