---
title: Convertir les rapports financiers via .NET
url: /fr/net/conversion/
description:  Code C# pour convertir les rapports financiers dans les formats de fichier XBRL, iXBRL(inline xbrl) et OFX via la bibliothèque .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir les fichiers de rapport financier via C#" h2="Conversion des formats de rapports financiers, y compris les fichiers XBRL, iXBRL et OFX du format 1.03 au format 2.2 dans les applications basées sur .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) est un API riche en fonctionnalités, extensible et facile à utiliser. Les développeurs peuvent facilement valider XBRL instances, bases de liens et schémas de taxonomie à l'aide de [méthode valider ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) qui doivent respecter les exigences de syntaxe imposées dans la spécification. De plus, ils peuvent lire les formats XBRL, iXBRL et créer une instance XBRL à partir de zéro. De plus, ils peuvent **convertir le format XBRL** en fichiers iXBRL et Microsoft Excel XLSX. API prend également en charge la création de demande/réponse au format Open Financial Exchange (OFX) et convertit la demande/réponse de fichier OFX du format 1.03 au format 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir OFX fichiers de réponse et de requête" %}}

API prend en charge la création de fichiers de requête et de réponse OFX en fournissant deux classes. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) pour créer et charger des fichiers de requête OFX au format 1.03 et 2.2 et [OfxRéponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) pour les fichiers de réponse OFX au format 1.03 et 2.2. De plus, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Énumération ayant des membres V1x qui est la version 1.x, format de fichier sgml et V2x version 2.x, format de fichier xml. Après avoir appelé la méthode Save de la classe OfxRequestDocument ou de la classe OfxResponseDocument, les développeurs peuvent facilement convertir le fichier 1.03 sgml au format 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# code pour convertir OFX fichiers de réponse" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# code pour convertir OFX fichiers de requête" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversion des rapports financiers" %}}

API prend en charge la conversion des fichiers XBRL au format iXBRL et Microsoft® Excel XLSX. Le processus de conversion est simple, chargez d'abord le fichier via [Classe XbrlDocumentXbrlDocument Class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Utilisez le [Classe SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) pour [Enregistrer le format](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), à utiliser comme paramètre dans la méthode Save de la classe XbrlDocument. Pour enregistrer dans le fichier iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) sera utilisé et pour l'exportation au format XLSX, SaveFormat.XLSX sera utilisé.

{{% blocks/products/pf/feature-page-code h3="C# Code à exporter XBRL vers iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code pour la conversion de XBRL en XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}