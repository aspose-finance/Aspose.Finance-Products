---
title: Valider les rapports financiers via Python
url: /fr/python-net/validate/
description:  Code Python pour valider les rapports financiers dans les fichiers XBRL et iXBRL via la bibliothèque Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Valider les fichiers de rapports financiers via Python" h2="Validation des formats de rapports financiers, y compris XBRL et iXBRL dans les applications basées sur Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance pour Python via .NET](https://products.aspose.com/finance/python-net/) est un traitement de rapports financiers riche en fonctionnalités, extensible et facile à utiliser API. Les développeurs peuvent facilement charger, valider, afficher ou créer des formats XBRL et iXBRL pour les solutions financières et commerciales. API fournit la classe XbrlDocument et la classe InlineXbrlDocument pour le chargement des fichiers XBRL et iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Valider XBRL document" %}}

La validation du fichier XBRL est nécessaire dans un certain nombre de cas, par exemple pour vérifier que les données sont dans la bonne structure et le bon format. Pour valider les documents XBLR, utilisez d'abord la classe XbrlDocument pour charger le fichier XBRL. Pour utiliser la méthode de validation de la classe XbrlInstance, commencez par initialiser XbrlInstanceCollection avec l'objet XbrlDocument XbrlInstances. Parcourez chaque XbrlInstance.ValidationErrors pour obtenir le bon code d'erreur et agissez en conséquence en imprimant les messages d'erreur personnalisés sur la console ou en écrivant dans un fichier.

{{% blocks/products/pf/feature-page-code h3="Python code pour valider XBRL fichier" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Valider iXBRL document" %}}

Pour la validation iXLRB, chargez-le via la classe InlineXbrlDocument et utilisez sa méthode validate(). Dans l'énumération ValidationErrorCode, les codes d'erreur de validation sont définis pour chaque règle de validation. Peu de codes sont ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup etc. Les développeurs peuvent déboguer et afficher les codes des utilisateurs finaux ou peuvent montrer la direction pour résoudre le problème.

{{% blocks/products/pf/feature-page-code h3="Python Code pour valider iXBRL Document" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}