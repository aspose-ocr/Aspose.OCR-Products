---
title: Java OCR Image To Text Conversion
url: /java/conversion/
description: Convert images to text within Java based OCR solution using Java OCR library.
---

{{< blocks/products/pf/feature-page-wrap />}}
{{< blocks/products/pf/feature-page-header h1="Image to Text Conversion Via Java" h2="Convert Images to Text via Java OCR API to build cross-platform applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

There are lot of cases when we have image data contating text such as scanned documents, invoices, receipts, bills and pictures and then there is need of text capturing software or app for recognizing and getting it. **Java OCR API** allows to extract text from images quite easily. Programmers can identify and extract text from pictures either it is single line or pages as well as in different languages by integrating the code. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Image to Text Conversion" %}}

Text recognition process with OCR API is simple. Create [AsposeOcr class](https://apireference.aspose.com/ocr/java/com.aspose.ocr/AsposeOCR) instance, Use the instance to invoke [AsposeOcr.recognizePage](https://apireference.aspose.com/ocr/java/com.aspose.ocr/AsposeOCR#RecognizePage-java.lang.String-) method by passing the image GIF, PNG, JPG, BMP etc with full path. It will automatically detect text areas and return information as a string. Finally display the string or write into file for viewing or editing. For those images having single line of text, use [RecognizeLine](https://apireference.aspose.com/ocr/java/com.aspose.ocr/AsposeOCR#RecognizeLine-java.lang.String-) for text extraction. 

{{% blocks/products/pf/feature-page-code h3="Java Code for Image to Text Conversion" %}}

{{< gist "aspose-com-gists" "707d3c2ba2f8d6920324e122dea31b4e" "convert-image-to-text.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Java Code for Single Line Text Capturing from Image" %}}

{{< gist "aspose-com-gists" "707d3c2ba2f8d6920324e122dea31b4e" "convert-image-to-text-having-single-line-text.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="bmp-to-txt jpeg-to-txt gif-to-txt tiff-to-txt png-to-txt" >}}