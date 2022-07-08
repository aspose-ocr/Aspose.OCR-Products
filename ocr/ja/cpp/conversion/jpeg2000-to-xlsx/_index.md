﻿---
title:  
weight: 3920
url: /ja/cpp/conversion/jpeg2000-to-xlsx/ 
lang: ja
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: JPEG2000からXLSXへのJava変換のサンプルコード。 WebまたはデスクトップJavaベースのアプリケーション内でのバッチJPEG2000ファイルからXLSXへの変換にAPIサンプルコードを使用します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.OCR" subTitlepfName="C++の場合" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="C++の場合" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/ja/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/ja/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="APIホーム" codeSamplesText="コードサンプル" liveDemosText="ライブデモ" downloadText="ダウンロード" learnText="学び">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java]（https://products.aspose.com/imaging/java）
 スキャンした画像やスマートフォンの写真をJPEG2000形式で処理し、認識されたテキストを含むJPEG2000ドキュメントを作成します。プロジェクトに追加するには、*Aspose.OCR*を取得する必要があります
[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging）またはAsposeMavenリポジトリ構成を指定します
_pom.xml_に次の構成を追加して、Mavenベースのプロジェクトにインストールします。 Graddle、Ivy、Sbtの例については、[リポジトリ]（https://repository.aspose.com/ocr/）を確認してください。

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

C ++ OCRと数行のコードを使用して、JPEG2000画像をXLSXドキュメントに変換するフル機能のアプリケーションを作成できます。

{{% /blocks/products/pf/agp/text %}}

+AsposeOcrクラスのインスタンスを作成します
+ AsposeOCR.asposeocr_page（）メソッドを呼び出す
+JPEG2000ファイルパスをパラメータとして渡します
+ AsposeOCR.asposeocr_pageは、XLSXタイプの文字列またはファイルを返します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

例を実行する前に、[Microsoft.ML.OnnxRuntime]（https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/）1.7.0以降がプロジェクトに追加されていることを確認してください。 NuGetパッケージマネージャーを介してAspose.OCRをインストールすると、自動的にインストールされます。

{{% /blocks/products/pf/agp/text %}}

-NETStandard2.0+互換ソリューション
-プロジェクトで参照されているAspose.OCRfor.NET。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="" offSpacer="true" %}}

```cpp

std::string img_path = "../srcSample.png";

// Prepare buffer for result (in symbols, len_byte = len * sizeof(wchar_t))
const size_t len = 4096;

wchar_t bfr[len] = { 0 };

size_t result = aspose::ocr::page(image_path.c_str(), bfr, len);

//Print result
std::wcout << bfr << L"\n";

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG2000" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="とは" whatIsFormat2="ファイル形式" readMoreFormat="続きを読む">}}
JPEG 2000（JP2）は、画像コーディングシステムであり、最先端の画像圧縮規格です。ウェーブレットテクノロジーを使用して設計されたJPEG2000は、ロスレスコンテンツを任意の品質で一度にコーディングできます。さらに、コーディング効率に実質的なペナルティを課すことなく、JPEG 2000には、同じコンテンツに効果的にアクセスしてデコードし、他のさまざまな解像度や品質に変換する機能があります。 JPEG 2000のコードストリームは非常にスケーラブルであり、空間ランダムアクセスの機能を提供する関心領域があります。テラピクセル単位の寸法と38ビット/サンプルの高精度を備えた最大16384の多様なコンポーネントを備えています。
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" whatIsFormat1="とは" whatIsFormat2="ファイル形式" readMoreFormat="続きを読む">}}
XLSXは、MicrosoftOffice2007のリリースでMicrosoftによって導入されたMicrosoftExcelドキュメントのよく知られた形式です。OOXML標準ECMA-376のパート2で概説されているOpenPackagingConventionに従って編成された構造に基づいて、新しい形式は次のようになります。多数のXMLファイルを含むzipパッケージ。基礎となる構造とファイルは、.xlsxファイルを解凍するだけで調べることができます。
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ja/cpp/conversion/jpeg2000-to-txt" name="TXT" description="テキストドキュメントファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ja/cpp/conversion/jpeg2000-to-text" name="Text" description="テキストドキュメントファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ja/cpp/conversion/jpeg2000-to-doc" name="DOC" description="MicrosoftWordによって生成されたドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ja/cpp/conversion/jpeg2000-to-docx" name="DOCX" description="MicrosoftWordドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ja/cpp/conversion/jpeg2000-to-xls" name="XLS" description="MicrosoftExcelバイナリファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ja/cpp/conversion/jpeg2000-to-xlsx" name="XLSX" description="MicrosoftExcelドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ja/cpp/conversion/jpeg2000-to-pdf" name="PDF" description="ポータブルドキュメントフォーマット（PDF）" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ja/cpp/conversion/jpeg2000-to-searchable_pdf" name="Searchable PDF" description="検索可能なポータブルネットワークグラフィックス" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}