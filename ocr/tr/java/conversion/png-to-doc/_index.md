﻿---
title:  
weight: 3920
url: /tr/java/conversion/png-to-doc/ 
lang: tr
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: PNG - DOC Java dönüşümü için örnek kod. Herhangi bir Web veya Masaüstü Java tabanlı uygulamada toplu PNG dosyalarını DOC'ye dönüştürmek için API örnek kodunu kullanın.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.OCR" subTitlepfName="Java için" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="Java için" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/tr/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/tr/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API Ana Sayfası" codeSamplesText="Kod örnekleri" liveDemosText="Canlı Demolar" downloadText="İndirmek" learnText="Öğrenmek">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
 taranan görüntüleri ve hatta akıllı telefon fotoğraflarını PNG biçiminde işler ve tanınan metin içeren PNG belgeleri oluşturur. Projenize eklemek için *Aspose.OCR* almanız yeterlidir.
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) veya Aspose Maven Repository yapılandırmasını belirtin
ve aşağıdaki konfigürasyonları _pom.xml_ dosyasına ekleyerek Maven tabanlı projenize kurun. Graddle, Ivy, Sbt örnekleri için [depomuza](https://repository.aspose.com/ocr/) göz atın.

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

Java OCR ve yalnızca birkaç satır kod ile, bir PNG görüntüsünü DOC belgesine dönüştüren tam özellikli bir uygulama oluşturabilirsiniz:

{{% /blocks/products/pf/agp/text %}}

+ AsposeOcr sınıfının bir örneğini oluşturun
+ AsposeOCR.RecognizePage yöntemini çağırın
+ PNG dosya yolunu parametre olarak iletin
+ AsposeOCR.RecognizePage, DOC türünde bir String veya dosya döndürür

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

Örneği çalıştırmadan önce, sisteminizde Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) veya sonraki sürümünün kurulu olduğundan emin olun.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 veya üstü yüklü.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Devamını oku">}}
PNG, Taşınabilir Ağ Grafikleri, kayıpsız sıkıştırma kullanan bir tür raster görüntü dosyası biçimini ifade eder. Bu dosya biçimi, Grafik Değişim Biçimi'nin (GIF) yerini almak üzere oluşturulmuştur ve herhangi bir telif hakkı sınırlaması yoktur. Ancak PNG dosya formatı animasyonları desteklemez. PNG dosya formatı, onu kullanıcıları arasında popüler kılan kayıpsız görüntü sıkıştırmayı destekler. Zaman geçtikçe PNG, en çok kullanılan resim dosyası formatlarından biri olarak gelişti. Hemen hemen tüm İşletim Sistemleri PNG dosyalarını açma desteğine sahiptir. Örneğin, işletim sisteminin varsayılan olarak kurulumun bir parçası olarak sunulan desteğe sahip olduğu gibi, Microsoft Windows görüntüleyici PNG dosyalarını açma özelliğine sahiptir.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOC" readMoreLink="https://docs.fileformat.com/word-processing/doc/" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Devamını oku">}}
.doc uzantılı dosyalar, Microsoft Word veya diğer kelime işlem belgeleri tarafından ikili dosya biçiminde oluşturulan belgeleri temsil eder. Uzantı başlangıçta birkaç farklı işletim sisteminde düz metin belgeleri için kullanıldı. Düz metin, grafikler, çizelgeler, gömülü nesneler, bağlantılar, sayfalar, sayfa biçimlendirme, yazdırma ayarları ve daha pek çok biçimin yanı sıra biçimlendirilmiş görüntüler gibi birkaç farklı veri türü içerebilir. Bu format, kullanıcılara kılavuzlar, teklifler, şartnameler, özgeçmişler, makaleler veya benzeri belgeler yazmak için sunduğu çeşitli seçenekler nedeniyle her türlü belge için popülerdi. DOC'nin güncellenmiş sürümü, özellikleri açık olan Office OpenXML tabanlı DOCX'tir.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-txt" name="TXT" description="Metin Belgesi Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-text" name="Text" description="Metin Belgesi Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-doc" name="DOC" description="Microsoft Word tarafından oluşturulan belgeler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-docx" name="DOCX" description="Microsoft Word belgeleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-xls" name="XLS" description="Microsoft Excel İkili Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-xlsx" name="XLSX" description="Microsoft Excel belgeleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-pdf" name="PDF" description="Taşınabilir Belge Formatı (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-searchable_pdf" name="Searchable PDF" description="Aranabilir Taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-xml" name="XML" description="Genişletilebilir İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/tr/java/conversion/png-to-json" name="JSON" description="JavaScript Nesnesi Gösterimi" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}