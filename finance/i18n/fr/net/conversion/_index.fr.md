---
title: Convertir les rapports financiers via .NET
url: /fr/net/conversion/
description:  C# code pour convertir les rapports financiers dans les fomats de fichiers XBRL, iXBRL et OFX via la bibliothèque .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir des fichiers de rapport financier via C#" h2="Le rapport financier formate la conversion, y compris les fichiers XBRL, iXBRL et OFX du format 1.03 au format 2.2 dans les applications basées sur .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Est une fonctionnalité riche, extensible et facile à utiliser API. Les développeurs peuvent facilement valider XBRL instances, linkbases et schémas de taxonomie en utilisant [Valider () méthode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Qui doit être conforme aux exigences de syntaxe imposées dans la spécification. De plus, ils peuvent lire les formats XBRL, iXBRL et créer une instance XBRL à partir de zéro. De plus, ils peuvent ** convertir XBRL format ** en iXBRL et fichiers Microsoft Excel XLSX. API prend également en charge la création de demande/réponse au format d'échange financier ouvert (OFX) et convertit la demande/réponse de fichier OFX du format 1.03 au format 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir OFX fichiers de réponse et de demande" %}}

API prend en charge la création de fichiers de demande et de réponse OFX en fournissant deux classes. [OfxDemestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Pour la création et le chargement des fichiers de demande OFX au format 1.03 et 2.2 et [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Pour les fichiers de réponse OFX au format 1.03 et 2.2. En outre, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Énumération ayant des membres V1x qui est la version 1.x, le format de fichier sgml et la version V2x 2.x, format de fichier xml. Après avoir appelé la méthode Save de la classe OfxRequestDocument ou de la classe OfxResponseDocument, les développeurs peuvent facilement convertir du fichier 1.03 sgml au format 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Code pour convertir OFX fichiers de réponse" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code pour convertir OFX fichiers de demande" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversion des rapports financiers" %}}

API prend en charge la conversion de fichiers XBRL en iXBRL et Microsoft®Format Excel XLSX. Le processus de conversion est simple, chargez d'abord le fichier via [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Utilisez le [Classe SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Pour [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), À utiliser comme paramètre dans la méthode Save de XbrlDocument Class. Pour enregistrer dans le fichier iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Sera utilisé et pour l'exportation au format XLSX, SaveFormat.XLSX sera utilisé.

{{% blocks/products/pf/feature-page-code h3="C# Code pour l\'exportation de XBRL vers iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code pour la conversion XBRL vers XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}