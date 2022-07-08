﻿---
title:  
weight: 3920
url: /es/java/conversion/tiff-to-docx/ 
lang: es
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de muestra para la conversión de Java de TIFF a DOCX. Utilice el código de ejemplo de la API para la conversión por lotes de archivos TIFF a DOCX dentro de cualquier aplicación web o de escritorio basada en Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOCX" pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/es/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-para-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/es/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Inicio de la API" codeSamplesText="Ejemplos de código" liveDemosText="demostraciones en vivo" downloadText="Descargar" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging para Java](https://products.aspose.com/imaging/java)
 procesa imágenes escaneadas o incluso fotos de teléfonos inteligentes en formato TIFF y crea documentos TIFF que contienen texto reconocido. Para agregarlo a su proyecto, solo necesita obtener *Aspose.OCR*
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) o especifique la configuración del Repositorio Aspose Maven
e instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones a _pom.xml_. Para ver ejemplos de Graddle, Ivy, Sbt, consulte nuestro [repositorio] (https://repository.aspose.com/ocr/).

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

Con Java OCR y solo unas pocas líneas de código, puede crear una aplicación con todas las funciones que convierte una imagen TIFF en un documento DOCX:

{{% /blocks/products/pf/agp/text %}}

+ Crear una instancia de la clase AsposeOcr
+ Llamar al método AsposeOCR.RecognizePage
+ Pase la ruta del archivo TIFF como parámetro
+ AsposeOCR.RecognizePage devuelve una cadena o archivo de tipo DOCX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de ejecutar el ejemplo, asegúrese de que Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) o posterior esté instalado en su sistema.

{{% /blocks/products/pf/agp/text %}}

- Está instalado JDK 1.6 o superior.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
TIFF o TIF, formato de archivo de imagen etiquetada, representa imágenes de trama diseñadas para su uso en una variedad de dispositivos que cumplen con este estándar de formato de archivo. Es capaz de describir datos de imágenes de dos niveles, escala de grises, colores de paleta y a todo color en varios espacios de color. Admite esquemas de compresión con pérdida y sin pérdida para elegir entre el espacio y el tiempo para las aplicaciones que utilizan el formato. El formato es extensible y ha sufrido varias revisiones que permiten la inclusión de una cantidad ilimitada de información privada o de propósito especial. El formato no depende de la máquina y está libre de límites como el procesador, el sistema operativo o los sistemas de archivos.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/procesamiento-de-palabras/docx/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
DOCX es un formato muy conocido para documentos de Microsoft Word. Introducido a partir de 2007 con el lanzamiento de Microsoft Office 2007, la estructura de este nuevo formato de documento se cambió de binario simple a una combinación de XML y archivos binarios. Los archivos Docx se pueden abrir con Word 2007 y versiones laterales, pero no con las versiones anteriores de MS Word que admiten extensiones de archivo DOC.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-txt" name="TXT" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-text" name="Text" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-doc" name="DOC" description="Documentos generados por Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-docx" name="DOCX" description="Documentos de Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-xls" name="XLS" description="Formato de archivo binario de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-xlsx" name="XLSX" description="Documentos de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-pdf" name="PDF" description="Formato de documento portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-searchable_pdf" name="Searchable PDF" description="Gráficos de red portátiles con capacidad de búsqueda" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-xml" name="XML" description="Lenguaje de marcado extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/tiff-to-json" name="JSON" description="Notación de objetos de JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}