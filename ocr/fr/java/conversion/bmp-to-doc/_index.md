﻿---
title:  
weight: 3920
url: /fr/java/conversion/bmp-to-doc/ 
lang: fr
langdirlevel: 2
locales: ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko
description: Exemple de code pour la conversion Java BMP vers DOC. Utilisez un exemple de code d'API pour la conversion par lots de fichiers BMP en DOC dans n'importe quelle application Java Web ou de bureau.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="" h2="" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.OCR" subTitlepfName="pour Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="OCR" fileiconsmall4="XML" fileiconsmall5="BMP" >}}


{{< blocks/products/pf/main-container pfName="Aspose.OCR" subTitlepfName="pour Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/aspose_ocr-for-java.svg" apiHomeLink="https://products.aspose.com/ocr/fr/java" codeSamplesLink="https://github.com/aspose-ocr/Aspose.OCR-for-Java" liveDemosLink="https://products.aspose.app/ocr/family" docsLink="https://docs.aspose.com/ocr/fr/java" installationsDocsLink="https://docs.aspose.com/ocr/java" mavenRepoLink="https://repository.aspose.com/ocr/" downloadAsLink="https://releases.aspose.com/ocr/java" learnAsLink="https://docs.aspose.com/ocr/java" apiReference="" apiHomeText="Accueil de l'API" codeSamplesText="Exemples de code" liveDemosText="Démos en direct" downloadText="Télécharger" learnText="Apprendre">}}

{{% blocks/products/pf/agp/content h2="" %}}



[Aspose.Imaging pour Java](https://products.aspose.com/imaging/java)
 traite les images numérisées ou même les photos de smartphone au format BMP et crée des documents BMP contenant du texte reconnu. Pour l'ajouter à votre projet, il vous suffit d'obtenir *Aspose.OCR*
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

Avec Java OCR et seulement quelques lignes de code, vous pouvez créer une application complète qui convertit une image BMP en document DOC :

{{% /blocks/products/pf/agp/text %}}

+ Créer une instance de la classe AsposeOcr
+ Appelez la méthode AsposeOCR.RecognizePage
+ Passez le chemin du fichier BMP en paramètre
+ AsposeOCR.RecognizePage renvoie une chaîne ou un fichier de type DOC

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
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite">}}
Les fichiers ayant l'extension .BMP représentent des fichiers d'image bitmap utilisés pour stocker des images numériques bitmap. Ces images sont indépendantes de la carte graphique et sont également appelées format de fichier bitmap indépendant du périphérique (DIB). Cette indépendance sert à ouvrir le fichier sur plusieurs plates-formes telles que Microsoft Windows et Mac. Le format de fichier BMP peut stocker des données sous forme d'images numériques bidimensionnelles au format monochrome et couleur avec différentes profondeurs de couleur.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DOC" readMoreLink="https://docs.fileformat.com/word-processing/doc/" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite">}}
Les fichiers avec l'extension .doc représentent des documents générés par Microsoft Word ou d'autres documents de traitement de texte au format de fichier binaire. L'extension était initialement utilisée pour la documentation en texte brut sur plusieurs systèmes d'exploitation différents. Il peut contenir plusieurs types de données différents tels que des images, formatées ainsi que du texte brut, des graphiques, des tableaux, des objets intégrés, des liens, des pages, le formatage des pages, les paramètres d'impression et bien d'autres. Le format était populaire pour toutes sortes de documentation en raison de la variété d'options qu'il offre aux utilisateurs pour la rédaction de manuels, de propositions, de spécifications, de CV, d'articles ou de tout autre document similaire. La version mise à jour de DOC est DOCX qui est basée sur Office OpenXML dont les spécifications sont librement disponibles.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-txt" name="TXT" description="Fichier de document texte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-text" name="Text" description="Fichier de document texte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-doc" name="DOC" description="Documents générés par Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-docx" name="DOCX" description="Document Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-xls" name="XLS" description="Format de fichier binaire Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-xlsx" name="XLSX" description="Documents Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-pdf" name="PDF" description="Format de document portable (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-searchable_pdf" name="Searchable PDF" description="Graphiques réseau portables consultables" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-xml" name="XML" description="Langage de balisage extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/ocr/fr/java/conversion/bmp-to-json" name="JSON" description="Notation d'objet JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
