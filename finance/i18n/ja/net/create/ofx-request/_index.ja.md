---
title: C#を介してOFXリクエストファイルを作成します
description: OFXリクエストファイル作成のサンプルコード。 .NETベースのアプリケーション内でバッチOFXリクエストファイルを生成するには、APIサンプルコードを使用します。 
url: /ja/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#を介してOFXリクエストファイルを作成します" h2="OFXMicrosoftOfficeやその他のソフトウェアをインストールせずにファイルの作成を要求します。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFXリクエストファイルを作成する方法" %}}

アプリケーション内にOFXリクエストファイルの作成要件を設定したら、コードスニペットの手順に従うか、要件に応じて拡張します。

1. 作成 [OfxRequestDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 物体。1. APIによって提供されるさまざまなクラスを使用して関連するプロパティを割り当てます。 [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)、 [FinancialInstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution)、 [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. xmlファイルとsgmlファイルにはそれぞれofxVersionV2xまたはV1xを使用します。 [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Saveメソッドのパラメーターとして。1. 電話する [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) ターゲットファイルとofxVersionを提供します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="作成要件" %}}
OFXリクエストファイルの作成に進むには、.NETFinanceAPIがレポート生成アプリケーションに含まれる主な要件です。 
- コマンドラインから```nuget install Aspose.Finance```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから`` `Install-PackageAspose.Finance```を使用してインストールします。
- または、オフラインのMSIインストーラーまたはDLLをZIPファイルで取得します。 [ダウンロード](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFXリクエストファイルを作成するためのC#コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の作成オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX応答ファイル" description="1.03または2.2フォーマット" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRLファイル" description="拡張可能なビジネスレポート言語" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}