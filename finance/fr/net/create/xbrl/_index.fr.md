---
title: Créer XBRL fichier via C#
description: Exemple de code pour la création de fichier XBRL. Utilisez l'exemple de code API pour la génération de fichiers batch XBRL dans les applications basées sur .NET. 
url: /fr/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer XBRL fichiers via C#" h2="XBRL création de fichiers sans avoir à installer Microsoft Office ou tout autre logiciel." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer des fichiers XBRL" %}}

Suivez les étapes de l'extrait de code ou améliorez-le en fonction des besoins de votre application pour générer des fichiers extensibles XBRL en langage de création de rapports commerciaux. Assurez-vous d'avoir des exigences de création dans votre application.

1. Créer [Classe XbrlDocumentXbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Exemple.1. Pour créer un nouveau document d'instance XBRL [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) et [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Ajouter une référence de schéma à l'aide de [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Selon la nature de l'application, ajoutez un contexte, une unité, un élément, un lien de note de bas de page, etc.1. Appeler le [Enregistrer la méthode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) en fournissant le chemin du fichier cible.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigence de création" %}}
Pour procéder à la génération de XBRL documents, .NET Finance API est la principale exigence à inclure dans l'application. 
- Installez-le via la ligne de commande en tant que ```nuget install Aspose.Finance``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Finance```.
- Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour la création de XBRL fichiers" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres options de création" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Demande" description="Format 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX réponse" description="Format 1.03 ou 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}