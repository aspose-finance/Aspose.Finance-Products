---
title: C#を介してXBRLファイルを検証します
description: XBRLファイル検証のサンプルコード。 APIサンプルコードを使用して、.NETベースのアプリケーション内のバッチXBRLファイルを検証します。 
url: /ja/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#を介してXBRLファイルを検証します" h2="Microsoft Officeやその他のソフトウェアをインストールせずに、XBRL形式の財務レポートを検証します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRLファイルを検証する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語XBRLドキュメントを検証するためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に検証要件があることを確認してください。

1. を使用してXBRLファイルをロードします [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 実例。1. ロードされたファイルの有効性をチェックし、それがと一致する必要があるようにする [XBRL仕様](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. 有効性を確認するには、 [検証（）](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) の方法 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) クラス。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="検証要件" %}}
XBRLドキュメントの検証に進むには、.NETFinanceAPIがアプリケーションに含まれる主な要件です。 
- コマンドラインから```nuget install Aspose.Finance```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Finance```を使用してインストールします。
- または、オフラインのMSIインストーラーまたはDLLをZIPファイルで取得します。 [ダウンロード](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRLファイルを検証するためのC#コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の検証オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="インライン拡張可能ビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}