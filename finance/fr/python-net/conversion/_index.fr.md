---
title: Convertir les rapports financiers via Python
url: /fr/python-net/conversion/
description:  Code Python pour convertir les rapports financiers dans les formats de fichier XBRL, iXBRL(inline xbrl) et OFX via la bibliothèque Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir les fichiers de rapport financier via Python" h2="Conversion des formats de rapports financiers, y compris les fichiers XBRL, iXBRL et OFX du format 1.03 au format 2.2 dans les applications basées sur Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance pour Python via .NET](https://products.aspose.com/finance/python-net/) est un API riche en fonctionnalités, extensible et facile à utiliser. Les développeurs peuvent facilement valider les instances XBRL, les bases de liens et les schémas de taxonomie à l'aide de la méthode validate() qui doit être conforme aux exigences de syntaxe imposées dans la spécification. De plus, ils peuvent lire les formats XBRL, iXBRL et créer une instance XBRL à partir de zéro. De plus, ils peuvent **convertir le format XBRL** en fichiers iXBRL et Microsoft Excel XLSX. API prend également en charge la création de requête/réponse au format Open Financial Exchange (OFX) et convertit la requête/réponse de fichier OFX du format 1.03 au format 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir OFX fichiers de réponse et de requête" %}}

API prend en charge la création de fichiers de requête et de réponse OFX en fournissant deux classes. OfxRequestDocument pour créer et charger les fichiers de requête OFX au format 1.03 et 2.2 et OfxResponseDocument pour les fichiers de réponse OFX au format 1.03 et 2.2. De plus, OfxVersionEnum Enumeration ayant des membres V1x qui est la version 1.x, le format de fichier sgml et la version V2x 2.x, le format de fichier xml. Après avoir appelé la méthode de sauvegarde de la classe OfxRequestDocument ou de la classe OfxResponseDocument, les développeurs peuvent facilement convertir le fichier 1.03 sgml au format 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# code pour convertir OFX fichiers de réponse" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# code pour convertir OFX fichiers de requête" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversion des rapports financiers" %}}

API prend en charge la conversion des fichiers XBRL au format iXBRL et Microsoft® Excel XLSX. Le processus de conversion est simple, chargez d'abord le fichier via la classe XbrlDocument. Utilisez la classe SaveOptions pour SaveFormat, à utiliser comme paramètre dans la méthode save de la classe XbrlDocument. Pour l'enregistrement dans le fichier iXBLR, SaveFormat.IXBRL sera utilisé et pour l'exportation au format XLSX, SaveFormat.XLSX sera utilisé.

{{% blocks/products/pf/feature-page-code h3="Python Code à exporter XBRL vers iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code pour la conversion de XBRL en XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}