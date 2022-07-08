﻿---
title:  
weight: 3920
url: /de/java/conversion/pdf-to-docx/ 
lang: de
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Beispielcode für die Java-Konvertierung von PDF in DOCX. Verwenden Sie den API-Beispielcode für die Batch-Konvertierung von PDF-Dateien in DOCX in jeder Web- oder Desktop-Java-basierten Anwendung.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOCX" pfName="Aspose.OCR" subTitlepfName="für Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="für Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/de/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/de/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API-Startseite" codeSamplesText="Codebeispiele" liveDemosText="Live-Demos" downloadText="Download" learnText="Lernen">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging für Java](https://products.aspose.com/imaging/java)
 verarbeitet gescannte Bilder oder sogar Smartphone-Fotos im PDF-Format und erstellt PDF-Dokumente mit erkanntem Text. Um es zu Ihrem Projekt hinzuzufügen, müssen Sie nur *Aspose.OCR* abrufen.
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) oder geben Sie die Aspose Maven Repository-Konfiguration an
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

Mit Java OCR und nur wenigen Codezeilen können Sie eine voll funktionsfähige Anwendung erstellen, die ein PDF-Bild in ein DOCX-Dokument konvertiert:

{{% /blocks/products/pf/agp/text %}}

+ Erstellen Sie eine Instanz der Klasse AsposeOcr
+ Rufen Sie die Methode AsposeOCR.RecognizePage auf
+ Übergeben Sie den Dateipfad PDF als Parameter
+ AsposeOCR.RecognizePage gibt einen String oder eine Datei vom Typ DOCX zurück

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Was ist" whatIsFormat2="Datei Format" readMoreFormat="Weiterlesen">}}
Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er Jahren erstellt wurde. Der Zweck dieses Dateiformats bestand darin, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware und Betriebssystem ist. Das PDF-Dateiformat kann Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich Media, digitale Signaturen, Anhänge, Metadaten, Geodaten und 3D-Objekte enthalten, die Teil des Quelldokuments werden können.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/word-processing/docx/" whatIsFormat1="Was ist" whatIsFormat2="Datei Format" readMoreFormat="Weiterlesen">}}
DOCX ist ein bekanntes Format für Microsoft Word-Dokumente. Die Struktur dieses neuen Dokumentformats, das 2007 mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde, wurde von einer reinen Binärdatei in eine Kombination aus XML- und Binärdateien geändert. Docx-Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit früheren Versionen von MS Word, die DOC-Dateierweiterungen unterstützen.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-txt" name="TXT" description="Textdokumentdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-text" name="Text" description="Textdokumentdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-doc" name="DOC" description="Von Microsoft Word generierte Dokumente" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-docx" name="DOCX" description="Microsoft Word-Dokumente" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-xls" name="XLS" description="Binäres Dateiformat von Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-xlsx" name="XLSX" description="Microsoft Excel-Dokumente" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-pdf" name="PDF" description="Portables Dokumentenformat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-searchable_pdf" name="Searchable PDF" description="Durchsuchbare tragbare Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-xml" name="XML" description="Erweiterbare Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/java/conversion/pdf-to-json" name="JSON" description="JavaScript-Objekt-Notation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}