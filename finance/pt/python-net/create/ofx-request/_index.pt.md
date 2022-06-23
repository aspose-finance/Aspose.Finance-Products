---
title: Criar arquivo de solicitação OFX via Python
description: Código de amostra para a criação do arquivo de solicitação OFX. Use o código de exemplo API para geração de arquivos de solicitação em lote OFX em aplicativos baseados em Python. 
url: /pt/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crie OFX arquivos de solicitação por meio de Python" h2="OFX solicite a criação de arquivos sem precisar do Microsoft Office instalado ou de qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como criar arquivos de solicitação OFX" %}}

Depois de ter os OFX requisitos de criação de arquivos de solicitação em seu aplicativo, siga as etapas no snippet de código ou aprimore-o conforme sua necessidade.

1. Crie o objeto de classe OfxRequestDocument.2. Atribua as propriedades relevantes usando diferentes classes fornecidas por API, como SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Use o ofxVersion V2x ou V1x para arquivos xml e sgml respectivamente do OfxVersionEnum como parâmetro no método Save.
4. Chame o método save fornecendo o arquivo de destino e ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de Criação" %}}
Para prosseguir para OFX Solicitar criação de arquivo, certifique-se de ter os seguintes pré-requisitos. 
- SO baseado em Microsoft Windows ou Linux.- Python 3.5 ou posterior.- Aspose.Finance para Python referenciado em seu projeto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python código para criação de arquivos de solicitação OFX" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de criação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Arquivo de resposta" description="Formato 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Arquivo" description="Linguagem Extensível de Relatórios de Negócios" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}