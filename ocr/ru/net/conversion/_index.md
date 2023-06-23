---
title: C# OCR скопировать текст с фото
url: /net/conversion/
description: Распознавание текста с фото в своем приложении используя библиотеку OCR с помощью нескольких строк C# кода в .NET.
---

{{< blocks/products/pf/feature-page-wrap />}}
{{< blocks/products/pf/feature-page-header h1="Преобразование изображения в текст с помощью C#" h2="Интегрируйте преобразовывайте изображения в текст в свое приложении с помощью ношей кросплатформенной OCR библиотеки для .NET. Распознайте текст на изображении в пару строк кода на C#." >}}

{{% blocks/products/pf/feature-page-summary %}}

Наше решение идеально подходит для извлечение текста из изображений, сканов и фото различных форматов, включая JPG, BMP, TIFF, PNG, PDF, DJVU и других. Подходит для текста на разных языках. Распознавание текста легко добавить в проекты на любых версиях .NET благодаря нашему простому, но гибкому OCR API. Достаточно всего пары строк кода, чтоб легко интегрировать код в свое приложение для работы с любыми текстовыми шрифтами, макетами страниц и стилями. Наш API позволяет работать с любыми сканами и фотографиями документов, как в полностью автоматическом режиме, с определением структуры документа, коррекцией шумов, наклона, поворота и искажений, так и применив гибкую настройку для достижения идеального качества распознавания. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Скопировать текст с фото" %}}

Всё просто! Для интеграций функции распознавания текста в своё приложение:
  1. Добавьте в проект [NuGet пакет Aspose.OCR](https://www.nuget.org/packages/Aspose.OCR)
  2. Создайте экземпляр класса [AsposeOcr class](https://apireference.aspose.com/ocr/net/aspose.ocr/asposeocr).
  3. Вызовите метод [RecognizeImage Method](https://apireference.aspose.com/ocr/net/aspose.ocr.asposeocr/recognizeimage/methods/4) передав ему изображение.

Алгоритм распознавания текста автоматически определит тип документа на фото, найдёт текст, извлечёт его, распознает, и вернет вам полученный на основе исходного изображения текстовый документ. 

Для тонкой настройки всех шагов распознавания и поиска текста на изображении воспользуйтесь [настройками](https://reference.aspose.com/ocr/net/aspose.ocr/recognitionsettings/). Например, вы можете выбрать [язык распознавания](https://reference.aspose.com/ocr/net/aspose.ocr/language/), или наиболее подходящий для вашего случая [режим поиска текста](https://reference.aspose.com/ocr/net/aspose.ocr/detectareasmode/) и предварительной обработки изображения, применение фильтров и [улучшений](https://reference.aspose.com/ocr/net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/). 

Распознанный текст можно получить в виде строки или указать тип документа для результата. Возможна конвертация изображений в множество форматов: TXT, Searchable PDF, Word, Excel, XML, JSON, HTML, EPUB, RTF.

Для извлечения текстовой информации из изображений таблиц, счетов, чеков, паспортов, ID-карт, автомобильных номеров, приборов учета (счетчиков), различных мультистраничных документов (PDF, TIFF, DJVU, ZIP-архивы) мы предлагаем вам специальные, уже настроенные  [API методы](https://reference.aspose.com/ocr/net/aspose.ocr/asposeocr/). 

А если у вас просто одна строка текста? Попробуйте эту простую функцию: [RecognizeLine](https://apireference.aspose.com/ocr/net/aspose.ocr/asposeocr/methods/recognizeline).

{{% blocks/products/pf/feature-page-code h3="C# Пример кода для преобразования изображения в текст" %}}

{{< gist "aspose-com-gists" "94103a826ebfd9e84e639bca106880ce" "convert-image-to-text.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C# Код для извлечения текста с фото" %}}

{{< gist "aspose-com-gists" "94103a826ebfd9e84e639bca106880ce" "convert-images-to-text-containing-single-line-text.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="bmp-to-txt jpeg-to-txt gif-to-txt tiff-to-txt png-to-txt" >}}