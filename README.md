# supplierbackoffice
Après avoir installé le module assurer vous:
      -que les surcharges (dossier override) ont bien été écrites (bug sur prestashop 1.6.0.14: le fichier AdminEmployeeController s'écrit avec des erreurs).
      -d'avoir bien greffé le module sur displayBackOfficeHeader

BUG: l'override de la template admin/product/informations.tpl ne semble pas fonctionner, copiez donc le fichier à la main.