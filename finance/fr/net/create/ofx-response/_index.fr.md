---
title: Créer OFX fichier de réponse via C#
description: Exemple de code pour la création du fichier de réponses OFX. Utilisez l'exemple de code API pour la génération de fichiers de réponse par lots OFX dans les applications basées sur .NET. 
url: /fr/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer OFX fichiers de réponse via C#" h2="OFX création de fichiers de réponse sans avoir besoin d\'installer Microsoft Office ou tout autre logiciel." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer OFX fichiers de réponse" %}}

Suivez les étapes de l'extrait de code ou améliorez-le en fonction des besoins de votre application après avoir défini les exigences de création dans votre application.

1. Créer [Classe OfxResponseDocumentOfxResponseDocument class](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) objet.1. Attribuez les propriétés pertinentes à l'aide de différentes classes fournies par API comme [SignonReponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionReponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [DéclarationTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Utilisez ofxVersion V2x ou V1x pour les fichiers xml et sgml respectivement à partir de [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) comme paramètre dans la méthode Save.1. Appeler le [Enregistrer la méthode](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) en fournissant le fichier cible et ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigence de création" %}}
Pour procéder à la création du fichier de réponse OFX, .NET Finance API est la principale exigence à inclure dans l'application de génération de rapport. 
- Installez-le via la ligne de commande en tant que ```nuget install Aspose.Finance``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Finance```.
- Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour la création de OFX fichiers de réponse" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres options de création" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX fichier de demande" description="Format 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Fichier" description="Langage de reporting métier extensible" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}