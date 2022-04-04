# Extraction automatique d’information dans les catalogues de vente

Le projet DataCatalogue, conjointement mené par l’équipe ALMANaCH - Inria, la Bibliothèque nationale de France (BnF) et l’Institut national d’histoire de l’art (INHA) a été lancé au début de l’automne 2021. Il vise à passer d’une numérisation en mode image des catalogues de vente (monnaies, objets d’art, etc.) conservés à la BnF et l’INHA à une base de données textuelle et requêtable. 

DataCatalogue s’attache à adapter la suite logicielle GROBID (GeneRation Of BIbliographic Data - https://github.com/kermitt2/grobid) au format des catalogues de vente. GROBID utilise des modèles CRF en cascade pour segmenter les zones d’information d’un document PDF et en produire un encodage XML-TEI. Grâce à l’encodage fin à grande échelle que permet un outil automatique comme GROBID, les catalogues de ventes bénéficieront d’un nouvel accès aux informations qu’ils contiennent. Cela passera notamment par la publication des fichiers obtenus dans une plateforme requêtable, ouverte aux publics. 

Nous proposons une mission de stage s’inscrivant dans ce contexte. Il s’agira pour le/la stagiaire d’explorer d’autres outils d’extraction automatique d’information, comme la reconnaissance d’entités nommées (NER), afin de voir s’il est pertinent de compléter un outil tel que GROBID avec d’autres technologies lorsqu’il s’agit d’aller chercher une granularité fine dans l’information. Le/la stagiaire travaillera en étroite collaboration avec des chercheur-es d’Inria, et les partenaires de la BnF et de l’INHA. Il/Elle pourra être amenée à se déplacer au Département des Monnaies, médailles et antiques de la Bibliothèque nationale de France pour consulter ces documents.

En collaboration avec l’ensemble des équipes, le stagiaire aura pour mission de :

* Se former à l’utilisation de GROBID dans le cadre du stage,
* Participer à la création de données d’entraînement pour les modèles de segmentation de GROBID, et de contrôler les documents créés automatiquement avec ces modèles,
* Explorer les outils d’extraction d’information déjà développés (au sein d’Inria ou non) et disponibles en ligne,
* Proposer un scénario d’intégration des technologies qui pourraient être ajoutées à la chaîne de traitement de DataCatalogue,
* Rédiger un rapport rendant compte de l’ensemble des tâches effectuées et des résultats obtenus.
