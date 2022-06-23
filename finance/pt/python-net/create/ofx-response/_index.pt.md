---
title: Criar arquivo de resposta OFX por meio de Python
description: Código de amostra para criação do arquivo de resposta OFX. Use o código de exemplo API para geração de arquivos de resposta em lote OFX em aplicativos baseados em Python. 
url: /pt/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crie OFX arquivos de resposta por meio de Python" h2="OFX criação de arquivos de resposta sem precisar do Microsoft Office instalado ou qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como criar OFX arquivos de resposta" %}}

Siga as etapas no trecho de código ou aprimore-o conforme as necessidades do seu aplicativo após ter os requisitos de criação em seu aplicativo.

1. Crie o objeto de classe OfxResponseDocument.1. Atribua as propriedades relevantes usando diferentes classes fornecidas por API como SignonResponse, StatementTransactionResponse, StatementTransaction1. Use o ofxVersion V2x ou V1x para arquivos xml e sgml respectivamente do OfxVersionEnum como parâmetro no método save.1. Chame o método save fornecendo o arquivo de destino e ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de Criação" %}}
Para prosseguir com a criação do arquivo de resposta OFX, certifique-se de ter os seguintes pré-requisitos. 
- SO baseado em Microsoft Windows ou Linux.- Python 3.5 ou posterior.- Aspose.Finance para Python referenciado em seu projeto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python código para criação de arquivos de resposta OFX" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de criação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Arquivo de solicitação" description="Formato 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Arquivo" description="Linguagem Extensível de Relatórios de Negócios" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}