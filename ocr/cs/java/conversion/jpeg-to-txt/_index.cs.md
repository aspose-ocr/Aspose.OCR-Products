---
title: Převést JPEG na TXT přes Java 
url: /cs/java/conversion/jpeg-to-txt/ 
description: Ukázka převodního kódu Java pro formát JPEG na soubor TXT. Tento příklad kódu použijte k převodu JPEG na TXT v jakékoli webové nebo desktopové aplikaci založené na Javě.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést JPEG na TXT přes Java" h2="Čtení textu z JPEG pomocí optického rozpoznávání znaků." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="Aspose.OCR" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JPEG" >}}

{{< blocks/products/pf/main-container pfName="Aspose.OCR " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-ocr" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/java" installationsDocsLink="https://docs.aspose.com/ocr/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" mavenRepoLink="https://repository.aspose.com/ocr/" >}}

{{% blocks/products/pf/agp/content h2="Jak převést JPEG na TXT pomocí Java" %}}

K vykreslení JPEG do TXT použijeme
 [Aspose.OCR for Java](https://products.aspose.com/ocr/java)
 API, což je funkčně bohaté, výkonné a snadno použitelné konverzní API pro platformu Java. Jeho nejnovější verzi si můžete stáhnout přímo z
 [Aspose Maven Repository](https://repository.aspose.com/ocr/)
 a nainstalujte jej do svého projektu založeného na Maven přidáním následujících konfigurací do souboru pom.xml.

{{% blocks/products/pf/agp/code-block title="úložiště" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Závislost" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu JPEG na TXT přes Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Vytvořte instanci třídy AsposeOcr
1. Zavolejte metodu AsposeOCR.recognizeImage
1. Předejte cestu k souboru JPEG jako parametr
1. AsposeOCR.RecognizeLine vrátí řetězec s rozpoznaným textem
1. V případě potřeby převeďte řetězec na soubor TXT

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
- Získejte nejnovější verzi Aspose.OCR pro Java přímo od Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze JPEG na TXT Java" offSpacer="" %}}
```cs
// initialize an instance of AsposeOcr
AsposeOCR ocr = new AsposeOCR();
// recognize image
String riText = ocr.RecognizeLine("template.jpeg");
// print text
System.out.print(riText);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

   

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Bezplatná aplikace pro převod JPEG na TXT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your JPEG file, it will be converted instantly to TXT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

  
{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}