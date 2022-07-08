﻿---
title: Convierta WBMP a PDF a través de C# 
weight: 3920
url: /es/net/conversion/wbmp-to-pdf/ 
lang: es
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de muestra para la conversión de C# de WBMP a PDF. Utilice el código de ejemplo de API para la conversión por lotes de archivos WBMP a PDF dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convertir {Formato1} a {Formato2} en C#" h2="Realice el reconocimiento óptico de caracteres en el documento WBMP y guarde el texto como documento WBMP usando Aspose.OCR de la biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/es/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/es/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Inicio de la API" codeSamplesText="Ejemplos de código" liveDemosText="demostraciones en vivo" downloadText="Descargar" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="Cómo convertir WBMP a PDF usando C#" %}}

Aspose.OCR para .NET es una biblioteca potente pero fácil de usar y rentable para convertir imágenes WBMP a documentos PDF. Compatible con 26 idiomas basados ​​en el latín, el cirílico y el chino, su motor de reconocimiento óptico de caracteres de última generación proporciona una velocidad y precisión de reconocimiento superiores, a la vez que lo aísla de fórmulas, redes neuronales y otros detalles técnicos complejos. Le permite agregar la funcionalidad OCR a sus aplicaciones .NET en menos de 10 líneas de código.

[Aspose.OCR para .NET](https://products.aspose.com/ocr/net)
 procesa imágenes escaneadas o incluso fotos de teléfonos inteligentes en formato WBMP y crea documentos WBMP que contienen texto reconocido. Para agregarlo a su proyecto, solo necesita instalar *Aspose.OCR*
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

Con .NET OCR y solo unas pocas líneas de código, puede crear una aplicación con todas las funciones que convierte una imagen WBMP en un documento PDF:

{{% /blocks/products/pf/agp/text %}}

+ Crear una instancia de la clase AsposeOcr
+ Llamar al método AsposeOCR.RecognizeImage
+ Pase la ruta del archivo WBMP como parámetro
+ AsposeOCR.RecognizeImage devuelve una cadena o archivo de tipo PDF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de ejecutar el ejemplo, asegúrese de que la API .NET compatible con la especificación NET Standard 2.0 esté instalada en su sistema y todas las [dependencias externas] (https://docs.aspose.com/ocr/net/system-requirements/#external- dependencias) del paquete Aspose.OCR se hace referencia en su proyecto.

{{% /blocks/products/pf/agp/text %}}

- Solución compatible con NET Standard 2.0+
- Aspose.OCR para .NET referenciado en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de ejemplo muestra la conversión de WBMP a PDF .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.WBMP");
// print text
File. File.WriteAllText("document.PDF", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="WBMP" readMoreLink="https://docs.fileformat.com/image/wbmp" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
WBMP es un formato de archivo de gráficos monocromáticos optimizado para dispositivos informáticos móviles.
Las imágenes WBMP son monocromáticas (blanco y negro), por lo que el tamaño de la imagen se reduce al mínimo. Un píxel negro se denota por 0 y un píxel blanco se denota por 1.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
El formato de documento portátil (PDF) es un tipo de documento creado por Adobe en la década de 1990. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato que es independiente del software de la aplicación, el hardware y el sistema operativo. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, firmas digitales, archivos adjuntos, metadatos, características geoespaciales y objetos 3D que pueden convertirse en parte del documento de origen.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="Usando C#, uno puede convertir fácilmente diferentes formatos, incluidos." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}