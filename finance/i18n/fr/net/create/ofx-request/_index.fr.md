---
title: Créer OFX fichier de demande via C#
description: Exemple de code pour la création de fichier de demande OFX. Utilisez API exemple de code pour la génération de fichiers de demande par lots OFX dans des applications basées sur .NET. 
url: /fr/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer des fichiers de demande OFX via C#" h2="OFX demande la création de fichiers sans avoir besoin de Microsoft Office installé ou de tout autre logiciel." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer des fichiers de demande OFX" %}}

Après avoir les OFX exigences de création de fichiers de demande dans votre application, Suivez les étapes dans l'extrait de code ou améliorez-le en tant que vous avez besoin.

1. Créer [Classe OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Objet.1. Attribuez les propriétés pertinentes en utilisant différentes classes fournies par API comme [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Institution financière](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementDemande de transaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Utilisez le ofxVersion V2x ou V1x pour les fichiers xml et sgml respectivement à partir de [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) En tant que paramètre dans la méthode Save.1. Appelez le [Méthode de sauvegarde](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) En fournissant le fichier cible et ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigence de création" %}}
Pour procéder à la création de OFX demande de fichier, .NET Finance API est la principale exigence à inclure dans l'application de génération de rapport. 
- Installez-le via la ligne de commande comme '''nuget install Aspose.Finance'' ou via la console du gestionnaire de packages de Visual Studio avec '''Installer-Package Aspose.Finance'''.
- Vous pouvez également obtenir l'installateur MSI hors ligne ou DLLs dans un fichier ZIP à partir de [Téléchargements](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour OFX demande de création de fichiers" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres options de création" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Fichier de réponse" description="Format 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Fichier" description="Langage des rapports commerciaux extensible" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}