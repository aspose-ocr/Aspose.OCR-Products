﻿---
title:  
weight: 3920
url: /id/java/conversion/pdf-to-text/ 
lang: id
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Contoh kode untuk PDF ke Text konversi Java. Gunakan kode contoh API untuk file batch PDF ke konversi Text dalam aplikasi berbasis Java Web atau Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="Text" pfName="Aspose.OCR" subTitlepfName="untuk Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="untuk Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/id/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/id/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Beranda API" codeSamplesText="Contoh kode" liveDemosText="Demo Langsung" downloadText="Unduh" learnText="Mempelajari">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
 memproses gambar pindaian atau bahkan foto ponsel cerdas dalam format PDF dan membuat dokumen PDF yang berisi teks yang dikenali. Untuk menambahkannya ke proyek Anda, Anda hanya perlu mendapatkan *Aspose.OCR*
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) atau tentukan konfigurasi Aspose Maven Repository
dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke _pom.xml_. Untuk contoh Graddle, Ivy, Sbt, lihat [repositori](https://repository.aspose.com/ocr/) kami.

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

Dengan Java OCR dan hanya beberapa baris kode, Anda dapat membuat aplikasi berfitur lengkap yang mengubah gambar PDF menjadi dokumen Text:

{{% /blocks/products/pf/agp/text %}}

+ Buat turunan dari kelas AsposeOcr
+ Panggil metode AsposeOCR.RecognizePage
+ Lewati jalur file PDF sebagai parameter
+ AsposeOCR.RecognizePage mengembalikan String atau file tipe Text

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

Sebelum menjalankan contoh, pastikan Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) atau yang lebih baru telah diinstal pada sistem Anda.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 atau lebih tinggi diinstal.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Apa" whatIsFormat2="Format Berkas" readMoreFormat="Baca selengkapnya">}}
Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan dari format file ini adalah untuk memperkenalkan standar representasi dokumen dan bahan referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Format file PDF memiliki kemampuan penuh untuk memuat informasi seperti teks, gambar, hyperlink, form-fields, media kaya, tanda tangan digital, lampiran, metadata, fitur Geospasial dan objek 3D di dalamnya yang dapat menjadi bagian dari dokumen sumber.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Text" readMoreLink="https://docs.fileformat.com/word-processing/txt/" whatIsFormat1="Apa" whatIsFormat2="Format Berkas" readMoreFormat="Baca selengkapnya">}}
File dengan ekstensi .TXT mewakili dokumen teks yang berisi teks biasa dalam bentuk garis. Paragraf dalam dokumen teks dikenali oleh carriage return dan digunakan untuk pengaturan konten file yang lebih baik. Dokumen teks standar dapat dibuka di editor teks atau aplikasi pengolah kata apa pun pada sistem operasi yang berbeda. Semua teks yang terkandung dalam file tersebut dalam format yang dapat dibaca manusia dan diwakili oleh urutan karakter.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-txt" name="TXT" description="File Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-text" name="Text" description="File Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-doc" name="DOC" description="Dokumen yang dihasilkan oleh Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-docx" name="DOCX" description="dokumen Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-xls" name="XLS" description="Format File Biner Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-xlsx" name="XLSX" description="dokumen Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-pdf" name="PDF" description="Format Dokumen Portabel (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-searchable_pdf" name="Searchable PDF" description="Grafik Jaringan Portabel yang Dapat Dicari" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-xml" name="XML" description="Bahasa Markup yang Dapat Diperluas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/pdf-to-json" name="JSON" description="Notasi Objek JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
