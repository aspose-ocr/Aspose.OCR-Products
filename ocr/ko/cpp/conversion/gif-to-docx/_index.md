﻿---
title:  
weight: 3920
url: /ko/cpp/conversion/gif-to-docx/ 
lang: ko
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: GIF에서 DOCX로의 Java 변환을 위한 샘플 코드입니다. 웹 또는 데스크톱 자바 기반 애플리케이션 내에서 일괄 GIF 파일을 DOCX로 변환하는 API 예제 코드를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOCX" pfName="Aspose.OCR" subTitlepfName="C++용" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="C++용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/ko/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/ko/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="API 홈" codeSamplesText="코드 샘플" liveDemosText="라이브 데모" downloadText="다운로드" learnText="배우다">}}

{{% blocks/products/pf/agp/content h2="" %}}



[자바용 Aspose.Imaging](https://products.aspose.com/imaging/java)
 스캔한 이미지나 스마트폰 사진까지 GIF 형식으로 처리하고 인식된 텍스트가 포함된 GIF 문서를 만듭니다. 프로젝트에 추가하려면 *Aspose.OCR*만 있으면 됩니다.
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) 또는 Aspose Maven Repository 구성 지정
다음 구성을 _pom.xml_에 추가하여 Maven 기반 프로젝트 내에 설치합니다. Gradle, Ivy, Sbt 예제는 [repository](https://repository.aspose.com/ocr/)에서 확인하세요.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="" %}}

{{% blocks/products/pf/agp/text %}}

C++ OCR과 몇 줄의 코드만 있으면 GIF 이미지를 DOCX 문서로 변환하는 완전한 기능의 애플리케이션을 만들 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

+ AsposeOcr 클래스의 인스턴스 생성
+ AsposeOCR.asposeocr_page() 메서드 호출
+ GIF 파일 경로를 매개변수로 전달
+ AsposeOCR.asposeocr_page는 DOCX 유형의 문자열 또는 파일을 반환합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

예제를 실행하기 전에 [Microsoft.ML.OnnxRuntime](https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/) 1.7.0 이상이 프로젝트에 추가되었는지 확인하십시오. NuGet 패키지 관리자를 통해 Aspose.OCR을 설치하면 자동으로 설치됩니다.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ 호환 솔루션
- 프로젝트에서 참조되는 .NET용 Aspose.OCR.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif" whatIsFormat1="무엇인가요" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기">}}
GIF 또는 그래픽 교환 형식은 고도로 압축된 이미지 유형입니다. Unisys가 소유한 GIF는 이미지 품질을 저하시키지 않는 LZW 압축 알고리즘을 사용합니다. 각 이미지에 대해 GIF는 일반적으로 픽셀당 최대 8비트를 허용하고 이미지 전체에 최대 256색을 허용합니다. 최대 1600만 색상을 표시할 수 있고 인간의 눈의 한계에 상당히 닿는 JPEG 이미지와 대조적입니다. 인터넷이 등장했을 때 GIF는 낮은 대역폭이 필요하고 단색 영역을 소비하는 그래픽과 호환되기 때문에 최고의 선택으로 남아 있었습니다. 애니메이션 GIF는 수많은 이미지 또는 프레임을 단일 파일로 결합하고 이를 시퀀스로 표시하여 애니메이션 클립 또는 짧은 비디오를 생성합니다. 색상 제한은 각 프레임에 대해 최대 256개이며 색상 그라디언트가 있는 다른 이미지 및 사진을 재생하는 데 가장 적합하지 않을 수 있습니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOCX" readMoreLink="https://docs.fileformat.com/word-processing/docx/" whatIsFormat1="무엇인가요" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기">}}
DOCX는 Microsoft Word 문서용으로 잘 알려진 형식입니다. Microsoft Office 2007 릴리스와 함께 2007년부터 도입된 이 새로운 문서 형식의 구조는 일반 바이너리에서 XML과 바이너리 파일의 조합으로 변경되었습니다. Docx 파일은 Word 2007 및 측면 버전에서 열 수 있지만 DOC 파일 확장자를 지원하는 이전 버전의 MS Word에서는 열 수 없습니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/gif-to-txt" name="TXT" description="텍스트 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/gif-to-text" name="Text" description="텍스트 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/gif-to-doc" name="DOC" description="Microsoft Word에서 생성한 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/gif-to-docx" name="DOCX" description="마이크로소프트 워드 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/gif-to-xls" name="XLS" description="Microsoft Excel 이진 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/gif-to-xlsx" name="XLSX" description="마이크로소프트 엑셀 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/gif-to-pdf" name="PDF" description="휴대용 문서 형식(PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/gif-to-searchable_pdf" name="Searchable PDF" description="검색 가능한 휴대용 네트워크 그래픽" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}