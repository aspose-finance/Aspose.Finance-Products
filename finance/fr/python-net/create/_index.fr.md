---
title: Créer des rapports financiers via Python
url: /fr/python-net/create/
description:  Code Python pour créer des rapports financiers dans XBRL et OFX fichiers de requête ou de réponse via la bibliothèque Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer des fichiers de rapports financiers via Python" h2="Création de formats de rapports financiers, y compris les fichiers de requête ou de réponse XBRL et OFX au format 1.03 ou 2.2 dans les applications basées sur Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance pour Python via .NET](https://products.aspose.com/finance/python-net/) est un outil de création et de traitement de rapports financiers riche en fonctionnalités, extensible et facile à utiliser API. Les développeurs peuvent facilement créer une instance XBRL à partir de zéro et ajouter une référence de schéma, un contexte, une unité, un élément, un lien de note de bas de page, une référence de rôle et 
référence de rôle d'arc. API fournit une classe pertinente pour chaque fonctionnalité, comme pour le contexte, les développeurs peuvent utiliser ContextPeriod, ContextEntity et Context. 
De plus, API prend également en charge la création de requêtes/réponses au format Open Financial Exchange (OFX) au format 1.03 ou 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Créer XBRL fichier en ajoutant un élément" %}}

Pour créer le fichier XBRL et ajouter un élément dans le document, le processus consiste à créer une instance de classe XbrlDocument. Préparez les paramètres pertinents pour l'élément en utilisant les classes API appropriées telles que la classe SchemaRef, les classes de contexte pertinentes comme mentionné ci-dessus et la classe Concept. Enfin, définissez et initialisez les propriétés de la classe Item et appelez la méthode save pour créer le fichier XBRL sur le disque.

{{% blocks/products/pf/feature-page-code h3="Python code pour créer XBRL fichier en ajoutant un élément" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Créer OFX fichiers de demande et de réponse" %}}


Pour générer des fichiers OFX, le API fournit les classes OfxRequestDocument et OfxResponseDocument et les développeurs peuvent facilement [créer OFX requête](https://products.aspose.com/finance/python-net/create/ofx-request/) et Fichiers de réponse aux formats 1.03 et 2.2. Pour initialiser les propriétés OfxRequestDocument, API fournit également d'autres classes telles que les classes SignonRequest, FinancialInstitution et StatementTransactionRequest. De même, pour initialiser les propriétés OfxResponseDocument, API fournit des classes de support telles que SignonResponse, StatementTransactionResponse et StatementTransaction. Vous trouverez ci-dessous les extraits de code pour les deux cas avec l'utilisation des classes appropriées pertinentes.

{{% blocks/products/pf/feature-page-code h3="Python code pour générer OFX documents de demande" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python code pour générer OFX documents de réponse" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}