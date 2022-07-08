﻿---
title:  
weight: 3920
url: /it/cpp/conversion/tif-to-docx/ 
lang: it
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Codice di esempio per la conversione Java da TIF a DOCX. Utilizzare il codice di esempio API per la conversione batch di file TIF in DOCX all'interno di qualsiasi applicazione basata su Java Web o desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOCX" pfName="Aspose.OCR" subTitlepfName="per C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="per C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/it/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/it/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="API Home" codeSamplesText="Campioni di codice" liveDemosText="Dimostrazioni dal vivo" downloadText="Scarica" learnText="Imparare">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging per Java](https://products.aspose.com/imaging/java)
 elabora le immagini scansionate o anche le foto dello smartphone in formato TIF e crea documenti TIF contenenti testo riconosciuto. Per aggiungerlo al tuo progetto, devi solo ottenere *Aspose.OCR*
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) o specifica la configurazione di Aspose Maven Repository
e installalo all'interno del tuo progetto basato su Maven aggiungendo le seguenti configurazioni a _pom.xml_. Per gli esempi di Graddle, Ivy, Sbt dai un'occhiata al nostro [repository](https://repository.aspose.com/ocr/).

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

Con C++ OCR e solo poche righe di codice, puoi creare un'applicazione completa che converte un'immagine TIF in un documento DOCX:

{{% /blocks/products/pf/agp/text %}}

+ Crea un'istanza della classe AsposeOcr
+ Chiama il metodo AsposeOCR.aposeocr_page()
+ Passa il percorso del file TIF come parametro
+ AsposeOCR.asposeocr_page restituisce una stringa o un file di tipo DOCX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

Prima di eseguire l'esempio, assicurati che [Microsoft.ML.OnnxRuntime](https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/) 1.7.0 o versione successiva sia aggiunto al progetto. Dovrebbe essere installato automaticamente se si installa Aspose.OCR tramite NuGet Package Manager.

{{% /blocks/products/pf/agp/text %}}

- Soluzione compatibile con NET Standard 2.0+
- Aspose.OCR per .NET referenziato nel tuo progetto.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIF" readMoreLink="https://docs.fileformat.com/image/tif" whatIsFormat1="Cos'è" whatIsFormat2="Formato del file" readMoreFormat="Leggi di più">}}
TIFF o TIF, Tagged Image File Format, rappresenta immagini raster destinate all'uso su una varietà di dispositivi conformi a questo standard di formato file. È in grado di descrivere dati di immagini a due livelli, in scala di grigi, a colori ea colori in diversi spazi colore. Supporta schemi di compressione lossy e lossless per scegliere tra spazio e tempo per le applicazioni che utilizzano il formato. Il formato è estensibile e ha subito diverse revisioni che consentono l'inclusione di una quantità illimitata di informazioni private o per scopi speciali. Il formato non dipende dalla macchina ed è libero da limiti come processore, sistema operativo o file system.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/word-processing/docx/" whatIsFormat1="Cos'è" whatIsFormat2="Formato del file" readMoreFormat="Leggi di più">}}
DOCX è un formato ben noto per i documenti di Microsoft Word. Introdotto dal 2007 con il rilascio di Microsoft Office 2007, la struttura di questo nuovo formato del documento è stata modificata da semplice binario a una combinazione di file XML e binari. I file Docx possono essere aperti con Word 2007 e versioni laterali ma non con le versioni precedenti di MS Word che supportano le estensioni di file DOC.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/cpp/conversion/tif-to-txt" name="TXT" description="File di documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/cpp/conversion/tif-to-text" name="Text" description="File di documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/cpp/conversion/tif-to-doc" name="DOC" description="Documenti generati da Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/cpp/conversion/tif-to-docx" name="DOCX" description="Documenti Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/cpp/conversion/tif-to-xls" name="XLS" description="Formato file binario Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/cpp/conversion/tif-to-xlsx" name="XLSX" description="Documenti Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/cpp/conversion/tif-to-pdf" name="PDF" description="Formato documento portatile (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/cpp/conversion/tif-to-searchable_pdf" name="Searchable PDF" description="Grafica di rete portatile ricercabile" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}