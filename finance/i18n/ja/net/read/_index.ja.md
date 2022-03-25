---
title: .NET 経由で財務レポートを読む
url: /ja/net/read/
description:  .NET ライブラリ経由で XBRL および iXBRL ファイルの財務報告を読み取るための C# コード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 経由で財務報告ファイルを読む" h2=".NET ベースのアプリケーション内で XBRL および iXBRL を含む財務報告の形式を読み取ります。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) は、豊富で拡張可能で使いやすい財務レポート処理 API の機能です。開発者は、ビジネスおよび金融ソリューション用の XBRL および iXBRL 形式を簡単にロード、表示、または作成できます。 API は [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) クラスと  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 有効な XBRL および iXBRL ファイルをロードするためのクラス。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL ドキュメントを読む" %}}

表示と分析のために既存のファイルをロードするには、 XBRL ファイルを読み取る必要があります。XBLRドキュメントを読み取るために、 API は上記の段落で説明したXbrlDocumentクラスに有効な XBRL ファイルを入力パラメーターとして提供します。他の API クラスを使用すると、開発者はその構造とデータを簡単に分析できます。クラスのいくつかは [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)、 [コンテキスト](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)、 [単位](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit)を使用します。

{{% blocks/products/pf/feature-page-code h3="C# ファイルを読み取るコード XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL ドキュメントを読む" %}}

前述のように、既存のデータを見たり、分析したり、編集したりする必要がある場合、 iXBRL ファイルを読み取る必要があります。それを読むために、 API はパラメータとして有効な iXBRL ファイルを持つInlineXbrlDocumentクラスを提供します。プログラマーはのようなクラスを利用できます [InlineFact](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact)、 [コンテキスト](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)、 [単位](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) そのデータと構造を表示します。 

{{% blocks/products/pf/feature-page-code h3="C# ドキュメントを読むコード iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Read" >}}