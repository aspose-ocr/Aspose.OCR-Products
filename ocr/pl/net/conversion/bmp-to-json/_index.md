﻿---
title: Konwertuj BMP na JSON przez C# 
weight: 3920
url: /pl/net/conversion/bmp-to-json/ 
lang: pl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Przykładowy kod konwersji BMP do JSON C#. Użyj przykładowego kodu API dla plików wsadowych BMP do konwersji JSON w ramach VB.NET, Asp.NET lub dowolnej aplikacji opartej na .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konwertuj BMP na JSON w C#" h2="Wykonaj optyczne rozpoznawanie znaków na dokumencie BMP i zapisz tekst jako dokument BMP przy użyciu Aspose.OCR z biblioteki .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="Aspose.OCR" subTitlepfName="dla .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="dla .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/pl/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/pl/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Strona główna API" codeSamplesText="Próbki kodu" liveDemosText="Prezentacje na żywo" downloadText="Ściągnij" learnText="Uczyć się">}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować BMP na JSON za pomocą C#" %}}

Aspose.OCR dla .NET to potężna, ale łatwa w użyciu i opłacalna biblioteka do konwersji obrazów BMP na dokumenty JSON. Dzięki obsłudze 26 języków opartych na łacinie, cyrylicy i chińskim, najnowocześniejszy mechanizm optycznego rozpoznawania znaków zapewnia doskonałą szybkość i dokładność rozpoznawania, izolując Cię od formuł, sieci neuronowych i innych złożonych szczegółów technicznych. Umożliwia dodanie funkcji OCR do aplikacji .NET w mniej niż 10 wierszach kodu.

[Aspose.OCR dla .NET](https://products.aspose.com/ocr/net)
 przetwarza zeskanowane obrazy, a nawet zdjęcia ze smartfona w formacie BMP i tworzy dokumenty BMP zawierające rozpoznany tekst. Aby dodać go do swojego projektu, wystarczy zainstalować *Aspose.OCR*
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 zapakuj w swój projekt za pomocą następującego polecenia:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować BMP na JSON" %}}

{{% blocks/products/pf/agp/text %}}

Dzięki .NET OCR i zaledwie kilku linijkom kodu możesz stworzyć w pełni funkcjonalną aplikację, która konwertuje obraz BMP na dokument JSON:

{{% /blocks/products/pf/agp/text %}}

+ Utwórz instancję klasy AsposeOcr
+ Wywołaj metodę AsposeOCR.RecognizeImage
+ Przekaż ścieżkę pliku BMP jako parametr
+ AsposeOCR.RecognizeImage zwraca ciąg lub plik typu JSON

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

Przed uruchomieniem przykładu upewnij się, że .NET API zgodne ze specyfikacją NET Standard 2.0 jest zainstalowane w Twoim systemie i wszystkie [zewnętrzne zależności](https://docs.aspose.com/ocr/net/system-requirements/#external- zależności) pakietu Aspose.OCR są przywoływane w projekcie.

{{% /blocks/products/pf/agp/text %}}

- Rozwiązanie kompatybilne z NET Standard 2.0+
- Aspose.OCR dla platformy .NET, do której odwołuje się Twój projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ten przykładowy kod pokazuje konwersję BMP na JSON .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.BMP");
// print text
File. File.WriteAllText("document.JSON", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej">}}
Pliki o rozszerzeniu .BMP reprezentują pliki obrazów bitmapowych, które są używane do przechowywania cyfrowych obrazów bitmapowych. Obrazy te są niezależne od karty graficznej i są również nazywane formatem plików mapy bitowej niezależnej od urządzenia (DIB). Ta niezależność służy do otwierania pliku na wielu platformach, takich jak Microsoft Windows i Mac. Format pliku BMP może przechowywać dane jako dwuwymiarowe obrazy cyfrowe zarówno w formacie monochromatycznym, jak i kolorowym z różnymi głębiami kolorów.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej">}}
JSON (JavaScript Object Notation) to otwarty standardowy format pliku do udostępniania danych, który wykorzystuje tekst czytelny dla człowieka do przechowywania i przesyłania danych. Pliki JSON są przechowywane z rozszerzeniem .json. JSON wymaga mniej formatowania i jest dobrą alternatywą dla XML. JSON wywodzi się z JavaScript, ale jest formatem danych niezależnym od języka. Generowanie i parsowanie JSON jest obsługiwane przez wiele nowoczesnych języków programowania. application/json to typ nośnika używany dla JSON.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Za pomocą C# można łatwo konwertować różne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-txt" name="TXT" description="Plik dokumentu tekstowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-text" name="Text" description="Plik dokumentu tekstowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-doc" name="DOC" description="Dokumenty generowane przez Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-docx" name="DOCX" description="Dokumenty Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-xls" name="XLS" description="Format pliku binarnego Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-xlsx" name="XLSX" description="Dokumenty Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-pdf" name="PDF" description="Przenośny format dokumentu (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-searchable_pdf" name="Searchable PDF" description="Przeszukiwalna przenośna grafika sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-xml" name="XML" description="Rozszerzalny język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/net/conversion/bmp-to-json" name="JSON" description="Notacja obiektu JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}