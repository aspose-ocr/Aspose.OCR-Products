﻿---
title: C# aracılığıyla JPEG öğesini Searchable PDF biçimine dönüştürün 
weight: 3920
url: /tr/net/conversion/jpeg-to-searchable_pdf/ 
lang: tr
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: JPEG - Searchable PDF C# dönüşümü için örnek kod. VB.NET, Asp.NET veya herhangi bir .NET tabanlı uygulama içinde toplu JPEG dosyalarını Searchable PDF'ye dönüştürmek için API örnek kodunu kullanın.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# içinde JPEG öğesini Searchable PDF biçimine dönüştürün" h2="JPEG belgesi üzerinde optik karakter tanıma gerçekleştirin ve Aspose.OCR'yi .NET kitaplığı için JPEG belgesi olarak kaydedin." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="Searchable PDF" pfName="Aspose.OCR" subTitlepfName=".NET için" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName=".NET için" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/tr/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/tr/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API Ana Sayfası" codeSamplesText="Kod örnekleri" liveDemosText="Canlı Demolar" downloadText="İndirmek" learnText="Öğrenmek">}}

{{% blocks/products/pf/agp/content h2="C# kullanılarak JPEG Searchable PDF biçimine nasıl dönüştürülür" %}}

Aspose.OCR for .NET, JPEG görüntüleri Searchable PDF belgelerine dönüştürmek için güçlü ancak kullanımı kolay ve uygun maliyetli bir kitaplıktır. Latince, Kiril ve Çince'ye dayalı 26 dili destekleyen son teknoloji optik karakter tanıma motoru, sizi formüllerden, sinir ağlarından ve diğer karmaşık teknik ayrıntılardan izole ederken üstün tanıma hızı ve doğruluğu sağlar. 10 satırdan daha kısa bir sürede .NET uygulamalarınıza OCR işlevi eklemenize olanak tanır.

[.NET için Aspose.OCR](https://products.aspose.com/ocr/net)
 taranan görüntüleri ve hatta akıllı telefon fotoğraflarını JPEG biçiminde işler ve tanınan metin içeren JPEG belgeleri oluşturur. Projenize eklemek için *Aspose.OCR* dosyasını yüklemeniz yeterlidir.
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 projenizde aşağıdaki komutla paketleyin:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="JPEG'i Searchable PDF'e Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

.NET OCR ve yalnızca birkaç satır kod ile, bir JPEG görüntüsünü Searchable PDF belgesine dönüştüren tam özellikli bir uygulama oluşturabilirsiniz:

{{% /blocks/products/pf/agp/text %}}

+ AsposeOcr sınıfının bir örneğini oluşturun
+ AsposeOCR.RecognizeImage yöntemini çağırın
+ JPEG dosya yolunu parametre olarak iletin
+ AsposeOCR.RecognizeImage, Searchable PDF türünde bir String veya dosya döndürür

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

Örneği çalıştırmadan önce, sisteminizde NET Standard 2.0 spesifikasyonu ile uyumlu .NET API'nin ve tüm [harici bağımlılıkların] kurulu olduğundan emin olun(https://docs.aspose.com/ocr/net/system-requirements/#external- Aspose.OCR paketinin bağımlılıkları) projenizde referans alınır.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ uyumlu çözüm
- Projenizde referans verilen Aspose.OCR for .NET.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, JPEG - Searchable PDF .NET Dönüşümünü gösterir" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.JPEG");
// print text
File. File.WriteAllText("document.Searchable PDF", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Devamını oku">}}
JPEG, kayıplı sıkıştırma yöntemi kullanılarak kaydedilen bir görüntü formatı türüdür. Sıkıştırmanın bir sonucu olarak çıktı görüntüsü, depolama boyutu ve görüntü kalitesi arasında bir dengedir. Kullanıcılar, istenen kalite seviyesine ulaşmak için sıkıştırma seviyesini ayarlayabilir ve aynı zamanda depolama boyutunu küçültebilir. Görüntüye 10:1 sıkıştırma uygulanırsa görüntü kalitesi ihmal edilebilir düzeyde etkilenir. Sıkıştırma değeri ne kadar yüksek olursa, görüntü kalitesindeki bozulma o kadar yüksek olur.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Searchable PDF" readMoreLink="https://docs.fileformat.com/pdf/a/" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Devamını oku">}}
Aranabilir PDF dosyaları, orijinal taranmış görüntüyü ve ayrıca bir belge içinde tam metin aramaları veya kopyalama ve yapıştırma işlemleri için metni vurgulama için kullanılabilen gizli bir katmandaki OCR metnini korur.
Orijinal görüntüyü içermeyen PDF'ye tam OCR dönüştürme, özellikle belgede çok sayıda görüntü veya karmaşık bir düzen varsa, orijinal biçimlendirmenin %100'ünü asla korumaz.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="C# kullanarak, dahil olmak üzere farklı formatları kolayca dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-txt" name="TXT" description="Metin Belgesi Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-text" name="Text" description="Metin Belgesi Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-doc" name="DOC" description="Microsoft Word tarafından oluşturulan belgeler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-docx" name="DOCX" description="Microsoft Word belgeleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-xls" name="XLS" description="Microsoft Excel İkili Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-xlsx" name="XLSX" description="Microsoft Excel belgeleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-pdf" name="PDF" description="Taşınabilir Belge Formatı (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-searchable_pdf" name="Searchable PDF" description="Aranabilir Taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-xml" name="XML" description="Genişletilebilir İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/net/conversion/jpeg-to-json" name="JSON" description="JavaScript Nesnesi Gösterimi" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
