---
title: Pythonを介して財務レポートを作成する
url: /ja/python-net/create/
description:  XBRLで財務レポートを作成するためのPythonコード、およびPythonライブラリを介したOFX要求または応答ファイル。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pythonを介して財務報告ファイルを作成する" h2="Pythonベースのアプリケーション内の1.03または2.2形式のXBRLおよびOFX要求または応答ファイルを含む財務レポート形式の作成。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET経由のPythonの場合はAspose.Finance](https://products.aspose.com/finance/python-net/) は機能が豊富で、拡張可能で、使いやすい財務レポートの作成と処理APIです。開発者は、XBRLインスタンスを最初から簡単に作成できるだけでなく、スキーマ参照、コンテキスト、ユニット、アイテム、脚注リンク、役割参照、および 
アークロールリファレンス。 APIは、コンテキストなどの各機能に関連するクラスを提供します。開発者はContextPeriod、ContextEntity、Contextを使用できます。 
さらに、APIは、1.03または2.2形式のOpen Financial Exchange（OFX）形式の要求/応答の作成もサポートしています。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="アイテムを追加してXBRLファイルを作成" %}}

XBRLファイルを作成し、ドキュメントにアイテムを追加するためのプロセスは、XbrlDocumentクラスインスタンスを作成することです。 SchemaRefクラス、上記の関連するコンテキストクラス、Conceptクラスなどの適切なAPIクラスを使用して、アイテムに関連する設定を準備します。最後に、Itemクラスのプロパティを定義して初期化し、saveメソッドを呼び出してXBRLファイルをディスクに作成します。

{{% blocks/products/pf/feature-page-code h3="Pythonアイテムを追加してXBRLファイルを作成するコード" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFXリクエストファイルとレスポンスファイルを作成する" %}}


OFXファイルを生成するために、APIはOfxRequestDocumentクラスとOfxResponseDocumentクラスを提供し、開発者は簡単に [OFXリクエストを作成](https://products.aspose.com/finance/python-net/create/ofx-request/) および1.03形式と2.2形式の両方の応答ファイル。 OfxRequestDocumentプロパティを初期化するために、APIはSignonRequest、FinancialInstitution、StatementTransactionRequestクラスなどの他のクラスも提供します。同様に、OfxResponseDocumentプロパティを初期化するために、APIはSignonResponse、StatementTransactionResponse、StatementTransactionなどのサポートクラスを提供します。以下は、関連する適切なクラスを使用した両方の場合のコードスニペットです。

{{% blocks/products/pf/feature-page-code h3="PythonOFXリクエストドキュメントを生成するコード" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="PythonOFX応答ドキュメントを生成するコード" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}