---
title: Incident de routage
date: 2019-06-24 13:10:00
resolved: true
resolvedWhen: 2019-06-24 15:07:00
severity: down
affected:
  - Passerelle
  - Service Web Opencomp
  - Gestion des abonnements
section: issue
---

L'accès à l'application est actuellement indisponible en raison d'un incident.   
   
---
   
***Identifié*** - L'incident est lié à Cloudflare qui assure les services de résolution de noms de domaine (DNS) et de réseau de diffusion de contenu (CDN). [Un incident](https://www.cloudflarestatus.com/incidents/46z55mdhg0t5) est ouvert chez Cloudflare.  {{< track "2019-06-24 13:22:00" >}}   
   
***Identifié*** - Les équipes de Cloudflare continuent de travailler à la résolution du problème. {{< track "2019-06-24 13:45:00" >}}   
   
***Identifié*** - L'incident semble finalement ne pas se limiter à Cloudflare uniquement. Amazon Web Services et Google rapportent également des problèmes de trafic réseau. Seuls certains FAI (Fournisseurs d'Accès à Internet) sont affectés. La plateforme est actuellement accessible par brefs moments. Nous continuons de vous recommander de reporter votre utilisation d'Opencomp tant que l'incident n'est pas réglé définitivement. {{< track "2019-06-24 14:32:00" >}}   
   
***Surveillance*** - Le réseau responsable de la fuite d'itinéraire a maintenant résolu le problème. Nous constatons une amélioration et continuons à surveiller cela avant de considérer ce problème comme résolu. {{< track "2019-06-24 14:42:00" >}}   
   
***Résolu*** - Les niveaux de trafic sont revenus à la normale maintenant que la fuite d’itinéraire a été corrigée. {{< track "2019-06-24 15:07:00" >}}   