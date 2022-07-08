﻿---
title:  
weight: 3920
url: /ru/java/conversion/tiff-to-xls/ 
lang: ru
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Пример кода для преобразования TIFF в XLS Java. Используйте пример кода API для пакетного преобразования файлов TIFF в XLS в любом веб-приложении или приложении на базе Java для настольных компьютеров.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.OCR" subTitlepfName="для Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="для Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/ru/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-для-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/ru/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Главная страница API" codeSamplesText="Примеры кода" liveDemosText="Живые демонстрации" downloadText="Скачать" learnText="Учиться">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging для Java](https://products.aspose.com/imaging/java)
 обрабатывает отсканированные изображения или даже фотографии со смартфона в формате TIFF и создает документы TIFF, содержащие распознанный текст. Чтобы добавить его в свой проект, вам просто нужно получить *Aspose.OCR*
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) или укажите конфигурацию репозитория Aspose Maven.
и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл _pom.xml_. Примеры Gradle, Ivy, Sbt можно найти в нашем [репозитории] (https://repository.aspose.com/ocr/).

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

С помощью Java OCR и всего нескольких строк кода вы можете создать полнофункциональное приложение, которое преобразует изображение TIFF в документ XLS:

{{% /blocks/products/pf/agp/text %}}

+ Создать экземпляр класса AsposeOcr
+ Вызов метода AsposeOCR.RecognizePage
+ Передайте путь к файлу TIFF в качестве параметра
+ AsposeOCR.RecognizePage возвращает строку или файл типа XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

Перед запуском примера убедитесь, что в вашей системе установлена ​​платформа Java 2 Standard Edition (J2SE) 6.0 (1.6) или более поздней версии.

{{% /blocks/products/pf/agp/text %}}

- Установлен JDK 1.6 или выше.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff" whatIsFormat1="Что такое" whatIsFormat2="Формат файла" readMoreFormat="Читать далее">}}
TIFF или TIF, Tagged Image File Format, представляет собой растровые изображения, которые предназначены для использования на различных устройствах, соответствующих этому стандарту формата файлов. Он способен описывать двухуровневые, полутоновые, палитры и полноцветные данные изображения в нескольких цветовых пространствах. Он поддерживает схемы сжатия с потерями, а также без потерь, чтобы выбирать между пространством и временем для приложений, использующих формат. Формат является расширяемым и претерпел несколько изменений, что позволяет включать неограниченное количество частной или специальной информации. Формат не зависит от машины и свободен от ограничений, таких как процессор, операционная система или файловые системы.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" whatIsFormat1="Что такое" whatIsFormat2="Формат файла" readMoreFormat="Читать далее">}}
Файлы с расширением XLS представляют собой формат двоичных файлов Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими подобными программами для работы с электронными таблицами, такими как OpenOffice Calc или Apple Numbers. Файл, сохраненный Excel, известен как рабочая книга, где каждая рабочая книга может иметь один или несколько рабочих листов. Данные хранятся и отображаются для пользователей в формате таблицы на листе и могут включать числовые значения, текстовые данные, формулы, подключения к внешним данным, изображения и диаграммы. Такие приложения, как Microsoft Excel, позволяют экспортировать данные рабочей книги в несколько различных форматов, включая PDF, CSV, XLSX, TXT, HTML, XPS и некоторые другие. Формат файла XLS был заменен более открытым и структурированным форматом XLSX с выпуском Microsoft Excel 2007. Последние версии по-прежнему поддерживают создание и чтение файлов XLS, хотя XLSX сейчас используется в первую очередь.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-txt" name="TXT" description="Файл текстового документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-text" name="Text" description="Файл текстового документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-doc" name="DOC" description="Документы, созданные Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-docx" name="DOCX" description="Документы Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-xls" name="XLS" description="Формат двоичного файла Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-xlsx" name="XLSX" description="Документы Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-pdf" name="PDF" description="Переносимый формат документа (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-searchable_pdf" name="Searchable PDF" description="Портативная сетевая графика с возможностью поиска" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-xml" name="XML" description="расширяемый язык разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/tiff-to-json" name="JSON" description="Обозначение объектов JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}