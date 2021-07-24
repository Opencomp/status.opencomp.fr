---
title: Maintenance planifiée
date: 2021-07-24 09:30:00
resolved: false
#resolvedWhen: 2021-07-14 15:50:00
severity: notice
affected:
  - Service Web Opencomp
  - Gestion des abonnements
section: issue
---

Une maintenance planifiée est programmée pour permettre la mise à jour de l'hyperviseur exécutant les machines virtuelles de l'infrastructure Opencomp. Il est prévu que l'application https://my.opencomp.fr et le système de gestion des abonnements soient inaccessibles pendant un maximum de 4 heures.

---

La sauvegarde locale des machines virtuelles est terminée. Nous débutons la sauvegrade distante.  {{< track "2021-07-24 10:00:00" >}}   

La sauvegarde distante des machines virtuelles est terminée. Nous débutons la montée de version de l'hyperviseur.  {{< track "2021-07-24 10:10:00" >}} 
