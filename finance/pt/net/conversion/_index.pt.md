---
title: Converter relatórios financeiros por meio de .NET
url: /pt/net/conversion/
description:  C# código para converter relatórios financeiros nos formatos de arquivo XBRL, iXBRL(inline xbrl) e OFX por meio da biblioteca .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter arquivos de relatórios financeiros por meio de C#" h2="Conversão de formatos de relatório financeiro, incluindo arquivo XBRL, iXBRL e OFX do formato 1.03 para 2.2 em aplicativos baseados em .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) é um recurso rico, extensível e fácil de usar API. Os desenvolvedores podem validar facilmente XBRL instâncias, bases de links e esquemas de taxonomia usando [valid() método](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) que devem cumprir os requisitos de sintaxe impostos na especificação. Além disso, eles podem ler os formatos XBRL, iXBRL e criar instâncias XBRL do zero. Além disso, eles podem **converter o formato XBRL** para iXBRL e arquivos XLSX do Microsoft Excel. API também suporta a criação de solicitação/resposta no formato de troca financeira aberta (OFX) e converte a solicitação/resposta de arquivo OFX do formato 1.03 para 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converter OFX arquivos de resposta e solicitação" %}}

API oferece suporte à criação de OFX arquivos de solicitação e resposta fornecendo duas classes. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) para criar e carregar OFX arquivos de solicitação nos formatos 1.03 e 2.2 e [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) para arquivos de resposta OFX nos formatos 1.03 e 2.2. Além disso, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumeração com membros V1x que é versão 1.x, formato de arquivo sgml e versão V2x 2.x, formato de arquivo xml. Depois de chamar o método Save da classe OfxRequestDocument ou da classe OfxResponseDocument, os desenvolvedores podem converter facilmente do arquivo sgml 1.03 para o formato xml 2.2.


{{% blocks/products/pf/feature-page-code h3="C# Código para converter OFX arquivos de resposta" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para converter OFX arquivos de solicitação" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversão de relatórios financeiros" %}}

API suporta a conversão de arquivos XBRL para iXBRL e formato Microsoft® Excel XLSX. O processo de conversão é simples, primeiro carregue o arquivo via [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Use o [Classe SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) por [Salvar formato](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), para ser usado como parâmetro no método Save da classe XbrlDocument. Para salvar no arquivo iXBLR, [Salvar formato.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) será usado e para exportar para o formato XLSX, será usado SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Código para exportar XBRL para iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para conversão de XBRL para XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}