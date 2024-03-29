﻿---
title: Converteer PDF naar XML via C# 
weight: 3920
url: /nl/net/conversion/pdf-to-xml/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor PDF naar XML C#-conversie. Gebruik API-voorbeeldcode voor batch PDF-bestanden naar XML-conversie binnen VB.NET, Asp.NET of een op .NET gebaseerde toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Converteer PDF naar XML in C#" h2="Voer optische tekenherkenning uit op het PDF-document en sla de tekst op als PDF-document met behulp van Aspose.OCR uit de .NET-bibliotheek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="Aspose.OCR" subTitlepfName="voor .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/nl/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="Hoe PDF naar XML te converteren met C#" %}}

Aspose.OCR voor .NET is een krachtige maar gebruiksvriendelijke en kosteneffectieve bibliotheek voor het converteren van PDF-afbeeldingen naar XML-documenten. De ultramoderne optische tekenherkenningsengine ondersteunt 26 talen op basis van Latijn, Cyrillisch en Chinees en biedt superieure herkenningssnelheid en nauwkeurigheid, terwijl u wordt geïsoleerd van formules, neurale netwerken en andere complexe technische details. Hiermee kunt u OCR-functionaliteit toevoegen aan uw .NET-toepassingen in minder dan 10 regels code.

[Aspose.OCR voor .NET](https://products.aspose.com/ocr/net)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in PDF-indeling en maakt PDF-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar de *Aspose.OCR* te installeren
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 pakket in uw project met de volgende opdracht:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om PDF naar XML te converteren" %}}

{{% blocks/products/pf/agp/text %}}

Met .NET OCR en slechts een paar regels code, kunt u een complete toepassing maken die een PDF-afbeelding converteert naar een XML-document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep AsposeOCR.RecognizeImage-methode aan
+ Geef het PDF bestandspad door als parameter
+ AsposeOCR.RecognizeImage retourneert een String of bestand van het type XML

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

Voordat u het voorbeeld uitvoert, moet u ervoor zorgen dat .NET API die compatibel is met de NET Standard 2.0-specificatie is geïnstalleerd op uw systeem en op alle [externe afhankelijkheden](https://docs.aspose.com/ocr/net/system-requirements/#external- afhankelijkheden) van het Aspose.OCR-pakket worden verwezen in uw project.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ compatibele oplossing
- Aspose.OCR voor .NET waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Deze voorbeeldcode toont PDF naar XML .NET Conversie" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.PDF");
// print text
File. File.WriteAllText("document.XML", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Portable Document Format (PDF) is een type document dat in de jaren negentig door Adobe is gemaakt. Het doel van dit bestandsformaat was om een ​​standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van applicatiesoftware, hardware en besturingssysteem. Het PDF-bestandsformaat heeft volledige mogelijkheden om informatie zoals tekst, afbeeldingen, hyperlinks, formuliervelden, rich media, digitale handtekeningen, bijlagen, metadata, geospatiale functies en 3D-objecten erin te bevatten die als onderdeel van het brondocument kunnen worden gebruikt.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
XML staat voor Extensible Markup Language en is vergelijkbaar met HTML, maar verschilt in het gebruik van tags voor het definiëren van objecten. Het hele idee achter het creëren van een XML-bestandsformaat was om gegevens op te slaan en te transporteren zonder afhankelijk te zijn van software- of hardwaretools. Zijn populariteit is te danken aan het feit dat het zowel menselijk als machinaal leesbaar is. Hierdoor kan het gemeenschappelijke dataprotocollen creëren in de vorm van objecten die moeten worden opgeslagen en gedeeld via een netwerk zoals World Wide Web (WWW). De "X" in XML is voor uitbreidbaar, wat inhoudt dat de taal kan worden uitgebreid tot een willekeurig aantal symbolen volgens gebruikersvereisten. Het is voor deze functies dat veel standaard bestandsindelingen er gebruik van maken, zoals Microsoft Open XML, LibreOffice OpenDocument, XHTML en SVG.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="Met C# kan men gemakkelijk verschillende formaten converteren, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-txt" name="TXT" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-text" name="Text" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-doc" name="DOC" description="Documenten gegenereerd door Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-docx" name="DOCX" description="Microsoft Word-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-xls" name="XLS" description="Microsoft Excel binaire bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-xlsx" name="XLSX" description="Microsoft Excel-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-pdf" name="PDF" description="Draagbaar documentformaat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-searchable_pdf" name="Searchable PDF" description="Doorzoekbare draagbare netwerkgraphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-xml" name="XML" description="Uitbreidbare opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/pdf-to-json" name="JSON" description="JavaScript-objectnotatie" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
