﻿---
title:  
weight: 3920
url: /fr/java/conversion/djvu-to-pdf/ 
lang: fr
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Exemple de code pour la conversion Java DJVU vers PDF. Utilisez un exemple de code d'API pour la conversion par lots de fichiers DJVU en PDF dans n'importe quelle application Java Web ou de bureau.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.OCR" subTitlepfName="pour Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="pour Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/fr/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/fr/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Accueil de l'API" codeSamplesText="Exemples de code" liveDemosText="Démos en direct" downloadText="Télécharger" learnText="Apprendre">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging pour Java](https://products.aspose.com/imaging/java)
 traite les images numérisées ou même les photos de smartphone au format DJVU et crée des documents DJVU contenant du texte reconnu. Pour l'ajouter à votre projet, il vous suffit d'obtenir *Aspose.OCR*
[Aspose Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ou spécifiez la configuration du référentiel Aspose Maven
et installez-le dans votre projet basé sur Maven en ajoutant les configurations suivantes au fichier _pom.xml_. Pour des exemples Graddle, Ivy, Sbt, consultez notre [référentiel](https://repository.aspose.com/ocr/).

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

Avec Java OCR et seulement quelques lignes de code, vous pouvez créer une application complète qui convertit une image DJVU en document PDF :

{{% /blocks/products/pf/agp/text %}}

+ Créer une instance de la classe AsposeOcr
+ Appelez la méthode AsposeOCR.RecognizePage
+ Passez le chemin du fichier DJVU en paramètre
+ AsposeOCR.RecognizePage renvoie une chaîne ou un fichier de type PDF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

Avant d'exécuter l'exemple, assurez-vous que Java 2 Platform, Standard Edition (J2SE) 6.0 (1.6) ou version ultérieure est installé sur votre système.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 ou supérieur est installé.

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite">}}
DjVu, prononcé comme "déjà vu", est un format de fichier graphique destiné aux documents numérisés et aux livres, en particulier ceux qui contiennent la combinaison de texte, dessins, images et photographies. Il a été développé par AT&T Labs. Il utilise plusieurs techniques telles que la séparation des couches d'image du texte et des images d'arrière-plan, le chargement progressif, le codage arithmétique et la compression avec perte pour les images bitonales. Étant donné que le fichier DJVU peut contenir des images, des photographies, du texte et des dessins en couleur compressés mais de haute qualité et peut donc être enregistré dans moins d'espace, il est utilisé sur le Web sous forme de livres électroniques, de manuels, de journaux, de documents anciens, etc.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite">}}
Portable Document Format (PDF) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et autres documents de référence dans un format indépendant du logiciel d'application, du matériel ainsi que du système d'exploitation. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias enrichis, des signatures numériques, des pièces jointes, des métadonnées, des fonctionnalités géospatiales et des objets 3D qui peuvent faire partie du document source.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
