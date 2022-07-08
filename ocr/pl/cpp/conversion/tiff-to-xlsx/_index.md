﻿---
title:  
weight: 3920
url: /pl/cpp/conversion/tiff-to-xlsx/ 
lang: pl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Przykładowy kod konwersji TIFF na XLSX Java. Użyj przykładowego kodu API dla plików wsadowych TIFF do konwersji XLSX w dowolnej aplikacji internetowej lub opartej na Javie na komputery stacjonarne.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.OCR" subTitlepfName="dla C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="dla C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/pl/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/pl/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="Strona główna API" codeSamplesText="Próbki kodu" liveDemosText="Prezentacje na żywo" downloadText="Ściągnij" learnText="Uczyć się">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging dla Javy](https://products.aspose.com/imaging/java)
 przetwarza zeskanowane obrazy, a nawet zdjęcia ze smartfona w formacie TIFF i tworzy dokumenty TIFF zawierające rozpoznany tekst. Aby dodać go do swojego projektu, wystarczy pobrać *Aspose.OCR*
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) lub określ konfigurację repozytorium Aspose Maven
i zainstaluj go w swoim projekcie opartym na Maven, dodając następujące konfiguracje do pliku _pom.xml_. Przykłady Graddle, Ivy, Sbt znajdziesz w naszym [repozytorium](https://repository.aspose.com/ocr/).

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

Dzięki C++ OCR i zaledwie kilku linijkom kodu możesz stworzyć w pełni funkcjonalną aplikację, która konwertuje obraz TIFF na dokument XLSX:

{{% /blocks/products/pf/agp/text %}}

+ Utwórz instancję klasy AsposeOcr
+ Wywołaj metodę AsposeOCR.asposeocr_page()
+ Przekaż ścieżkę pliku TIFF jako parametr
+ AsposeOCR.asposeocr_page zwraca ciąg lub plik typu XLSX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

Przed uruchomieniem przykładu upewnij się, że do projektu dodano [Microsoft.ML.OnnxRuntime](https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/) 1.7.0 lub nowszy. Powinien zostać zainstalowany automatycznie, jeśli zainstalujesz Aspose.OCR za pomocą Menedżera pakietów NuGet.

{{% /blocks/products/pf/agp/text %}}

- Rozwiązanie kompatybilne z NET Standard 2.0+
- Aspose.OCR dla platformy .NET, do której odwołuje się Twój projekt.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej">}}
TIFF lub TIF, Tagged Image File Format, reprezentuje obrazy rastrowe przeznaczone do użytku na różnych urządzeniach zgodnych z tym standardem formatu plików. Jest w stanie opisać dane obrazu dwupoziomowego, w skali szarości, w palecie kolorów i w pełnym kolorze w kilku przestrzeniach kolorów. Obsługuje stratne i bezstratne schematy kompresji, aby wybrać między przestrzenią a czasem dla aplikacji korzystających z formatu. Format jest rozszerzalny i przeszedł kilka zmian, które umożliwiają włączenie nieograniczonej ilości informacji prywatnych lub informacji specjalnego przeznaczenia. Format nie jest zależny od komputera i nie zawiera ograniczeń, takich jak procesor, system operacyjny lub systemy plików.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej">}}
XLSX to dobrze znany format dokumentów programu Microsoft Excel, który został wprowadzony przez firmę Microsoft wraz z wydaniem pakietu Microsoft Office 2007. W oparciu o strukturę zorganizowaną zgodnie z konwencjami otwartego pakowania, jak określono w części 2 standardu OOXML ECMA-376, nowy format jest pakiet zip, który zawiera wiele plików XML. Bazową strukturę i pliki można sprawdzić, po prostu rozpakowując plik .xlsx.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/cpp/conversion/tiff-to-txt" name="TXT" description="Plik dokumentu tekstowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/cpp/conversion/tiff-to-text" name="Text" description="Plik dokumentu tekstowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/cpp/conversion/tiff-to-doc" name="DOC" description="Dokumenty generowane przez Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/cpp/conversion/tiff-to-docx" name="DOCX" description="Dokumenty Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/cpp/conversion/tiff-to-xls" name="XLS" description="Format pliku binarnego Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/cpp/conversion/tiff-to-xlsx" name="XLSX" description="Dokumenty Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/cpp/conversion/tiff-to-pdf" name="PDF" description="Przenośny format dokumentu (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/cpp/conversion/tiff-to-searchable_pdf" name="Searchable PDF" description="Przeszukiwalna przenośna grafika sieciowa" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}