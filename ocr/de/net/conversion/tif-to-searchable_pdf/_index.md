﻿---
title: Konvertieren Sie TIF in Searchable PDF über C# 
weight: 3920
url: /de/net/conversion/tif-to-searchable_pdf/ 
lang: de
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Beispielcode für die C#-Konvertierung von TIF in Searchable PDF. Verwenden Sie den API-Beispielcode für die Batch-Konvertierung von TIF-Dateien in Searchable PDF innerhalb von VB.NET, Asp.NET oder einer beliebigen .NET-basierten Anwendung.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konvertieren Sie TIF in Searchable PDF in C#" h2="Führen Sie eine optische Zeichenerkennung für das TIF-Dokument durch und speichern Sie Text als TIF-Dokument mit Aspose.OCR aus der .NET-Bibliothek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="Searchable PDF" pfName="Aspose.OCR" subTitlepfName="für .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="für .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/de/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/de/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API-Startseite" codeSamplesText="Codebeispiele" liveDemosText="Live-Demos" downloadText="Download" learnText="Lernen">}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie TIF in Searchable PDF mit C#" %}}

Aspose.OCR für .NET ist eine leistungsstarke, aber benutzerfreundliche und kostengünstige Bibliothek zum Konvertieren von TIF-Bildern in Searchable PDF-Dokumente. Die hochmoderne optische Zeichenerkennungs-Engine unterstützt 26 Sprachen basierend auf Latein, Kyrillisch und Chinesisch und bietet eine überlegene Erkennungsgeschwindigkeit und -genauigkeit, während Sie von Formeln, neuronalen Netzwerken und anderen komplexen technischen Details isoliert werden. Es ermöglicht Ihnen, OCR-Funktionalität zu Ihren .NET-Anwendungen in weniger als 10 Codezeilen hinzuzufügen.

[Aspose.OCR für .NET](https://products.aspose.com/ocr/net)
 verarbeitet gescannte Bilder oder sogar Smartphone-Fotos im TIF-Format und erstellt TIF-Dokumente mit erkanntem Text. Um es zu Ihrem Projekt hinzuzufügen, müssen Sie nur die Datei *Aspose.OCR* installieren.
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 Paket in Ihrem Projekt mit dem folgenden Befehl:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von TIF in Searchable PDF" %}}

{{% blocks/products/pf/agp/text %}}

Mit .NET OCR und nur wenigen Codezeilen können Sie eine voll funktionsfähige Anwendung erstellen, die ein TIF-Bild in ein Searchable PDF-Dokument konvertiert:

{{% /blocks/products/pf/agp/text %}}

+ Erstellen Sie eine Instanz der Klasse AsposeOcr
+ Rufen Sie die Methode AsposeOCR.RecognizeImage auf
+ Übergeben Sie den Dateipfad TIF als Parameter
+ AsposeOCR.RecognizeImage gibt einen String oder eine Datei vom Typ Searchable PDF zurück

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

Stellen Sie vor dem Ausführen des Beispiels sicher, dass die mit der NET Standard 2.0-Spezifikation kompatible .NET-API auf Ihrem System installiert ist und alle [externen Abhängigkeiten](https://docs.aspose.com/ocr/net/system-requirements/#external- Abhängigkeiten) des Aspose.OCR-Pakets werden in Ihrem Projekt referenziert.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ kompatible Lösung
- Aspose.OCR für .NET, auf das in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieser Beispielcode zeigt die Konvertierung von TIF in Searchable PDF .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.TIF");
// print text
File. File.WriteAllText("document.Searchable PDF", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIF" readMoreLink="https://docs.fileformat.com/image/tif" whatIsFormat1="Was ist" whatIsFormat2="Datei Format" readMoreFormat="Weiterlesen">}}
TIFF oder TIF, Tagged Image File Format, stellt Rasterbilder dar, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Es ist in der Lage, Bilevel-, Graustufen-, Palettenfarben- und Vollfarben-Bilddaten in mehreren Farbräumen zu beschreiben. Es unterstützt sowohl verlustbehaftete als auch verlustfreie Komprimierungsschemata, um zwischen Speicherplatz und Zeit für Anwendungen zu wählen, die das Format verwenden. Das Format ist erweiterbar und wurde mehrfach überarbeitet, was die Aufnahme einer unbegrenzten Menge an privaten oder speziellen Informationen ermöglicht. Das Format ist nicht maschinenabhängig und frei von Grenzen wie Prozessor, Betriebssystem oder Dateisystem.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Searchable PDF" readMoreLink="https://docs.fileformat.com/pdf/a/" whatIsFormat1="Was ist" whatIsFormat2="Datei Format" readMoreFormat="Weiterlesen">}}
Durchsuchbare PDF-Dateien behalten das gescannte Originalbild zur Anzeige sowie OCR-Text in einer verborgenen Ebene bei, die für die Volltextsuche in einem Dokument oder zum Hervorheben von Text zum Kopieren und Einfügen verwendet werden kann.
Die vollständige OCR-Konvertierung in PDF, ohne das Originalbild, wird niemals 100 % der Originalformatierung beibehalten, insbesondere wenn das Dokument viele Bilder oder ein komplexes Layout enthält.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Mit C# kann man problemlos verschiedene Formate konvertieren, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-txt" name="TXT" description="Textdokumentdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-text" name="Text" description="Textdokumentdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-doc" name="DOC" description="Von Microsoft Word generierte Dokumente" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-docx" name="DOCX" description="Microsoft Word-Dokumente" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-xls" name="XLS" description="Binäres Dateiformat von Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-xlsx" name="XLSX" description="Microsoft Excel-Dokumente" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-pdf" name="PDF" description="Portables Dokumentenformat (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-searchable_pdf" name="Searchable PDF" description="Durchsuchbare tragbare Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-xml" name="XML" description="Erweiterbare Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/de/net/conversion/tif-to-json" name="JSON" description="JavaScript-Objekt-Notation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}