---
title: Python経由でXBRLファイルを表示
description: XBRLファイル表示のサンプルコード。 APIサンプルコードを使用して、Pythonベースのアプリケーション内のバッチXBRLファイルを表示します。 
url: /ja/python-net/view/xbrl/
family: finance
platformtag: python
feature: view
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python経由でXBRLファイルを表示" h2="Microsoft Officeやその他のソフトウェアをインストールせずに、財務レポートをXBRL形式で表示します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRLファイルを表示する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語XBRLファイルを読み取るためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に読み取り要件があることを確認してください。

1. XbrlDocumentクラスインスタンスを作成します。2.有効なXBRLファイルの名前をパラメーターとして渡します。
3.ファイルの内部詳細を取得するには、SchemaRefCollection、Context、Unitなどの関連するクラスを使用します
4.これらの情報を表示します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="読書要件" %}}
XBRLドキュメントの表示に進むには、次の前提条件があることを確認してください。 
- MicrosoftWindowsまたはLinuxベースのOS。- Python3.5以降。- プロジェクトで参照されているPythonのAspose.Finance。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRLファイルを読み取るためのPythonコード" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "read-xbrl-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の表示オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/view/ixbrl/" name="iXBRL" description="インライン拡張可能ビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}