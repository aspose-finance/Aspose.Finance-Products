---
title: Créer OFX Fichier de réponse via C#
description: Exemple de code pour la création de fichier de réponse OFX. Utilisez API exemple de code pour la génération de fichiers de réponse par lots OFX dans des applications basées sur .NET. 
url: /fr/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer OFX fichiers de réponse via C#" h2="OFX création de fichiers de réponse sans avoir besoin de Microsoft Office installé ou tout autre logiciel." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer des fichiers de réponse OFX" %}}

Suivez les étapes de l'extrait de code ou améliorez-le en fonction des besoins de votre application après avoir les exigences de création dans votre application.

1. Créer [Classe OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Objet.1. Attribuez les propriétés pertinentes en utilisant différentes classes fournies par API comme [SignonRéponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionRéponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Utilisez le ofxVersion V2x ou V1x pour les fichiers xml et sgml respectivement à partir de [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) En tant que paramètre dans la méthode Save.1. Appelez le [Méthode de sauvegarde](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) En fournissant le fichier cible et ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigence de création" %}}
Pour procéder à la création de OFX fichier de réponse, .NET Finance API est la principale exigence à inclure dans l'application de génération de rapport. 
- Installez-le via la ligne de commande comme '''nuget install Aspose.Finance'' ou via la console du gestionnaire de packages de Visual Studio avec '''Installer-Package Aspose.Finance'''.
- Vous pouvez également obtenir l'installateur MSI hors ligne ou DLLs dans un fichier ZIP à partir de [Téléchargements](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour OFX création de fichiers de réponse" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres options de création" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Dossier de demande" description="Format 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Fichier" description="Langage des rapports commerciaux extensible" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}