﻿---
title: Converteer WBMP naar XLS via C# 
weight: 3920
url: /nl/net/conversion/wbmp-to-xls/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor WBMP naar XLS C#-conversie. Gebruik API-voorbeeldcode voor batch WBMP-bestanden naar XLS-conversie binnen VB.NET, Asp.NET of een op .NET gebaseerde toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Converteer WBMP naar XLS in C#" h2="Voer optische tekenherkenning uit op het WBMP-document en sla de tekst op als WBMP-document met behulp van Aspose.OCR uit de .NET-bibliotheek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.OCR" subTitlepfName="voor .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/nl/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="Hoe WBMP naar XLS te converteren met C#" %}}

Aspose.OCR voor .NET is een krachtige maar gebruiksvriendelijke en kosteneffectieve bibliotheek voor het converteren van WBMP-afbeeldingen naar XLS-documenten. De ultramoderne optische tekenherkenningsengine ondersteunt 26 talen op basis van Latijn, Cyrillisch en Chinees en biedt superieure herkenningssnelheid en nauwkeurigheid, terwijl u wordt geïsoleerd van formules, neurale netwerken en andere complexe technische details. Hiermee kunt u OCR-functionaliteit toevoegen aan uw .NET-toepassingen in minder dan 10 regels code.

[Aspose.OCR voor .NET](https://products.aspose.com/ocr/net)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in WBMP-indeling en maakt WBMP-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar de *Aspose.OCR* te installeren
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 pakket in uw project met de volgende opdracht:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om WBMP naar XLS te converteren" %}}

{{% blocks/products/pf/agp/text %}}

Met .NET OCR en slechts een paar regels code, kunt u een complete toepassing maken die een WBMP-afbeelding converteert naar een XLS-document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep AsposeOCR.RecognizeImage-methode aan
+ Geef het WBMP bestandspad door als parameter
+ AsposeOCR.RecognizeImage retourneert een String of bestand van het type XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

Voordat u het voorbeeld uitvoert, moet u ervoor zorgen dat .NET API die compatibel is met de NET Standard 2.0-specificatie is geïnstalleerd op uw systeem en op alle [externe afhankelijkheden](https://docs.aspose.com/ocr/net/system-requirements/#external- afhankelijkheden) van het Aspose.OCR-pakket worden verwezen in uw project.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ compatibele oplossing
- Aspose.OCR voor .NET waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Deze voorbeeldcode toont WBMP naar XLS .NET Conversie" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.WBMP");
// print text
File. File.WriteAllText("document.XLS", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="WBMP" readMoreLink="https://docs.fileformat.com/image/wbmp" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
WBMP is een monochrome grafische bestandsindeling die is geoptimaliseerd voor mobiele computerapparatuur.
WBMP-afbeeldingen zijn monochroom (zwart-wit) zodat de afbeeldingsgrootte tot een minimum wordt beperkt. Een zwarte pixel wordt aangeduid met 0 en een witte pixel wordt aangeduid met 1.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Bestanden met de XLS-extensie vertegenwoordigen Excel Binary File Format. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel en andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Bestand opgeslagen door Excel staat bekend als werkmap, waarbij elke werkmap een of meer werkbladen kan hebben. Gegevens worden opgeslagen en weergegeven aan gebruikers in tabelindeling in werkblad en kunnen numerieke waarden, tekstgegevens, formules, externe gegevensverbindingen, afbeeldingen en grafieken omvatten. Met toepassingen zoals Microsoft Excel kunt u werkmapgegevens exporteren naar verschillende formaten, waaronder PDF, CSV, XLSX, TXT, HTML, XPS en verschillende andere. Het XLS-bestandsformaat werd vervangen door een meer open en gestructureerd formaat, XLSX, met de release van Microsoft Excel 2007. De nieuwste versies bieden nog steeds ondersteuning voor het maken en lezen van XLS-bestanden, hoewel XLSX nu de eerste keuze is voor gebruik.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="Met C# kan men gemakkelijk verschillende formaten converteren, waaronder." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}