---
title: C# 経由で OFX リクエストファイルを作成
description: OFX リクエストファイル作成のサンプルコード。 .NET ベースのアプリケーション内でのバッチ OFX リクエストファイル生成には、 API サンプルコードを使用します。 
url: /ja/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 経由で OFX リクエストファイルを作成" h2="OFX は、Microsoft Officeのインストールやその他のソフトウェアを必要とせずにファイルの作成をリクエストします。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX リクエストファイルを作成する方法" %}}

アプリケーション内で OFX リクエストファイルの作成要件を取得した後、コードスニペットの手順に従うか、要件に応じて強化します。

1. 作成 [OfxRequestDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) オブジェクト1. API が提供するさまざまなクラスを使用して関連するプロパティを割り当てます。 [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)、 [金融機関](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution)、 [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. XmlおよびsgmlファイルにそれぞれofxVersion V2xまたはV1xを使用します。 [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Saveメソッドのパラメーターとして1. を呼び出す [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) ターゲットファイルとofxVersionを提供します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="作成要件" %}}
OFX リクエストファイルの作成を続行するには、 .NET Finance API がレポート生成アプリケーションに含める主な要件です。 
- コマンドラインを介して「 'nuget install Aspose.Finance 」として、またはVisual StudioのPackage Manager Consoleを介して「Install-Package Aspose.Finance 」でインストールします。
- または、オフラインのMSIインストーラーまたはZIPファイルのDLLを [ダウンロード](https://downloads.aspose.com/finance/net)を使用します。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX リクエストファイル作成の C# コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の作成オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX 応答ファイル" description="1.03または2.2フォーマット" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ファイル" description="拡張ビジネスレポート言語" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}