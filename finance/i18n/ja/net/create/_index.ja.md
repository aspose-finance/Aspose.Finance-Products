---
title: .NET 経由で財務レポートを作成
url: /ja/net/create/
description:  XBRL に財務レポートを作成するための C# コード、および .NET ライブラリを介して OFX リクエストまたは応答ファイル。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 経由で財務報告ファイルを作成" h2="XBRL および .NET ベースのアプリケーション内の1.03または2.2形式の OFX リクエストまたはレスポンスファイルを含む財務レポート形式の作成。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) は、豊富で拡張可能で使いやすい財務レポートの作成と処理が API の機能です。開発者は、 XBRL インスタンスを最初から簡単に作成するだけでなく、スキーマ参照、コンテキスト、ユニット、アイテム、脚注リンク、ロール参照、および 
アークの役割参照。 API は、コンテキストなどの機能ごとに関連するクラスを提供し、開発者は [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod)、 [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) と [コンテキスト](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)を使用します。 
さらに、 API は、1.03または2.2形式のオープンファイナンシャルエクスチェンジ (OFX) 形式のリクエスト/レスポンス作成もサポートしています。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="アイテムを追加して XBRL ファイルを作成" %}}

XBRL ファイルを作成し、ドキュメントにアイテムを追加する場合、プロセスは、 [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) インスタンスを使用します。などの適切な API クラスを使用して、アイテムに関連する設定を準備します。 [SchemaRefクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)、前述の関連するコンテキストクラスと [コンセプトクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept)を使用します。最後に定義し、intialize [アイテムクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) プロパティを呼び出すだけでなく、 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) に [XBRL を作成](https://products.aspose.com/finance/net/create/xbrl/) ファイルをディスクに入れます。

{{% blocks/products/pf/feature-page-code h3="C# アイテムを追加して XBRL ファイルを作成するコード" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX 件のリクエストおよび応答ファイルを作成する" %}}


OFX ファイルを生成する場合、 API は [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) と [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) クラスと開発者は簡単にできます [OFX リクエストを作成](https://products.aspose.com/finance/net/create/ofx-request/) と1.03と2.2の両方の形式の応答ファイル。OfxRequestDocumentプロパティを初期化するために、 API は次のような他のクラスも提供します。 [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)、 [金融機関](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) と [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) クラス。同様に、OfxResponseDocumentプロパティを初期化するために、 API は次のようなサポートクラスを提供します。 [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)、  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) と [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)を使用します。以下は、関連する適切なクラスを使用した両方のケースのコードスニペットです。

{{% blocks/products/pf/feature-page-code h3="C# リクエストドキュメントを生成するコード OFX" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# OFX 応答ドキュメントを生成するコード" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}