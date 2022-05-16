---
title: C#経由でiXBRLファイルを表示
description: iXBRLファイル表示のサンプルコード。 APIサンプルコードを使用して、.NETベースのアプリケーション内のバッチiXBRLファイルを表示します。 
url: /ja/net/view/ixbrl/
family: finance
platformtag: net
feature: view
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#経由でiXBRLファイルを表示" h2="Microsoft Officeやその他のソフトウェアをインストールせずに、財務レポートをiXBRL形式で表示します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="iXBRLファイルを表示する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語iXBRLドキュメントを表示するためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に読み取り要件があることを確認してください。

1. 作成 [InlineXbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 実例。2.有効なiXBRLファイルの名前をパラメーターとして渡します。
3.ファイルの内部の詳細を取得するには、次のような関連するクラスを使用します。 [InlineFact](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact)、 [環境](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)、 [単位](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4.これらの情報を表示します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="読書要件" %}}
iXBRLドキュメントの表示に進むには、.NETFinanceAPIがアプリケーションに含まれる主な要件です。 
- コマンドラインから```nuget install Aspose.Finance```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Finance```を使用してインストールします。
- または、オフラインのMSIインストーラーまたはDLLをZIPファイルで取得します。 [ダウンロード](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="iXBRLファイルを読み取るためのC#コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の表示オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/xbrl/" name="XBRL" description="拡張可能なビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}