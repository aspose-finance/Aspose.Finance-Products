---
title: Créer XBRL fichier via C#
description: Exemple de code pour la création de fichier XBRL. Utilisez API exemple de code pour la génération de fichiers par lots XBRL dans des applications basées sur .NET. 
url: /fr/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer XBRL fichiers via C#" h2="XBRL création de fichiers sans avoir besoin de Microsoft Office installé ou tout autre logiciel." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer des fichiers XBRL" %}}

Suivez les étapes de l'extrait de code ou améliorez-le en fonction des besoins de votre application pour générer des fichiers de langage de reporting d'entreprise extensible XBRL. Assurez-vous d'avoir des exigences de création au sein de votre application.

1. Créer [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instance.1. Pour créer un nouveau document d'instance XBRL [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Et [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Ajouter une référence de schéma en utilisant [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Selon la nature de l'application, ajoutez du contexte, de l'unité, de l'élément, du lien de note de bas de page et plus encore.1. Appelez le [Méthode de sauvegarde](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) En fournissant le chemin du fichier cible.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigence de création" %}}
Pour procéder à la génération de XBRL documents, .NET Finance API est la principale exigence à inclure dans la demande. 
- Installez-le via la ligne de commande comme '''nuget install Aspose.Finance'' ou via la console du gestionnaire de packages de Visual Studio avec '''Installer-Package Aspose.Finance'''.
- Vous pouvez également obtenir l'installateur MSI hors ligne ou DLLs dans un fichier ZIP à partir de [Téléchargements](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour XBRL création de fichiers" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres options de création" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX demande" description="Format 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Réponse" description="Format 1.03 ou 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}