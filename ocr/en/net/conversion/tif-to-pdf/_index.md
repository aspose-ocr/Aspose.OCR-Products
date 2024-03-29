﻿---
title: Convert TIF to PDF via C# 
weight: 3920
url: /net/conversion/tif-to-pdf/ 
lang: en
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Sample code for TIF to PDF C# conversion. Use API example code for batch TIF files to PDF conversion within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert TIF to PDF in C#" h2="Perform optical character recognition on TIF document and save text as TIF document using Aspose.OCR for .NET library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.OCR" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API Home" codeSamplesText="Code samples" liveDemosText="Live Demos" downloadText="Download" learnText="Learn">}}

{{% blocks/products/pf/agp/content h2="How to convert TIF to PDF using C#" %}}

Aspose.OCR for .NET is a powerful yet easy-to-use and cost-effective library for converting TIF images to PDF documents. Supporting 26 languages based on Latin, Cyrillic and Chinese, its state-of-the-art optical character recognition engine provides superior recognition speed and accuracy, while isolating you from formulas, neural networks, and other complex technical details. It allows you to add OCR functionality to your .NET applications in less than 10 lines of code.

[Aspose.OCR for .NET](https://products.aspose.com/ocr/net) 
 processes scanned images or even smartphone photos in TIF format and creates TIF documents containing recognized text. To add it to your project, you just need to install the *Aspose.OCR* 
 [NuGet](https://www.nuget.org/packages/aspose.ocr) 
 package in your project with the following command:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert TIF to PDF" %}}

{{% blocks/products/pf/agp/text %}}

With .NET OCR and just a few lines of code, you can create full-featured application that converts an TIF image to PDF document:

{{% /blocks/products/pf/agp/text %}}

+ Create an instance of AsposeOcr class
+ Call AsposeOCR.RecognizeImage method
+ Pass the TIF file path as parameter
+ AsposeOCR.RecognizeImage returns a String or file of PDF type

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

Before running the example, make sure that .NET API compatible with NET Standard 2.0 specification is installed on your system and all [external dependencies](https://docs.aspose.com/ocr/net/system-requirements/#external-dependencies) of Aspose.OCR package are referenced in your project.

{{% /blocks/products/pf/agp/text %}}

-  NET Standard 2.0+ compatible solution
-  Aspose.OCR for .NET referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows TIF to PDF .NET Conversion" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.TIF");
// print text
File. File.WriteAllText("document.PDF", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIF" readMoreLink="https://docs.fileformat.com/image/tif" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More">}}
TIFF or TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. It supports lossy as well as lossless compression schemes to choose between space and time for applications using the format. The format is extensible and has underwent several revisions that allows the inclusion of an unlimited amount of private or special-purpose information. The format is not machine dependent and is free from bounds like processor, operating system, or file systems.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More">}}
Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. The PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, digital signatures, attachments, metadata, Geospatial features and 3D objects in it that can become as part of source document.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="Using C#, one can easily convert different formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-txt" name="TXT" description="Text Document File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-text" name="Text" description="Text Document File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-doc" name="DOC" description="Documents generated by Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-docx" name="DOCX" description="Microsoft Word documents" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-xls" name="XLS" description="Microsoft Excel Binary File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-xlsx" name="XLSX" description="Microsoft Excel documents" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-pdf" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-searchable_pdf" name="Searchable PDF" description="Searchable Portable Network Graphics " >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-xml" name="XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/conversion/tif-to-json" name="JSON" description="JavaScript Object Notation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
