﻿---
title: Converteer GIF naar Text via C# 
weight: 3920
url: /nl/net/conversion/gif-to-text/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor GIF naar Text C#-conversie. Gebruik API-voorbeeldcode voor batch GIF-bestanden naar Text-conversie binnen VB.NET, Asp.NET of een op .NET gebaseerde toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Converteer GIF naar Text in C#" h2="Voer optische tekenherkenning uit op het GIF-document en sla de tekst op als GIF-document met behulp van Aspose.OCR uit de .NET-bibliotheek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="Text" pfName="Aspose.OCR" subTitlepfName="voor .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/nl/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="Hoe GIF naar Text te converteren met C#" %}}

Aspose.OCR voor .NET is een krachtige maar gebruiksvriendelijke en kosteneffectieve bibliotheek voor het converteren van GIF-afbeeldingen naar Text-documenten. De ultramoderne optische tekenherkenningsengine ondersteunt 26 talen op basis van Latijn, Cyrillisch en Chinees en biedt superieure herkenningssnelheid en nauwkeurigheid, terwijl u wordt geïsoleerd van formules, neurale netwerken en andere complexe technische details. Hiermee kunt u OCR-functionaliteit toevoegen aan uw .NET-toepassingen in minder dan 10 regels code.

[Aspose.OCR voor .NET](https://products.aspose.com/ocr/net)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in GIF-indeling en maakt GIF-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar de *Aspose.OCR* te installeren
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 pakket in uw project met de volgende opdracht:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om GIF naar Text te converteren" %}}

{{% blocks/products/pf/agp/text %}}

Met .NET OCR en slechts een paar regels code, kunt u een complete toepassing maken die een GIF-afbeelding converteert naar een Text-document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep AsposeOCR.RecognizeImage-methode aan
+ Geef het GIF bestandspad door als parameter
+ AsposeOCR.RecognizeImage retourneert een String of bestand van het type Text

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

Voordat u het voorbeeld uitvoert, moet u ervoor zorgen dat .NET API die compatibel is met de NET Standard 2.0-specificatie is geïnstalleerd op uw systeem en op alle [externe afhankelijkheden](https://docs.aspose.com/ocr/net/system-requirements/#external- afhankelijkheden) van het Aspose.OCR-pakket worden verwezen in uw project.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ compatibele oplossing
- Aspose.OCR voor .NET waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Deze voorbeeldcode toont GIF naar Text .NET Conversie" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.GIF");
// print text
File. File.WriteAllText("document.Text", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Een GIF of Graphical Interchange Format is een type sterk gecomprimeerde afbeelding. GIF, eigendom van Unisys, gebruikt het LZW-compressie-algoritme dat de beeldkwaliteit niet verslechtert. Voor elke afbeelding staat GIF doorgaans tot 8 bits per pixel toe en tot 256 kleuren over de afbeelding. In tegenstelling tot een JPEG-afbeelding, die tot 16 miljoen kleuren kan weergeven en redelijk de grenzen van het menselijk oog raakt. Toen het internet opkwam, bleven GIF's de beste keuze omdat ze een lage bandbreedte nodig hadden en compatibel waren voor de afbeeldingen die effen kleurvlakken verbruiken. Een geanimeerde GIF combineert een groot aantal afbeeldingen of frames in een enkel bestand en geeft ze in een volgorde weer om een ​​geanimeerde clip of een korte video te genereren. De kleurbeperkingen zijn tot 256 voor elk frame en zijn waarschijnlijk het minst geschikt voor het reproduceren van andere afbeeldingen en foto's met kleurverloop.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Text" readMoreLink="https://docs.fileformat.com/word-processing/txt/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Een bestand met de extensie .TXT vertegenwoordigt een tekstdocument dat platte tekst in de vorm van regels bevat. Alinea's in een tekstdocument worden herkend door regelterugloop en worden gebruikt om de bestandsinhoud beter te ordenen. Een standaard tekstdocument kan in elke teksteditor of tekstverwerkingsprogramma op verschillende besturingssystemen worden geopend. Alle tekst in zo'n bestand is in een voor mensen leesbaar formaat en wordt weergegeven door een reeks tekens.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="Met C# kan men gemakkelijk verschillende formaten converteren, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-txt" name="TXT" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-text" name="Text" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-doc" name="DOC" description="Documenten gegenereerd door Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-docx" name="DOCX" description="Microsoft Word-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-xls" name="XLS" description="Microsoft Excel binaire bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-xlsx" name="XLSX" description="Microsoft Excel-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-pdf" name="PDF" description="Draagbaar documentformaat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-searchable_pdf" name="Searchable PDF" description="Doorzoekbare draagbare netwerkgraphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-xml" name="XML" description="Uitbreidbare opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/net/conversion/gif-to-json" name="JSON" description="JavaScript-objectnotatie" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
