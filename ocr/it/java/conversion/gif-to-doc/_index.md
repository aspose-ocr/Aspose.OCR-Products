﻿---
title:  
weight: 3920
url: /it/java/conversion/gif-to-doc/ 
lang: it
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Codice di esempio per la conversione Java da GIF a DOC. Utilizzare il codice di esempio API per la conversione batch di file GIF in DOC all'interno di qualsiasi applicazione basata su Java Web o desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.OCR" subTitlepfName="per Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="per Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/it/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/it/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API Home" codeSamplesText="Campioni di codice" liveDemosText="Dimostrazioni dal vivo" downloadText="Scarica" learnText="Imparare">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging per Java](https://products.aspose.com/imaging/java)
 elabora le immagini scansionate o anche le foto dello smartphone in formato GIF e crea documenti GIF contenenti testo riconosciuto. Per aggiungerlo al tuo progetto, devi solo ottenere *Aspose.OCR*
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) o specifica la configurazione di Aspose Maven Repository
e installalo all'interno del tuo progetto basato su Maven aggiungendo le seguenti configurazioni a _pom.xml_. Per gli esempi di Graddle, Ivy, Sbt dai un'occhiata al nostro [repository](https://repository.aspose.com/ocr/).

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

Con Java OCR e solo poche righe di codice, puoi creare un'applicazione completa che converte un'immagine GIF in un documento DOC:

{{% /blocks/products/pf/agp/text %}}

+ Crea un'istanza della classe AsposeOcr
+ Chiama il metodo AsposeOCR.RecognizePage
+ Passa il percorso del file GIF come parametro
+ AsposeOCR.RecognizePage restituisce una stringa o un file di tipo DOC

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

Prima di eseguire l'esempio, assicurarsi che Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) o successivo sia installato sul sistema.

{{% /blocks/products/pf/agp/text %}}

- È installato JDK 1.6 o versioni successive.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif" whatIsFormat1="Cos'è" whatIsFormat2="Formato del file" readMoreFormat="Leggi di più">}}
Un formato GIF o Graphical Interchange Format è un tipo di immagine altamente compressa. Di proprietà di Unisys, GIF utilizza l'algoritmo di compressione LZW che non degrada la qualità dell'immagine. Per ogni immagine GIF in genere consentono fino a 8 bit per pixel e sono consentiti fino a 256 colori nell'immagine. In contrasto con un'immagine JPEG, che può visualizzare fino a 16 milioni di colori e tocca abbastanza i limiti dell'occhio umano. Quando è emerso Internet, le GIF sono rimaste la scelta migliore perché richiedevano una larghezza di banda ridotta e compatibili per la grafica che consuma aree di colore solide. Una GIF animata combina numerose immagini o fotogrammi in un unico file e le visualizza in sequenza per generare una clip animata o un breve video. I limiti di colore sono fino a 256 per ogni fotogramma e sono probabilmente i meno adatti per riprodurre altre immagini e fotografie con gradiente di colore.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOC" readMoreLink="https://docs.fileformat.com/word-processing/doc/" whatIsFormat1="Cos'è" whatIsFormat2="Formato del file" readMoreFormat="Leggi di più">}}
I file con estensione .doc rappresentano documenti generati da Microsoft Word o altri documenti di elaborazione testi in formato binario. L'estensione è stata inizialmente utilizzata per la documentazione in testo normale su diversi sistemi operativi. Può contenere diversi tipi di dati come immagini, formattati e testo normale, grafici, grafici, oggetti incorporati, collegamenti, pagine, formattazione della pagina, impostazioni di stampa e molti altri. Il formato era popolare per tutti i tipi di documentazione grazie alla varietà di opzioni che offre agli utenti per la scrittura di manuali, proposte, specifiche, curriculum, articoli o documenti simili. La versione aggiornata di DOC è DOCX che si basa su Office OpenXML le cui specifiche sono pubblicamente disponibili.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-txt" name="TXT" description="File di documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-text" name="Text" description="File di documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-doc" name="DOC" description="Documenti generati da Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-docx" name="DOCX" description="Documenti Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-xls" name="XLS" description="Formato file binario Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-xlsx" name="XLSX" description="Documenti Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-pdf" name="PDF" description="Formato documento portatile (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-searchable_pdf" name="Searchable PDF" description="Grafica di rete portatile ricercabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-xml" name="XML" description="Linguaggio di markup estensibile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/it/java/conversion/gif-to-json" name="JSON" description="Notazione oggetto JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}