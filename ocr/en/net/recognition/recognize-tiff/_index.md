﻿---
title: Recognize multipage TIFF via C# 
weight: 3920
url: /net/recognition/recognize-tiff/ 
lang: en
langdirlevel: 2
locales: ru
description: Recognize multipage TIFF via C#. 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Recognize multipage TIFF in C# " h2="Recognize multipage TIFF using Aspose.OCR for .NET library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OCR" pfName="Aspose.OCR" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="PDF" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API Home" codeSamplesText="Code samples" liveDemosText="Live Demos" downloadText="Download" learnText="Learn">}}

{{% blocks/products/pf/agp/content h2="How to Recognize multipage TIFF using C#" %}}

To recognize a TIFF file, you need to set the InputType as TIFF. You can also specify the start page and the total number of pages to be recognized. Pages are indexed starting from 0. By default, you will receive the recognition results for all pages in the document. Please note that this process may take a considerable amount of time.



[Aspose.OCR for .NET](https://products.aspose.com/ocr/net) 
 processes multipages TIFF. To run the examples, you just need to download the *Aspose.OCR* 
 tools with the following link:  [**Download Comman Line Tools**](https://github.com/aspose-ocr/Aspose.OCR-for-.NET/releases/download/23.5.0/CommandLineToolsAsposeOcr23.5.0.zip)
 or run the example project in IDE: [**RecognizeMultipageTiff project**](https://github.com/aspose-ocr/Aspose.OCR-for-.NET/tree/master/Applications_Aspose_Ocr_Net_6/RecognizeMultipageTiff) 



{{% blocks/products/pf/agp/code-block title="Run program in Command Prompt" offSpacer="true" %}}

```cs

  RecognizeMultipageTiff



```
{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/text %}}

or

{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/code-block title="Run program in Command Prompt if you want to use own TIFF file, start page and pages count" offSpacer="false" %}}

```cs

  RecognizeMultipageTiff folder/image.pdf 0 2

```
{{% /blocks/products/pf/agp/code-block %}}


<br/>





{{% blocks/products/pf/agp/code-block title="This sample code shows how to get areas coordinates" offSpacer="true" %}}

```cs

 // Set the license file
            //License lic = new License();
            //lic.SetLicense("Aspose.Total.lic");

            // Create AsposeOcr instance.
            // You can use the overloaded constructor to set characters restriction.
            AsposeOcr api = new AsposeOcr();

            // Create OcrInput object to containerize images
            // Add filters as you need 
            // PreprocessingFilter filters = new PreprocessingFilter // we automaticaly preprocess your image, but if your recognition result still bad, you can set up the set of filters by your own
            // {
            //     PreprocessingFilter.Dilate()
            // },
            OcrInput input = new OcrInput(InputType.TIFF/*, filters*/);
            input.Add(fileName, pageStart, pageCount);

            // Set the options for recognition - start page and the pages number
            var res = api.Recognize(input, new RecognitionSettings 
            {
                //// allowed options
                // AllowedCharacters = CharactersAllowedType.LATIN_ALPHABET, // ignore not latin symbols
                // AutoContrast = false, // use Contrast correction filter before recognition - good for images with noice 
                // AutoSkew = true, // switch off if your image not rotated
                // DetectAreas = true, // switch off if your image has a simple document structure (one column text without pictures)
                // DetectAreasMode = DetectAreasMode.DOCUMENT, // depends on the structure of your image
                // IgnoredCharacters = "*-!@#$%^&", // define the symbols you want to ignore in the recognition result
                // Language = Language.Eng, // we support 26 languages
                // LinesFiltration = false, // this works slowly, so choose it only if your picture has lines and it they bad detected in TABLE ar DOCUMENT DetectAreasMode   
                // ThreadsCount = 1, // by default our API use all you threads. But you can run it in one thread. Simply set up this here
                // ThresholdValue = 150 // if you want to binarize image with your own threashold value, you can set up this here (from 1 to 255)
            });


            Console.WriteLine("RESULT");
            Console.ResetColor();
            Console.WriteLine("------------------------------------------------------------------------------");
            for (int i = 0; i < res.Count; i++)
            {
                Console.WriteLine("------------------------------------------------------------------------------");
                Console.WriteLine($"PAGE {i + 1}  skew {res[i].Skew}");
                Console.WriteLine("------------------------------------------------------------------------------");
                Console.WriteLine(res[i].RecognitionText);
                Console.WriteLine("------------------------------------------------------------------------------");

                // you can print here additional information and spell-check the result
                // also you can save each page result in your prefered file format
                // res[i].Save(...);
                // or convert your result to json or xml string
                // res[i].GetJson();
                // res[i].GetXml();
            }

            // you can also save result as one multipage document
            // AsposeOcr.SaveMultipageDocument("result.pdf", SaveFormat.Pdf, res);
```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

  

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Tools" subTitle="Using C#, one can easily run our examples." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/recognize-image" name="Recognize image" description="GIF, PNG, JPEG, BMP, TIFF, JFIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/recognize-pdf" name="Recognize PDF" description="Scanned PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/recognize-tiff" name="Recognize TIFF" description="Multipage TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/preprocess" name="Preprocess image" description="GIF, PNG, JPEG, BMP, TIFF, JFIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/recognize-zip" name="Recognize ZIP archive" description="ZIP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/get-json" name="Get JSON" description="GIF, PNG, JPEG, BMP, TIFF, JFIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/get-xlsx" name="Get XLSX" description="GIF, PNG, JPEG, BMP, TIFF, JFIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/get-skew" name="Detect angle" description="GIF, PNG, JPEG, BMP, TIFF, JFIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/recognize-url" name="Recognize image from URL" description="URL with GIF, PNG, JPEG, BMP, TIFF, JFIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/net/recognition/get-text-areas" name="Text areas detection" description="GIF, PNG, JPEG, BMP, TIFF, JFIF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
