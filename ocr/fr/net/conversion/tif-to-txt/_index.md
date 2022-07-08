﻿---
title: Convertir TIF en TXT via C# 
weight: 3920
url: /fr/net/conversion/tif-to-txt/ 
lang: fr
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Exemple de code pour la conversion TIF vers TXT C#. Utilisez le code d'exemple d'API pour les fichiers batch TIF vers la conversion TXT dans VB.NET, Asp.NET ou toute application basée sur .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convertir TIF en TXT en C#" h2="Effectuez la reconnaissance optique des caractères sur le document TIF et enregistrez le texte en tant que document TIF à l'aide d'Aspose.OCR de la bibliothèque .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="Aspose.OCR" subTitlepfName="pour .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="pour .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-net.svg" apiHomeLink="https://products.aspose.com/ocr/fr/net" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-.NET" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/fr/net" installationsDocsLink="https://docs.aspose.com/ocr/net" nugetLink="https://www.nuget.org/packages/Aspose.OCR" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/ocr/net" learnAsLink="https://docs.aspose.com/ocr/net" apiReference="" apiHomeText="Accueil de l'API" codeSamplesText="Exemples de code" liveDemosText="Démos en direct" downloadText="Télécharger" learnText="Apprendre">}}

{{% blocks/products/pf/agp/content h2="Comment convertir TIF en TXT en utilisant C#" %}}

Aspose.OCR pour .NET est une bibliothèque puissante mais facile à utiliser et rentable pour convertir des images TIF en documents TXT. Prenant en charge 26 langues basées sur le latin, le cyrillique et le chinois, son moteur de reconnaissance optique de caractères à la pointe de la technologie offre une vitesse et une précision de reconnaissance supérieures, tout en vous isolant des formules, des réseaux de neurones et d'autres détails techniques complexes. Il vous permet d'ajouter la fonctionnalité OCR à vos applications .NET en moins de 10 lignes de code.

[Aspose.OCR pour .NET](https://products.aspose.com/ocr/net)
 traite les images numérisées ou même les photos de smartphone au format TIF et crée des documents TIF contenant du texte reconnu. Pour l'ajouter à votre projet, il vous suffit d'installer le *Aspose.OCR*
 [NuGet](https://www.nuget.org/packages/aspose.ocr)
 package dans votre projet avec la commande suivante :

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OCR

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir TIF en TXT" %}}

{{% blocks/products/pf/agp/text %}}

Avec .NET OCR et seulement quelques lignes de code, vous pouvez créer une application complète qui convertit une image TIF en document TXT :

{{% /blocks/products/pf/agp/text %}}

+ Créer une instance de la classe AsposeOcr
+ Appelez la méthode AsposeOCR.RecognizeImage
+ Passez le chemin du fichier TIF en paramètre
+ AsposeOCR.RecognizeImage renvoie une chaîne ou un fichier de type TXT

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

Avant d'exécuter l'exemple, assurez-vous que l'API .NET compatible avec la spécification NET Standard 2.0 est installée sur votre système et que toutes les [dépendances externes](https://docs.aspose.com/ocr/net/system-requirements/#external- dépendances) du package Aspose.OCR sont référencés dans votre projet.

{{% /blocks/products/pf/agp/text %}}

- Solution compatible NET Standard 2.0+
- Aspose.OCR pour .NET référencé dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cet exemple de code montre la conversion TIF à TXT .NET" offSpacer="true" %}}

```cs

// initialize an instance of AsposeOcr
AsposeOcr ocr = new AsposeOcr();
// recognize image
string riText = ocr.RecognizeImage("template.TIF");
// print text
File. File.WriteAllText("document.TXT", riText);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIF" readMoreLink="https://docs.fileformat.com/image/tif" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite">}}
TIFF ou TIF, Tagged Image File Format, représente des images raster destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. Il est capable de décrire des données d'image à deux niveaux, en niveaux de gris, en couleurs de palette et en couleurs dans plusieurs espaces colorimétriques. Il prend en charge les schémas de compression avec perte et sans perte pour choisir entre l'espace et le temps pour les applications utilisant le format. Le format est extensible et a subi plusieurs révisions qui permettent l'inclusion d'une quantité illimitée d'informations privées ou à usage spécial. Le format ne dépend pas de la machine et est exempt de limites telles que le processeur, le système d'exploitation ou les systèmes de fichiers.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite">}}
Un fichier avec l'extension .TXT représente un document texte qui contient du texte brut sous forme de lignes. Les paragraphes d'un document texte sont reconnus par des retours chariot et sont utilisés pour une meilleure organisation du contenu du fichier. Un document texte standard peut être ouvert dans n'importe quel éditeur de texte ou application de traitement de texte sur différents systèmes d'exploitation. Tout le texte contenu dans un tel fichier est dans un format lisible par l'homme et représenté par une séquence de caractères.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="En utilisant C#, on peut facilement convertir différents formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-txt" name="TXT" description="Fichier de document texte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-text" name="Text" description="Fichier de document texte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-doc" name="DOC" description="Documents générés par Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-docx" name="DOCX" description="Document Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-xls" name="XLS" description="Format de fichier binaire Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-xlsx" name="XLSX" description="Documents Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-pdf" name="PDF" description="Format de document portable (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-searchable_pdf" name="Searchable PDF" description="Graphiques réseau portables consultables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-xml" name="XML" description="Langage de balisage extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/net/conversion/tif-to-json" name="JSON" description="Notation d'objet JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}