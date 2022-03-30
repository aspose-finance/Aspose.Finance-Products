---
title: Créer OFX fichier de demande via C#
description: Exemple de code pour la création du fichier de requête OFX. Utilisez l'exemple de code API pour la génération de fichiers de requête par lot OFX dans les applications basées sur .NET. 
url: /fr/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer OFX fichiers de demande via C#" h2="OFX demande la création de fichiers sans avoir besoin d\'installer Microsoft Office ou tout autre logiciel." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer OFX fichiers de demande" %}}

Après avoir défini les exigences de création de fichiers de demande OFX dans votre application, suivez les étapes de l'extrait de code ou améliorez-le selon vos besoins.

1. Créer [Classe OfxRequestDocumentOfxRequestDocument class](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) objet.1. Attribuez les propriétés pertinentes à l'aide de différentes classes fournies par API comme [Demande d'ouverture de session](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Institution financière](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Utilisez ofxVersion V2x ou V1x pour les fichiers xml et sgml respectivement à partir de [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) comme paramètre dans la méthode Save.1. Appeler le [Enregistrer la méthode](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) en fournissant le fichier cible et ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigence de création" %}}
Pour procéder à la OFX création du fichier de demande, .NET Finance API est la principale exigence à inclure dans l'application de génération de rapport. 
- Installez-le via la ligne de commande en tant que ```nuget install Aspose.Finance``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Finance```.
- Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour la création de OFX fichiers de requête" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres options de création" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Fichier de réponse" description="Format 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Fichier" description="Langage de reporting commercial extensible" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}