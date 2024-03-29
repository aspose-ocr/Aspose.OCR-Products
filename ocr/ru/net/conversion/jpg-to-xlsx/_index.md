﻿---
title: Преобразование JPG в XLSX с помощью C# 
weight: 3920
url: /ru/net/conversion/jpg-to-xlsx/ 
lang: ru
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Пример кода для преобразования JPG в XLSX C#. Используйте пример кода API для пакетного преобразования файлов JPG в XLSX в VB.NET, Asp.NET или любом приложении на основе .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Преобразование JPG в XLSX в C#" h2="Выполните оптическое распознавание символов в документе JPG и сохраните текст как документ JPG, используя Aspose.OCR для библиотеки .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.OCR" subTitlepfName="для .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="для .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/ru/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/ru/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Главная страница API" codeSamplesText="Примеры кода" liveDemosText="Живые демонстрации" downloadText="Скачать" learnText="Учиться">}}

{{% blocks/products/pf/agp/content h2="Как преобразовать JPG в XLSX с помощью C#" %}}

Aspose.OCR для .NET — это мощная, но простая в использовании и недорогая библиотека для преобразования изображений JPG в документы XLSX. Поддерживая 26 языков на основе латиницы, кириллицы и китайского языка, его современный механизм оптического распознавания символов обеспечивает превосходную скорость и точность распознавания, изолируя вас от формул, нейронных сетей и других сложных технических деталей. Он позволяет добавить функциональность OCR в ваши приложения .NET менее чем за 10 строк кода.

[Aspose.OCR для .NET](https://products.aspose.com/ocr/net)
 обрабатывает отсканированные изображения или даже фотографии со смартфона в формате JPG и создает документы JPG, содержащие распознанный текст. Чтобы добавить его в свой проект, вам просто нужно установить *Aspose.OCR*
 [NuGet] (https://www.nuget.org/packages/aspose.ocr)
 package в своем проекте с помощью следующей команды:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию JPG в XLSX" %}}

{{% blocks/products/pf/agp/text %}}

С помощью .NET OCR и всего нескольких строк кода вы можете создать полнофункциональное приложение, которое преобразует изображение JPG в документ XLSX:

{{% /blocks/products/pf/agp/text %}}

+ Создать экземпляр класса AsposeOcr
+ Вызов метода AsposeOCR.RecognizeImage
+ Передайте путь к файлу JPG в качестве параметра
+ AsposeOCR.RecognizeImage возвращает строку или файл типа XLSX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

Перед запуском примера убедитесь, что в вашей системе установлен .NET API, совместимый со спецификацией NET Standard 2.0, и все [внешние зависимости] (https://docs.aspose.com/ocr/net/system-requirements/#external- зависимости) пакета Aspose.OCR упоминаются в вашем проекте.

{{% /blocks/products/pf/agp/text %}}

- Решение, совместимое с NET Standard 2.0+
- Aspose.OCR для .NET, указанный в вашем проекте.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Этот пример кода показывает преобразование JPG в XLSX .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.JPG");
// print text
File. File.WriteAllText("document.XLSX", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPG" readMoreLink="https://docs.fileformat.com/image/jpg" whatIsFormat1="Что такое" whatIsFormat2="Формат файла" readMoreFormat="Читать далее">}}
JPEG — это тип формата изображения, который сохраняется с использованием метода сжатия с потерями. Выходное изображение в результате сжатия представляет собой компромисс между размером хранилища и качеством изображения. Пользователи могут настроить уровень сжатия для достижения желаемого уровня качества и в то же время уменьшить размер хранилища. Качество изображения незначительно ухудшается, если к изображению применяется сжатие 10:1. Чем выше значение сжатия, тем выше ухудшение качества изображения.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" whatIsFormat1="Что такое" whatIsFormat2="Формат файла" readMoreFormat="Читать далее">}}
XLSX — это хорошо известный формат для документов Microsoft Excel, который был представлен Microsoft с выпуском Microsoft Office 2007. Основанный на структуре, организованной в соответствии с соглашениями об открытой упаковке, как указано в части 2 стандарта OOXML ECMA-376, новый формат ZIP-пакет, содержащий несколько XML-файлов. Базовую структуру и файлы можно изучить, просто разархивировав файл .xlsx.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="С помощью C# можно легко конвертировать различные форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-txt" name="TXT" description="Файл текстового документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-text" name="Text" description="Файл текстового документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-doc" name="DOC" description="Документы, созданные Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-docx" name="DOCX" description="Документы Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-xls" name="XLS" description="Формат двоичного файла Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-xlsx" name="XLSX" description="Документы Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-pdf" name="PDF" description="Переносимый формат документа (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-searchable_pdf" name="Searchable PDF" description="Портативная сетевая графика с возможностью поиска" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-xml" name="XML" description="расширяемый язык разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/ru/net/conversion/jpg-to-json" name="JSON" description="Обозначение объектов JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
