---
title: C# 経由で XBRL ファイルを検証
description: XBRL ファイル検証用のサンプルコード。 API サンプルコードを使用して、 .NET ベースのアプリケーション内のバッチ XBRL ファイルを検証します。 
url: /ja/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# を介して XBRL ファイルを検証" h2="Microsoft Officeのインストールやその他のソフトウェアを必要とせずに、 XBRL 形式の財務レポートを検証します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL ファイルを検証する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語 XBRL ドキュメントを検証するためのアプリケーションのニーズに応じて強化します。アプリケーション内の要件を検証してください。

1. を使用して XBRL ファイルをロード [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) インスタンス1. ロードされたファイルの有効性をチェックするには、 [XBRL 仕様](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Validatityを確認するには、を使用します。 [検証 ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) メソッドの [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) クラスです。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="検証要件" %}}
XBRL ドキュメントの検証を進めるには、 .NET Finance API がアプリケーションに含まれる主な要件です。 
- コマンドラインを介して「 'nuget install Aspose.Finance 」として、またはVisual StudioのPackage Manager Consoleを介して「Install-Package Aspose.Finance 」でインストールします。
- または、オフラインのMSIインストーラーまたはZIPファイルのDLLを [ダウンロード](https://downloads.aspose.com/finance/net)を使用します。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL ファイルを検証するための C# コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の検証オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="インライン拡張ビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}