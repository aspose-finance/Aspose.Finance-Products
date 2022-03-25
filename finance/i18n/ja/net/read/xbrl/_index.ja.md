---
title: C# 経由で XBRL ファイルを読む
description: XBRL ファイル読み取り用のサンプルコード。 API サンプルコードを使用して、 .NET ベースのアプリケーション内のバッチ XBRL ファイルを読み取ります。 
url: /ja/net/read/xbrl/
family: finance
platformtag: net
feature: read
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 経由で XBRL ファイルを読む" h2="Microsoft Officeをインストールしたり、その他のソフトウェアを必要とせずに、 XBRL 形式で財務レポートを読み取ります。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL ファイルを読む方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語 XBRL ファイルを読み取るためのアプリケーションのニーズに応じて強化します。アプリケーション内に読み取り要件があることを確認してください。

1. 作成 [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) インスタンス1. 有効な XBRL ファイルの名前をパラメーターとして渡します。1. ファイルの内部詳細を取得するには、次のような関連クラスを使用します。 [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)、 [コンテキスト](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)、 [単位](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="読書要件" %}}
XBRL ドキュメントの読み取りを続行するには、 .NET Finance API がアプリケーションに含める主な要件です。 
- コマンドラインを介して「 'nuget install Aspose.Finance 」として、またはVisual StudioのPackage Manager Consoleを介して「Install-Package Aspose.Finance 」でインストールします。
- または、オフラインのMSIインストーラーまたはZIPファイルのDLLを [ダウンロード](https://downloads.aspose.com/finance/net)を使用します。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL ファイルを読み取るための C# コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の読み取りオプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="インライン拡張ビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}