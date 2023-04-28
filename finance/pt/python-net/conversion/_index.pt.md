---
title: Converter relatórios financeiros por meio de Python
url: /pt/python-net/conversion/
description:  Python código para converter relatórios financeiros nos formatos de arquivo XBRL, iXBRL(inline xbrl) e OFX por meio da biblioteca Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter arquivos de relatórios financeiros por meio de Python" h2="Conversão de formatos de relatório financeiro, incluindo arquivo XBRL, iXBRL e OFX do formato 1.03 para 2.2 em aplicativos baseados em Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance para Python via .NET](https://products.aspose.com/finance/python-net/) é um recurso rico, extensível e fácil de usar API. Os desenvolvedores podem validar facilmente XBRL instâncias, bases de links e esquemas de taxonomia usando o método validate() que deve estar em conformidade com os requisitos de sintaxe impostos na especificação. Além disso, eles podem ler os formatos XBRL, iXBRL, bem como criar instâncias XBRL do zero. Além disso, eles podem **converter o formato XBRL** para iXBRL e arquivos XLSX do Microsoft Excel. API também suporta a criação de solicitação/resposta no formato de troca financeira aberta (OFX) e converte a solicitação/resposta de arquivo OFX do formato 1.03 para 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converter OFX arquivos de resposta e solicitação" %}}

API oferece suporte à criação de OFX arquivos de solicitação e resposta fornecendo duas classes. OfxRequestDocument para criar e carregar OFX arquivos de solicitação nos formatos 1.03 e 2.2 e OfxResponseDocument para OFX arquivos de resposta nos formatos 1.03 e 2.2. Além disso, OfxVersionEnum Enumeration tendo membros V1x que é versão 1.x, formato de arquivo sgml e versão V2x 2.x, formato de arquivo xml. Depois de chamar o método save da classe OfxRequestDocument ou da classe OfxResponseDocument, os desenvolvedores podem converter facilmente do arquivo sgml 1.03 para o formato xml 2.2.


{{% blocks/products/pf/feature-page-code h3="C# Código para converter OFX arquivos de resposta" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para converter OFX arquivos de solicitação" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversão de relatórios financeiros" %}}

API suporta a conversão de arquivos XBRL para iXBRL e formato Microsoft® Excel XLSX. O processo de conversão é simples, primeiro carregue o arquivo via XbrlDocument Class. Use a classe SaveOptions para SaveFormat, para ser usado como parâmetro no método save da classe XbrlDocument. Para salvar no arquivo iXBLR, será usado SaveFormat.IXBRL e para exportar para o formato XLSX, será usado SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="Python Código para exportar XBRL para iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Código para conversão de XBRL para XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}