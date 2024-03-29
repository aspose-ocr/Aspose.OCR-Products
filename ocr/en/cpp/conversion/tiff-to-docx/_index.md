﻿---
title:  
weight: 3920
url: /cpp/conversion/tiff-to-docx/ 
lang: en
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Sample code for TIFF to DOCX Java conversion. Use API example code for batch TIFF files to DOCX conversion within any Web or Desktop Java based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOCX" pfName="Aspose.OCR" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="API Home" codeSamplesText="Code samples" liveDemosText="Live Demos" downloadText="Download" learnText="Learn">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java) 
 processes scanned images or even smartphone photos in TIFF format and creates TIFF documents containing recognized text. To add it to your project, you just need to get *Aspose.OCR* 
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) or specify Aspose Maven Repository configuration 
and install it within your Maven-based project by adding the following configurations to the _pom.xml_. For Graddle, Ivy, Sbt examples check out our [repository](https://repository.aspose.com/ocr/).

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

With C++ OCR and just a few lines of code, you can create full-featured application that converts an TIFF image to DOCX document:

{{% /blocks/products/pf/agp/text %}}

+ Create an instance of AsposeOcr class
+ Call AsposeOCR.asposeocr_page() method
+ Pass the TIFF file path as parameter
+ AsposeOCR.asposeocr_page returns a String or file of DOCX type

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

Before running the example, make sure that [Microsoft.ML.OnnxRuntime](https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/) 1.7.0 or above is added to the project. It should be automatically installed if you install Aspose.OCR via NuGet Package Manager.

{{% /blocks/products/pf/agp/text %}}

-  NET Standard 2.0+ compatible solution
-  Aspose.OCR for .NET referenced in your project.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More">}}
TIFF or TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. It supports lossy as well as lossless compression schemes to choose between space and time for applications using the format. The format is extensible and has underwent several revisions that allows the inclusion of an unlimited amount of private or special-purpose information. The format is not machine dependent and is free from bounds like processor, operating system, or file systems.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/word-processing/docx/" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More">}}
DOCX is a well-known format for Microsoft Word documents. Introduced from 2007 with the release of Microsoft Office 2007, the structure of this new Document format was changed from plain binary to a combination of XML and binary files. Docx files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word which support DOC file extensions.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/cpp/conversion/tiff-to-txt" name="TXT" description="Text Document File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/cpp/conversion/tiff-to-text" name="Text" description="Text Document File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/cpp/conversion/tiff-to-doc" name="DOC" description="Documents generated by Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/cpp/conversion/tiff-to-docx" name="DOCX" description="Microsoft Word documents" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/cpp/conversion/tiff-to-xls" name="XLS" description="Microsoft Excel Binary File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/cpp/conversion/tiff-to-xlsx" name="XLSX" description="Microsoft Excel documents" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/cpp/conversion/tiff-to-pdf" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/cpp/conversion/tiff-to-searchable_pdf" name="Searchable PDF" description="Searchable Portable Network Graphics " >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
