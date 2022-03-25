---
title: C# 経由で iXBRL ファイルを検証
description: iXBRL ファイル検証用のサンプルコード。 API サンプルコードを使用して、 .NET ベースのアプリケーション内のバッチ iXBRL ファイルを検証します。 
url: /ja/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# を介して iXBRL ファイルを検証" h2="Microsoft Officeのインストールやその他のソフトウェアを必要とせずに、 iXBRL 形式の財務レポートを検証します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="iXBRL ファイルを検証する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語 iXBRL ドキュメントを検証するためのアプリケーションのニーズに応じて強化します。アプリケーション内の要件を検証してください。

1. を使用して iXBRL ファイルをロード [InlineXbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) インスタンス1. ロードされたファイルの有効性をチェックするには、 [iXBRL 仕様](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. 使用 [検証 ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) ファイルの有効性のためのメソッド。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="検証要件" %}}
iXBRL ドキュメントの検証を進めるには、 .NET Finance API がアプリケーションに含まれる主な要件です。 
- コマンドラインを介して「 'nuget install Aspose.Finance 」として、またはVisual StudioのPackage Manager Consoleを介して「Install-Package Aspose.Finance 」でインストールします。
- または、オフラインのMSIインストーラーまたはZIPファイルのDLLを [ダウンロード](https://downloads.aspose.com/finance/net)を使用します。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="iXBRL ファイルを検証するための C# コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の検証オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="拡張ビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}