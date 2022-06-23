---
title: Pythonを介して財務報告を読む
url: /ja/python-net/read/
description:  Pythonライブラリを介してXBRLおよびiXBRLファイルの財務レポートを読み取るためのPythonコード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pythonを介して財務報告ファイルを読む" h2="Pythonベースのアプリケーション内でXBRLおよびiXBRLを含む財務レポート形式を読み取る。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET経由のPythonの場合はAspose.Finance](https://products.aspose.com/finance/python-net/) は、豊富で拡張性があり、使いやすい財務レポート処理APIの機能です。開発者は、ビジネスおよび金融ソリューション用のXBRLおよびiXBRL形式を簡単にロード、表示、または作成できます。 APIは、有効なXBRLおよびiXBRLファイルをロードするためのXbrlDocumentクラスとInlineXbrlDocumentクラスを提供します。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRLドキュメントを読む" %}}

表示および分析のために既存のファイルをロードするには、XBRLファイルを読み取る必要があります。 XBLRドキュメントを読み取るために、APIは、上記の段落で説明したXbrlDocumentクラスに、入力パラメーターとして有効なXBRLファイルを提供します。他のAPIクラスを使用すると、開発者はその構造とデータを簡単に分析できます。クラスのいくつかは、SchemaRefCollection、Context、Unitです。

{{% blocks/products/pf/feature-page-code h3="Python読み取りコードXBRLファイル" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "read-xbrl-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRLドキュメントを読む" %}}

上記のように、既存のデータを表示、分析、または編集する必要がある場合は、iXBRLファイルを読み取る必要があります。それを読むために、APIはパラメータとして有効なiXBRLファイルを持つInlineXbrlDocumentクラスを提供します。プログラマーは、InlineFact、Context、Unitなどのクラスを利用してデータと構造を表示できます。 

{{% blocks/products/pf/feature-page-code h3="Python読み取るコードiXBRLドキュメント" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "read-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Read" >}}