---
title: Criar arquivo XBRL via Python
description: Código de amostra para criação de arquivo XBRL. Use o código de exemplo API para geração de arquivos em lote XBRL em aplicativos baseados em Python. 
url: /pt/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crie arquivos XBRL por meio de Python" h2="XBRL criação de arquivos sem precisar do Microsoft Office instalado ou qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como criar arquivos XBRL" %}}

Siga as etapas no snippet de código ou aprimore-o conforme as necessidades do seu aplicativo para gerar arquivos extensíveis de linguagem de relatórios de negócios XBRL. Certifique-se de ter requisitos de criação em seu aplicativo.

1. Crie a instância da classe XbrlDocument.1. Para criar um novo documento de instância XBRL XbrlInstanceCollection e XbrlInstance.1. Adicionar referência de esquema usando SchemaRefCollection1. Dependendo da natureza do aplicativo, adicione contexto, unidade, item, link de nota de rodapé e muito mais.1. Chame o método save fornecendo o caminho do arquivo de destino.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de Criação" %}}
Para prosseguir com a geração de documentos XBRL, certifique-se de ter os seguintes pré-requisitos. 
- SO baseado em Microsoft Windows ou Linux.- Python 3.5 ou posterior.- Aspose.Finance para Python referenciado em seu projeto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python código para criação de XBRL arquivos" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de criação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Solicitar" description="Formato 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Resposta" description="Formato 1.03 ou 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}