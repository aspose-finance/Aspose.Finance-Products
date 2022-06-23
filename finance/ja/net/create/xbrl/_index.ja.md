---
title: C#を介してXBRLファイルを作成します
description: XBRLファイル作成のサンプルコード。 .NETベースのアプリケーション内でのバッチXBRLファイルの生成にはAPIサンプルコードを使用します。 
url: /ja/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#を介してXBRLファイルを作成する" h2="MicrosoftOfficeやその他のソフトウェアをインストールせずにXBRLファイルを作成できます。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRLファイルの作成方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語XBRLファイルを生成するためのアプリケーションのニーズに応じてコードスニペットを拡張します。アプリケーション内に作成要件があることを確認してください。

1. 作成 [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 実例。1. 新しいXBRLインスタンスドキュメントを作成するには [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) と [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance)。1. を使用してスキーマ参照を追加する [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. アプリケーションの性質に応じて、コンテキスト、ユニット、アイテム、脚注リンクなどを追加します。1. 電話する [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) ターゲットファイルのパスを指定します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="作成要件" %}}
XBRLドキュメントの生成を続行するには、.NETFinanceAPIがアプリケーションに含まれる主な要件です。 
- コマンドラインから```nuget install Aspose.Finance```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから`` `Install-PackageAspose.Finance```を使用してインストールします。
- または、オフラインのMSIインストーラーまたはDLLをZIPファイルで取得します。 [ダウンロード](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRLファイル作成用のC#コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の作成オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFXリクエスト" description="1.03または2.2フォーマット" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX応答" description="1.03または2.2フォーマット" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}