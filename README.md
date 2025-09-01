# Autodeploy template
Dit toont een template van het autodeploy proces wat mogelijk is gemaakt door [Sam Kirkland: FTP-Deploy-Action](https://github.com/SamKirkland/FTP-Deploy-Action/tree/4.0.0/)

Mochten de bestanden niet succesvol geüpload kunnen worden door 
`Error: Client is closed
    at /home/runner/work/_actions/SamKirkland/FTP-Deploy-Action/4.0.0/dist/index.js:3704:29
    at new Promise (<anonymous>)`
Probeer dan handmatig `.ftp-deploy-sync-state.json` aan te maken in de root van je project. Dit zou het probleem kunnen verhelpen.


<!-- Security scan triggered at 2025-09-02 00:16:29 -->