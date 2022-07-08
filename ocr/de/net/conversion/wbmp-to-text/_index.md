﻿---
title: Konvertieren Sie WBMP in Text über C# 
weight: 3920
url: /de/net/conversion/wbmp-to-text/ 
lang: de
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Beispielcode für die C#-Konvertierung von WBMP in Text. Verwenden Sie den API-Beispielcode für die Batch-Konvertierung von WBMP-Dateien in Text innerhalb von VB.NET, Asp.NET oder einer beliebigen .NET-basierten Anwendung.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konvertieren Sie WBMP in Text in C#" h2="Führen Sie eine optische Zeichenerkennung für das WBMP-Dokument durch und speichern Sie Text als WBMP-Dokument mit Aspose.OCR aus der .NET-Bibliothek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="Text" pfName="Aspose.OCR" subTitlepfName="für .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="für .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/de/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/de/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API-Startseite" codeSamplesText="Codebeispiele" liveDemosText="Live-Demos" downloadText="Download" learnText="Lernen">}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie WBMP in Text mit C#" %}}

Aspose.OCR für .NET ist eine leistungsstarke, aber benutzerfreundliche und kostengünstige Bibliothek zum Konvertieren von WBMP-Bildern in Text-Dokumente. Die hochmoderne optische Zeichenerkennungs-Engine unterstützt 26 Sprachen basierend auf Latein, Kyrillisch und Chinesisch und bietet eine überlegene Erkennungsgeschwindigkeit und -genauigkeit, während Sie von Formeln, neuronalen Netzwerken und anderen komplexen technischen Details isoliert werden. Es ermöglicht Ihnen, OCR-Funktionalität zu Ihren .NET-Anwendungen in weniger als 10 Codezeilen hinzuzufügen.

[Aspose.OCR für .NET](https://products.aspose.com/ocr/net)
 verarbeitet gescannte Bilder oder sogar Smartphone-Fotos im WBMP-Format und erstellt WBMP-Dokumente mit erkanntem Text. Um es zu Ihrem Projekt hinzuzufügen, müssen Sie nur die Datei *Aspose.OCR* installieren.
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 Paket in Ihrem Projekt mit dem folgenden Befehl:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von WBMP in Text" %}}

{{% blocks/products/pf/agp/text %}}

Mit .NET OCR und nur wenigen Codezeilen können Sie eine voll funktionsfähige Anwendung erstellen, die ein WBMP-Bild in ein Text-Dokument konvertiert:

{{% /blocks/products/pf/agp/text %}}

+ Erstellen Sie eine Instanz der Klasse AsposeOcr
+ Rufen Sie die Methode AsposeOCR.RecognizeImage auf
+ Übergeben Sie den Dateipfad WBMP als Parameter
+ AsposeOCR.RecognizeImage gibt einen String oder eine Datei vom Typ Text zurück

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

Stellen Sie vor dem Ausführen des Beispiels sicher, dass die mit der NET Standard 2.0-Spezifikation kompatible .NET-API auf Ihrem System installiert ist und alle [externen Abhängigkeiten](https://docs.aspose.com/ocr/net/system-requirements/#external- Abhängigkeiten) des Aspose.OCR-Pakets werden in Ihrem Projekt referenziert.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ kompatible Lösung
- Aspose.OCR für .NET, auf das in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieser Beispielcode zeigt die Konvertierung von WBMP in Text .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.WBMP");
// print text
File. File.WriteAllText("document.Text", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="WBMP" readMoreLink="https://docs.fileformat.com/image/wbmp" whatIsFormat1="Was ist" whatIsFormat2="Datei Format" readMoreFormat="Weiterlesen">}}
WBMP ist ein monochromes Grafikdateiformat, das für mobile Computergeräte optimiert ist.
WBMP-Bilder sind monochrom (schwarzweiß), sodass die Bildgröße auf ein Minimum reduziert wird. Ein schwarzer Pixel wird mit 0 und ein weißer Pixel mit 1 bezeichnet.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Text" readMoreLink="https://docs.fileformat.com/word-processing/txt/" whatIsFormat1="Was ist" whatIsFormat2="Datei Format" readMoreFormat="Weiterlesen">}}
Eine Datei mit der Erweiterung .TXT stellt ein Textdokument dar, das einfachen Text in Form von Zeilen enthält. Absätze in einem Textdokument werden durch Carriage Returns erkannt und dienen der besseren Anordnung von Dateiinhalten. Ein Standardtextdokument kann in jedem Texteditor oder jeder Textverarbeitungsanwendung auf verschiedenen Betriebssystemen geöffnet werden. Der gesamte in einer solchen Datei enthaltene Text ist in einem für Menschen lesbaren Format und wird durch eine Zeichenfolge dargestellt.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Mit C# kann man problemlos verschiedene Formate konvertieren, einschließlich." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}