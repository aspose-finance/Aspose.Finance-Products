---
title: C#を介してiXBRLファイルを検証します
description: iXBRLファイル検証のサンプルコード。 APIサンプルコードを使用して、.NETベースのアプリケーション内のバッチiXBRLファイルを検証します。 
url: /ja/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#を介してiXBRLファイルを検証します" h2="Microsoft Officeやその他のソフトウェアをインストールせずに、iXBRL形式の財務レポートを検証します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="iXBRLファイルを検証する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語iXBRLドキュメントを検証するためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に検証要件があることを確認してください。

1. を使用してiXBRLファイルをロードします [InlineXbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 実例。1. ロードされたファイルの有効性をチェックし、それがと一致する必要があるようにする [iXBRL仕様](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. 使用する [検証（）](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) ファイルの有効性の方法。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="検証要件" %}}
iXBRLドキュメントの検証に進むには、.NETFinanceAPIがアプリケーションに含まれる主な要件です。 
- コマンドラインから```nuget install Aspose.Finance```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Finance```を使用してインストールします。
- または、オフラインのMSIインストーラーまたはDLLをZIPファイルで取得します。 [ダウンロード](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="iXBRLファイルを検証するためのC#コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の検証オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="拡張可能なビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}