﻿---
title:  
weight: 3920
url: /es/java/conversion/jpeg2000-to-doc/ 
lang: es
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Código de muestra para la conversión de Java de JPEG2000 a DOC. Utilice el código de ejemplo de la API para la conversión por lotes de archivos JPEG2000 a DOC dentro de cualquier aplicación web o de escritorio basada en Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="para {plataforma de idioma}" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/es/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-para-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/es/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Inicio de la API" codeSamplesText="Ejemplos de código" liveDemosText="demostraciones en vivo" downloadText="Descargar" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging para Java](https://products.aspose.com/imaging/java)
 procesa imágenes escaneadas o incluso fotos de teléfonos inteligentes en formato JPEG2000 y crea documentos JPEG2000 que contienen texto reconocido. Para agregarlo a su proyecto, solo necesita obtener *Aspose.OCR*
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

Con Java OCR y solo unas pocas líneas de código, puede crear una aplicación con todas las funciones que convierte una imagen JPEG2000 en un documento DOC:

{{% /blocks/products/pf/agp/text %}}

+ Crear una instancia de la clase AsposeOcr
+ Llamar al método AsposeOCR.RecognizePage
+ Pase la ruta del archivo JPEG2000 como parámetro
+ AsposeOCR.RecognizePage devuelve una cadena o archivo de tipo DOC

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG2000" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
JPEG 2000 (JP2) es un sistema de codificación de imágenes y un estándar de compresión de imágenes de última generación. Diseñado, utilizando la tecnología wavelet, JPEG 2000 puede codificar contenido sin pérdidas en cualquier calidad a la vez. Además, sin ninguna penalización sustancial en la eficiencia de la codificación, JPEG 2000 tiene la capacidad de acceder y decodificar el mismo contenido de manera eficaz en una variedad de otras resoluciones y calidades. Los flujos de código en JPEG 2000 son significativamente escalables y tienen regiones de interés que brindan la posibilidad de acceso espacial aleatorio. Posee hasta 16384 componentes diversos con las dimensiones en terapixels y una precisión que puede llegar a 38 bits/muestra.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOC" readMoreLink="https://docs.fileformat.com/word-processing/doc/" whatIsFormat1="Que es" whatIsFormat2="Formato de archivo" readMoreFormat="Lee mas">}}
Los archivos con extensión .doc representan documentos generados por Microsoft Word u otros documentos de procesamiento de texto en formato de archivo binario. La extensión se usó inicialmente para la documentación de texto sin formato en varios sistemas operativos diferentes. Puede contener varios tipos diferentes de datos, como imágenes, texto formateado y sin formato, gráficos, tablas, objetos incrustados, enlaces, páginas, formato de página, configuraciones de impresión y muchos otros. El formato fue popular para todo tipo de documentación debido a la variedad de opciones que ofrece a los usuarios para escribir manuales, propuestas, especificaciones, currículos, artículos o cualquier documento similar. La versión actualizada de DOC es DOCX, que se basa en Office OpenXML cuyas especificaciones están disponibles abiertamente.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-txt" name="TXT" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-text" name="Text" description="Archivo de documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-doc" name="DOC" description="Documentos generados por Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-docx" name="DOCX" description="Documentos de Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-xls" name="XLS" description="Formato de archivo binario de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-xlsx" name="XLSX" description="Documentos de Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-pdf" name="PDF" description="Formato de documento portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-searchable_pdf" name="Searchable PDF" description="Gráficos de red portátiles con capacidad de búsqueda" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-xml" name="XML" description="Lenguaje de marcado extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/es/java/conversion/jpeg2000-to-json" name="JSON" description="Notación de objetos de JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}