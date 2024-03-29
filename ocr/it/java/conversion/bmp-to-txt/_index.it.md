---
title: Converti BMP in TXT tramite Java 
url: /it/java/conversion/bmp-to-txt/ 
description: Esempio di codice di conversione Java per il formato BMP in file TXT. Utilizzare questo codice di esempio per convertire BMP in TXT all'interno di qualsiasi applicazione basata su Java Web o Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti BMP in TXT tramite Java" h2="Leggi il testo da BMP utilizzando il riconoscimento ottico dei caratteri." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="Aspose.OCR" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="BMP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.OCR " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-ocr" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/java" installationsDocsLink="https://docs.aspose.com/ocr/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" mavenRepoLink="https://repository.aspose.com/ocr/" >}}

{{% blocks/products/pf/agp/content h2="Come convertire BMP in TXT usando Java" %}}

Per rendere BMP in TXT, useremo
 [Aspose.OCR per Java](https://products.aspose.com/ocr/java)
 API che è un'API di conversione ricca di funzionalità, potente e facile da usare per la piattaforma Java. Puoi scaricare la sua ultima versione direttamente da
 [Aspose Maven Repository](https://repository.aspose.com/ocr/)
 e installalo all'interno del tuo progetto basato su Maven aggiungendo le seguenti configurazioni a pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dipendenza" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-ocr</artifactId>
<version>version of aspose-ocr API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire BMP in TXT tramite Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Crea un'istanza della classe AsposeOcr
1. Chiamare il metodo AsposeOCR.recognizeImage
1. Passare il percorso del file BMP come parametro
1. AsposeOCR.RecognizeLine restituisce una stringa con testo riconosciuto
1. Converti stringa in file TXT, se necessario

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.
- Ottieni l'ultima versione di Aspose.OCR per Java direttamente da Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice sorgente di conversione Java da BMP a TXT" offSpacer="" %}}


```cs
// initialize an instance of AsposeOcr
AsposeOCR ocr = new AsposeOCR();
// recognize image
String riText = ocr.RecognizeLine("template.bmp");
// print text
System.out.print(riText);   

```



{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

   

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per convertire BMP in TXT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your BMP file, it will be converted instantly to TXT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

  
{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}