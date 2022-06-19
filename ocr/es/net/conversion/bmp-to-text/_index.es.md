---
title: Convierta BMP a TEXTO a través de C# 
url: /es/net/conversion/bmp-to-text/ 
description: Código de muestra para la conversión de BMP a TEXTO C#. Utilice el código de ejemplo API para la conversión de archivos BMP por lotes a TEXTO dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta BMP a TEXTO a través de C#" h2="Convierta BMP a texto en cualquier aplicación basada en .NET mediante el reconocimiento óptico de caracteres." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TEXT" pfName="Aspose.OCR" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.OCR " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-ocr" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/aspose.ocr" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir BMP a TEXTO usando C#" %}}

Para convertir BMP a TEXTO, utilizaremos <a href=https://products.aspose.com/ocr/net>Aspose.OCR para .NET</a> API, que es una API rica en funciones, potente y API de manipulación y conversión de documentos fácil de usar para la plataforma C#. Abra el administrador de paquetes <a href=https://www.nuget.org/packages/aspose.ocr>NuGet</a>, busque <b>Aspose.OCR</b> e instálelo. También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title=" Comando de la consola del Administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir BMP a TEXTO a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Crea una instancia de la clase AsposeOcr
1. Llame al método AsposeOCR.RecognizeImage
1. Pase la ruta del archivo BMP como parámetro
1. AsposeOCR.RecognizeImage devuelve una cadena con texto reconocido
1. Convierta String a archivo TXT, si es necesario


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core y PHP, VBScript, Delphi, C++ a través de COM Interop.
- Entorno de desarrollo como Microsoft Visual Studio.
- Aspose.OCR para .NET DLL referenciado en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de ejemplo muestra la conversión de BMP a TEXTO C#" offSpacer="" %}}



```cs
// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.bmp");
// print text
Console.WriteLine(riText); 

```



{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para convertir BMP a TEXTO" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your BMP file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant TEXT file." >}}


{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/ocr/es/net/conversion/bmp-to-text" name="BMP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/ocr/es/net/conversion/gif-to-text" name="GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/ocr/es/net/conversion/jpg-to-text" name="JPG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/ocr/es/net/conversion/jpeg-to-txt" name="JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/ocr/es/net/conversion/png-to-text" name="PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/ocr/es/net/conversion/tiff-to-text" name="TIFF" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}