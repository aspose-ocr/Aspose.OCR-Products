﻿---
title:  
weight: 3920
url: /id/java/conversion/png-to-xml/ 
lang: id
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Contoh kode untuk PNG ke XML konversi Java. Gunakan kode contoh API untuk file batch PNG ke konversi XML dalam aplikasi berbasis Java Web atau Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="Aspose.OCR" subTitlepfName="untuk Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="untuk Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/id/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/id/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Beranda API" codeSamplesText="Contoh kode" liveDemosText="Demo Langsung" downloadText="Unduh" learnText="Mempelajari">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
 memproses gambar pindaian atau bahkan foto ponsel cerdas dalam format PNG dan membuat dokumen PNG yang berisi teks yang dikenali. Untuk menambahkannya ke proyek Anda, Anda hanya perlu mendapatkan *Aspose.OCR*
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

Dengan Java OCR dan hanya beberapa baris kode, Anda dapat membuat aplikasi berfitur lengkap yang mengubah gambar PNG menjadi dokumen XML:

{{% /blocks/products/pf/agp/text %}}

+ Buat turunan dari kelas AsposeOcr
+ Panggil metode AsposeOCR.RecognizePage
+ Lewati jalur file PNG sebagai parameter
+ AsposeOCR.RecognizePage mengembalikan String atau file tipe XML

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png" whatIsFormat1="Apa" whatIsFormat2="Format Berkas" readMoreFormat="Baca selengkapnya">}}
PNG, Portable Network Graphics, mengacu pada jenis format file gambar raster yang menggunakan kompresi tanpa kehilangan. Format file ini dibuat sebagai pengganti Graphics Interchange Format (GIF) dan tidak memiliki batasan hak cipta. Namun, format file PNG tidak mendukung animasi. Format file PNG mendukung kompresi gambar tanpa kehilangan yang membuatnya populer di kalangan penggunanya. Dengan berlalunya waktu, PNG telah berkembang sebagai salah satu format file gambar yang paling banyak digunakan. Hampir semua Sistem Operasi memiliki dukungan untuk membuka file PNG. Misalnya, penampil Microsoft Windows memiliki kemampuan untuk membuka file PNG karena OS secara default memiliki dukungan yang tersedia sebagai bagian dari instalasi.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" whatIsFormat1="Apa" whatIsFormat2="Format Berkas" readMoreFormat="Baca selengkapnya">}}
XML adalah singkatan dari Extensible Markup Language yang mirip dengan HTML tetapi berbeda dalam penggunaan tag untuk mendefinisikan objek. Seluruh ide di balik pembuatan format file XML adalah untuk menyimpan dan mengangkut data tanpa bergantung pada perangkat lunak atau perangkat keras. Popularitasnya adalah karena dapat dibaca manusia dan juga mesin. Ini memungkinkannya untuk membuat protokol data umum dalam bentuk objek untuk disimpan dan dibagikan melalui jaringan seperti World Wide Web (WWW). "X" dalam XML adalah untuk extensible yang menyiratkan bahwa bahasa tersebut dapat diperluas ke sejumlah simbol sesuai kebutuhan pengguna. Untuk fitur-fitur inilah banyak format file standar menggunakannya seperti Microsoft Open XML, LibreOffice OpenDocument, XHTML dan SVG.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-txt" name="TXT" description="File Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-text" name="Text" description="File Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-doc" name="DOC" description="Dokumen yang dihasilkan oleh Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-docx" name="DOCX" description="dokumen Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-xls" name="XLS" description="Format File Biner Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-xlsx" name="XLSX" description="dokumen Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-pdf" name="PDF" description="Format Dokumen Portabel (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-searchable_pdf" name="Searchable PDF" description="Grafik Jaringan Portabel yang Dapat Dicari" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-xml" name="XML" description="Bahasa Markup yang Dapat Diperluas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/java/conversion/png-to-json" name="JSON" description="Notasi Objek JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
