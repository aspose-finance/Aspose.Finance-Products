---
title: C#経由でXBRLファイルを表示
description: XBRLファイル表示のサンプルコード。 APIサンプルコードを使用して、.NETベースのアプリケーション内のバッチXBRLファイルを表示します。 
url: /ja/net/view/xbrl/
family: finance
platformtag: net
feature: view
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#経由でXBRLファイルを表示" h2="Microsoft Officeやその他のソフトウェアをインストールせずに、財務レポートをXBRL形式で表示します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRLファイルを表示する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語XBRLファイルを読み取るためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に読み取り要件があることを確認してください。

1. 作成 [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 実例。2.有効なXBRLファイルの名前をパラメーターとして渡します。
3.ファイルの内部の詳細を取得するには、次のような関連するクラスを使用します。 [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)、 [環境](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)、 [単位](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4.これらの情報を表示します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="読書要件" %}}
XBRLドキュメントの表示に進むには、.NETFinanceAPIがアプリケーションに含まれる主な要件です。 
- コマンドラインから```nuget install Aspose.Finance```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから`` `Install-PackageAspose.Finance```を使用してインストールします。
- または、オフラインのMSIインストーラーまたはDLLをZIPファイルで取得します。 [ダウンロード](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRLファイルを読み取るためのC#コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の表示オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/ixbrl/" name="iXBRL" description="インライン拡張可能ビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}