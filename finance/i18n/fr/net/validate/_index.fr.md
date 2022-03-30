---
title: Valider les rapports financiers via .NET
url: /fr/net/validate/
description:  Code C# pour valider les rapports financiers dans les fichiers XBRL et iXBRL via la bibliothèque .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Valider les fichiers de rapports financiers via C#" h2="Validation des formats de rapports financiers, y compris XBRL et iXBRL dans les applications basées sur .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) est un traitement de rapports financiers riche en fonctionnalités, extensible et facile à utiliser API. Les développeurs peuvent facilement charger, valider, afficher ou créer des formats XBRL et iXBRL pour les solutions financières et commerciales. API fournit [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) classe et  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) classe pour charger les fichiers XBRL et iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Valider XBRL document" %}}

La validation du fichier XBRL est nécessaire dans un certain nombre de cas, par exemple pour vérifier que les données sont dans la bonne structure et le bon format. Pour valider les documents XBLR, utilisez d'abord la classe XbrlDocument pour charger le fichier XBRL. Pour utiliser le [valider()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) méthode de [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) classe, initialisez d'abord la [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) avec l'objet XbrlDocument XbrlInstances. Parcourez chaque [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) pour obtenir le bon code d'erreur et agir en conséquence en imprimant les messages d'erreur personnalisés sur la console ou en écrivant dans un fichier.

{{% blocks/products/pf/feature-page-code h3="C# code pour valider XBRL fichier" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Valider iXBRL document" %}}

Pour la validation iXLRB, chargez-le via [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class et utilisez sa méthode Validate(). Dans [CodeErreurValidation](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) énumération, des codes d'erreur de validation sont définis pour chaque règle de validation. Peu de codes sont ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup etc. Les développeurs peuvent déboguer et afficher les codes des utilisateurs finaux ou peuvent montrer la direction pour résoudre le problème.

{{% blocks/products/pf/feature-page-code h3="C# Code pour valider iXBRL Document" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}