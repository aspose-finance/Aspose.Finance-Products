---
title: .NETを介して財務レポートを作成する
url: /ja/net/create/
description:  XBRLで財務レポートを作成するためのC#コード、および.NETライブラリを介したOFX要求または応答ファイル。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#を介して財務報告ファイルを作成する" h2=".NETベースのアプリケーション内の1.03または2.2形式のXBRLおよびOFX要求または応答ファイルを含む財務レポート形式の作成。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) は機能が豊富で、拡張可能で、使いやすい財務レポートの作成と処理APIです。開発者は、XBRLインスタンスを最初から簡単に作成できるだけでなく、スキーマ参照、コンテキスト、ユニット、アイテム、脚注リンク、役割参照、および 
アークロールリファレンス。 APIは、コンテキストなどの各機能に関連するクラスを提供し、開発者は使用できます [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod)、 [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) と [環境](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)。 
さらに、APIは、1.03または2.2形式のOpen Financial Exchange（OFX）形式の要求/応答の作成もサポートしています。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="アイテムを追加してXBRLファイルを作成" %}}

XBRLファイルを作成し、ドキュメントにアイテムを追加するためのプロセスは、次のとおりです。 [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 実例。次のような適切なAPIクラスを使用して、アイテムに関連する設定を準備します。 [SchemaRefクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)、上記の関連するコンテキストクラスと [コンセプトクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept)。最後に、定義して初期化します [アイテムクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) プロパティだけでなく、 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) に [XBRLを作成](https://products.aspose.com/finance/net/create/xbrl/) ディスクにファイルします。

{{% blocks/products/pf/feature-page-code h3="C#アイテムを追加してXBRLファイルを作成するコード" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFXリクエストファイルとレスポンスファイルを作成する" %}}


OFXファイルを生成するために、APIは [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) と [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) クラスと開発者は簡単にできます [OFXリクエストを作成](https://products.aspose.com/finance/net/create/ofx-request/) および1.03形式と2.2形式の両方の応答ファイル。 OfxRequestDocumentプロパティを初期化するために、APIは次のような他のクラスも提供します。 [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)、 [FinancialInstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) と [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) クラス。同様に、OfxResponseDocumentプロパティを初期化するために、APIは次のようなサポートクラスを提供します。 [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)、  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) と [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)。以下は、関連する適切なクラスを使用した両方の場合のコードスニペットです。

{{% blocks/products/pf/feature-page-code h3="C#OFXリクエストドキュメントを生成するコード" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C#OFX応答ドキュメントを生成するコード" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}