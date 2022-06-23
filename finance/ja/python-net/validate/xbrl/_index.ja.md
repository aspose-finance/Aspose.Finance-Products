---
title: Pythonを介してXBRLファイルを検証します
description: XBRLファイル検証のサンプルコード。 APIサンプルコードを使用して、Pythonベースのアプリケーション内のバッチXBRLファイルを検証します。 
url: /ja/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pythonを介してXBRLファイルを検証します" h2="Microsoft Officeやその他のソフトウェアをインストールせずに、XBRL形式の財務レポートを検証します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRLファイルを検証する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語XBRLドキュメントを検証するためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に検証要件があることを確認してください。

1. XbrlDocumentクラスインスタンスを使用してXBRLファイルをロードします。2.ロードされたファイルの有効性をチェックし、それがと一致する必要があるようにする [XBRL仕様](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3.有効性を確認するには、XbrlInstanceクラスのvalidateメソッドを使用します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="検証要件" %}}
XBRLドキュメントの検証に進むには、次の前提条件があることを確認してください。 
- MicrosoftWindowsまたはLinuxベースのOS。- Python3.5以降。- プロジェクトで参照されているPythonのAspose.Finance。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRLファイルを検証するためのPythonコード" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の検証オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="インライン拡張可能ビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}