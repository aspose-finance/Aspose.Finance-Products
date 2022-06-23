---
title: Python経由でiXBRLファイルを表示
description: iXBRLファイル表示のサンプルコード。 APIサンプルコードを使用して、Pythonベースのアプリケーション内のバッチiXBRLファイルを表示します。 
url: /ja/python-net/view/ixbrl/
family: finance
platformtag: python
feature: view
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python経由でiXBRLファイルを表示" h2="Microsoft Officeやその他のソフトウェアをインストールせずに、財務レポートをiXBRL形式で表示します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="iXBRLファイルを表示する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語iXBRLドキュメントを表示するためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に読み取り要件があることを確認してください。

1. InlineXbrlDocumentクラスインスタンスを作成します。2.有効なiXBRLファイルの名前をパラメーターとして渡します。
3.ファイルの内部の詳細を取得するには、InlineFact、Context、Unitなどの関連するクラスを使用します
4.これらの情報を表示します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="読書要件" %}}
iXBRLドキュメントの表示に進むには、次の前提条件があることを確認してください。 
- MicrosoftWindowsまたはLinuxベースのOS。- Python3.5以降。- プロジェクトで参照されているPythonのAspose.Finance。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="iXBRLファイルを読み取るためのPythonコード" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "read-ixbrl-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の表示オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/view/xbrl/" name="XBRL" description="拡張可能なビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}