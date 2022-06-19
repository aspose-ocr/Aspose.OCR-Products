---
title: Konversi BMP ke TXT melalui Java 
url: /id/java/conversion/bmp-to-txt/ 
description: Contoh kode konversi Java untuk format BMP ke file TXT. Gunakan kode contoh ini untuk mengonversi BMP ke TXT dalam aplikasi berbasis Java Web atau Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi BMP ke TXT melalui Java" h2="Membaca teks dari BMP menggunakan Optical Character Recognition." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="Aspose.OCR" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="BMP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.OCR " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-ocr" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/java" installationsDocsLink="https://docs.aspose.com/ocr/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-ocr" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi BMP ke TXT Menggunakan Java" %}}

Untuk merender BMP ke TXT, kami akan menggunakan
 [Aspose.OCR untuk Java](https://products.aspose.com/ocr/java)
 API yang merupakan API konversi yang kaya fitur, kuat, dan mudah digunakan untuk platform Java. Anda dapat mengunduh versi terbarunya langsung dari
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-ocr)
 dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke pom.xml.

{{% blocks/products/pf/agp/code-block title="Gudang" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ketergantungan" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-ocr</artifactId>
<version>version of aspose-ocr API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengkonversi BMP ke TXT melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Buat turunan dari kelas AsposeOcr
1. Panggil metode AsposeOCR.recognizeImage
1. Lewati jalur file BMP sebagai parameter
1. AsposeOCR.RecognizeLine mengembalikan String dengan teks yang dikenali
1. Konversikan String ke file TXT, jika diperlukan

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
- Dapatkan Aspose.OCR versi terbaru untuk Java langsung dari Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode Sumber Konversi Java BMP ke TXT" offSpacer="" %}}


```cs
// initialize an instance of AsposeOcr
AsposeOCR ocr = new AsposeOCR();
// recognize image
String riText = ocr.RecognizeLine("template.bmp");
// print text
System.out.print(riText);   

```



{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

   

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplikasi Gratis untuk Mengonversi BMP ke TXT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your BMP file, it will be converted instantly to TXT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

  
{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}