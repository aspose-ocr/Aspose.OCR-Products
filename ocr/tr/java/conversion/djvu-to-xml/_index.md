﻿---
title:  
weight: 3920
url: /tr/java/conversion/djvu-to-xml/ 
lang: tr
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: DJVU - XML Java dönüşümü için örnek kod. Herhangi bir Web veya Masaüstü Java tabanlı uygulamada toplu DJVU dosyalarını XML'ye dönüştürmek için API örnek kodunu kullanın.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="Aspose.OCR" subTitlepfName="Java için" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="Java için" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/tr/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/tr/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API Ana Sayfası" codeSamplesText="Kod örnekleri" liveDemosText="Canlı Demolar" downloadText="İndirmek" learnText="Öğrenmek">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
 taranan görüntüleri ve hatta akıllı telefon fotoğraflarını DJVU biçiminde işler ve tanınan metin içeren DJVU belgeleri oluşturur. Projenize eklemek için *Aspose.OCR* almanız yeterlidir.
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

Java OCR ve yalnızca birkaç satır kod ile, bir DJVU görüntüsünü XML belgesine dönüştüren tam özellikli bir uygulama oluşturabilirsiniz:

{{% /blocks/products/pf/agp/text %}}

+ AsposeOcr sınıfının bir örneğini oluşturun
+ AsposeOCR.RecognizePage yöntemini çağırın
+ DJVU dosya yolunu parametre olarak iletin
+ AsposeOCR.RecognizePage, XML türünde bir String veya dosya döndürür

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Devamını oku">}}
DjVu, “déjà vu” olarak telaffuz edilir, özellikle metin, çizim, resim ve fotoğrafların birleşimini içeren taranmış belgeler ve kitaplar için tasarlanmış bir grafik dosya formatıdır. AT&T Labs tarafından geliştirilmiştir. Metin ve arka plan görüntülerinin görüntü katmanı ayrımı, aşamalı yükleme, aritmetik kodlama ve iki tonlu görüntüler için kayıplı sıkıştırma gibi birden çok teknik kullanır. DJVU dosyası sıkıştırılmış ancak yüksek kaliteli renkli görüntüler, fotoğraflar, metinler ve çizimler içerebildiğinden ve daha az alana kaydedilebildiğinden, web'de e-Kitaplar, kılavuzlar, gazeteler, eski belgeler vb. olarak kullanılır.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Devamını oku">}}
XML, HTML'ye benzer, ancak nesneleri tanımlamak için etiketlerin kullanımında farklı olan Genişletilebilir İşaretleme Dili anlamına gelir. XML dosya formatının yaratılmasının ardındaki tüm fikir, yazılım veya donanım araçlarına bağımlı olmadan verileri depolamak ve taşımaktı. Popülerliği, hem insan hem de makine tarafından okunabilmesinden kaynaklanmaktadır. Bu, World Wide Web (WWW) gibi ağ üzerinden depolanacak ve paylaşılacak nesneler biçiminde ortak veri protokolleri oluşturmasını sağlar. XML'deki "X" genişletilebilir içindir; bu, dilin kullanıcı gereksinimlerine göre herhangi bir sayıda simgeye genişletilebileceği anlamına gelir. Microsoft Open XML, LibreOffice OpenDocument, XHTML ve SVG gibi birçok standart dosya formatı bu özelliklerden yararlanır.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}