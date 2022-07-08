﻿---
title:  
weight: 3920
url: /it/cpp/conversion/wbmp-to-xls/ 
lang: it
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Codice di esempio per la conversione Java da WBMP a XLS. Utilizzare il codice di esempio API per la conversione batch di file WBMP in XLS all'interno di qualsiasi applicazione basata su Java Web o desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.OCR" subTitlepfName="per C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="per C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/it/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/it/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="API Home" codeSamplesText="Campioni di codice" liveDemosText="Dimostrazioni dal vivo" downloadText="Scarica" learnText="Imparare">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging per Java](https://products.aspose.com/imaging/java)
 elabora le immagini scansionate o anche le foto dello smartphone in formato WBMP e crea documenti WBMP contenenti testo riconosciuto. Per aggiungerlo al tuo progetto, devi solo ottenere *Aspose.OCR*
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

Con C++ OCR e solo poche righe di codice, puoi creare un'applicazione completa che converte un'immagine WBMP in un documento XLS:

{{% /blocks/products/pf/agp/text %}}

+ Crea un'istanza della classe AsposeOcr
+ Chiama il metodo AsposeOCR.aposeocr_page()
+ Passa il percorso del file WBMP come parametro
+ AsposeOCR.asposeocr_page restituisce una stringa o un file di tipo XLS

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="WBMP" readMoreLink="https://docs.fileformat.com/image/wbmp" whatIsFormat1="Cos'è" whatIsFormat2="Formato del file" readMoreFormat="Leggi di più">}}
WBMP è un formato di file grafico monocromatico ottimizzato per i dispositivi mobili.
Le immagini WBMP sono monocromatiche (bianco e nero) in modo che le dimensioni dell'immagine siano ridotte al minimo. Un pixel nero è indicato con 0 e un pixel bianco è indicato con 1.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" whatIsFormat1="Cos'è" whatIsFormat2="Formato del file" readMoreFormat="Leggi di più">}}
I file con estensione XLS rappresentano il formato file binario di Excel. Tali file possono essere creati da Microsoft Excel e da altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Il file salvato da Excel è noto come cartella di lavoro in cui ogni cartella di lavoro può avere uno o più fogli di lavoro. I dati vengono archiviati e visualizzati agli utenti in formato tabella nel foglio di lavoro e possono comprendere valori numerici, dati di testo, formule, connessioni dati esterne, immagini e grafici. Applicazioni come Microsoft Excel ti consentono di esportare i dati della cartella di lavoro in diversi formati tra cui PDF, CSV, XLSX, TXT, HTML, XPS e molti altri. Il formato di file XLS è stato sostituito con un formato più aperto e strutturato, XLSX, con il rilascio di Microsoft Excel 2007. Le ultime versioni forniscono ancora supporto per la creazione e la lettura di file XLS, sebbene XLSX sia la prima scelta di utilizzo ora.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}