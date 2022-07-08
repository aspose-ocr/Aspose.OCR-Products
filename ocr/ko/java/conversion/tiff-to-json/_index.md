﻿---
title:  
weight: 3920
url: /ko/java/conversion/tiff-to-json/ 
lang: ko
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: TIFF에서 JSON로의 Java 변환을 위한 샘플 코드입니다. 웹 또는 데스크톱 자바 기반 애플리케이션 내에서 일괄 TIFF 파일을 JSON로 변환하는 API 예제 코드를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="Aspose.OCR" subTitlepfName="Java용" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="Java용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/ko/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/ko/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API 홈" codeSamplesText="코드 샘플" liveDemosText="라이브 데모" downloadText="다운로드" learnText="배우다">}}

{{% blocks/products/pf/agp/content h2="" %}}



[자바용 Aspose.Imaging](https://products.aspose.com/imaging/java)
 스캔한 이미지나 스마트폰 사진까지 TIFF 형식으로 처리하고 인식된 텍스트가 포함된 TIFF 문서를 만듭니다. 프로젝트에 추가하려면 *Aspose.OCR*만 있으면 됩니다.
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) 또는 Aspose Maven Repository 구성 지정
다음 구성을 _pom.xml_에 추가하여 Maven 기반 프로젝트 내에 설치합니다. Gradle, Ivy, Sbt 예제는 [repository](https://repository.aspose.com/ocr/)에서 확인하세요.

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

Java OCR과 몇 줄의 코드만으로 TIFF 이미지를 JSON 문서로 변환하는 완전한 기능의 애플리케이션을 만들 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

+ AsposeOcr 클래스의 인스턴스 생성
+ AsposeOCR.RecognizePage 메서드 호출
+ TIFF 파일 경로를 매개변수로 전달
+ AsposeOCR.RecognizePage는 JSON 유형의 문자열 또는 파일을 반환합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

예제를 실행하기 전에 J2SE(Java 2 Platform, Standard Edition) 6.0(1.6) 이상이 시스템에 설치되어 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 이상이 설치되어 있습니다.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff" whatIsFormat1="무엇인가요" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기">}}
TIFF 또는 TIF(Tagged Image File Format)는 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 여러 색상 공간에서 이중 레벨, 회색조, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 형식을 사용하는 응용 프로그램에 대해 공간과 시간 사이에서 선택하기 위해 손실 및 무손실 압축 방식을 지원합니다. 이 형식은 확장 가능하며 개인 정보 또는 특수 목적 정보를 무제한으로 포함할 수 있도록 여러 번 수정되었습니다. 형식은 시스템에 종속되지 않으며 프로세서, 운영 체제 또는 파일 시스템과 같은 범위에서 자유롭습니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" whatIsFormat1="무엇인가요" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기">}}
JSON(JavaScript Object Notation)은 사람이 읽을 수 있는 텍스트를 사용하여 데이터를 저장하고 전송하는 데이터 공유를 위한 개방형 표준 파일 형식입니다. JSON 파일은 .json 확장자로 저장됩니다. JSON은 형식이 덜 필요하며 XML에 대한 좋은 대안입니다. JSON은 JavaScript에서 파생되지만 언어 독립적인 데이터 형식입니다. JSON의 생성 및 구문 분석은 많은 최신 프로그래밍 언어에서 지원됩니다. application/json은 JSON에 사용되는 미디어 유형입니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-txt" name="TXT" description="텍스트 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-text" name="Text" description="텍스트 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-doc" name="DOC" description="Microsoft Word에서 생성한 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-docx" name="DOCX" description="마이크로소프트 워드 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-xls" name="XLS" description="Microsoft Excel 이진 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-xlsx" name="XLSX" description="마이크로소프트 엑셀 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-pdf" name="PDF" description="휴대용 문서 형식(PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-searchable_pdf" name="Searchable PDF" description="검색 가능한 휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-xml" name="XML" description="확장 가능한 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ko/java/conversion/tiff-to-json" name="JSON" description="자바스크립트 객체 표기법" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}