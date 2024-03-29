﻿---
title:  
weight: 3920
url: /lt/java/conversion/bmp-to-doc/ 
lang: lt
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Pavyzdinis kodas, skirtas Java konvertavimui iš BMP į DOC. Naudokite API pavyzdinį kodą paketiniams BMP failams konvertuoti į DOC bet kurioje žiniatinklio ar darbalaukio Java pagrįstoje programoje.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.OCR" subTitlepfName="skirta Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="skirta Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/lt/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/lt/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="API pagrindinis puslapis" codeSamplesText="Kodo pavyzdžiai" liveDemosText="Tiesioginės demonstracinės versijos" downloadText="parsisiųsti" learnText="Mokytis">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
 apdoroja nuskaitytus vaizdus ar net išmaniųjų telefonų nuotraukas BMP formatu ir sukuria BMP dokumentus su atpažintu tekstu. Norėdami pridėti jį prie projekto, tereikia gauti *Aspose.OCR*
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) arba nurodykite Aspose Maven saugyklos konfigūraciją
ir įdiekite jį savo „Maven“ projekte, pridėdami toliau nurodytas konfigūracijas prie _pom.xml_. Graddle, Ivy, Sbt pavyzdžių ieškokite mūsų [saugykloje] (https://repository.aspose.com/ocr/).

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

Naudodami „Java“ OCR ir vos kelias kodo eilutes galite sukurti visų funkcijų turinčią programą, kuri konvertuoja BMP vaizdą į DOC dokumentą:

{{% /blocks/products/pf/agp/text %}}

+ Sukurkite AsposeOcr klasės egzempliorių
+ Iškvieskite AsposeOCR.RecognizePage metodą
+ Perduokite BMP failo kelią kaip parametrą
+ AsposeOCR.RecognizePage grąžina DOC tipo eilutę arba failą

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sistemos reikalavimai" %}}

{{% blocks/products/pf/agp/text %}}

Prieš paleisdami pavyzdį įsitikinkite, kad jūsų sistemoje yra įdiegta Java 2 platforma, standartinis leidimas (J2SE) 6.0 (1.6) arba naujesnė versija.

{{% /blocks/products/pf/agp/text %}}

- Įdiegta JDK 1.6 arba naujesnė versija.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau">}}
Failai, kurių plėtinys yra .BMP, yra taškinio vaizdo failai, naudojami taškinio formato skaitmeniniams vaizdams saugoti. Šie vaizdai nepriklauso nuo grafikos adapterio ir taip pat vadinami nepriklausomu bitmap (DIB) failo formatu. Ši nepriklausomybė skirta atidaryti failą keliose platformose, pvz., „Microsoft Windows“ ir „Mac“. BMP failo formatas gali saugoti duomenis kaip dvimačius skaitmeninius vaizdus tiek nespalvotu, tiek spalvotu formatu su įvairiu spalvų gyliu.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOC" readMoreLink="https://docs.fileformat.com/word-processing/doc/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau">}}
Failai su plėtiniu .doc yra dokumentai, sukurti naudojant Microsoft Word arba kitus teksto apdorojimo dokumentus dvejetainiu failo formatu. Iš pradžių plėtinys buvo naudojamas paprasto teksto dokumentacijai keliose skirtingose ​​operacinėse sistemose. Jame gali būti kelių skirtingų tipų duomenų, tokių kaip vaizdai, suformatuoti, taip pat paprastas tekstas, grafikai, diagramos, įterptieji objektai, nuorodos, puslapiai, puslapio formatavimas, spausdinimo nustatymai ir daug kitų. Formatas buvo populiarus visų rūšių dokumentacijai dėl daugybės galimybių, kurias jis siūlo vartotojams rašant vadovus, pasiūlymus, specifikacijas, gyvenimo aprašymus, straipsnius ar bet kokius panašius dokumentus. Atnaujinta DOC versija yra DOCX, pagrįsta Office OpenXML, kurios specifikacijos yra atvirai prieinamos.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-txt" name="TXT" description="Tekstinio dokumento failas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-text" name="Text" description="Tekstinio dokumento failas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-doc" name="DOC" description="„Microsoft Word“ sukurti dokumentai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-docx" name="DOCX" description="Microsoft Word dokumentai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-xls" name="XLS" description="Microsoft Excel dvejetainis failo formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-xlsx" name="XLSX" description="Microsoft Excel dokumentai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-pdf" name="PDF" description="Nešiojamo dokumento formatas (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-searchable_pdf" name="Searchable PDF" description="Ieškoma nešiojama tinklo grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-xml" name="XML" description="Išplečiama žymėjimo kalba" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/lt/java/conversion/bmp-to-json" name="JSON" description="„JavaScript“ objektų žymėjimas" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
