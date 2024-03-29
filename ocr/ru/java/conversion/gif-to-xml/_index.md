﻿---
title:  
weight: 3920
url: /ru/java/conversion/gif-to-xml/ 
lang: ru
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Пример кода для преобразования GIF в XML Java. Используйте пример кода API для пакетного преобразования файлов GIF в XML в любом веб-приложении или приложении на базе Java для настольных компьютеров.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="Aspose.OCR" subTitlepfName="для Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="для Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/ru/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-для-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/ru/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Главная страница API" codeSamplesText="Примеры кода" liveDemosText="Живые демонстрации" downloadText="Скачать" learnText="Учиться">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging для Java](https://products.aspose.com/imaging/java)
 обрабатывает отсканированные изображения или даже фотографии со смартфона в формате GIF и создает документы GIF, содержащие распознанный текст. Чтобы добавить его в свой проект, вам просто нужно получить *Aspose.OCR*
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) или укажите конфигурацию репозитория Aspose Maven.
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

С помощью Java OCR и всего нескольких строк кода вы можете создать полнофункциональное приложение, которое преобразует изображение GIF в документ XML:

{{% /blocks/products/pf/agp/text %}}

+ Создать экземпляр класса AsposeOcr
+ Вызов метода AsposeOCR.RecognizePage
+ Передайте путь к файлу GIF в качестве параметра
+ AsposeOCR.RecognizePage возвращает строку или файл типа XML

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif" whatIsFormat1="Что такое" whatIsFormat2="Формат файла" readMoreFormat="Читать далее">}}
Формат GIF или Graphical Interchange Format представляет собой тип сильно сжатого изображения. Принадлежащий Unisys, GIF использует алгоритм сжатия LZW, который не ухудшает качество изображения. Для каждого изображения в формате GIF обычно допускается до 8 бит на пиксель, а в изображении допускается до 256 цветов. В отличие от изображения в формате JPEG, которое может отображать до 16 миллионов цветов и довольно далеко выходит за пределы возможностей человеческого глаза. Когда появился Интернет, GIF-файлы оставались лучшим выбором, потому что они требовали низкой пропускной способности и были совместимы с графикой, которая использует сплошные области цвета. Анимированный GIF объединяет множество изображений или кадров в один файл и отображает их в последовательности для создания анимированного клипа или короткого видео. Ограничения по цвету составляют до 256 для каждого кадра и, вероятно, будут наименее подходящими для воспроизведения других изображений и фотографий с цветовым градиентом.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" whatIsFormat1="Что такое" whatIsFormat2="Формат файла" readMoreFormat="Читать далее">}}
XML означает Extensible Markup Language, который похож на HTML, но отличается использованием тегов для определения объектов. Вся идея создания формата файла XML заключалась в том, чтобы хранить и передавать данные, не завися от программных или аппаратных инструментов. Его популярность связана с тем, что он читается как человеком, так и машиной. Это позволяет создавать общие протоколы данных в виде объектов, которые будут храниться и совместно использоваться по сети, такой как World Wide Web (WWW). «X» в XML означает расширяемость, что означает, что язык может быть расширен до любого количества символов в соответствии с требованиями пользователя. Именно для этих функций его используют многие стандартные форматы файлов, такие как Microsoft Open XML, LibreOffice OpenDocument, XHTML и SVG.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-txt" name="TXT" description="Файл текстового документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-text" name="Text" description="Файл текстового документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-doc" name="DOC" description="Документы, созданные Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-docx" name="DOCX" description="Документы Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-xls" name="XLS" description="Формат двоичного файла Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-xlsx" name="XLSX" description="Документы Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-pdf" name="PDF" description="Переносимый формат документа (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-searchable_pdf" name="Searchable PDF" description="Портативная сетевая графика с возможностью поиска" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-xml" name="XML" description="расширяемый язык разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/java/conversion/gif-to-json" name="JSON" description="Обозначение объектов JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
