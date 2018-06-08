# Antispam Outlook
---
## Situation actuelle
### chez les utilisateurs
* Aucun filtrage Outlook (configuration par defaut)
* Le dossier courrier indésirable est caché
* aucun avertissement par outlook sur les emails suspicieux
* Les images provenant d'Internet ne sont pas chargés
    * Sauf si destinataires approuvés
    * Venant de Sharepoint
    * Zone de sécurité fiable

---
### chez Global Infra
* 3 strategies (outlook 2010, 2013, 2016)
* Filtrage minimal
    * bloque les emails légitimement considérés comme du SPAM
    > ex: liste noire, domaines refusées, encodage
* Liste blanche globale
    > Permet d'accepter les images provenant des emetteurs autorisés: Teams, service-now, Qualys...
* Liste blanche par Utilisateurs
    > peupler automatiquement avec les destinataires

---
## Bonus avec Exchange

* Outlook en mode cache
    * les listes blanches/noires utilisateurs sont stockés sur Exchange   
---

