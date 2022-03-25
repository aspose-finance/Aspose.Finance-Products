---
title: Converter relatórios financeiros via .NET
url: /pt/net/conversion/
description:  C# código para converter Relatórios Financeiros em XBRL, iXBRL e OFX arquivos fomats via .NET biblioteca.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter arquivos de relatório financeiro via C#" h2="Conversão de formatos de relatório financeiro incluindo XBRL, iXBRL e OFX arquivos de formato 1.03 para 2.2 dentro de .NET aplicativos baseados." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) É um recurso rico, extensível e fácil de usar API. Os desenvolvedores podem validar facilmente XBRL instâncias, linkbases e esquemas de taxonomia usando [Validar () método](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Que deve cumprir os requisitos de sintaxe impostos na especificação. Além disso, eles podem ler os formatos XBRL, iXBRL, bem como criar a instância XBRL do zero. Além disso, eles podem ** converter XBRL formato ** para iXBRL e arquivos XLSX do Microsoft Excel. API também oferece suporte à criação de solicitação/resposta de formato de troca financeira aberta (OFX) e converte OFX solicitação/resposta de arquivo do formato 1.03 para 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converter OFX Arquivos de Resposta e Solicitação" %}}

API suporta a criação de OFX arquivos de solicitação e resposta, fornecendo duas classes. [OfxRequestDocumento](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Para criar e carregar OFX arquivos de solicitação nos formatos 1.03 e 2.2 e [OfxResponseDocumento](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Para OFX arquivos de resposta nos formatos 1.03 e 2.2. Além disso, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumeração com membros V1x que é versão 1.x, formato de arquivo sgml e versão V2x 2.x, formato de arquivo xml. Depois de chamar o método Save da classe OfxRequestDocument ou classe OfxResponseDocument, os desenvolvedores podem converter facilmente do arquivo 1.03 sgml para o formato 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Código para converter OFX arquivos de resposta" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para converter OFX arquivos de solicitação" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversão de Relatórios Financeiros" %}}

API suporta a conversão de XBRL arquivos para iXBRL e Microsoft®Formato Excel XLSX. Processo de conversão é simples, em primeiro lugar carregar o arquivo via [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument)... Use o [Classe SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Para [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Para ser usado como parâmetro no método Save de XbrlDocument Class. Para salvar no arquivo iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Será usado e para exportar para o formato XLSX, SaveFormat.XLSX será usado.

{{% blocks/products/pf/feature-page-code h3="C# Código para exportar XBRL para iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para XBRL para conversão XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}