﻿---
title: Converteer JP2 naar PDF via C# 
weight: 3920
url: /nl/net/conversion/jp2-to-pdf/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor JP2 naar PDF C#-conversie. Gebruik API-voorbeeldcode voor batch JP2-bestanden naar PDF-conversie binnen VB.NET, Asp.NET of een op .NET gebaseerde toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Converteer JP2 naar PDF in C#" h2="Voer optische tekenherkenning uit op het JP2-document en sla de tekst op als JP2-document met behulp van Aspose.OCR uit de .NET-bibliotheek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.OCR" subTitlepfName="voor .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/nl/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="Hoe JP2 naar PDF te converteren met C#" %}}

Aspose.OCR voor .NET is een krachtige maar gebruiksvriendelijke en kosteneffectieve bibliotheek voor het converteren van JP2-afbeeldingen naar PDF-documenten. De ultramoderne optische tekenherkenningsengine ondersteunt 26 talen op basis van Latijn, Cyrillisch en Chinees en biedt superieure herkenningssnelheid en nauwkeurigheid, terwijl u wordt geïsoleerd van formules, neurale netwerken en andere complexe technische details. Hiermee kunt u OCR-functionaliteit toevoegen aan uw .NET-toepassingen in minder dan 10 regels code.

[Aspose.OCR voor .NET](https://products.aspose.com/ocr/net)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in JP2-indeling en maakt JP2-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar de *Aspose.OCR* te installeren
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 pakket in uw project met de volgende opdracht:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om JP2 naar PDF te converteren" %}}

{{% blocks/products/pf/agp/text %}}

Met .NET OCR en slechts een paar regels code, kunt u een complete toepassing maken die een JP2-afbeelding converteert naar een PDF-document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep AsposeOCR.RecognizeImage-methode aan
+ Geef het JP2 bestandspad door als parameter
+ AsposeOCR.RecognizeImage retourneert een String of bestand van het type PDF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

Voordat u het voorbeeld uitvoert, moet u ervoor zorgen dat .NET API die compatibel is met de NET Standard 2.0-specificatie is geïnstalleerd op uw systeem en op alle [externe afhankelijkheden](https://docs.aspose.com/ocr/net/system-requirements/#external- afhankelijkheden) van het Aspose.OCR-pakket worden verwezen in uw project.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ compatibele oplossing
- Aspose.OCR voor .NET waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Deze voorbeeldcode toont JP2 naar PDF .NET Conversie" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.JP2");
// print text
File. File.WriteAllText("document.PDF", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
JPEG 2000 (JP2) is een beeldcoderingssysteem en de modernste beeldcompressiestandaard. Ontworpen, met behulp van wavelet-technologie, kan JPEG 2000 verliesvrije inhoud in elke kwaliteit tegelijk coderen. Bovendien heeft JPEG 2000, zonder enige substantiële schade aan de coderingsefficiëntie, de mogelijkheid om dezelfde inhoud op doeltreffende wijze te openen en te decoderen in een verscheidenheid aan andere resoluties en kwaliteiten. De codestromen in JPEG 2000 zijn aanzienlijk schaalbaar met interessegebieden die de mogelijkheid bieden voor ruimtelijke willekeurige toegang. Met tot 16384 verschillende componenten met afmetingen in terapixels en een precisie die kan oplopen tot 38 bits/sample.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Portable Document Format (PDF) is een type document dat in de jaren negentig door Adobe is gemaakt. Het doel van dit bestandsformaat was om een ​​standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van applicatiesoftware, hardware en besturingssysteem. Het PDF-bestandsformaat heeft volledige mogelijkheden om informatie zoals tekst, afbeeldingen, hyperlinks, formuliervelden, rich media, digitale handtekeningen, bijlagen, metadata, geospatiale functies en 3D-objecten erin te bevatten die als onderdeel van het brondocument kunnen worden gebruikt.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="Met C# kan men gemakkelijk verschillende formaten converteren, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-txt" name="TXT" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-text" name="Text" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-doc" name="DOC" description="Documenten gegenereerd door Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-docx" name="DOCX" description="Microsoft Word-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-xls" name="XLS" description="Microsoft Excel binaire bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-xlsx" name="XLSX" description="Microsoft Excel-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-pdf" name="PDF" description="Draagbaar documentformaat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-searchable_pdf" name="Searchable PDF" description="Doorzoekbare draagbare netwerkgraphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-xml" name="XML" description="Uitbreidbare opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/jp2-to-json" name="JSON" description="JavaScript-objectnotatie" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
