﻿---
title: Konversi BMP ke XML melalui C# 
weight: 3920
url: /id/net/conversion/bmp-to-xml/ 
lang: id
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Contoh kode untuk BMP ke XML C# konversi. Gunakan kode contoh API untuk file batch BMP ke konversi XML dalam VB.NET, Asp.NET atau aplikasi berbasis .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konversi BMP ke XML di C#" h2="Lakukan pengenalan karakter optik pada dokumen BMP dan simpan teks sebagai dokumen BMP menggunakan Aspose.OCR dari pustaka .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="Aspose.OCR" subTitlepfName="untuk .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="untuk .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/id/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/id/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Beranda API" codeSamplesText="Contoh kode" liveDemosText="Demo Langsung" downloadText="Unduh" learnText="Mempelajari">}}

{{% blocks/products/pf/agp/content h2="Cara mengonversi BMP ke XML menggunakan C#" %}}

Aspose.OCR untuk .NET adalah pustaka yang kuat namun mudah digunakan dan hemat biaya untuk mengonversi gambar BMP ke dokumen XML. Mendukung 26 bahasa berdasarkan bahasa Latin, Sirilik, dan Cina, mesin pengenalan karakter optik canggihnya memberikan kecepatan dan akurasi pengenalan yang unggul, sekaligus mengisolasi Anda dari rumus, jaringan saraf, dan detail teknis kompleks lainnya. Ini memungkinkan Anda untuk menambahkan fungsionalitas OCR ke aplikasi .NET Anda dalam waktu kurang dari 10 baris kode.

[Aspose.OCR untuk .NET](https://products.aspose.com/ocr/net)
 memproses gambar pindaian atau bahkan foto ponsel cerdas dalam format BMP dan membuat dokumen BMP yang berisi teks yang dikenali. Untuk menambahkannya ke proyek Anda, Anda hanya perlu menginstal *Aspose.OCR*
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 paket dalam proyek Anda dengan perintah berikut:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengonversi BMP ke XML" %}}

{{% blocks/products/pf/agp/text %}}

Dengan .NET OCR dan hanya beberapa baris kode, Anda dapat membuat aplikasi berfitur lengkap yang mengubah gambar BMP menjadi dokumen XML:

{{% /blocks/products/pf/agp/text %}}

+ Buat turunan dari kelas AsposeOcr
+ Panggil metode AsposeOCR.RecognizeImage
+ Lewati jalur file BMP sebagai parameter
+ AsposeOCR.RecognizeImage mengembalikan String atau file tipe XML

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

Sebelum menjalankan contoh, pastikan bahwa .NET API kompatibel dengan spesifikasi NET Standard 2.0 diinstal pada sistem Anda dan semua [dependensi eksternal](https://docs.aspose.com/ocr/net/system-requirements/#external- dependensi) dari paket Aspose.OCR direferensikan dalam proyek Anda.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ solusi yang kompatibel
- Aspose.OCR untuk .NET yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode contoh ini menunjukkan Konversi BMP ke XML .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.BMP");
// print text
File. File.WriteAllText("document.XML", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp" whatIsFormat1="Apa" whatIsFormat2="Format Berkas" readMoreFormat="Baca selengkapnya">}}
File yang berekstensi .BMP merupakan file Gambar Bitmap yang digunakan untuk menyimpan gambar digital bitmap. Gambar-gambar ini tidak tergantung pada adaptor grafis dan juga disebut format file bitmap independen perangkat (DIB). Independensi ini bertujuan untuk membuka file di berbagai platform seperti Microsoft Windows dan Mac. Format file BMP dapat menyimpan data sebagai gambar digital dua dimensi baik dalam format monokrom maupun warna dengan kedalaman warna yang bervariasi.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" whatIsFormat1="Apa" whatIsFormat2="Format Berkas" readMoreFormat="Baca selengkapnya">}}
XML adalah singkatan dari Extensible Markup Language yang mirip dengan HTML tetapi berbeda dalam penggunaan tag untuk mendefinisikan objek. Seluruh ide di balik pembuatan format file XML adalah untuk menyimpan dan mengangkut data tanpa bergantung pada perangkat lunak atau perangkat keras. Popularitasnya adalah karena dapat dibaca manusia dan juga mesin. Ini memungkinkannya untuk membuat protokol data umum dalam bentuk objek untuk disimpan dan dibagikan melalui jaringan seperti World Wide Web (WWW). "X" dalam XML adalah untuk extensible yang menyiratkan bahwa bahasa tersebut dapat diperluas ke sejumlah simbol sesuai kebutuhan pengguna. Untuk fitur-fitur inilah banyak format file standar menggunakannya seperti Microsoft Open XML, LibreOffice OpenDocument, XHTML dan SVG.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Menggunakan C#, seseorang dapat dengan mudah mengonversi berbagai format termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-txt" name="TXT" description="File Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-text" name="Text" description="File Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-doc" name="DOC" description="Dokumen yang dihasilkan oleh Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-docx" name="DOCX" description="dokumen Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-xls" name="XLS" description="Format File Biner Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-xlsx" name="XLSX" description="dokumen Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-pdf" name="PDF" description="Format Dokumen Portabel (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-searchable_pdf" name="Searchable PDF" description="Grafik Jaringan Portabel yang Dapat Dicari" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-xml" name="XML" description="Bahasa Markup yang Dapat Diperluas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/id/net/conversion/bmp-to-json" name="JSON" description="Notasi Objek JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
