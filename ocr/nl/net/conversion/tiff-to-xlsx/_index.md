﻿---
title: Converteer TIFF naar XLSX via C# 
weight: 3920
url: /nl/net/conversion/tiff-to-xlsx/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor TIFF naar XLSX C#-conversie. Gebruik API-voorbeeldcode voor batch TIFF-bestanden naar XLSX-conversie binnen VB.NET, Asp.NET of een op .NET gebaseerde toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Converteer TIFF naar XLSX in C#" h2="Voer optische tekenherkenning uit op het TIFF-document en sla de tekst op als TIFF-document met behulp van Aspose.OCR uit de .NET-bibliotheek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.OCR" subTitlepfName="voor .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/nl/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="Hoe TIFF naar XLSX te converteren met C#" %}}

Aspose.OCR voor .NET is een krachtige maar gebruiksvriendelijke en kosteneffectieve bibliotheek voor het converteren van TIFF-afbeeldingen naar XLSX-documenten. De ultramoderne optische tekenherkenningsengine ondersteunt 26 talen op basis van Latijn, Cyrillisch en Chinees en biedt superieure herkenningssnelheid en nauwkeurigheid, terwijl u wordt geïsoleerd van formules, neurale netwerken en andere complexe technische details. Hiermee kunt u OCR-functionaliteit toevoegen aan uw .NET-toepassingen in minder dan 10 regels code.

[Aspose.OCR voor .NET](https://products.aspose.com/ocr/net)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in TIFF-indeling en maakt TIFF-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar de *Aspose.OCR* te installeren
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 pakket in uw project met de volgende opdracht:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om TIFF naar XLSX te converteren" %}}

{{% blocks/products/pf/agp/text %}}

Met .NET OCR en slechts een paar regels code, kunt u een complete toepassing maken die een TIFF-afbeelding converteert naar een XLSX-document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep AsposeOCR.RecognizeImage-methode aan
+ Geef het TIFF bestandspad door als parameter
+ AsposeOCR.RecognizeImage retourneert een String of bestand van het type XLSX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

Voordat u het voorbeeld uitvoert, moet u ervoor zorgen dat .NET API die compatibel is met de NET Standard 2.0-specificatie is geïnstalleerd op uw systeem en op alle [externe afhankelijkheden](https://docs.aspose.com/ocr/net/system-requirements/#external- afhankelijkheden) van het Aspose.OCR-pakket worden verwezen in uw project.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ compatibele oplossing
- Aspose.OCR voor .NET waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Deze voorbeeldcode toont TIFF naar XLSX .NET Conversie" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.TIFF");
// print text
File. File.WriteAllText("document.XLSX", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
TIFF of TIF, Tagged Image File Format, staat voor rasterafbeeldingen die bedoeld zijn voor gebruik op verschillende apparaten die voldoen aan deze standaard voor bestandsindelingen. Het is in staat om bilevel-, grijswaarden-, paletkleur- en full-color afbeeldingsgegevens in verschillende kleurruimten te beschrijven. Het ondersteunt zowel lossy als lossless compressieschema's om te kiezen tussen ruimte en tijd voor toepassingen die het formaat gebruiken. Het formaat is uitbreidbaar en heeft verschillende revisies ondergaan waardoor een onbeperkte hoeveelheid persoonlijke of speciale informatie kan worden opgenomen. Het formaat is niet machine-afhankelijk en is vrij van beperkingen zoals processor, besturingssysteem of bestandssystemen.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
XLSX is een bekende indeling voor Microsoft Excel-documenten die door Microsoft is geïntroduceerd met de release van Microsoft Office 2007. Gebaseerd op de structuur die is georganiseerd volgens de Open Packaging Conventions zoals uiteengezet in deel 2 van de OOXML-standaard ECMA-376, is de nieuwe indeling een zip-pakket dat een aantal XML-bestanden bevat. De onderliggende structuur en bestanden kunnen worden onderzocht door het .xlsx-bestand eenvoudig uit te pakken.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="Met C# kan men gemakkelijk verschillende formaten converteren, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-txt" name="TXT" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-text" name="Text" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-doc" name="DOC" description="Documenten gegenereerd door Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-docx" name="DOCX" description="Microsoft Word-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-xls" name="XLS" description="Microsoft Excel binaire bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-xlsx" name="XLSX" description="Microsoft Excel-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-pdf" name="PDF" description="Draagbaar documentformaat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-searchable_pdf" name="Searchable PDF" description="Doorzoekbare draagbare netwerkgraphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-xml" name="XML" description="Uitbreidbare opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/tiff-to-json" name="JSON" description="JavaScript-objectnotatie" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
