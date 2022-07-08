﻿---
title: Converter DJVU para Searchable PDF via C# 
weight: 3920
url: /pt/net/conversion/djvu-to-searchable_pdf/ 
lang: pt
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de exemplo para conversão de C# DJVU para Searchable PDF. Use o código de exemplo de API para arquivos DJVU em lote para conversão Searchable PDF em VB.NET, Asp.NET ou qualquer aplicativo baseado em .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Converter DJVU em Searchable PDF em C#" h2="Execute o reconhecimento óptico de caracteres no documento DJVU e salve o texto como documento DJVU usando a biblioteca Aspose.OCR fro .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="Searchable PDF" pfName="Aspose.OCR" subTitlepfName="para .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/pt/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/pt/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Página inicial da API" codeSamplesText="Amostras de código" liveDemosText="Demonstrações ao vivo" downloadText="Download" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="Como converter DJVU para Searchable PDF usando C#" %}}

Aspose.OCR para .NET é uma biblioteca poderosa, mas fácil de usar e econômica para converter imagens DJVU em documentos Searchable PDF. Suportando 26 idiomas baseados em latim, cirílico e chinês, seu mecanismo de reconhecimento óptico de caracteres de última geração fornece velocidade e precisão de reconhecimento superiores, enquanto isola você de fórmulas, redes neurais e outros detalhes técnicos complexos. Ele permite que você adicione a funcionalidade OCR aos seus aplicativos .NET em menos de 10 linhas de código.

[Aspose.OCR para .NET](https://products.aspose.com/ocr/net)
 processa imagens digitalizadas ou até mesmo fotos de smartphones no formato DJVU e cria documentos DJVU contendo texto reconhecido. Para adicioná-lo ao seu projeto, você só precisa instalar o *Aspose.OCR*
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 package em seu projeto com o seguinte comando:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter DJVU em Searchable PDF" %}}

{{% blocks/products/pf/agp/text %}}

Com o OCR .NET e apenas algumas linhas de código, você pode criar um aplicativo completo que converte uma imagem DJVU em um documento Searchable PDF:

{{% /blocks/products/pf/agp/text %}}

+ Crie uma instância da classe AsposeOcr
+ Chamar o método AsposeOCR.RecognizeImage
+ Passe o caminho do arquivo DJVU como parâmetro
+ AsposeOCR.RecognizeImage retorna uma String ou arquivo do tipo Searchable PDF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de executar o exemplo, certifique-se de que a API .NET compatível com a especificação NET Standard 2.0 esteja instalada em seu sistema e todas as [dependências externas](https://docs.aspose.com/ocr/net/system-requirements/#external- dependencies) do pacote Aspose.OCR são referenciados em seu projeto.

{{% /blocks/products/pf/agp/text %}}

- Solução compatível com NET Standard 2.0+
- Aspose.OCR para .NET referenciado em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de amostra mostra a conversão de DJVU para Searchable PDF .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.DJVU");
// print text
File. File.WriteAllText("document.Searchable PDF", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação">}}
DjVu, pronunciado como “déjà vu”, é um formato de arquivo gráfico destinado a documentos e livros digitalizados, especialmente aqueles que contêm a combinação de texto, desenhos, imagens e fotografias. Foi desenvolvido pela AT&T Labs. Ele usa várias técnicas, como separação de camadas de imagem de texto e imagens de fundo, carregamento progressivo, codificação aritmética e compactação com perdas para imagens bitonais. Como o arquivo DJVU pode conter imagens coloridas, fotografias, textos e desenhos compactados e de alta qualidade e pode ser salvo em menos espaço, ele é usado na web como eBooks, manuais, jornais, documentos antigos etc.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Searchable PDF" readMoreLink="https://docs.fileformat.com/pdf/a/" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação">}}
Os arquivos PDF pesquisáveis ​​retêm a imagem digitalizada original para visualização, bem como o texto OCR em uma camada oculta que pode ser usada para pesquisas de texto completo em um documento ou realce de texto para operações de copiar e colar.
A conversão OCR completa para PDF, sem incluir a imagem original, nunca reterá 100% da formatação original, especialmente se o documento tiver muitas imagens ou um layout complexo.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Usando C#, pode-se converter facilmente diferentes formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-txt" name="TXT" description="Arquivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-text" name="Text" description="Arquivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-doc" name="DOC" description="Documentos gerados pelo Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-docx" name="DOCX" description="Documentos do Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-xls" name="XLS" description="Formato de arquivo binário do Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-xlsx" name="XLSX" description="Documentos do Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-pdf" name="PDF" description="Formato de Documento Portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-searchable_pdf" name="Searchable PDF" description="Gráficos de rede portáteis pesquisáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-xml" name="XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/net/conversion/djvu-to-json" name="JSON" description="Notação de Objeto JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}