﻿---
title:  
weight: 3920
url: /nl/cpp/conversion/jpeg2000-to-xls/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor JPEG2000 naar XLS Java-conversie. Gebruik API-voorbeeldcode voor batch-JPEG2000-bestanden naar XLS-conversie binnen elke web- of desktop-Java-toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.OCR" subTitlepfName="voor C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/nl/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging voor Java](https://products.aspose.com/imaging/java)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in JPEG2000-indeling en maakt JPEG2000-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar *Aspose.OCR* te downloaden.
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) of specificeer de Aspose Maven Repository-configuratie
en installeer het binnen uw op Maven gebaseerde project door de volgende configuraties toe te voegen aan de _pom.xml_. Bekijk voor voorbeelden van Graddle, Ivy en Sbt onze [repository](https://repository.aspose.com/ocr/).

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

Met C++ OCR en slechts een paar regels code, kun je een complete applicatie maken die een JPEG2000 afbeelding converteert naar een XLS document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep de methode AsposeOCR.asposeocr_page() aan
+ Geef het JPEG2000 bestandspad door als parameter
+ AsposeOCR.asposeocr_page retourneert een String of bestand van het type XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

Voordat u het voorbeeld uitvoert, moet u ervoor zorgen dat [Microsoft.ML.OnnxRuntime](https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/) 1.7.0 of hoger aan het project is toegevoegd. Het zou automatisch moeten worden geïnstalleerd als u Aspose.OCR installeert via NuGet Package Manager.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ compatibele oplossing
- Aspose.OCR voor .NET waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="" offSpacer="true" %}}

```cpp

std::string img_path = "../srcSample.png";

// Prepare buffer for result (in symbols, len_byte = len * sizeof(wchar_t))
const size_t len = 4096;

wchar_t bfr[len] = { 0 };

size_t result = aspose::ocr::page(image_path.c_str(), bfr, len);

//Print result
std::wcout << bfr << L"\n";

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG2000" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
JPEG 2000 (JP2) is een beeldcoderingssysteem en de modernste beeldcompressiestandaard. Ontworpen, met behulp van wavelet-technologie, kan JPEG 2000 verliesvrije inhoud in elke kwaliteit tegelijk coderen. Bovendien heeft JPEG 2000, zonder enige substantiële schade aan de coderingsefficiëntie, de mogelijkheid om dezelfde inhoud op doeltreffende wijze te openen en te decoderen in een verscheidenheid aan andere resoluties en kwaliteiten. De codestromen in JPEG 2000 zijn aanzienlijk schaalbaar met interessegebieden die de mogelijkheid bieden voor ruimtelijke willekeurige toegang. Met tot 16384 verschillende componenten met afmetingen in terapixels en een precisie die kan oplopen tot 38 bits/sample.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
Bestanden met de XLS-extensie vertegenwoordigen Excel Binary File Format. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel en andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Bestand opgeslagen door Excel staat bekend als werkmap, waarbij elke werkmap een of meer werkbladen kan hebben. Gegevens worden opgeslagen en weergegeven aan gebruikers in tabelindeling in werkblad en kunnen numerieke waarden, tekstgegevens, formules, externe gegevensverbindingen, afbeeldingen en grafieken omvatten. Met toepassingen zoals Microsoft Excel kunt u werkmapgegevens exporteren naar verschillende formaten, waaronder PDF, CSV, XLSX, TXT, HTML, XPS en verschillende andere. Het XLS-bestandsformaat werd vervangen door een meer open en gestructureerd formaat, XLSX, met de release van Microsoft Excel 2007. De nieuwste versies bieden nog steeds ondersteuning voor het maken en lezen van XLS-bestanden, hoewel XLSX nu de eerste keuze is voor gebruik.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/cpp/conversion/jpeg2000-to-txt" name="TXT" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/cpp/conversion/jpeg2000-to-text" name="Text" description="Tekstdocumentbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/cpp/conversion/jpeg2000-to-doc" name="DOC" description="Documenten gegenereerd door Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/cpp/conversion/jpeg2000-to-docx" name="DOCX" description="Microsoft Word-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/cpp/conversion/jpeg2000-to-xls" name="XLS" description="Microsoft Excel binaire bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/cpp/conversion/jpeg2000-to-xlsx" name="XLSX" description="Microsoft Excel-documenten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/cpp/conversion/jpeg2000-to-pdf" name="PDF" description="Draagbaar documentformaat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/nl/cpp/conversion/jpeg2000-to-searchable_pdf" name="Searchable PDF" description="Doorzoekbare draagbare netwerkgraphics" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
