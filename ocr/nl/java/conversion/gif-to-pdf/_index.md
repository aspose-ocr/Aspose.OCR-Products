﻿---
title:  
weight: 3920
url: /nl/java/conversion/gif-to-pdf/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor GIF naar PDF Java-conversie. Gebruik API-voorbeeldcode voor batch-GIF-bestanden naar PDF-conversie binnen elke web- of desktop-Java-toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.OCR" subTitlepfName="voor Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/nl/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging voor Java](https://products.aspose.com/imaging/java)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in GIF-indeling en maakt GIF-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar *Aspose.OCR* te downloaden.
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) of specificeer de Aspose Maven Repository-configuratie
en installeer het binnen uw op Maven gebaseerde project door de volgende configuraties toe te voegen aan de _pom.xml_. Bekijk voor voorbeelden van Graddle, Ivy en Sbt onze [repository](https://repository.aspose.com/ocr/).

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

Met Java OCR en slechts een paar regels code, kunt u een complete applicatie maken die een GIF-afbeelding converteert naar een PDF-document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep AsposeOCR.RecognizePage-methode aan
+ Geef het GIF bestandspad door als parameter
+ AsposeOCR.RecognizePage retourneert een tekenreeks of bestand van het type PDF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

Voordat u het voorbeeld uitvoert, moet u ervoor zorgen dat Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) of hoger op uw systeem is geïnstalleerd.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 of hoger is geïnstalleerd.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Een GIF of Graphical Interchange Format is een type sterk gecomprimeerde afbeelding. GIF, eigendom van Unisys, gebruikt het LZW-compressie-algoritme dat de beeldkwaliteit niet verslechtert. Voor elke afbeelding staat GIF doorgaans tot 8 bits per pixel toe en tot 256 kleuren over de afbeelding. In tegenstelling tot een JPEG-afbeelding, die tot 16 miljoen kleuren kan weergeven en redelijk de grenzen van het menselijk oog raakt. Toen het internet opkwam, bleven GIF's de beste keuze omdat ze een lage bandbreedte nodig hadden en compatibel waren voor de afbeeldingen die effen kleurvlakken verbruiken. Een geanimeerde GIF combineert een groot aantal afbeeldingen of frames in een enkel bestand en geeft ze in een volgorde weer om een ​​geanimeerde clip of een korte video te genereren. De kleurbeperkingen zijn tot 256 voor elk frame en zijn waarschijnlijk het minst geschikt voor het reproduceren van andere afbeeldingen en foto's met kleurverloop.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Portable Document Format (PDF) is een type document dat in de jaren negentig door Adobe is gemaakt. Het doel van dit bestandsformaat was om een ​​standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van applicatiesoftware, hardware en besturingssysteem. Het PDF-bestandsformaat heeft volledige mogelijkheden om informatie zoals tekst, afbeeldingen, hyperlinks, formuliervelden, rich media, digitale handtekeningen, bijlagen, metadata, geospatiale functies en 3D-objecten erin te bevatten die als onderdeel van het brondocument kunnen worden gebruikt.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-txt" name="TXT" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-text" name="Text" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-doc" name="DOC" description="Documenten gegenereerd door Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-docx" name="DOCX" description="Microsoft Word-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-xls" name="XLS" description="Microsoft Excel binaire bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-xlsx" name="XLSX" description="Microsoft Excel-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-pdf" name="PDF" description="Draagbaar documentformaat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-searchable_pdf" name="Searchable PDF" description="Doorzoekbare draagbare netwerkgraphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-xml" name="XML" description="Uitbreidbare opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/gif-to-json" name="JSON" description="JavaScript-objectnotatie" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}