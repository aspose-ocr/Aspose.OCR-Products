﻿---
title: Convierta JP2 a TXT a través de C# 
weight: 3920
url: /es/net/conversion/jp2-to-txt/ 
lang: es
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de muestra para la conversión de C# de JP2 a TXT. Utilice el código de ejemplo de API para la conversión por lotes de archivos JP2 a TXT dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convertir {Formato1} a {Formato2} en C#" h2="Realice el reconocimiento óptico de caracteres en el documento JP2 y guarde el texto como documento JP2 usando Aspose.OCR de la biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/es/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/es/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Inicio de la API" codeSamplesText="Ejemplos de código" liveDemosText="demostraciones en vivo" downloadText="Descargar" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="Cómo convertir JP2 a TXT usando C#" %}}

Aspose.OCR para .NET es una biblioteca potente pero fácil de usar y rentable para convertir imágenes JP2 a documentos TXT. Compatible con 26 idiomas basados ​​en el latín, el cirílico y el chino, su motor de reconocimiento óptico de caracteres de última generación proporciona una velocidad y precisión de reconocimiento superiores, a la vez que lo aísla de fórmulas, redes neuronales y otros detalles técnicos complejos. Le permite agregar la funcionalidad OCR a sus aplicaciones .NET en menos de 10 líneas de código.

[Aspose.OCR para .NET](https://products.aspose.com/ocr/net)
 procesa imágenes escaneadas o incluso fotos de teléfonos inteligentes en formato JP2 y crea documentos JP2 que contienen texto reconocido. Para agregarlo a su proyecto, solo necesita instalar *Aspose.OCR*
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 paquete en su proyecto con el siguiente comando:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir {Formato1} a {Formato2}" %}}

{{% blocks/products/pf/agp/text %}}

Con .NET OCR y solo unas pocas líneas de código, puede crear una aplicación con todas las funciones que convierte una imagen JP2 en un documento TXT:

{{% /blocks/products/pf/agp/text %}}

+ Crear una instancia de la clase AsposeOcr
+ Llamar al método AsposeOCR.RecognizeImage
+ Pase la ruta del archivo JP2 como parámetro
+ AsposeOCR.RecognizeImage devuelve una cadena o archivo de tipo TXT

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de ejecutar el ejemplo, asegúrese de que la API .NET compatible con la especificación NET Standard 2.0 esté instalada en su sistema y todas las [dependencias externas] (https://docs.aspose.com/ocr/net/system-requirements/#external- dependencias) del paquete Aspose.OCR se hace referencia en su proyecto.

{{% /blocks/products/pf/agp/text %}}

- Solución compatible con NET Standard 2.0+
- Aspose.OCR para .NET referenciado en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de ejemplo muestra la conversión de JP2 a TXT .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.JP2");
// print text
File. File.WriteAllText("document.TXT", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
JPEG 2000 (JP2) es un sistema de codificación de imágenes y un estándar de compresión de imágenes de última generación. Diseñado, utilizando la tecnología wavelet, JPEG 2000 puede codificar contenido sin pérdidas en cualquier calidad a la vez. Además, sin ninguna penalización sustancial en la eficiencia de la codificación, JPEG 2000 tiene la capacidad de acceder y decodificar el mismo contenido de manera eficaz en una variedad de otras resoluciones y calidades. Los flujos de código en JPEG 2000 son significativamente escalables y tienen regiones de interés que brindan la posibilidad de acceso espacial aleatorio. Posee hasta 16384 componentes diversos con las dimensiones en terapixels y una precisión que puede llegar a 38 bits/muestra.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/procesamiento-de-palabras/txt/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
Un archivo con extensión .TXT representa un documento de texto que contiene texto sin formato en forma de líneas. Los párrafos de un documento de texto se reconocen mediante retornos de carro y se utilizan para organizar mejor el contenido del archivo. Un documento de texto estándar se puede abrir en cualquier editor de texto o aplicación de procesamiento de texto en diferentes sistemas operativos. Todo el texto contenido en dicho archivo está en formato legible por humanos y representado por una secuencia de caracteres.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="Usando C#, uno puede convertir fácilmente diferentes formatos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-txt" name="TXT" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-text" name="Text" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-doc" name="DOC" description="Documentos generados por Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-docx" name="DOCX" description="Documentos de Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-xls" name="XLS" description="Formato de archivo binario de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-xlsx" name="XLSX" description="Documentos de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-pdf" name="PDF" description="Formato de documento portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-searchable_pdf" name="Searchable PDF" description="Gráficos de red portátiles con capacidad de búsqueda" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-xml" name="XML" description="Lenguaje de marcado extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jp2-to-json" name="JSON" description="Notación de objetos de JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
