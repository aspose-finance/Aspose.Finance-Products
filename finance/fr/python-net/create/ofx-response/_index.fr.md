---
title: Créer OFX fichier de réponse via Python
description: Exemple de code pour la création du fichier de réponses OFX. Utilisez l'exemple de code API pour la génération de fichiers de réponse par lots OFX dans les applications basées sur Python. 
url: /fr/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Créer OFX fichiers de réponse via Python" h2="OFX création de fichiers de réponse sans avoir besoin d\'installer Microsoft Office ou tout autre logiciel." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer OFX fichiers de réponse" %}}

Suivez les étapes de l'extrait de code ou améliorez-le en fonction des besoins de votre application après avoir défini les exigences de création dans votre application.

1. Créez un objet de classe OfxResponseDocument.1. Attribuez les propriétés pertinentes à l'aide de différentes classes fournies par API comme SignonResponse, StatementTransactionResponse, StatementTransaction1. Utilisez ofxVersion V2x ou V1x pour les fichiers xml et sgml respectivement à partir d'OfxVersionEnum comme paramètre dans la méthode de sauvegarde.1. Appelez la méthode save en fournissant le fichier cible et ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigence de création" %}}
Pour procéder à la création du fichier de réponse OFX, assurez-vous que vous disposez des prérequis suivants. 
- Système d'exploitation basé sur Microsoft Windows ou Linux.- Python 3.5 ou version ultérieure.- Aspose.Finance pour Python référencé dans votre projet.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python code pour la création de OFX fichiers de réponse" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres options de création" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX fichier de demande" description="Format 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Fichier" description="Langage de reporting métier extensible" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}