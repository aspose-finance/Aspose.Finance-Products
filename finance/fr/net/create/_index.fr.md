---
title: Créer des rapports financiers via .NET
url: /fr/net/create/
description:  Code C# pour créer des rapports financiers dans XBRL et OFX fichiers de requête ou de réponse via la bibliothèque .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer des fichiers de rapports financiers via C#" h2="Création de formats de rapports financiers, y compris les fichiers de requête ou de réponse XBRL et OFX au format 1.03 ou 2.2 dans les applications basées sur .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) est un outil de création et de traitement de rapports financiers riche en fonctionnalités, extensible et facile à utiliser API. Les développeurs peuvent facilement créer une instance XBRL à partir de zéro et ajouter une référence de schéma, un contexte, une unité, un élément, un lien de note de bas de page, une référence de rôle et 
référence de rôle d'arc. API fournit une classe pertinente pour chaque fonctionnalité, par exemple pour le contexte, les développeurs peuvent utiliser [ContextePériode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Entité de contexte](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) et [Le contexte](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
De plus, API prend également en charge la création de requêtes/réponses au format Open Financial Exchange (OFX) au format 1.03 ou 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Créer XBRL fichier en ajoutant un élément" %}}

Pour créer un fichier XBRL et ajouter un élément dans le document, le processus consiste à créer [Classe XbrlDocumentXbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) exemple. Préparez les paramètres pertinents pour l'élément en utilisant les classes API appropriées telles que [Classe SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)les classes de contexte pertinentes comme mentionné ci-dessus et [Classe conceptuelle](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Enfin définir et initialiser [Classe d'article](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) propriétés ainsi que d'appeler le [Enregistrer la méthode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) pour [créer XBRL](https://products.aspose.com/finance/net/create/xbrl/) fichier sur le disque.

{{% blocks/products/pf/feature-page-code h3="C# code pour créer XBRL fichier en ajoutant un élément" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Créer OFX fichiers de demande et de réponse" %}}


Pour générer des fichiers OFX, le API fournit [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) et [OfxRéponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) les classes et les développeurs peuvent facilement [créer OFX requête](https://products.aspose.com/finance/net/create/ofx-request/) et Fichiers de réponse aux formats 1.03 et 2.2. Pour initialiser les propriétés OfxRequestDocument, API fournit également d'autres classes telles que [Demande d'ouverture de session](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Institution financière](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) et [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Des classes. De même, pour initialiser les propriétés OfxResponseDocument, API fournit des classes de support telles que [SignonReponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionReponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) et [DéclarationTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Vous trouverez ci-dessous les extraits de code pour les deux cas avec l'utilisation des classes appropriées pertinentes.

{{% blocks/products/pf/feature-page-code h3="C# code pour générer OFX documents de demande" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# code pour générer OFX documents de réponse" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}