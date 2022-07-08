﻿---
title: Converti TIFF in XLS tramite C# 
weight: 3920
url: /it/net/conversion/tiff-to-xls/ 
lang: it
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Codice di esempio per la conversione da TIFF a XLS C#. Utilizzare il codice di esempio API per la conversione batch di file TIFF in XLS all'interno di VB.NET, Asp.NET o qualsiasi applicazione basata su .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Converti TIFF in XLS in C#" h2="Esegui il riconoscimento ottico dei caratteri sul documento TIFF e salva il testo come documento TIFF utilizzando Aspose.OCR dalla libreria .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.OCR" subTitlepfName="per .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="per .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/it/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/it/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API Home" codeSamplesText="Campioni di codice" liveDemosText="Dimostrazioni dal vivo" downloadText="Scarica" learnText="Imparare">}}

{{% blocks/products/pf/agp/content h2="Come convertire TIFF in XLS usando C#" %}}

Aspose.OCR per .NET è una libreria potente ma facile da usare ed economica per convertire immagini TIFF in documenti XLS. Supportando 26 lingue basate su latino, cirillico e cinese, il suo motore di riconoscimento ottico dei caratteri all'avanguardia offre velocità e precisione di riconoscimento superiori, isolandoti da formule, reti neurali e altri dettagli tecnici complessi. Ti consente di aggiungere funzionalità OCR alle tue applicazioni .NET in meno di 10 righe di codice.

[Aspose.OCR per .NET](https://products.aspose.com/ocr/net)
 elabora le immagini scansionate o anche le foto dello smartphone in formato TIFF e crea documenti TIFF contenenti testo riconosciuto. Per aggiungerlo al tuo progetto, devi solo installare *Aspose.OCR*
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 pacchetto nel tuo progetto con il seguente comando:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire TIFF in XLS" %}}

{{% blocks/products/pf/agp/text %}}

Con .NET OCR e poche righe di codice, puoi creare un'applicazione completa che converte un'immagine TIFF in un documento XLS:

{{% /blocks/products/pf/agp/text %}}

+ Crea un'istanza della classe AsposeOcr
+ Chiama il metodo AsposeOCR.RecognizeImage
+ Passa il percorso del file TIFF come parametro
+ AsposeOCR.RecognizeImage restituisce una stringa o un file di tipo XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

Prima di eseguire l'esempio, assicurati che l'API .NET compatibile con la specifica NET Standard 2.0 sia installata sul tuo sistema e tutte le [dipendenze esterne](https://docs.aspose.com/ocr/net/system-requirements/#external- dipendenze) del pacchetto Aspose.OCR sono referenziati nel progetto.

{{% /blocks/products/pf/agp/text %}}

- Soluzione compatibile con NET Standard 2.0+
- Aspose.OCR per .NET referenziato nel tuo progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo codice di esempio mostra la conversione da TIFF a XLS .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.TIFF");
// print text
File. File.WriteAllText("document.XLS", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff" whatIsFormat1="Cos'è" whatIsFormat2="Formato del file" readMoreFormat="Leggi di più">}}
TIFF o TIF, Tagged Image File Format, rappresenta immagini raster destinate all'uso su una varietà di dispositivi conformi a questo standard di formato file. È in grado di descrivere dati di immagini a due livelli, in scala di grigi, a colori ea colori in diversi spazi colore. Supporta schemi di compressione lossy e lossless per scegliere tra spazio e tempo per le applicazioni che utilizzano il formato. Il formato è estensibile e ha subito diverse revisioni che consentono l'inclusione di una quantità illimitata di informazioni private o per scopi speciali. Il formato non dipende dalla macchina ed è libero da limiti come processore, sistema operativo o file system.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" whatIsFormat1="Cos'è" whatIsFormat2="Formato del file" readMoreFormat="Leggi di più">}}
I file con estensione XLS rappresentano il formato file binario di Excel. Tali file possono essere creati da Microsoft Excel e da altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Il file salvato da Excel è noto come cartella di lavoro in cui ogni cartella di lavoro può avere uno o più fogli di lavoro. I dati vengono archiviati e visualizzati agli utenti in formato tabella nel foglio di lavoro e possono comprendere valori numerici, dati di testo, formule, connessioni dati esterne, immagini e grafici. Applicazioni come Microsoft Excel ti consentono di esportare i dati della cartella di lavoro in diversi formati tra cui PDF, CSV, XLSX, TXT, HTML, XPS e molti altri. Il formato di file XLS è stato sostituito con un formato più aperto e strutturato, XLSX, con il rilascio di Microsoft Excel 2007. Le ultime versioni forniscono ancora supporto per la creazione e la lettura di file XLS, sebbene XLSX sia la prima scelta di utilizzo ora.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Usando C#, è possibile convertire facilmente diversi formati tra cui." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-txt" name="TXT" description="File di documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-text" name="Text" description="File di documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-doc" name="DOC" description="Documenti generati da Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-docx" name="DOCX" description="Documenti Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-xls" name="XLS" description="Formato file binario Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-xlsx" name="XLSX" description="Documenti Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-pdf" name="PDF" description="Formato documento portatile (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-searchable_pdf" name="Searchable PDF" description="Grafica di rete portatile ricercabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-xml" name="XML" description="Linguaggio di markup estensibile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/net/conversion/tiff-to-json" name="JSON" description="Notazione oggetto JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}