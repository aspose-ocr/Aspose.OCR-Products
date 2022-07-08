﻿---
title:  
weight: 3920
url: /nl/java/conversion/djvu-to-json/ 
lang: nl
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Voorbeeldcode voor DJVU naar JSON Java-conversie. Gebruik API-voorbeeldcode voor batch-DJVU-bestanden naar JSON-conversie binnen elke web- of desktop-Java-toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="Aspose.OCR" subTitlepfName="voor Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="voor Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/nl/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/nl/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://downloads.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API-startpagina" codeSamplesText="Codevoorbeelden" liveDemosText="Live demo's" downloadText="Downloaden" learnText="Leren">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging voor Java](https://products.aspose.com/imaging/java)
 verwerkt gescande afbeeldingen of zelfs smartphonefoto's in DJVU-indeling en maakt DJVU-documenten met herkende tekst. Om het aan uw project toe te voegen, hoeft u alleen maar *Aspose.OCR* te downloaden.
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) of specificeer de Aspose Maven Repository-configuratie
en installeer het binnen uw op Maven gebaseerde project door de volgende configuraties toe te voegen aan de _pom.xml_. Bekijk voor voorbeelden van Graddle, Ivy en Sbt onze [repository](https://repository.aspose.com/ocr/).

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

Met Java OCR en slechts een paar regels code, kunt u een complete applicatie maken die een DJVU-afbeelding converteert naar een JSON-document:

{{% /blocks/products/pf/agp/text %}}

+ Maak een instantie van de AsposeOcr-klasse
+ Roep AsposeOCR.RecognizePage-methode aan
+ Geef het DJVU bestandspad door als parameter
+ AsposeOCR.RecognizePage retourneert een tekenreeks of bestand van het type JSON

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

Voordat u het voorbeeld uitvoert, moet u ervoor zorgen dat Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) of hoger op uw systeem is geïnstalleerd.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 of hoger is geïnstalleerd.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
DjVu, uitgesproken als "déjà vu", is een grafisch bestandsformaat dat bedoeld is voor gescande documenten en boeken, met name die welke de combinatie van tekst, tekeningen, afbeeldingen en foto's bevatten. Het is ontwikkeld door AT&T Labs. Het maakt gebruik van meerdere technieken, zoals scheiding van tekst- en achtergrondafbeeldingen in beeldlagen, progressief laden, rekenkundige codering en compressie met verlies voor bitonale afbeeldingen. Omdat het DJVU-bestand gecomprimeerde maar hoogwaardige kleurenafbeeldingen, foto's, tekst en tekeningen kan bevatten en daarom in minder ruimte kan worden opgeslagen, wordt het op internet gebruikt als eBooks, handleidingen, kranten, oude documenten, enz.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" whatIsFormat1="Wat is" whatIsFormat2="Bestandsformaat" readMoreFormat="Lees verder">}}
JSON (JavaScript Object Notation) is een open standaardbestandsindeling voor het delen van gegevens die door mensen leesbare tekst gebruikt om gegevens op te slaan en te verzenden. JSON-bestanden worden opgeslagen met de .json-extensie. JSON vereist minder opmaak en is een goed alternatief voor XML. JSON is afgeleid van JavaScript, maar is een taalonafhankelijk gegevensformaat. Het genereren en parseren van JSON wordt ondersteund door veel moderne programmeertalen. application/json is het mediatype dat voor JSON wordt gebruikt.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}