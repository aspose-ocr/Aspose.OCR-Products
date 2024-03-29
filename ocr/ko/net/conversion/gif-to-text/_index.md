﻿---
title: C#를 통해 GIF을 Text로 변환 
weight: 3920
url: /ko/net/conversion/gif-to-text/ 
lang: ko
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: GIF에서 Text로의 C# 변환을 위한 샘플 코드입니다. VB.NET, Asp.NET 또는 모든 .NET 기반 응용 프로그램 내에서 일괄 GIF 파일을 Text로 변환하는 API 예제 코드를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C#에서 GIF을 Text로 변환" h2="GIF 문서에 광학 문자 인식을 수행하고 .NET 라이브러리의 Aspose.OCR을 사용하여 텍스트를 GIF 문서로 저장합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="Text" pfName="Aspose.OCR" subTitlepfName=".NET용" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName=".NET용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/ko/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/ko/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API 홈" codeSamplesText="코드 샘플" liveDemosText="라이브 데모" downloadText="다운로드" learnText="배우다">}}

{{% blocks/products/pf/agp/content h2="C#을 사용하여 GIF을 Text로 변환하는 방법" %}}

.NET용 Aspose.OCR은 GIF 이미지를 Text 문서로 변환하기 위한 강력하면서도 사용하기 쉽고 비용 효율적인 라이브러리입니다. 라틴어, 키릴 자모 및 중국어를 기반으로 하는 26개 언어를 지원하는 최신 광학 문자 인식 엔진은 수식, 신경망 및 기타 복잡한 기술 세부 사항에서 사용자를 분리하면서 뛰어난 인식 속도와 정확성을 제공합니다. 10줄 미만의 코드로 .NET 애플리케이션에 OCR 기능을 추가할 수 있습니다.

[.NET용 Aspose.OCR](https://products.aspose.com/ocr/net)
 스캔한 이미지나 스마트폰 사진까지 GIF 형식으로 처리하고 인식된 텍스트가 포함된 GIF 문서를 만듭니다. 프로젝트에 추가하려면 *Aspose.OCR*을 설치하기만 하면 됩니다.
 [누겟](https://www.nuget.org/packages/aspose.ocr)
 다음 명령을 사용하여 프로젝트에 패키지를 추가합니다.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="GIF을 Text로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

.NET OCR과 몇 줄의 코드로 GIF 이미지를 Text 문서로 변환하는 완전한 기능의 애플리케이션을 만들 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

+ AsposeOcr 클래스의 인스턴스 생성
+ AsposeOCR.RecognizeImage 메서드 호출
+ GIF 파일 경로를 매개변수로 전달
+ AsposeOCR.RecognizeImage는 Text 유형의 문자열 또는 파일을 반환합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

예제를 실행하기 전에 NET Standard 2.0 사양과 호환되는 .NET API가 시스템 및 모든 [외부 종속성](https://docs.aspose.com/ocr/net/system-requirements/#external- Aspose.OCR 패키지의 종속성)이 프로젝트에서 참조됩니다.

{{% /blocks/products/pf/agp/text %}}

- NET Standard 2.0+ 호환 솔루션
- 프로젝트에서 참조되는 .NET용 Aspose.OCR.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 GIF에서 Text로의 .NET 변환을 보여줍니다." offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.GIF");
// print text
File. File.WriteAllText("document.Text", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif" whatIsFormat1="무엇인가요" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기">}}
GIF 또는 그래픽 교환 형식은 고도로 압축된 이미지 유형입니다. Unisys가 소유한 GIF는 이미지 품질을 저하시키지 않는 LZW 압축 알고리즘을 사용합니다. 각 이미지에 대해 GIF는 일반적으로 픽셀당 최대 8비트를 허용하고 이미지 전체에 최대 256색을 허용합니다. 최대 1600만 색상을 표시할 수 있고 인간의 눈의 한계에 상당히 닿는 JPEG 이미지와 대조적입니다. 인터넷이 등장했을 때 GIF는 낮은 대역폭이 필요하고 단색 영역을 소비하는 그래픽과 호환되기 때문에 최고의 선택으로 남아 있었습니다. 애니메이션 GIF는 수많은 이미지 또는 프레임을 단일 파일로 결합하고 이를 시퀀스로 표시하여 애니메이션 클립 또는 짧은 비디오를 생성합니다. 색상 제한은 각 프레임에 대해 최대 256개이며 색상 그라디언트가 있는 다른 이미지 및 사진을 재생하는 데 가장 적합하지 않을 수 있습니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Text" readMoreLink="https://docs.fileformat.com/word-processing/txt/" whatIsFormat1="무엇인가요" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기">}}
.TXT 확장자를 가진 파일은 라인 형태의 일반 텍스트를 포함하는 텍스트 문서를 나타냅니다. 텍스트 문서의 단락은 캐리지 리턴으로 인식되며 파일 내용을 더 잘 정렬하는 데 사용됩니다. 표준 텍스트 문서는 다른 운영 체제의 모든 텍스트 편집기 또는 워드 프로세싱 응용 프로그램에서 열 수 있습니다. 이러한 파일에 포함된 모든 텍스트는 사람이 읽을 수 있는 형식이며 일련의 문자로 표시됩니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="C#을 사용하면 다음을 포함한 다양한 형식을 쉽게 변환할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-txt" name="TXT" description="텍스트 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-text" name="Text" description="텍스트 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-doc" name="DOC" description="Microsoft Word에서 생성한 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-docx" name="DOCX" description="마이크로소프트 워드 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-xls" name="XLS" description="Microsoft Excel 이진 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-xlsx" name="XLSX" description="마이크로소프트 엑셀 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-pdf" name="PDF" description="휴대용 문서 형식(PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-searchable_pdf" name="Searchable PDF" description="검색 가능한 휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-xml" name="XML" description="확장 가능한 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/net/conversion/gif-to-json" name="JSON" description="자바스크립트 객체 표기법" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
