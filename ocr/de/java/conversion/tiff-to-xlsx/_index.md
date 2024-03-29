﻿---
title:  
weight: 3920
url: /de/java/conversion/tiff-to-xlsx/ 
lang: de
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Beispielcode für die Java-Konvertierung von TIFF in XLSX. Verwenden Sie den API-Beispielcode für die Batch-Konvertierung von TIFF-Dateien in XLSX in jeder Web- oder Desktop-Java-basierten Anwendung.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.OCR" subTitlepfName="für Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="für Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/de/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/de/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API-Startseite" codeSamplesText="Codebeispiele" liveDemosText="Live-Demos" downloadText="Download" learnText="Lernen">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging für Java](https://products.aspose.com/imaging/java)
 verarbeitet gescannte Bilder oder sogar Smartphone-Fotos im TIFF-Format und erstellt TIFF-Dokumente mit erkanntem Text. Um es zu Ihrem Projekt hinzuzufügen, müssen Sie nur *Aspose.OCR* abrufen.
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) oder geben Sie die Aspose Maven Repository-Konfiguration an
und installieren Sie es in Ihrem Maven-basierten Projekt, indem Sie die folgenden Konfigurationen zu _pom.xml_ hinzufügen. Beispiele für Graddle, Ivy und Sbt finden Sie in unserem [Repository] (https://repository.aspose.com/ocr/).

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

Mit Java OCR und nur wenigen Codezeilen können Sie eine voll funktionsfähige Anwendung erstellen, die ein TIFF-Bild in ein XLSX-Dokument konvertiert:

{{% /blocks/products/pf/agp/text %}}

+ Erstellen Sie eine Instanz der Klasse AsposeOcr
+ Rufen Sie die Methode AsposeOCR.RecognizePage auf
+ Übergeben Sie den Dateipfad TIFF als Parameter
+ AsposeOCR.RecognizePage gibt einen String oder eine Datei vom Typ XLSX zurück

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

Stellen Sie vor dem Ausführen des Beispiels sicher, dass Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) oder höher auf Ihrem System installiert ist.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 oder höher ist installiert.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff" whatIsFormat1="Was ist" whatIsFormat2="Datei Format" readMoreFormat="Weiterlesen">}}
TIFF oder TIF, Tagged Image File Format, stellt Rasterbilder dar, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Es ist in der Lage, Bilevel-, Graustufen-, Palettenfarben- und Vollfarben-Bilddaten in mehreren Farbräumen zu beschreiben. Es unterstützt sowohl verlustbehaftete als auch verlustfreie Komprimierungsschemata, um zwischen Speicherplatz und Zeit für Anwendungen zu wählen, die das Format verwenden. Das Format ist erweiterbar und wurde mehrfach überarbeitet, was die Aufnahme einer unbegrenzten Menge an privaten oder speziellen Informationen ermöglicht. Das Format ist nicht maschinenabhängig und frei von Grenzen wie Prozessor, Betriebssystem oder Dateisystem.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" whatIsFormat1="Was ist" whatIsFormat2="Datei Format" readMoreFormat="Weiterlesen">}}
XLSX ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Das neue Format basiert auf einer Struktur, die gemäß den Open Packaging Conventions organisiert ist, wie in Teil 2 des OOXML-Standards ECMA-376 beschrieben ein ZIP-Paket, das eine Reihe von XML-Dateien enthält. Die zugrunde liegende Struktur und Dateien können durch einfaches Entpacken der .xlsx-Datei untersucht werden.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-txt" name="TXT" description="Textdokumentdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-text" name="Text" description="Textdokumentdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-doc" name="DOC" description="Von Microsoft Word generierte Dokumente" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-docx" name="DOCX" description="Microsoft Word-Dokumente" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-xls" name="XLS" description="Binäres Dateiformat von Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-xlsx" name="XLSX" description="Microsoft Excel-Dokumente" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-pdf" name="PDF" description="Portables Dokumentenformat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-searchable_pdf" name="Searchable PDF" description="Durchsuchbare tragbare Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-xml" name="XML" description="Erweiterbare Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/tiff-to-json" name="JSON" description="JavaScript-Objekt-Notation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
