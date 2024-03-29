﻿---
title:  
weight: 3920
url: /vi/cpp/conversion/djvu-to-pdf/ 
lang: vi
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Mã mẫu cho chuyển đổi Java từ DJVU sang PDF. Sử dụng mã mẫu API cho hàng loạt tệp DJVU thành chuyển đổi PDF trong bất kỳ ứng dụng dựa trên Web hoặc Máy tính Java nào.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.OCR" subTitlepfName="cho C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="cho C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/vi/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/vi/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="Trang chủ API" codeSamplesText="Mẫu mã" liveDemosText="Bản trình diễn trực tiếp" downloadText="Tải xuống" learnText="Học">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging cho Java] (https://products.aspose.com/imaging/java)
 xử lý hình ảnh được quét hoặc thậm chí ảnh điện thoại thông minh ở định dạng DJVU và tạo tài liệu DJVU chứa văn bản được nhận dạng. Để thêm nó vào dự án của bạn, bạn chỉ cần lấy * Aspose.OCR *
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

Với C ++ OCR và chỉ một vài dòng mã, bạn có thể tạo ứng dụng đầy đủ tính năng để chuyển đổi hình ảnh DJVU thành tài liệu PDF:

{{% /blocks/products/pf/agp/text %}}

+ Tạo một thể hiện của lớp AsposeOcr
+ Gọi phương thức AsposeOCR.asposeocr_page ()
+ Chuyển đường dẫn tệp DJVU làm tham số
+ AsposeOCR.asposeocr_page trả về một Chuỗi hoặc tệp thuộc loại PDF

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu" whatIsFormat1="Là gì" whatIsFormat2="Định dạng tệp" readMoreFormat="Đọc thêm">}}
DjVu, được phát âm là “déjà vu”, là một định dạng tệp đồ họa dành cho các tài liệu và sách được quét, đặc biệt là những tài liệu có chứa sự kết hợp của văn bản, bản vẽ, hình ảnh và ảnh chụp. Nó được phát triển bởi AT&T Labs. Nó sử dụng nhiều kỹ thuật như tách lớp hình ảnh của văn bản và hình ảnh nền, tải liên tục, mã hóa số học và nén mất dữ liệu cho hình ảnh bitonal. Vì tệp DJVU có thể chứa hình ảnh, ảnh, văn bản và bản vẽ màu được nén nhưng chất lượng cao và có thể được lưu trong ít dung lượng hơn, do đó, nó được sử dụng trên web dưới dạng sách điện tử, sách hướng dẫn, báo chí, tài liệu cổ, v.v.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Là gì" whatIsFormat2="Định dạng tệp" readMoreFormat="Đọc thêm">}}
Định dạng tài liệu di động (PDF) là một loại tài liệu được tạo bởi Adobe vào những năm 1990. Mục đích của định dạng tệp này là giới thiệu một tiêu chuẩn để trình bày tài liệu và tài liệu tham khảo khác ở định dạng độc lập với phần mềm ứng dụng, phần cứng cũng như Hệ điều hành. Định dạng tệp PDF có đầy đủ khả năng chứa thông tin như văn bản, hình ảnh, siêu liên kết, trường biểu mẫu, đa phương tiện, chữ ký số, tệp đính kèm, siêu dữ liệu, các tính năng không gian địa lý và các đối tượng 3D trong đó có thể trở thành một phần của tài liệu nguồn.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
