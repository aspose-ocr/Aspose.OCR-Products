﻿---
title: Convierta DJVU a Searchable PDF a través de C# 
weight: 3920
url: /es/net/conversion/djvu-to-searchable_pdf/ 
lang: es
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de muestra para la conversión de C# de DJVU a Searchable PDF. Utilice el código de ejemplo de API para la conversión por lotes de archivos DJVU a Searchable PDF dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convertir {Formato1} a {Formato2} en C#" h2="Realice el reconocimiento óptico de caracteres en el documento DJVU y guarde el texto como documento DJVU usando Aspose.OCR de la biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="Searchable PDF" pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/es/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/es/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Inicio de la API" codeSamplesText="Ejemplos de código" liveDemosText="demostraciones en vivo" downloadText="Descargar" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="Cómo convertir DJVU a Searchable PDF usando C#" %}}

Aspose.OCR para .NET es una biblioteca potente pero fácil de usar y rentable para convertir imágenes DJVU a documentos Searchable PDF. Compatible con 26 idiomas basados ​​en el latín, el cirílico y el chino, su motor de reconocimiento óptico de caracteres de última generación proporciona una velocidad y precisión de reconocimiento superiores, a la vez que lo aísla de fórmulas, redes neuronales y otros detalles técnicos complejos. Le permite agregar la funcionalidad OCR a sus aplicaciones .NET en menos de 10 líneas de código.

[Aspose.OCR para .NET](https://products.aspose.com/ocr/net)
 procesa imágenes escaneadas o incluso fotos de teléfonos inteligentes en formato DJVU y crea documentos DJVU que contienen texto reconocido. Para agregarlo a su proyecto, solo necesita instalar *Aspose.OCR*
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

Con .NET OCR y solo unas pocas líneas de código, puede crear una aplicación con todas las funciones que convierte una imagen DJVU en un documento Searchable PDF:

{{% /blocks/products/pf/agp/text %}}

+ Crear una instancia de la clase AsposeOcr
+ Llamar al método AsposeOCR.RecognizeImage
+ Pase la ruta del archivo DJVU como parámetro
+ AsposeOCR.RecognizeImage devuelve una cadena o archivo de tipo Searchable PDF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de ejecutar el ejemplo, asegúrese de que la API .NET compatible con la especificación NET Standard 2.0 esté instalada en su sistema y todas las [dependencias externas] (https://docs.aspose.com/ocr/net/system-requirements/#external- dependencias) del paquete Aspose.OCR se hace referencia en su proyecto.

{{% /blocks/products/pf/agp/text %}}

- Solución compatible con NET Standard 2.0+
- Aspose.OCR para .NET referenciado en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de ejemplo muestra la conversión de DJVU a Searchable PDF .NET" offSpacer="true" %}}

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
DjVu, pronunciado como "déjà vu", es un formato de archivo de gráficos destinado a documentos escaneados y libros, especialmente aquellos que contienen una combinación de texto, dibujos, imágenes y fotografías. Fue desarrollado por AT&T Labs. Utiliza múltiples técnicas como la separación de capas de imágenes de texto e imágenes de fondo, carga progresiva, codificación aritmética y compresión con pérdida para imágenes bitonales. Dado que el archivo DJVU puede contener imágenes en color, fotografías, texto y dibujos comprimidos pero de alta calidad y se puede guardar en menos espacio, por lo tanto, se usa en la web como libros electrónicos, manuales, periódicos, documentos antiguos, etc.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Searchable PDF" readMoreLink="https://docs.fileformat.com/pdf/a/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
Los archivos PDF que admiten búsquedas conservan la imagen escaneada original para su visualización, así como el texto OCR en una capa oculta que se puede utilizar para búsquedas de texto completo dentro de un documento o para resaltar texto para operaciones de copiar y pegar.
La conversión completa de OCR a PDF, sin incluir la imagen original, nunca conservará el 100 % del formato original, especialmente si el documento tiene muchas imágenes o un diseño complejo.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="Usando C#, uno puede convertir fácilmente diferentes formatos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-txt" name="TXT" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-text" name="Text" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-doc" name="DOC" description="Documentos generados por Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-docx" name="DOCX" description="Documentos de Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-xls" name="XLS" description="Formato de archivo binario de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-xlsx" name="XLSX" description="Documentos de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-pdf" name="PDF" description="Formato de documento portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-searchable_pdf" name="Searchable PDF" description="Gráficos de red portátiles con capacidad de búsqueda" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-xml" name="XML" description="Lenguaje de marcado extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/djvu-to-json" name="JSON" description="Notación de objetos de JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
