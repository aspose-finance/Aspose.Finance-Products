---
title: .NETを介して財務報告を読む
url: /ja/net/read/
description:  .NETライブラリを介してXBRLおよびiXBRLファイルの財務レポートを読み取るためのC#コード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#を介して財務報告ファイルを読む" h2=".NETベースのアプリケーション内でXBRLおよびiXBRLを含む財務レポート形式を読み取る。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) は、豊富で拡張性があり、使いやすい財務レポート処理APIの機能です。開発者は、ビジネスおよび金融ソリューション用のXBRLおよびiXBRL形式を簡単にロード、表示、または作成できます。 APIは提供します [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) クラスと  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 有効なXBRLおよびiXBRLファイルをロードするためのクラス。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRLドキュメントを読む" %}}

表示および分析のために既存のファイルをロードするには、XBRLファイルを読み取る必要があります。 XBLRドキュメントを読み取るために、APIは、上記の段落で説明したXbrlDocumentクラスに、入力パラメーターとして有効なXBRLファイルを提供します。他のAPIクラスを使用すると、開発者はその構造とデータを簡単に分析できます。いくつかのクラスは [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)、 [環境](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)、 [単位](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit)。

{{% blocks/products/pf/feature-page-code h3="C#読み取りコードXBRLファイル" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRLドキュメントを読む" %}}

上記のように、既存のデータを表示、分析、または編集する必要がある場合は、iXBRLファイルを読み取る必要があります。それを読むために、APIはパラメータとして有効なiXBRLファイルを持つInlineXbrlDocumentクラスを提供します。プログラマーは次のようなクラスを利用できます [InlineFact](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact)、 [環境](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)、 [単位](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) そのデータと構造を表示します。 

{{% blocks/products/pf/feature-page-code h3="C#読み取るコードiXBRLドキュメント" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Read" >}}