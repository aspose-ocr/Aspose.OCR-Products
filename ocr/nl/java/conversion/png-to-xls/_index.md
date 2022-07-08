﻿---
title:  
weight: 3920
url: /nl/java/conversion/png-to-xls/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor PNG naar XLS Java-conversie. Gebruik API-voorbeeldcode voor batch-PNG-bestanden naar XLS-conversie binnen elke web- of desktop-Java-toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.OCR" subTitlepfName="voor Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/nl/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging voor Java](https://products.aspose.com/imaging/java)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in PNG-indeling en maakt PNG-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar *Aspose.OCR* te downloaden.
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

Met Java OCR en slechts een paar regels code, kunt u een complete applicatie maken die een PNG-afbeelding converteert naar een XLS-document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep AsposeOCR.RecognizePage-methode aan
+ Geef het PNG bestandspad door als parameter
+ AsposeOCR.RecognizePage retourneert een tekenreeks of bestand van het type XLS

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
PNG, Portable Network Graphics, verwijst naar een type rasterafbeeldingsbestandsindeling die lossless compressie gebruikt. Dit bestandsformaat is gemaakt als vervanging van Graphics Interchange Format (GIF) en heeft geen copyrightbeperkingen. Het PNG-bestandsformaat ondersteunt echter geen animaties. Het PNG-bestandsformaat ondersteunt lossless beeldcompressie waardoor het populair is onder zijn gebruikers. Met het verstrijken van de tijd is PNG geëvolueerd als een van de meest gebruikte afbeeldingsbestandsindelingen. Bijna alle besturingssystemen hebben ondersteuning voor het openen van PNG-bestanden. Microsoft Windows-viewer heeft bijvoorbeeld de mogelijkheid om PNG-bestanden te openen, aangezien het besturingssysteem standaard de ondersteuning heeft die beschikbaar is als onderdeel van de installatie.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Bestanden met de XLS-extensie vertegenwoordigen Excel Binary File Format. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel en andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Bestand opgeslagen door Excel staat bekend als werkmap, waarbij elke werkmap een of meer werkbladen kan hebben. Gegevens worden opgeslagen en weergegeven aan gebruikers in tabelindeling in werkblad en kunnen numerieke waarden, tekstgegevens, formules, externe gegevensverbindingen, afbeeldingen en grafieken omvatten. Met toepassingen zoals Microsoft Excel kunt u werkmapgegevens exporteren naar verschillende formaten, waaronder PDF, CSV, XLSX, TXT, HTML, XPS en verschillende andere. Het XLS-bestandsformaat werd vervangen door een meer open en gestructureerd formaat, XLSX, met de release van Microsoft Excel 2007. De nieuwste versies bieden nog steeds ondersteuning voor het maken en lezen van XLS-bestanden, hoewel XLSX nu de eerste keuze is voor gebruik.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-txt" name="TXT" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-text" name="Text" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-doc" name="DOC" description="Documenten gegenereerd door Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-docx" name="DOCX" description="Microsoft Word-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-xls" name="XLS" description="Microsoft Excel binaire bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-xlsx" name="XLSX" description="Microsoft Excel-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-pdf" name="PDF" description="Draagbaar documentformaat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-searchable_pdf" name="Searchable PDF" description="Doorzoekbare draagbare netwerkgraphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-xml" name="XML" description="Uitbreidbare opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/java/conversion/png-to-json" name="JSON" description="JavaScript-objectnotatie" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}