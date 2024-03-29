﻿---
title:  
weight: 3920
url: /java/conversion/tif-to-docx/ 
lang: en
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Sample code for TIF to DOCX Java conversion. Use API example code for batch TIF files to DOCX conversion within any Web or Desktop Java based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOCX" pfName="Aspose.OCR" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API Home" codeSamplesText="Code samples" liveDemosText="Live Demos" downloadText="Download" learnText="Learn">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java) 
 processes scanned images or even smartphone photos in TIF format and creates TIF documents containing recognized text. To add it to your project, you just need to get *Aspose.OCR* 
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) or specify Aspose Maven Repository configuration 
and install it within your Maven-based project by adding the following configurations to the _pom.xml_. For Graddle, Ivy, Sbt examples check out our [repository](https://repository.aspose.com/ocr/).

{{% blocks/products/pf/agp/code-block title="Maven Dependency" offSpacer="true" %}}

```xml

 <dependency>
 <groupId>com.aspose</groupId>
 <artifactId>aspose-ocr</artifactId>
 <version>22.5</version>
 </dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

With Java OCR and just a few lines of code, you can create full-featured application that converts an TIF image to DOCX document:

{{% /blocks/products/pf/agp/text %}}

+ Create an instance of AsposeOcr class
+ Call AsposeOCR.RecognizePage method
+ Pass the TIF file path as parameter
+ AsposeOCR.RecognizePage returns a String or file of DOCX type

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

Before running the example, make sure that Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) or later is installed on your system.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 or higher is installed.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="" offSpacer="true" %}}

```java

 //Create API instance
 AsposeOCR api = new AsposeOCR();

 //Prepare rectangles with texts.
 ArrayList rectArray = new ArrayList();

 rectArray.add(new Rectangle(138, 352, 2033, 537));
 rectArray.add(new Rectangle(147, 890, 2033, 1157));

 String result = api.RecognizePage("srcImage.png", rectArray);
 System.out.println("Result with rect: " + result);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIF" readMoreLink="https://docs.fileformat.com/image/tif" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More">}}
TIFF or TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. It supports lossy as well as lossless compression schemes to choose between space and time for applications using the format. The format is extensible and has underwent several revisions that allows the inclusion of an unlimited amount of private or special-purpose information. The format is not machine dependent and is free from bounds like processor, operating system, or file systems.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/word-processing/docx/" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More">}}
DOCX is a well-known format for Microsoft Word documents. Introduced from 2007 with the release of Microsoft Office 2007, the structure of this new Document format was changed from plain binary to a combination of XML and binary files. Docx files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word which support DOC file extensions.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-txt" name="TXT" description="Text Document File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-text" name="Text" description="Text Document File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-doc" name="DOC" description="Documents generated by Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-docx" name="DOCX" description="Microsoft Word documents" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-xls" name="XLS" description="Microsoft Excel Binary File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-xlsx" name="XLSX" description="Microsoft Excel documents" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-pdf" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-searchable_pdf" name="Searchable PDF" description="Searchable Portable Network Graphics " >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-xml" name="XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/tif-to-json" name="JSON" description="JavaScript Object Notation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
