---
title: Pythonを介してXBRLファイルを作成します
description: XBRLファイル作成のサンプルコード。 Pythonベースのアプリケーション内でのバッチXBRLファイルの生成にはAPIサンプルコードを使用します。 
url: /ja/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pythonを介してXBRLファイルを作成する" h2="MicrosoftOfficeやその他のソフトウェアをインストールせずにXBRLファイルを作成できます。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRLファイルの作成方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語XBRLファイルを生成するためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に作成要件があることを確認してください。

1. XbrlDocumentクラスインスタンスを作成します。1. 新しいXBRLインスタンスドキュメントXbrlInstanceCollectionおよびXbrlInstanceを作成します。1. SchemaRefCollectionを使用してスキーマ参照を追加する1. アプリケーションの性質に応じて、コンテキスト、ユニット、アイテム、脚注リンクなどを追加します。1. ターゲットファイルのパスを指定して、saveメソッドを呼び出します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="作成要件" %}}
XBRLドキュメントの生成を続行するには、次の前提条件があることを確認してください。 
- MicrosoftWindowsまたはLinuxベースのOS。- Python3.5以降。- プロジェクトで参照されているPythonのAspose.Finance。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRLファイル作成用のPythonコード" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の作成オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFXリクエスト" description="1.03または2.2フォーマット" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX応答" description="1.03または2.2フォーマット" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}