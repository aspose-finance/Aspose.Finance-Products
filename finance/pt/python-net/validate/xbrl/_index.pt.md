---
title: Validar arquivo XBRL via Python
description: Código de amostra para validação de arquivo XBRL. Use o código de exemplo API para validar arquivos XBRL em lote em aplicativos baseados em Python. 
url: /pt/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Valide XBRL Arquivos por meio de Python" h2="Validação de relatórios financeiros no formato XBRL sem precisar do Microsoft Office instalado ou qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como validar arquivos XBRL" %}}

Siga as etapas no snippet de código ou aprimore-o de acordo com as necessidades do seu aplicativo para validar documentos de linguagem de relatório comercial extensível XBRL. Certifique-se de ter requisitos de validação em seu aplicativo.

1. Carregue o arquivo XBRL usando a instância da classe XbrlDocument.2. Para verificar a validade do arquivo carregado, para que ele corresponda [XBRL especificação](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3. Para verificar a validade, use o método validate da classe XbrlInstance.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de validação" %}}
Para prosseguir com a validação de documentos XBRL, certifique-se de ter os seguintes pré-requisitos. 
- SO baseado em Microsoft Windows ou Linux.- Python 3.5 ou posterior.- Aspose.Finance para Python referenciado em seu projeto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python código para validar XBRL arquivos" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de validação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="Linguagem Extensível de Relatórios de Negócios Inline" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}