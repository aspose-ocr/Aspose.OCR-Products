﻿---
title:  
weight: 3920
url: /java/conversion/jp2-to-searchable_pdf/ 
lang: en
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Sample code for JP2 to Searchable PDF Java conversion. Use API example code for batch JP2 files to Searchable PDF conversion within any Web or Desktop Java based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="Searchable PDF" pfName="Aspose.OCR" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API Home" codeSamplesText="Code samples" liveDemosText="Live Demos" downloadText="Download" learnText="Learn">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java) 
 processes scanned images or even smartphone photos in JP2 format and creates JP2 documents containing recognized text. To add it to your project, you just need to get *Aspose.OCR* 
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) or specify Aspose Maven Repository configuration 
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

With Java OCR and just a few lines of code, you can create full-featured application that converts an JP2 image to Searchable PDF document:

{{% /blocks/products/pf/agp/text %}}

+ Create an instance of AsposeOcr class
+ Call AsposeOCR.RecognizePage method
+ Pass the JP2 file path as parameter
+ AsposeOCR.RecognizePage returns a String or file of Searchable PDF type

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More">}}
JPEG 2000 (JP2) is an image coding system and state-of-the-art image compression standard. Designed, using wavelet technology JPEG 2000 can code lossless content in any quality at once. Moreover, without any substantial penalty in coding efficiency, JPEG 2000 have the capability to access and decode the same content efficaciously into a variety of other resolutions and qualities. The code streams in JPEG 2000 is significantly scalable having regions of interest that provide the facility for spatial random access. Possessing Up to 16384 diverse components with the dimensions in terapixels, and precision that can be high as 38 bits/sample.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Searchable PDF" readMoreLink="https://docs.fileformat.com/pdf/a/" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More">}}
Searchable PDF files retain the original scanned image for viewing, as well as OCR text in a hidden layer that can be used for full-text searches within a document or highlighting text for copy and paste operations.
Full OCR conversion to PDF, not including the original image, will never retain 100% of the original formatting, especially if the document has many images or a complex layout.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-txt" name="TXT" description="Text Document File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-text" name="Text" description="Text Document File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-doc" name="DOC" description="Documents generated by Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-docx" name="DOCX" description="Microsoft Word documents" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-xls" name="XLS" description="Microsoft Excel Binary File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-xlsx" name="XLSX" description="Microsoft Excel documents" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-pdf" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-searchable_pdf" name="Searchable PDF" description="Searchable Portable Network Graphics " >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-xml" name="XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/java/conversion/jp2-to-json" name="JSON" description="JavaScript Object Notation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}