﻿---
title:  
weight: 3920
url: /pl/java/conversion/wbmp-to-xls/ 
lang: pl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Przykładowy kod konwersji WBMP na XLS Java. Użyj przykładowego kodu API dla plików wsadowych WBMP do konwersji XLS w dowolnej aplikacji internetowej lub opartej na Javie na komputery stacjonarne.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.OCR" subTitlepfName="dla Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="dla Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/pl/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/pl/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Strona główna API" codeSamplesText="Próbki kodu" liveDemosText="Prezentacje na żywo" downloadText="Ściągnij" learnText="Uczyć się">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging dla Javy](https://products.aspose.com/imaging/java)
 przetwarza zeskanowane obrazy, a nawet zdjęcia ze smartfona w formacie WBMP i tworzy dokumenty WBMP zawierające rozpoznany tekst. Aby dodać go do swojego projektu, wystarczy pobrać *Aspose.OCR*
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

Dzięki Java OCR i zaledwie kilku linijkom kodu możesz stworzyć w pełni funkcjonalną aplikację, która konwertuje obraz WBMP na dokument XLS:

{{% /blocks/products/pf/agp/text %}}

+ Utwórz instancję klasy AsposeOcr
+ Wywołaj metodę AsposeOCR.RecognizePage
+ Przekaż ścieżkę pliku WBMP jako parametr
+ AsposeOCR.RecognizePage zwraca ciąg lub plik typu XLS

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="WBMP" readMoreLink="https://docs.fileformat.com/image/wbmp" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej">}}
WBMP to monochromatyczny format plików graficznych zoptymalizowany pod kątem mobilnych urządzeń komputerowych.
Obrazy WBMP są monochromatyczne (czarno-białe), dzięki czemu rozmiar obrazu jest ograniczony do minimum. Czarny piksel jest oznaczony przez 0, a biały piksel jest oznaczony przez 1.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej">}}
Pliki z rozszerzeniem XLS reprezentują format pliku binarnego Excel. Takie pliki mogą być tworzone przez Microsoft Excel, a także inne podobne programy do arkuszy kalkulacyjnych, takie jak OpenOffice Calc lub Apple Numbers. Plik zapisany przez program Excel jest znany jako skoroszyt, w którym każdy skoroszyt może zawierać jeden lub więcej arkuszy. Dane są przechowywane i wyświetlane użytkownikom w formacie tabeli w arkuszu i mogą obejmować wartości liczbowe, dane tekstowe, formuły, połączenia danych zewnętrznych, obrazy i wykresy. Aplikacje takie jak Microsoft Excel umożliwiają eksportowanie danych ze skoroszytu do kilku różnych formatów, w tym PDF, CSV, XLSX, TXT, HTML, XPS i kilku innych. Format pliku XLS został zastąpiony bardziej otwartym i ustrukturyzowanym formatem, XLSX, wraz z wydaniem Microsoft Excel 2007. Najnowsze wersje nadal zapewniają obsługę tworzenia i odczytywania plików XLS, chociaż XLSX jest teraz pierwszym wyborem.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-txt" name="TXT" description="Plik dokumentu tekstowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-text" name="Text" description="Plik dokumentu tekstowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-doc" name="DOC" description="Dokumenty generowane przez Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-docx" name="DOCX" description="Dokumenty Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-xls" name="XLS" description="Format pliku binarnego Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-xlsx" name="XLSX" description="Dokumenty Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-pdf" name="PDF" description="Przenośny format dokumentu (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-searchable_pdf" name="Searchable PDF" description="Przeszukiwalna przenośna grafika sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-xml" name="XML" description="Rozszerzalny język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pl/java/conversion/wbmp-to-json" name="JSON" description="Notacja obiektu JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
