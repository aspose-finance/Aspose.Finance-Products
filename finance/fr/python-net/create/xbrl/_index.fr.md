---
title: Créer XBRL fichier via Python
description: Exemple de code pour la création de fichier XBRL. Utilisez l'exemple de code API pour la génération de fichiers batch XBRL dans les applications basées sur Python. 
url: /fr/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer XBRL fichiers via Python" h2="XBRL création de fichiers sans avoir à installer Microsoft Office ou tout autre logiciel." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer des fichiers XBRL" %}}

Suivez les étapes de l'extrait de code ou améliorez-le en fonction des besoins de votre application pour générer des fichiers extensibles XBRL en langage de création de rapports commerciaux. Assurez-vous d'avoir des exigences de création dans votre application.

1. Créez une instance de classe XbrlDocument.1. Pour créer un nouveau document d'instance XBRL XbrlInstanceCollection et XbrlInstance.1. Ajouter une référence de schéma à l'aide de SchemaRefCollection1. Selon la nature de l'application, ajoutez un contexte, une unité, un élément, un lien de note de bas de page, etc.1. Appelez la méthode save en fournissant le chemin du fichier cible.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigence de création" %}}
Pour procéder à la génération de documents XBRL, assurez-vous que vous disposez des prérequis suivants. 
- Système d'exploitation basé sur Microsoft Windows ou Linux.- Python 3.5 ou version ultérieure.- Aspose.Finance pour Python référencé dans votre projet.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python code pour la création de XBRL fichiers" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres options de création" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Demande" description="Format 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX réponse" description="Format 1.03 ou 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}