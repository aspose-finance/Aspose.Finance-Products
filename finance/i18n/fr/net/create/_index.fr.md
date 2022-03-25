---
title: Créer des rapports financiers via .NET
url: /fr/net/create/
description:  C# code pour créer des rapports financiers dans XBRL, et OFX fichiers de demande ou de réponse via la bibliothèque .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer des fichiers de rapports financiers via C#" h2="Le rapport financier forme la création, y compris le fichier de demande ou de réponse XBRL et OFX au format 1.03 ou 2.2 dans les applications basées sur .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Est une fonctionnalité riche, extensible et facile à utiliser la création et le traitement de rapports financiers API. Les développeurs peuvent facilement créer une instance XBRL à partir de zéro et peuvent ajouter une référence de schéma, un contexte, une unité, un élément, un lien de note de bas de page, une référence de rôle et 
Référence de rôle d'arc. API fournit une classe pertinente pour chaque fonctionnalité, par exemple pour le contexte, les développeurs peuvent utiliser [ContextPériode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntité](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) Et [Contexte](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
De plus, API prend également en charge la création de demande/réponse au format d'échange financier ouvert (OFX) au format 1.03 ou 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Créer XBRL fichier en ajoutant un élément" %}}

Pour créer un fichier XBRL et ajouter un élément dans le document, le processus est, créer [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instance. Préparez les paramètres pertinents pour l'article en utilisant des classes API appropriées telles que [Classe SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Classes de contexte pertinentes comme mentionné ci-dessus et [Concept de classe](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Enfin définir et intialiser [Classe d'article](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Propriétés ainsi que l'appel [Méthode de sauvegarde](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) À [Créer XBRL](https://products.aspose.com/finance/net/create/xbrl/) Fichier dans le disque.

{{% blocks/products/pf/feature-page-code h3="C# Code pour créer XBRL fichier en ajoutant un élément" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Créer OFX fichiers de demande et de réponse" %}}


Pour générer des fichiers OFX, le API fournit [OfxDemestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Et [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Les classes et les développeurs peuvent facilement [Créer OFX demande](https://products.aspose.com/finance/net/create/ofx-request/) Et fichiers de réponse dans les deux formats 1.03 et 2.2. Pour l'initialisation des propriétés OfxRequestDocument, API fournit également d'autres classes telles que [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Institution financière](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) Et [StatementDemande de transaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Classes. De même, pour l'intialisation des propriétés OfxResponseDocument, API fournit des classes de soutien telles que [SignonRéponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionRéponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) Et [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Vous trouverez ci-dessous les extraits de code pour les deux cas avec l'utilisation de classes appropriées pertinentes.

{{% blocks/products/pf/feature-page-code h3="C# Code pour générer OFX demandes de documents" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code pour générer OFX Documents de réponse" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}