﻿---
title:  
weight: 3920
url: /pt/cpp/conversion/tif-to-pdf/ 
lang: pt
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de exemplo para conversão Java de TIF para PDF. Use o código de exemplo da API para arquivos em lote TIF para conversão PDF em qualquer aplicativo baseado em Java da Web ou Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.OCR" subTitlepfName="para C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/pt/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/pt/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="Página inicial da API" codeSamplesText="Amostras de código" liveDemosText="Demonstrações ao vivo" downloadText="Download" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
 processa imagens digitalizadas ou até mesmo fotos de smartphones no formato TIF e cria documentos TIF contendo texto reconhecido. Para adicioná-lo ao seu projeto, você só precisa obter *Aspose.OCR*
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ou especifique a configuração do repositório Aspose Maven
e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao arquivo _pom.xml_. Para exemplos de Graddle, Ivy, Sbt, confira nosso [repositório](https://repository.aspose.com/ocr/).

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

Com OCR C++ e apenas algumas linhas de código, você pode criar um aplicativo completo que converte uma imagem TIF em um documento PDF:

{{% /blocks/products/pf/agp/text %}}

+ Crie uma instância da classe AsposeOcr
+ Chama o método AsposeOCR.asposeocr_page()
+ Passe o caminho do arquivo TIF como parâmetro
+ AsposeOCR.asposeocr_page retorna uma String ou arquivo do tipo PDF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de executar o exemplo, certifique-se de que [Microsoft.ML.OnnxRuntime](https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/) 1.7.0 ou superior foi adicionado ao projeto. Ele deve ser instalado automaticamente se você instalar o Aspose.OCR por meio do NuGet Package Manager.

{{% /blocks/products/pf/agp/text %}}

- Solução compatível com NET Standard 2.0+
- Aspose.OCR para .NET referenciado em seu projeto.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIF" readMoreLink="https://docs.fileformat.com/image/tif" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação">}}
TIFF ou TIF, Tagged Image File Format, representa imagens raster que se destinam ao uso em uma variedade de dispositivos que estão em conformidade com este padrão de formato de arquivo. Ele é capaz de descrever dados de imagem de dois níveis, tons de cinza, cores de paleta e cores em vários espaços de cores. Ele suporta esquemas de compactação com e sem perdas para escolher entre espaço e tempo para aplicativos que usam o formato. O formato é extensível e passou por várias revisões que permitem a inclusão de uma quantidade ilimitada de informações privadas ou de finalidade especial. O formato não depende da máquina e está livre de limites como processador, sistema operacional ou sistemas de arquivos.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação">}}
Portable Document Format (PDF) é um tipo de documento criado pela Adobe na década de 1990. O objetivo deste formato de arquivo foi introduzir um padrão para representação de documentos e outros materiais de referência em um formato independente do software aplicativo, hardware e sistema operacional. O formato de arquivo PDF tem capacidade total para conter informações como texto, imagens, hiperlinks, campos de formulário, rich media, assinaturas digitais, anexos, metadados, recursos geoespaciais e objetos 3D que podem se tornar parte do documento de origem.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/cpp/conversion/tif-to-txt" name="TXT" description="Arquivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/cpp/conversion/tif-to-text" name="Text" description="Arquivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/cpp/conversion/tif-to-doc" name="DOC" description="Documentos gerados pelo Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/cpp/conversion/tif-to-docx" name="DOCX" description="Documentos do Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/cpp/conversion/tif-to-xls" name="XLS" description="Formato de arquivo binário do Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/cpp/conversion/tif-to-xlsx" name="XLSX" description="Documentos do Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/cpp/conversion/tif-to-pdf" name="PDF" description="Formato de Documento Portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/pt/cpp/conversion/tif-to-searchable_pdf" name="Searchable PDF" description="Gráficos de rede portáteis pesquisáveis" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
