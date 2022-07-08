﻿---
title: Konvertuoti WBMP į Searchable PDF naudojant C# 
weight: 3920
url: /lt/net/conversion/wbmp-to-searchable_pdf/ 
lang: lt
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: C# konvertavimo iš WBMP į Searchable PDF pavyzdinis kodas. Naudokite API pavyzdinį kodą paketiniams WBMP failams konvertuoti į Searchable PDF VB.NET, Asp.NET arba bet kurioje .NET pagrįstoje programoje.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konvertuoti WBMP į Searchable PDF C#" h2="Atlikite optinį simbolių atpažinimą dokumente WBMP ir išsaugokite tekstą kaip WBMP dokumentą naudodami Aspose.OCR iš .NET bibliotekos." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="Searchable PDF" pfName="Aspose.OCR" subTitlepfName="skirta .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="skirta .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/lt/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/lt/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="API pagrindinis puslapis" codeSamplesText="Kodo pavyzdžiai" liveDemosText="Tiesioginės demonstracinės versijos" downloadText="parsisiųsti" learnText="Mokytis">}}

{{% blocks/products/pf/agp/content h2="Kaip konvertuoti WBMP į Searchable PDF naudojant C#" %}}

Aspose.OCR, skirta .NET, yra galinga, bet paprasta naudoti ir ekonomiška biblioteka, skirta WBMP vaizdams konvertuoti į Searchable PDF dokumentus. Modernus optinis simbolių atpažinimo variklis, palaikantis 26 kalbas, pagrįstas lotynų, kirilicos ir kinų kalbomis, užtikrina puikų atpažinimo greitį ir tikslumą, tuo pačiu izoliuodamas jus nuo formulių, neuroninių tinklų ir kitų sudėtingų techninių detalių. Tai leidžia pridėti OCR funkciją prie .NET programų naudojant mažiau nei 10 kodo eilučių.

[Aspose.OCR, skirtas .NET](https://products.aspose.com/ocr/net)
 apdoroja nuskaitytus vaizdus ar net išmaniųjų telefonų nuotraukas WBMP formatu ir sukuria WBMP dokumentus su atpažintu tekstu. Norėdami pridėti jį prie savo projekto, tereikia įdiegti *Aspose.OCR*
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 paketą savo projekte su šia komanda:

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Veiksmai, kaip konvertuoti WBMP į Searchable PDF" %}}

{{% blocks/products/pf/agp/text %}}

Naudodami .NET OCR ir vos kelias kodo eilutes, galite sukurti visų funkcijų turinčią programą, kuri konvertuoja WBMP vaizdą į Searchable PDF dokumentą:

{{% /blocks/products/pf/agp/text %}}

+ Sukurkite AsposeOcr klasės egzempliorių
+ Iškvieskite AsposeOCR.RecognizeImage metodą
+ Perduokite WBMP failo kelią kaip parametrą
+ AsposeOCR.RecognizeImage grąžina Searchable PDF tipo eilutę arba failą

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sistemos reikalavimai" %}}

{{% blocks/products/pf/agp/text %}}

Prieš paleisdami pavyzdį įsitikinkite, kad jūsų sistemoje įdiegta .NET API, suderinama su NET Standard 2.0 specifikacija, ir visos [išorinės priklausomybės](https://docs.aspose.com/ocr/net/system-requirements/#external- priklausomybės) Aspose.OCR paketo yra nurodytos jūsų projekte.

{{% /blocks/products/pf/agp/text %}}

- Su NET Standard 2.0+ suderinamas sprendimas
– Aspose.OCR, skirtas .NET, nurodytas jūsų projekte.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Šis pavyzdinis kodas rodo konvertavimą iš WBMP į Searchable PDF .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.WBMP");
// print text
File. File.WriteAllText("document.Searchable PDF", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="WBMP" readMoreLink="https://docs.fileformat.com/image/wbmp" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau">}}
WBMP yra vienspalvis grafikos failo formatas, optimizuotas mobiliesiems kompiuterių įrenginiams.
WBMP vaizdai yra vienspalviai (juodai balti), todėl vaizdo dydis yra minimalus. Juodas pikselis žymimas 0, o baltas pikselis žymimas 1.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="Searchable PDF" readMoreLink="https://docs.fileformat.com/pdf/a/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau">}}
Ieškomi PDF failai išsaugo originalų nuskaitytą vaizdą, kad būtų galima peržiūrėti, taip pat OCR tekstas paslėptame sluoksnyje, kuris gali būti naudojamas viso teksto paieškai dokumente arba paryškinant tekstą kopijavimo ir įklijavimo operacijoms.
Visiškas OCR konvertavimas į PDF, neįskaitant originalaus vaizdo, niekada neišsaugos 100% pradinio formatavimo, ypač jei dokumente yra daug vaizdų arba sudėtingas išdėstymas.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Kitos palaikomos konversijos" subTitle="Naudodami C# galite lengvai konvertuoti įvairius formatus, įskaitant." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}