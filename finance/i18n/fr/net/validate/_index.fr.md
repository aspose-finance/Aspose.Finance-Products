---
title: Valider les rapports financiers via .NET
url: /fr/net/validate/
description:  C# code pour valider les rapports financiers dans les fichiers XBRL et iXBRL via la bibliothèque .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Valider les fichiers d\'information financière via C#" h2="Validation des formats de rapports financiers, y compris XBRL et iXBRL dans les applications basées sur .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Est une fonctionnalité riche, extensible et facile à utiliser le traitement des rapports financiers API. Les développeurs peuvent facilement charger, valider, afficher ou créer des formats XBRL et iXBRL pour les solutions financières et commerciales. API fournit [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Classe et  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Classe pour le chargement des fichiers XBRL et iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Valider XBRL Document" %}}

La validation du fichier XBRL est nécessaire pour un certain nombre de cas, par exemple pour vérifier que les données sont dans la bonne structure et le bon format. Pour valider les documents XBLR, utilisez d'abord la classe XbrlDocument pour charger le fichier XBRL. Pour utiliser le [Valider ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Méthode de [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Classe, d'abord intialiser le [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Avec XbrlDocument objet XbrlInstances. Itérer à travers chacun [XbrlInstance. ValidationErreurs](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Pour obtenir le bon code d'erreur et agir en conséquence en imprimant les messages d'erreur personnalisés sur la console ou en écrivant dans un fichier.

{{% blocks/products/pf/feature-page-code h3="C# Code pour valider XBRL fichier" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Valider iXBRL Document" %}}

Pour la validation iXLRB, chargez-le via [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Classe et utilisez sa méthode Valider (). Dans [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Énumération, codes d'erreur de validation sont définis pour chaque règle de validation. Rares sont les codes ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarionGroup, ContextScenarioXbrlSubtitutionGroup etc. Les développeurs peuvent déboguer et afficher les codes en tant qu'utilisateurs finaux ou indiquer la direction pour résoudre le problème.

{{% blocks/products/pf/feature-page-code h3="C# Code pour valider iXBRL document" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}