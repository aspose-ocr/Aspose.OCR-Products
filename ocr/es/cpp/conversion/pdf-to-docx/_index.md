﻿---
title:  
weight: 3920
url: /es/cpp/conversion/pdf-to-docx/ 
lang: es
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de muestra para la conversión de Java de PDF a DOCX. Utilice el código de ejemplo de la API para la conversión por lotes de archivos PDF a DOCX dentro de cualquier aplicación web o de escritorio basada en Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOCX" pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/es/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/es/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="Inicio de la API" codeSamplesText="Ejemplos de código" liveDemosText="demostraciones en vivo" downloadText="Descargar" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging para Java](https://products.aspose.com/imaging/java)
 procesa imágenes escaneadas o incluso fotos de teléfonos inteligentes en formato PDF y crea documentos PDF que contienen texto reconocido. Para agregarlo a su proyecto, solo necesita obtener *Aspose.OCR*
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) o especifique la configuración del Repositorio Aspose Maven
e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones a _pom.xml_. Para ver ejemplos de Graddle, Ivy, Sbt, consulte nuestro [repositorio] (https://repository.aspose.com/ocr/).

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

Con C++ OCR y solo unas pocas líneas de código, puede crear una aplicación con todas las funciones que convierte una imagen PDF en un documento DOCX:

{{% /blocks/products/pf/agp/text %}}

+ Crear una instancia de la clase AsposeOcr
+ Llamar al método AsposeOCR.asposeocr_page()
+ Pase la ruta del archivo PDF como parámetro
+ AsposeOCR.asposeocr_page devuelve una cadena o archivo de tipo DOCX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de ejecutar el ejemplo, asegúrese de que [Microsoft.ML.OnnxRuntime](https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/) 1.7.0 o superior se agregue al proyecto. Debería instalarse automáticamente si instala Aspose.OCR a través de NuGet Package Manager.

{{% /blocks/products/pf/agp/text %}}

- Solución compatible con NET Standard 2.0+
- Aspose.OCR para .NET referenciado en su proyecto.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
El formato de documento portátil (PDF) es un tipo de documento creado por Adobe en la década de 1990. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato que es independiente del software de la aplicación, el hardware y el sistema operativo. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, firmas digitales, archivos adjuntos, metadatos, características geoespaciales y objetos 3D que pueden convertirse en parte del documento de origen.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/procesamiento-de-palabras/docx/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
DOCX es un formato muy conocido para documentos de Microsoft Word. Introducido a partir de 2007 con el lanzamiento de Microsoft Office 2007, la estructura de este nuevo formato de documento se cambió de binario simple a una combinación de XML y archivos binarios. Los archivos Docx se pueden abrir con Word 2007 y versiones laterales, pero no con las versiones anteriores de MS Word que admiten extensiones de archivo DOC.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
