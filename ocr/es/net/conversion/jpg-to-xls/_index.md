﻿---
title: Convierta JPG a XLS a través de C# 
weight: 3920
url: /es/net/conversion/jpg-to-xls/ 
lang: es
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de muestra para la conversión de C# de JPG a XLS. Utilice el código de ejemplo de API para la conversión por lotes de archivos JPG a XLS dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convertir {Formato1} a {Formato2} en C#" h2="Realice el reconocimiento óptico de caracteres en el documento JPG y guarde el texto como documento JPG usando Aspose.OCR de la biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/es/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/es/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Inicio de la API" codeSamplesText="Ejemplos de código" liveDemosText="demostraciones en vivo" downloadText="Descargar" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="Cómo convertir JPG a XLS usando C#" %}}

Aspose.OCR para .NET es una biblioteca potente pero fácil de usar y rentable para convertir imágenes JPG a documentos XLS. Compatible con 26 idiomas basados ​​en el latín, el cirílico y el chino, su motor de reconocimiento óptico de caracteres de última generación proporciona una velocidad y precisión de reconocimiento superiores, a la vez que lo aísla de fórmulas, redes neuronales y otros detalles técnicos complejos. Le permite agregar la funcionalidad OCR a sus aplicaciones .NET en menos de 10 líneas de código.

[Aspose.OCR para .NET](https://products.aspose.com/ocr/net)
 procesa imágenes escaneadas o incluso fotos de teléfonos inteligentes en formato JPG y crea documentos JPG que contienen texto reconocido. Para agregarlo a su proyecto, solo necesita instalar *Aspose.OCR*
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

Con .NET OCR y solo unas pocas líneas de código, puede crear una aplicación con todas las funciones que convierte una imagen JPG en un documento XLS:

{{% /blocks/products/pf/agp/text %}}

+ Crear una instancia de la clase AsposeOcr
+ Llamar al método AsposeOCR.RecognizeImage
+ Pase la ruta del archivo JPG como parámetro
+ AsposeOCR.RecognizeImage devuelve una cadena o archivo de tipo XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de ejecutar el ejemplo, asegúrese de que la API .NET compatible con la especificación NET Standard 2.0 esté instalada en su sistema y todas las [dependencias externas] (https://docs.aspose.com/ocr/net/system-requirements/#external- dependencias) del paquete Aspose.OCR se hace referencia en su proyecto.

{{% /blocks/products/pf/agp/text %}}

- Solución compatible con NET Standard 2.0+
- Aspose.OCR para .NET referenciado en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de ejemplo muestra la conversión de JPG a XLS .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.JPG");
// print text
File. File.WriteAllText("document.XLS", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPG" readMoreLink="https://docs.fileformat.com/image/jpg" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
Un JPEG es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. La imagen de salida, como resultado de la compresión, es un equilibrio entre el tamaño de almacenamiento y la calidad de la imagen. Los usuarios pueden ajustar el nivel de compresión para lograr el nivel de calidad deseado y, al mismo tiempo, reducir el tamaño de almacenamiento. La calidad de la imagen se ve afectada de manera insignificante si se aplica una compresión de 10:1 a la imagen. Cuanto mayor sea el valor de compresión, mayor será la degradación de la calidad de la imagen.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
Los archivos con extensión XLS representan el formato de archivo binario de Excel. Estos archivos pueden crearse con Microsoft Excel, así como con otros programas de hojas de cálculo similares, como OpenOffice Calc o Apple Numbers. El archivo guardado por Excel se conoce como Libro de trabajo, donde cada libro de trabajo puede tener una o más hojas de trabajo. Los datos se almacenan y muestran a los usuarios en formato de tabla en la hoja de trabajo y pueden abarcar valores numéricos, datos de texto, fórmulas, conexiones de datos externos, imágenes y gráficos. Las aplicaciones como Microsoft Excel le permiten exportar datos de libros de trabajo a varios formatos diferentes, incluidos PDF, CSV, XLSX, TXT, HTML, XPS y muchos otros. El formato de archivo XLS se reemplazó con un formato más abierto y estructurado, XLSX, con el lanzamiento de Microsoft Excel 2007. Las últimas versiones aún brindan soporte para crear y leer archivos XLS, aunque XLSX es la primera opción de uso ahora.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="Usando C#, uno puede convertir fácilmente diferentes formatos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-txt" name="TXT" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-text" name="Text" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-doc" name="DOC" description="Documentos generados por Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-docx" name="DOCX" description="Documentos de Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-xls" name="XLS" description="Formato de archivo binario de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-xlsx" name="XLSX" description="Documentos de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-pdf" name="PDF" description="Formato de documento portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-searchable_pdf" name="Searchable PDF" description="Gráficos de red portátiles con capacidad de búsqueda" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-xml" name="XML" description="Lenguaje de marcado extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/net/conversion/jpg-to-json" name="JSON" description="Notación de objetos de JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
