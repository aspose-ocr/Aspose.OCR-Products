﻿---
title:  
weight: 3920
url: /pt/java/conversion/jpg-to-searchable_pdf/ 
lang: pt
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de exemplo para conversão Java de JPG para Searchable PDF. Use o código de exemplo da API para arquivos em lote JPG para conversão Searchable PDF em qualquer aplicativo baseado em Java da Web ou Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="Searchable PDF" pfName="Aspose.OCR" subTitlepfName="para Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/pt/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/pt/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Página inicial da API" codeSamplesText="Amostras de código" liveDemosText="Demonstrações ao vivo" downloadText="Download" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
 processa imagens digitalizadas ou até mesmo fotos de smartphones no formato JPG e cria documentos JPG contendo texto reconhecido. Para adicioná-lo ao seu projeto, você só precisa obter *Aspose.OCR*
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ou especifique a configuração do repositório Aspose Maven
e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao arquivo _pom.xml_. Para exemplos de Graddle, Ivy, Sbt, confira nosso [repositório](https://repository.aspose.com/ocr/).

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

Com Java OCR e apenas algumas linhas de código, você pode criar um aplicativo completo que converte uma imagem JPG em um documento Searchable PDF:

{{% /blocks/products/pf/agp/text %}}

+ Crie uma instância da classe AsposeOcr
+ Chamar o método AsposeOCR.RecognizePage
+ Passe o caminho do arquivo JPG como parâmetro
+ AsposeOCR.RecognizePage retorna uma String ou arquivo do tipo Searchable PDF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de executar o exemplo, certifique-se de que o Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) ou posterior esteja instalado em seu sistema.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 ou superior está instalado.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPG" readMoreLink="https://docs.fileformat.com/image/jpg" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação">}}
Um JPEG é um tipo de formato de imagem que é salvo usando o método de compactação com perdas. A imagem de saída, como resultado da compactação, é uma compensação entre o tamanho do armazenamento e a qualidade da imagem. Os usuários podem ajustar o nível de compactação para atingir o nível de qualidade desejado e, ao mesmo tempo, reduzir o tamanho do armazenamento. A qualidade da imagem é afetada de forma insignificante se a compressão 10:1 for aplicada à imagem. Quanto maior o valor de compactação, maior a degradação na qualidade da imagem.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Searchable PDF" readMoreLink="https://docs.fileformat.com/pdf/a/" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação">}}
Os arquivos PDF pesquisáveis ​​retêm a imagem digitalizada original para visualização, bem como o texto OCR em uma camada oculta que pode ser usada para pesquisas de texto completo em um documento ou realce de texto para operações de copiar e colar.
A conversão OCR completa para PDF, sem incluir a imagem original, nunca reterá 100% da formatação original, especialmente se o documento tiver muitas imagens ou um layout complexo.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-txt" name="TXT" description="Arquivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-text" name="Text" description="Arquivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-doc" name="DOC" description="Documentos gerados pelo Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-docx" name="DOCX" description="Documentos do Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-xls" name="XLS" description="Formato de arquivo binário do Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-xlsx" name="XLSX" description="Documentos do Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-pdf" name="PDF" description="Formato de Documento Portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-searchable_pdf" name="Searchable PDF" description="Gráficos de rede portáteis pesquisáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-xml" name="XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/java/conversion/jpg-to-json" name="JSON" description="Notação de Objeto JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}