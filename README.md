# Analysez-des-indiateurs-de-l-egalite-femme-homme
Projet 7 de la formation de data analyst de OpenClassrooms

<img width="614" alt="IMG_Scenario" src="https://github.com/AlexisDlge/Detectez-des-faux-billets/assets/152527939/6c949932-3da9-4faa-a408-3d3da4ec7247">

Vous êtes data analyst dans un cabinet de consultant spécialisé dans la transformation digitale des entreprises. Le cabinet compte déjà plus de 150 salariés et est en plein développement. Dans ce contexte économique, le recrutement de consultants expérimentés devient un véritable enjeu stratégique.

Ce matin, en arrivant à votre poste de travail, vous recevez un courriel de Laura, la directrice des ressources humaines avec en copie Vincent, contrôleur de gestion sociale :



    Objet : Diagnostic égalité femmes-hommes
    De : Laura
    À : Moi
    CC : Vincent

    Bonjour, 

    Chaque année avant le 1er mars, les entreprises d’au moins 50 salariés doivent calculer et publier sur leur site Internet leur index de l’égalité femmes-hommes. 
    Comme tu le sais, nous sommes en phase de croissance importante, 
    et il me semble important d’avoir une politique volontariste pour développer l’égalité femmes-hommes dans notre cabinet.
    Cela nous permettra d’améliorer notre marque employeur et d’attirer plus facilement des talents.

    J’aimerais donc que tu aides Vincent à automatiser la création d’un rapport diagnostique sur l’égalité professionnelle femmes hommes. 
    Pour cela, il m’a suggéré l’utilisation de KNIME. J’aurais donc besoin que, 
    à partir des fichiers des données (en pièce jointe) issues de notre Système d’Informations des Ressources Humaines (SIRH), tu lui prépares :
      ● un workflow avec le logiciel KNIME qui crée les graphiques du diagnostic ;
      ● un fichier .csv prêt pour être utilisé dans nos futures analyses via Tableau Software.

    Le site du ministère du Travail donne de nombreuses informations pour établir un diagnostic. 
    Regarde notamment le document de présentation de lʼoutil Diagnostic Égalité dans lequel tu trouveras une liste des indicateurs à surveiller. 
    Pas besoin de tout les extraire, mais dans un premier temps choisis-en au minimum 5 dans la liste que ton workflow devra générer.
    Aussi, je te rappelle que les données issues du SIRH ne sont pas anonymisées, alors il faudra les traiter pour que ton rapport respecte le RGPD.

    Dès que tu auras terminé, nous ferons un point ensemble avec Vincent pour que tu nous présentes le fonctionnement de ton workflow ainsi que les graphiques générés.
    Je reste à ta disposition en cas de besoin.

    Bien à toi, 

    Laura Tellier
    DRH

    Pièce jointe : 
      donnees_sirh.zip 

**Données :**
[donnees_sirh.zip ](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/DAN-P7-datasets.zip)
**Liens :**
[Le site du ministère du Travail](https://travail-emploi.gouv.fr/IMG/pdf/guide_egalite_tpe_pme_2021.pdf)
[présentation de lʼoutil Diagnostic Égalité](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/Pre%CC%81sentation+outil+Diagnostic+E%CC%81galite%CC%81.pdf)
[RGPD](https://www.cnil.fr/cnil-direct/question/quels-sont-les-grands-principes-des-regles-de-protection-des-donnees?visiteur=part)

<img width="614" alt="IMG_Livrables" src="https://github.com/AlexisDlge/Detectez-des-faux-billets/assets/152527939/86af4a1f-0feb-4235-b2ba-2f685fcaca46">

* Workflow KNIME avec commentaires.
* Fichier .csv avec les données préparées.



Pour faciliter votre passage devant le jury, déposez sur la plateforme, dans un dossier zip nommé “Titre_du_projet_nom_prénom”, tous les livrables du projet comme suit : Nom_Prénom_n° du livrable_nom du livrable_date de démarrage du projet. Cela donnera : 

* Nom_Prénom_1_workflow_KNIME_mmaaaa
* Nom_Prénom_2_fichier_csv_mmaaaa

Par exemple, le premier livrable peut être nommé comme suit : Dupont_Jean_1_workflow_KNIME_012023.

<img width="614" alt="IMG_Soutenance" src="https://github.com/AlexisDlge/Detectez-des-faux-billets/assets/152527939/a1a8bf0e-898d-4fa4-808b-091d870eb595">

Pendant la soutenance, l’évaluateur jouera le rôle du DRH, à qui vous présentez (à l’aide d’un diaporama si vous le souhaitez) : 

* Présentation des livrables (20 minutes)
  - la démarche de préparation des données avec le workflow KNIME ;
  - le fichier CSV généré, pour lequel vous expliquerez en quoi il respecte les contraintes du RGPD ;
  - les graphiques d’analyse des indicateurs du diagnostic de l’égalité femmes-hommes.
* Discussion (5 minutes)
  - L’évaluateur vous posera des questions sur le travail réalisé.
* Débriefing (5 minutes)
  - À la fin de la soutenance, l'évaluateur arrêtera de jouer le rôle de la DRH pour vous permettre de débriefer ensemble.
