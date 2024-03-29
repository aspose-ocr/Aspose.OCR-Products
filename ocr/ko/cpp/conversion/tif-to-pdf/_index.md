﻿---
title:  
weight: 3920
url: /ko/cpp/conversion/tif-to-pdf/ 
lang: ko
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: TIF에서 PDF로의 Java 변환을 위한 샘플 코드입니다. 웹 또는 데스크톱 자바 기반 애플리케이션 내에서 일괄 TIF 파일을 PDF로 변환하는 API 예제 코드를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.OCR" subTitlepfName="C++용" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="C++용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-cpp.svg" apiHomeLink="https://products.aspose.com/ocr/ko/cpp" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-C" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/ko/cpp" installationsDocsLink="https://docs.aspose.com/ocr/cpp" nugetLink="https://www.nuget.org/packages/Aspose.OCR.Cpp" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/cpp" learnAsLink="https://docs.aspose.com/ocr/cpp" apiReference="" apiHomeText="API 홈" codeSamplesText="코드 샘플" liveDemosText="라이브 데모" downloadText="다운로드" learnText="배우다">}}

{{% blocks/products/pf/agp/content h2="" %}}



[자바용 Aspose.Imaging](https://products.aspose.com/imaging/java)
 스캔한 이미지나 스마트폰 사진까지 TIF 형식으로 처리하고 인식된 텍스트가 포함된 TIF 문서를 만듭니다. 프로젝트에 추가하려면 *Aspose.OCR*만 있으면 됩니다.
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) 또는 Aspose Maven Repository 구성 지정
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

C++ OCR과 몇 줄의 코드만 있으면 TIF 이미지를 PDF 문서로 변환하는 완전한 기능의 애플리케이션을 만들 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

+ AsposeOcr 클래스의 인스턴스 생성
+ AsposeOCR.asposeocr_page() 메서드 호출
+ TIF 파일 경로를 매개변수로 전달
+ AsposeOCR.asposeocr_page는 PDF 유형의 문자열 또는 파일을 반환합니다.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIF" readMoreLink="https://docs.fileformat.com/image/tif" whatIsFormat1="무엇인가요" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기">}}
TIFF 또는 TIF(Tagged Image File Format)는 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 여러 색상 공간에서 이중 레벨, 회색조, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 형식을 사용하는 응용 프로그램에 대해 공간과 시간 사이에서 선택하기 위해 손실 및 무손실 압축 방식을 지원합니다. 이 형식은 확장 가능하며 개인 정보 또는 특수 목적 정보를 무제한으로 포함할 수 있도록 여러 번 수정되었습니다. 형식은 시스템에 종속되지 않으며 프로세서, 운영 체제 또는 파일 시스템과 같은 범위에서 자유롭습니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="무엇인가요" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기">}}
PDF(Portable Document Format)는 1990년대에 Adobe에서 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식으로 문서 및 기타 참조 자료를 표시하기 위한 표준을 도입하는 것입니다. PDF 파일 형식에는 원본 문서의 일부가 될 수 있는 텍스트, 이미지, 하이퍼링크, 양식 필드, 리치 미디어, 디지털 서명, 첨부 파일, 메타데이터, 지리 공간 기능 및 3D 개체와 같은 정보를 포함할 수 있는 모든 기능이 있습니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/tif-to-txt" name="TXT" description="텍스트 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/tif-to-text" name="Text" description="텍스트 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/tif-to-doc" name="DOC" description="Microsoft Word에서 생성한 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/tif-to-docx" name="DOCX" description="마이크로소프트 워드 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/tif-to-xls" name="XLS" description="Microsoft Excel 이진 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/tif-to-xlsx" name="XLSX" description="마이크로소프트 엑셀 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/tif-to-pdf" name="PDF" description="휴대용 문서 형식(PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/cpp/conversion/tif-to-searchable_pdf" name="Searchable PDF" description="검색 가능한 휴대용 네트워크 그래픽" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
