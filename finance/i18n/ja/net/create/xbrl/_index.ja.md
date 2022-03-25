---
title: C# 経由で XBRL ファイルを作成
description: XBRL ファイル作成のサンプルコード。 .NET ベースのアプリケーション内でのバッチ XBRL ファイル生成には、 API サンプルコードを使用します。 
url: /ja/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 経由で XBRL ファイルを作成" h2="インストールされたMicrosoft Officeやその他のソフトウェアを必要とせずに XBRL ファイルを作成。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL 個のファイルを作成する方法" %}}

コードスニペットの手順に従うか、拡張可能なビジネスレポート言語 XBRL ファイルを生成するためのアプリケーションのニーズに応じて強化します。アプリケーション内に作成要件があることを確認してください。

1. 作成 [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) インスタンス1. 新しい XBRL インスタンスドキュメントを作成するには [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) と [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance)を使用します。1. を使用してスキーマ参照を追加 [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. アプリケーションの性質に応じて、コンテキスト、ユニット、アイテム、脚注リンクなどを追加します。1. を呼び出す [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) ターゲットファイルのパスを提供します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="作成要件" %}}
XBRL ドキュメントの生成を進めるには、 .NET Finance API がアプリケーションに含まれる主な要件です。 
- コマンドラインを介して「 'nuget install Aspose.Finance 」として、またはVisual StudioのPackage Manager Consoleを介して「Install-Package Aspose.Finance 」でインストールします。
- または、オフラインのMSIインストーラーまたはZIPファイルのDLLを [ダウンロード](https://downloads.aspose.com/finance/net)を使用します。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 個のファイルを作成するための C# コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他の作成オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX リクエスト" description="1.03または2.2フォーマット" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX 応答" description="1.03または2.2フォーマット" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}