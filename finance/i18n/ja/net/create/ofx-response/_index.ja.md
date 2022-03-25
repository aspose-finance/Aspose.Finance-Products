---
title: C# 経由で OFX 応答ファイルを作成
description: OFX 応答ファイル作成のサンプルコード。 .NET ベースのアプリケーション内でのバッチ OFX 応答ファイル生成には、 API サンプルコードを使用します。 
url: /ja/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# を介して OFX 応答ファイルを作成" h2="OFX は、Microsoft Officeをインストールしたり、その他のソフトウェアを必要とせずに応答ファイルを作成します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX 応答ファイルを作成する方法" %}}

コードスニペットの手順に従うか、アプリケーション内で作成要件を満たした後、アプリケーションのニーズに応じて強化します。

1. 作成 [OfxResponseDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) オブジェクト1. API が提供するさまざまなクラスを使用して関連するプロパティを割り当てます。 [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)、  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse)、 [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. XmlおよびsgmlファイルにそれぞれofxVersion V2xまたはV1xを使用します。 [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Saveメソッドのパラメーターとして1. を呼び出す [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) ターゲットファイルとofxVersionを提供します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="作成要件" %}}
OFX レスポンスファイルの作成を進めるには、 .NET Finance API がレポート生成アプリケーションに含まれる主な要件です。 
- コマンドラインを介して「 'nuget install Aspose.Finance 」として、またはVisual StudioのPackage Manager Consoleを介して「Install-Package Aspose.Finance 」でインストールします。
- または、オフラインのMSIインストーラーまたはZIPファイルのDLLを [ダウンロード](https://downloads.aspose.com/finance/net)を使用します。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX 件のレスポンスファイルを作成するための C# コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の作成オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX リクエストファイル" description="1.03または2.2フォーマット" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ファイル" description="拡張ビジネスレポート言語" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}