---
title: Pythonを介してOFXリクエストファイルを作成します
description: OFXリクエストファイル作成のサンプルコード。 Pythonベースのアプリケーション内でバッチOFXリクエストファイルを生成するには、APIサンプルコードを使用します。 
url: /ja/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pythonを介してOFXリクエストファイルを作成します" h2="OFXMicrosoftOfficeやその他のソフトウェアをインストールせずにファイルの作成を要求します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFXリクエストファイルを作成する方法" %}}

アプリケーション内にOFXリクエストファイルの作成要件を設定したら、コードスニペットの手順に従うか、要件に応じてファイルを拡張します。

1. OfxRequestDocumentクラスオブジェクトを作成します。2. SignonRequest、FinancialInstitution]、StatementTransactionRequestなどのAPIによって提供されるさまざまなクラスを使用して、関連するプロパティを割り当てます
3. Saveメソッドのパラメーターとして、OfxVersionEnumのxmlファイルとsgmlファイルにそれぞれofxVersionV2xまたはV1xを使用します。
4.ターゲットファイルとofxVersionを指定して、saveメソッドを呼び出します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="作成要件" %}}
OFXリクエストファイルの作成に進むには、次の前提条件があることを確認してください。 
- MicrosoftWindowsまたはLinuxベースのOS。- Python3.5以降。- プロジェクトで参照されているPythonのAspose.Finance。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFXリクエストファイルを作成するためのPythonコード" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の作成オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX応答ファイル" description="1.03または2.2フォーマット" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRLファイル" description="拡張可能なビジネスレポート言語" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}