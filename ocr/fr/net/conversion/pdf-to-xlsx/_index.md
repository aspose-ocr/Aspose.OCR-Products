﻿---
title: Convertir PDF en XLSX via C# 
weight: 3920
url: /fr/net/conversion/pdf-to-xlsx/ 
lang: fr
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Exemple de code pour la conversion PDF vers XLSX C#. Utilisez le code d'exemple d'API pour les fichiers batch PDF vers la conversion XLSX dans VB.NET, Asp.NET ou toute application basée sur .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convertir PDF en XLSX en C#" h2="Effectuez la reconnaissance optique des caractères sur le document PDF et enregistrez le texte en tant que document PDF à l'aide d'Aspose.OCR de la bibliothèque .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.OCR" subTitlepfName="pour .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="pour .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/fr/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/fr/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://releases.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Accueil de l'API" codeSamplesText="Exemples de code" liveDemosText="Démos en direct" downloadText="Télécharger" learnText="Apprendre">}}

{{% blocks/products/pf/agp/content h2="Comment convertir PDF en XLSX en utilisant C#" %}}

Aspose.OCR pour .NET est une bibliothèque puissante mais facile à utiliser et rentable pour convertir des images PDF en documents XLSX. Prenant en charge 26 langues basées sur le latin, le cyrillique et le chinois, son moteur de reconnaissance optique de caractères à la pointe de la technologie offre une vitesse et une précision de reconnaissance supérieures, tout en vous isolant des formules, des réseaux de neurones et d'autres détails techniques complexes. Il vous permet d'ajouter la fonctionnalité OCR à vos applications .NET en moins de 10 lignes de code.

[Aspose.OCR pour .NET](https://products.aspose.com/ocr/net)
 traite les images numérisées ou même les photos de smartphone au format PDF et crée des documents PDF contenant du texte reconnu. Pour l'ajouter à votre projet, il vous suffit d'installer le *Aspose.OCR*
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 package dans votre projet avec la commande suivante :

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir PDF en XLSX" %}}

{{% blocks/products/pf/agp/text %}}

Avec .NET OCR et seulement quelques lignes de code, vous pouvez créer une application complète qui convertit une image PDF en document XLSX :

{{% /blocks/products/pf/agp/text %}}

+ Créer une instance de la classe AsposeOcr
+ Appelez la méthode AsposeOCR.RecognizeImage
+ Passez le chemin du fichier PDF en paramètre
+ AsposeOCR.RecognizeImage renvoie une chaîne ou un fichier de type XLSX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

Avant d'exécuter l'exemple, assurez-vous que l'API .NET compatible avec la spécification NET Standard 2.0 est installée sur votre système et que toutes les [dépendances externes](https://docs.aspose.com/ocr/net/system-requirements/#external- dépendances) du package Aspose.OCR sont référencés dans votre projet.

{{% /blocks/products/pf/agp/text %}}

- Solution compatible NET Standard 2.0+
- Aspose.OCR pour .NET référencé dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cet exemple de code montre la conversion PDF à XLSX .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.PDF");
// print text
File. File.WriteAllText("document.XLSX", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite">}}
Portable Document Format (PDF) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et autres documents de référence dans un format indépendant du logiciel d'application, du matériel ainsi que du système d'exploitation. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias enrichis, des signatures numériques, des pièces jointes, des métadonnées, des fonctionnalités géospatiales et des objets 3D qui peuvent faire partie du document source.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite">}}
XLSX est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. Basé sur une structure organisée selon les conventions d'emballage ouvertes comme indiqué dans la partie 2 de la norme OOXML ECMA-376, le nouveau format est un package zip contenant un certain nombre de fichiers XML. La structure sous-jacente et les fichiers peuvent être examinés en décompressant simplement le fichier .xlsx.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="En utilisant C#, on peut facilement convertir différents formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-txt" name="TXT" description="Fichier de document texte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-text" name="Text" description="Fichier de document texte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-doc" name="DOC" description="Documents générés par Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-docx" name="DOCX" description="Document Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-xls" name="XLS" description="Format de fichier binaire Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-xlsx" name="XLSX" description="Documents Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-pdf" name="PDF" description="Format de document portable (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-searchable_pdf" name="Searchable PDF" description="Graphiques réseau portables consultables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-xml" name="XML" description="Langage de balisage extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/pdf-to-json" name="JSON" description="Notation d'objet JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
