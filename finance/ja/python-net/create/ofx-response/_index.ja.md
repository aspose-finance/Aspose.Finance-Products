---
title: Pythonを介してOFX応答ファイルを作成します
description: OFX応答ファイル作成のサンプルコード。 Pythonベースのアプリケーション内でバッチOFX応答ファイルを生成するには、APIサンプルコードを使用します。 
url: /ja/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pythonを介してOFX応答ファイルを作成する" h2="MicrosoftOfficeやその他のソフトウェアをインストールせずにOFX応答ファイルを作成します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX応答ファイルを作成する方法" %}}

コードスニペットの手順に従うか、アプリケーション内に作成要件を設定した後、アプリケーションのニーズに応じてコードスニペットを拡張します。

1. OfxResponseDocumentクラスオブジェクトを作成します。1. SignonResponse、StatementTransactionResponse、StatementTransactionなど、APIが提供するさまざまなクラスを使用して関連するプロパティを割り当てます1. saveメソッドのパラメーターとして、OfxVersionEnumのxmlファイルとsgmlファイルにそれぞれofxVersionV2xまたはV1xを使用します。1. ターゲットファイルとofxVersionを指定して、saveメソッドを呼び出します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="作成要件" %}}
OFX応答ファイルの作成に進むには、次の前提条件があることを確認してください。 
- MicrosoftWindowsまたはLinuxベースのOS。- Python3.5以降。- プロジェクトで参照されているPythonのAspose.Finance。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX応答ファイルを作成するためのPythonコード" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の作成オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFXリクエストファイル" description="1.03または2.2フォーマット" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRLファイル" description="拡張可能なビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}