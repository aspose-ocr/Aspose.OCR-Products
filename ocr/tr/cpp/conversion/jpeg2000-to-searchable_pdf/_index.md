﻿---
title:  
weight: 3920
url: /tr/cpp/conversion/jpeg2000-to-searchable_pdf/ 
lang: tr
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: JPEG2000 - Searchable PDF Java dönüşümü için örnek kod. Herhangi bir Web veya Masaüstü Java tabanlı uygulamada toplu JPEG2000 dosyalarını Searchable PDF'ye dönüştürmek için API örnek kodunu kullanın.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="Searchable PDF" pfName="Aspose.OCR" subTitlepfName="C++ için" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="C++ için" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/tr/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/tr/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="API Ana Sayfası" codeSamplesText="Kod örnekleri" liveDemosText="Canlı Demolar" downloadText="İndirmek" learnText="Öğrenmek">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
 taranan görüntüleri ve hatta akıllı telefon fotoğraflarını JPEG2000 biçiminde işler ve tanınan metin içeren JPEG2000 belgeleri oluşturur. Projenize eklemek için *Aspose.OCR* almanız yeterlidir.
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) veya Aspose Maven Repository yapılandırmasını belirtin
ve aşağıdaki konfigürasyonları _pom.xml_ dosyasına ekleyerek Maven tabanlı projenize kurun. Graddle, Ivy, Sbt örnekleri için [depomuza](https://repository.aspose.com/ocr/) göz atın.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

C++ OCR ve yalnızca birkaç satır kodla, bir JPEG2000 görüntüsünü Searchable PDF belgesine dönüştüren tam özellikli bir uygulama oluşturabilirsiniz:

{{% /blocks/products/pf/agp/text %}}

+ AsposeOcr sınıfının bir örneğini oluşturun
+ AsposeOCR.asposeocr_page() yöntemini çağırın
+ JPEG2000 dosya yolunu parametre olarak iletin
+ AsposeOCR.asposeocr_page, Searchable PDF türünde bir String veya dosya döndürür

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

Örneği çalıştırmadan önce, projeye [Microsoft.ML.OnnxRuntime](https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/) 1.7.0 veya üzerinin eklendiğinden emin olun. Aspose.OCR'ı NuGet Paket Yöneticisi aracılığıyla kurarsanız, otomatik olarak kurulmalıdır.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ uyumlu çözüm
- Projenizde referans verilen Aspose.OCR for .NET.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG2000" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Devamını oku">}}
JPEG 2000 (JP2), bir görüntü kodlama sistemi ve son teknoloji görüntü sıkıştırma standardıdır. Dalgacık teknolojisi kullanılarak tasarlanan JPEG 2000, kayıpsız içeriği herhangi bir kalitede bir kerede kodlayabilir. Ayrıca, kodlama verimliliğinde önemli bir ceza olmaksızın, JPEG 2000, aynı içeriğe etkili bir şekilde çeşitli diğer çözünürlük ve niteliklere erişme ve kodunu çözme yeteneğine sahiptir. JPEG 2000'deki kod akışları, uzamsal rasgele erişim olanağı sağlayan ilgi bölgelerine sahip olarak önemli ölçüde ölçeklenebilir. Terapixels'deki boyutları ve 38 bit/numune kadar yüksek hassasiyete sahip 16384'e kadar farklı bileşene sahip olma.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Searchable PDF" readMoreLink="https://docs.fileformat.com/pdf/a/" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Devamını oku">}}
Aranabilir PDF dosyaları, orijinal taranmış görüntüyü ve ayrıca bir belge içinde tam metin aramaları veya kopyalama ve yapıştırma işlemleri için metni vurgulama için kullanılabilen gizli bir katmandaki OCR metnini korur.
Orijinal görüntüyü içermeyen PDF'ye tam OCR dönüştürme, özellikle belgede çok sayıda görüntü veya karmaşık bir düzen varsa, orijinal biçimlendirmenin %100'ünü asla korumaz.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/cpp/conversion/jpeg2000-to-txt" name="TXT" description="Metin Belgesi Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/cpp/conversion/jpeg2000-to-text" name="Text" description="Metin Belgesi Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/cpp/conversion/jpeg2000-to-doc" name="DOC" description="Microsoft Word tarafından oluşturulan belgeler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/cpp/conversion/jpeg2000-to-docx" name="DOCX" description="Microsoft Word belgeleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/cpp/conversion/jpeg2000-to-xls" name="XLS" description="Microsoft Excel İkili Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/cpp/conversion/jpeg2000-to-xlsx" name="XLSX" description="Microsoft Excel belgeleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/cpp/conversion/jpeg2000-to-pdf" name="PDF" description="Taşınabilir Belge Formatı (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/cpp/conversion/jpeg2000-to-searchable_pdf" name="Searchable PDF" description="Aranabilir Taşınabilir Ağ Grafikleri" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
