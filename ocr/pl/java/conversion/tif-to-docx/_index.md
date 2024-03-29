﻿---
title:  
weight: 3920
url: /pl/java/conversion/tif-to-docx/ 
lang: pl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Przykładowy kod konwersji TIF na DOCX Java. Użyj przykładowego kodu API dla plików wsadowych TIF do konwersji DOCX w dowolnej aplikacji internetowej lub opartej na Javie na komputery stacjonarne.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOCX" pfName="Aspose.OCR" subTitlepfName="dla Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="dla Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/pl/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/pl/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Strona główna API" codeSamplesText="Próbki kodu" liveDemosText="Prezentacje na żywo" downloadText="Ściągnij" learnText="Uczyć się">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging dla Javy](https://products.aspose.com/imaging/java)
 przetwarza zeskanowane obrazy, a nawet zdjęcia ze smartfona w formacie TIF i tworzy dokumenty TIF zawierające rozpoznany tekst. Aby dodać go do swojego projektu, wystarczy pobrać *Aspose.OCR*
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) lub określ konfigurację repozytorium Aspose Maven
i zainstaluj go w swoim projekcie opartym na Maven, dodając następujące konfiguracje do pliku _pom.xml_. Przykłady Graddle, Ivy, Sbt znajdziesz w naszym [repozytorium](https://repository.aspose.com/ocr/).

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

Dzięki Java OCR i zaledwie kilku linijkom kodu możesz stworzyć w pełni funkcjonalną aplikację, która konwertuje obraz TIF na dokument DOCX:

{{% /blocks/products/pf/agp/text %}}

+ Utwórz instancję klasy AsposeOcr
+ Wywołaj metodę AsposeOCR.RecognizePage
+ Przekaż ścieżkę pliku TIF jako parametr
+ AsposeOCR.RecognizePage zwraca ciąg lub plik typu DOCX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

Przed uruchomieniem przykładu upewnij się, że w systemie jest zainstalowana Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) lub nowsza.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 lub nowszy jest zainstalowany.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIF" readMoreLink="https://docs.fileformat.com/image/tif" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej">}}
TIFF lub TIF, Tagged Image File Format, reprezentuje obrazy rastrowe przeznaczone do użytku na różnych urządzeniach zgodnych z tym standardem formatu plików. Jest w stanie opisać dane obrazu dwupoziomowego, w skali szarości, w palecie kolorów i w pełnym kolorze w kilku przestrzeniach kolorów. Obsługuje stratne i bezstratne schematy kompresji, aby wybrać między przestrzenią a czasem dla aplikacji korzystających z formatu. Format jest rozszerzalny i przeszedł kilka zmian, które umożliwiają włączenie nieograniczonej ilości informacji prywatnych lub informacji specjalnego przeznaczenia. Format nie jest zależny od komputera i nie zawiera ograniczeń, takich jak procesor, system operacyjny lub systemy plików.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/przetwarzanie tekstu/docx/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej">}}
DOCX to dobrze znany format dokumentów Microsoft Word. Wprowadzony w 2007 roku wraz z wydaniem pakietu Microsoft Office 2007, struktura tego nowego formatu dokumentu została zmieniona ze zwykłego binarnego na kombinację plików XML i binarnych. Pliki Docx można otwierać w programie Word 2007 i wersjach pobocznych, ale nie we wcześniejszych wersjach programu MS Word, które obsługują rozszerzenia plików DOC.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-txt" name="TXT" description="Plik dokumentu tekstowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-text" name="Text" description="Plik dokumentu tekstowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-doc" name="DOC" description="Dokumenty generowane przez Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-docx" name="DOCX" description="Dokumenty Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-xls" name="XLS" description="Format pliku binarnego Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-xlsx" name="XLSX" description="Dokumenty Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-pdf" name="PDF" description="Przenośny format dokumentu (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-searchable_pdf" name="Searchable PDF" description="Przeszukiwalna przenośna grafika sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-xml" name="XML" description="Rozszerzalny język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/tif-to-json" name="JSON" description="Notacja obiektu JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
