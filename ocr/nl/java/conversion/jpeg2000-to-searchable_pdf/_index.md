﻿---
title:  
weight: 3920
url: /nl/java/conversion/jpeg2000-to-searchable_pdf/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor JPEG2000 naar Searchable PDF Java-conversie. Gebruik API-voorbeeldcode voor batch-JPEG2000-bestanden naar Searchable PDF-conversie binnen elke web- of desktop-Java-toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="Searchable PDF" pfName="Aspose.OCR" subTitlepfName="voor Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/nl/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging voor Java](https://products.aspose.com/imaging/java)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in JPEG2000-indeling en maakt JPEG2000-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar *Aspose.OCR* te downloaden.
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

Met Java OCR en slechts een paar regels code, kunt u een complete applicatie maken die een JPEG2000-afbeelding converteert naar een Searchable PDF-document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep AsposeOCR.RecognizePage-methode aan
+ Geef het JPEG2000 bestandspad door als parameter
+ AsposeOCR.RecognizePage retourneert een tekenreeks of bestand van het type Searchable PDF

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG2000" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
JPEG 2000 (JP2) is een beeldcoderingssysteem en de modernste beeldcompressiestandaard. Ontworpen, met behulp van wavelet-technologie, kan JPEG 2000 verliesvrije inhoud in elke kwaliteit tegelijk coderen. Bovendien heeft JPEG 2000, zonder enige substantiële schade aan de coderingsefficiëntie, de mogelijkheid om dezelfde inhoud op doeltreffende wijze te openen en te decoderen in een verscheidenheid aan andere resoluties en kwaliteiten. De codestromen in JPEG 2000 zijn aanzienlijk schaalbaar met interessegebieden die de mogelijkheid bieden voor ruimtelijke willekeurige toegang. Met tot 16384 verschillende componenten met afmetingen in terapixels en een precisie die kan oplopen tot 38 bits/sample.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Searchable PDF" readMoreLink="https://docs.fileformat.com/pdf/a/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Doorzoekbare PDF-bestanden behouden de originele gescande afbeelding voor weergave, evenals OCR-tekst in een verborgen laag die kan worden gebruikt voor zoekopdrachten in volledige tekst in een document of om tekst te markeren voor kopieer- en plakbewerkingen.
Volledige OCR-conversie naar PDF, exclusief de originele afbeelding, zal nooit 100% van de originele opmaak behouden, vooral als het document veel afbeeldingen of een complexe lay-out heeft.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-txt" name="TXT" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-text" name="Text" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-doc" name="DOC" description="Documenten gegenereerd door Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-docx" name="DOCX" description="Microsoft Word-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-xls" name="XLS" description="Microsoft Excel binaire bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-xlsx" name="XLSX" description="Microsoft Excel-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-pdf" name="PDF" description="Draagbaar documentformaat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-searchable_pdf" name="Searchable PDF" description="Doorzoekbare draagbare netwerkgraphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-xml" name="XML" description="Uitbreidbare opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/jpeg2000-to-json" name="JSON" description="JavaScript-objectnotatie" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}