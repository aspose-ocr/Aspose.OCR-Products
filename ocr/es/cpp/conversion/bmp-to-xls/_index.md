﻿---
title:  
weight: 3920
url: /es/cpp/conversion/bmp-to-xls/ 
lang: es
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de muestra para la conversión de Java de BMP a XLS. Utilice el código de ejemplo de la API para la conversión por lotes de archivos BMP a XLS dentro de cualquier aplicación web o de escritorio basada en Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/es/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/es/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="Inicio de la API" codeSamplesText="Ejemplos de código" liveDemosText="demostraciones en vivo" downloadText="Descargar" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging para Java](https://products.aspose.com/imaging/java)
 procesa imágenes escaneadas o incluso fotos de teléfonos inteligentes en formato BMP y crea documentos BMP que contienen texto reconocido. Para agregarlo a su proyecto, solo necesita obtener *Aspose.OCR*
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

Con C++ OCR y solo unas pocas líneas de código, puede crear una aplicación con todas las funciones que convierte una imagen BMP en un documento XLS:

{{% /blocks/products/pf/agp/text %}}

+ Crear una instancia de la clase AsposeOcr
+ Llamar al método AsposeOCR.asposeocr_page()
+ Pase la ruta del archivo BMP como parámetro
+ AsposeOCR.asposeocr_page devuelve una cadena o archivo de tipo XLS

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
Los archivos que tienen la extensión .BMP representan archivos de imagen de mapa de bits que se utilizan para almacenar imágenes digitales de mapa de bits. Estas imágenes son independientes del adaptador de gráficos y también se denominan formato de archivo de mapa de bits independiente del dispositivo (DIB). Esta independencia sirve para abrir el archivo en múltiples plataformas, como Microsoft Windows y Mac. El formato de archivo BMP puede almacenar datos como imágenes digitales bidimensionales tanto en formato monocromático como en color con varias profundidades de color.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
Los archivos con extensión XLS representan el formato de archivo binario de Excel. Estos archivos pueden crearse con Microsoft Excel, así como con otros programas de hojas de cálculo similares, como OpenOffice Calc o Apple Numbers. El archivo guardado por Excel se conoce como Libro de trabajo, donde cada libro de trabajo puede tener una o más hojas de trabajo. Los datos se almacenan y muestran a los usuarios en formato de tabla en la hoja de trabajo y pueden abarcar valores numéricos, datos de texto, fórmulas, conexiones de datos externos, imágenes y gráficos. Las aplicaciones como Microsoft Excel le permiten exportar datos de libros de trabajo a varios formatos diferentes, incluidos PDF, CSV, XLSX, TXT, HTML, XPS y muchos otros. El formato de archivo XLS se reemplazó con un formato más abierto y estructurado, XLSX, con el lanzamiento de Microsoft Excel 2007. Las últimas versiones aún brindan soporte para crear y leer archivos XLS, aunque XLSX es la primera opción de uso ahora.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/cpp/conversion/bmp-to-txt" name="TXT" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/cpp/conversion/bmp-to-text" name="Text" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/cpp/conversion/bmp-to-doc" name="DOC" description="Documentos generados por Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/cpp/conversion/bmp-to-docx" name="DOCX" description="Documentos de Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/cpp/conversion/bmp-to-xls" name="XLS" description="Formato de archivo binario de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/cpp/conversion/bmp-to-xlsx" name="XLSX" description="Documentos de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/cpp/conversion/bmp-to-pdf" name="PDF" description="Formato de documento portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/cpp/conversion/bmp-to-searchable_pdf" name="Searchable PDF" description="Gráficos de red portátiles con capacidad de búsqueda" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
