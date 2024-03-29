﻿---
title:  
weight: 3920
url: /vi/cpp/conversion/bmp-to-txt/ 
lang: vi
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Mã mẫu cho chuyển đổi Java từ BMP sang TXT. Sử dụng mã mẫu API cho hàng loạt tệp BMP thành chuyển đổi TXT trong bất kỳ ứng dụng dựa trên Web hoặc Máy tính Java nào.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="Aspose.OCR" subTitlepfName="cho C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="cho C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/vi/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/vi/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="Trang chủ API" codeSamplesText="Mẫu mã" liveDemosText="Bản trình diễn trực tiếp" downloadText="Tải xuống" learnText="Học">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging cho Java] (https://products.aspose.com/imaging/java)
 xử lý hình ảnh được quét hoặc thậm chí ảnh điện thoại thông minh ở định dạng BMP và tạo tài liệu BMP chứa văn bản được nhận dạng. Để thêm nó vào dự án của bạn, bạn chỉ cần lấy * Aspose.OCR *
[Aspose Maven Repository] (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) hoặc chỉ định cấu hình kho lưu trữ Aspose Maven
và cài đặt nó trong dự án dựa trên Maven của bạn bằng cách thêm các cấu hình sau vào _pom.xml_. Đối với các ví dụ về Graddle, Ivy, Sbt, hãy xem [kho lưu trữ] của chúng tôi (https://repository.aspose.com/ocr/).

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

Với C ++ OCR và chỉ một vài dòng mã, bạn có thể tạo ứng dụng đầy đủ tính năng để chuyển đổi hình ảnh BMP thành tài liệu TXT:

{{% /blocks/products/pf/agp/text %}}

+ Tạo một thể hiện của lớp AsposeOcr
+ Gọi phương thức AsposeOCR.asposeocr_page ()
+ Chuyển đường dẫn tệp BMP làm tham số
+ AsposeOCR.asposeocr_page trả về một Chuỗi hoặc tệp thuộc loại TXT

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

Trước khi chạy ví dụ, hãy đảm bảo rằng [Microsoft.ML.OnnxRuntime] (https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/) 1.7.0 trở lên được thêm vào dự án. Nó sẽ được tự động cài đặt nếu bạn cài đặt Aspose.OCR qua NuGet Package Manager.

{{% /blocks/products/pf/agp/text %}}

- Giải pháp tương thích NET Standard 2.0+
- Aspose.OCR cho .NET được tham chiếu trong dự án của bạn.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp" whatIsFormat1="Là gì" whatIsFormat2="Định dạng tệp" readMoreFormat="Đọc thêm">}}
Các tệp có phần mở rộng .BMP đại diện cho các tệp Hình ảnh Bitmap được sử dụng để lưu trữ hình ảnh kỹ thuật số bitmap. Những hình ảnh này độc lập với bộ điều hợp đồ họa và còn được gọi là định dạng tệp bitmap (DIB) độc lập với thiết bị. Tính độc lập này phục vụ mục đích mở tệp trên nhiều nền tảng như Microsoft Windows và Mac. Định dạng tệp BMP có thể lưu trữ dữ liệu dưới dạng hình ảnh kỹ thuật số hai chiều ở cả định dạng đơn sắc và màu với nhiều độ sâu màu khác nhau.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" whatIsFormat1="Là gì" whatIsFormat2="Định dạng tệp" readMoreFormat="Đọc thêm">}}
Tệp có phần mở rộng .TXT đại diện cho một tài liệu văn bản có chứa văn bản thuần túy ở dạng dòng. Các đoạn trong tài liệu văn bản được nhận dạng bằng ký tự xuống dòng và được sử dụng để sắp xếp nội dung tệp tốt hơn. Một tài liệu văn bản tiêu chuẩn có thể được mở trong bất kỳ trình soạn thảo văn bản hoặc ứng dụng xử lý văn bản nào trên các hệ điều hành khác nhau. Tất cả văn bản trong một tệp như vậy đều ở định dạng con người có thể đọc được và được biểu thị bằng chuỗi ký tự.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/cpp/conversion/bmp-to-txt" name="TXT" description="Tệp tài liệu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/cpp/conversion/bmp-to-text" name="Text" description="Tệp tài liệu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/cpp/conversion/bmp-to-doc" name="DOC" description="Tài liệu được tạo bởi Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/cpp/conversion/bmp-to-docx" name="DOCX" description="Tài liệu Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/cpp/conversion/bmp-to-xls" name="XLS" description="Định dạng tệp nhị phân Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/cpp/conversion/bmp-to-xlsx" name="XLSX" description="Tài liệu Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/cpp/conversion/bmp-to-pdf" name="PDF" description="Định dạng tài liệu di động (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/vi/cpp/conversion/bmp-to-searchable_pdf" name="Searchable PDF" description="Đồ họa mạng di động có thể tìm kiếm" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
