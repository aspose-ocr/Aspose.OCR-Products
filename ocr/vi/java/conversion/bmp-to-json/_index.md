﻿---
title:  
weight: 3920
url: /vi/java/conversion/bmp-to-json/ 
lang: vi
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Mã mẫu cho chuyển đổi Java từ BMP sang JSON. Sử dụng mã mẫu API cho hàng loạt tệp BMP thành chuyển đổi JSON trong bất kỳ ứng dụng dựa trên Web hoặc Máy tính Java nào.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="Aspose.OCR" subTitlepfName="cho Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="cho Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/vi/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/vi/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Trang chủ API" codeSamplesText="Mẫu mã" liveDemosText="Bản trình diễn trực tiếp" downloadText="Tải xuống" learnText="Học">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging cho Java] (https://products.aspose.com/imaging/java)
 xử lý hình ảnh được quét hoặc thậm chí ảnh điện thoại thông minh ở định dạng BMP và tạo tài liệu BMP chứa văn bản được nhận dạng. Để thêm nó vào dự án của bạn, bạn chỉ cần lấy * Aspose.OCR *
[Maven] (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) hoặc chỉ định cấu hình kho lưu trữ Aspose Maven
và cài đặt nó trong dự án dựa trên Maven của bạn bằng cách thêm các cấu hình sau vào _pom.xml_. Đối với các ví dụ về Graddle, Ivy, Sbt, hãy xem [kho lưu trữ] của chúng tôi (https://repository.aspose.com/ocr/).

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

Với Java OCR và chỉ một vài dòng mã, bạn có thể tạo ứng dụng đầy đủ tính năng để chuyển đổi hình ảnh BMP thành tài liệu JSON:

{{% /blocks/products/pf/agp/text %}}

+ Tạo một thể hiện của lớp AsposeOcr
+ Gọi phương thức AsposeOCR.RecognizePage
+ Chuyển đường dẫn tệp BMP làm tham số
+ AsposeOCR.RecognizePage trả về một Chuỗi hoặc tệp thuộc loại JSON

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

Trước khi chạy ví dụ này, hãy đảm bảo rằng Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) trở lên được cài đặt trên hệ thống của bạn.

{{% /blocks/products/pf/agp/text %}}

- Đã cài đặt JDK 1.6 trở lên.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp" whatIsFormat1="Là gì" whatIsFormat2="Định dạng tệp" readMoreFormat="Đọc thêm">}}
Các tệp có phần mở rộng .BMP đại diện cho các tệp Hình ảnh Bitmap được sử dụng để lưu trữ hình ảnh kỹ thuật số bitmap. Những hình ảnh này độc lập với bộ điều hợp đồ họa và còn được gọi là định dạng tệp bitmap (DIB) độc lập với thiết bị. Tính độc lập này phục vụ mục đích mở tệp trên nhiều nền tảng như Microsoft Windows và Mac. Định dạng tệp BMP có thể lưu trữ dữ liệu dưới dạng hình ảnh kỹ thuật số hai chiều ở cả định dạng đơn sắc và màu với nhiều độ sâu màu khác nhau.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" whatIsFormat1="Là gì" whatIsFormat2="Định dạng tệp" readMoreFormat="Đọc thêm">}}
JSON (JavaScript Object Notation) là một định dạng tệp tiêu chuẩn mở để chia sẻ dữ liệu sử dụng văn bản có thể đọc được của con người để lưu trữ và truyền dữ liệu. Các tệp JSON được lưu trữ với phần mở rộng .json. JSON yêu cầu ít định dạng hơn và là một giải pháp thay thế tốt cho XML. JSON có nguồn gốc từ JavaScript nhưng là một định dạng dữ liệu độc lập với ngôn ngữ. Việc tạo và phân tích cú pháp JSON được hỗ trợ bởi nhiều ngôn ngữ lập trình hiện đại. application / json là loại phương tiện được sử dụng cho JSON.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-txt" name="TXT" description="Tệp tài liệu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-text" name="Text" description="Tệp tài liệu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-doc" name="DOC" description="Tài liệu được tạo bởi Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-docx" name="DOCX" description="Tài liệu Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-xls" name="XLS" description="Định dạng tệp nhị phân Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-xlsx" name="XLSX" description="Tài liệu Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-pdf" name="PDF" description="Định dạng tài liệu di động (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-searchable_pdf" name="Searchable PDF" description="Đồ họa mạng di động có thể tìm kiếm" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-xml" name="XML" description="Ngôn ngữ đánh dấu có thể mở rộng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/java/conversion/bmp-to-json" name="JSON" description="Ký hiệu đối tượng JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}