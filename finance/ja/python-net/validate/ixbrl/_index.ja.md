---
title: Pythonを介してiXBRLファイルを検証します
description: iXBRLファイル検証のサンプルコード。 APIサンプルコードを使用して、Pythonベースのアプリケーション内のバッチiXBRLファイルを検証します。 
url: /ja/python-net/validate/ixbrl/
family: finance
platformtag: python
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pythonを介してiXBRLファイルを検証します" h2="Microsoft Officeやその他のソフトウェアをインストールせずに、iXBRL形式の財務レポートを検証します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="iXBRLファイルを検証する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語iXBRLドキュメントを検証するためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に検証要件があることを確認してください。

1. InlineXbrlDocumentクラスインスタンスを使用してiXBRLファイルをロードします。1. ロードされたファイルの有効性をチェックし、それがと一致する必要があるようにする [iXBRL仕様](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. ファイルの有効性にはvalidateメソッドを使用します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="検証要件" %}}
iXBRLドキュメントの検証に進むには、次の前提条件があることを確認してください。 
- MicrosoftWindowsまたはLinuxベースのOS。- Python3.5以降。- プロジェクトで参照されているPythonのAspose.Finance。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="iXBRLファイルを検証するためのPythonコード" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の検証オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/xbrl/" name="XBRL" description="拡張可能なビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}