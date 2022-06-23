---
layout: page
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial

  # Course details
       # "name" -> The acronym and extended name of the course, separated by " - "
       # "description" -> Short description of the course
  name: "IBIP22 - Integrative Biological Interpretation using Proteomics"
  description: ""
  
  # Keywords -> Consult EDAM:Topic
keywords:  "http://edamontology.org/topic_0121,http://edamontology.org/topic_0602,http://edamontology.org/topic_0085,http://edamontology.org/topic_0121,http://edamontology.org/topic_3922"

  # Audience -> Following Elixir-Tess input
  audience: ["Academia/ Research Institution", "Industry", "Non-Profit Organisation", "Healthcare"]

  # Author info
  author:
    - "@type": Organization
      name: "The Gulbenkian Training Programme in Bioinformatics"
      alternateName: "GTPB"
      sameAs: "gtpb.igc.gulbenkian.pt/bicourses/index.html"

  # predominant type of learning resources
  "learningResourceType": ["presentation", "exercise", "scripts", "handout"]

  # Contributor info
  contributor:
    - "@type": Person
      name: "Veit Schwämmle"
    - "@type": Person
      name: "Marc Vaudel"
    - "@type": Person
      name: "Nadezhda Doncheva"

  # License & Language & url
  license: https://creativecommons.org/licenses/by/4.0/
  inLanguage: "en-us"
  url: "https://gtpb.github.io/Web_course_template/"
---


![IBIP22](/assets/IBIP22.png)

## Course Description

Quantitative proteomics by mass spectrometry has become an essential tool for multi-omics studies aiming at answering important biological questions in a system-wide perspective. Proteomics data contain rich and deep information that can become challenging to extract, interpret, and interface with other experimental outcomes. This training course is aimed at researchers who are not expert in proteomics and want to integrate quantitative proteomics results into wider biomedical experiments. We will focus on quality control from an end-user perspective, link to the underlying genomic context, multivariate analysis, protein complexes investigation, and compare different platforms for biological interpretation.

## Target Audience

This course is oriented towards biologists and bioinformaticians. The course will be of particular interest to researchers interested in biologically interpreting proteomics data, and to integrate it with other data types like genomics.

## Detailed Program

### Introduction
- [Installation](pages/Installation.md)
- [Proteomics Assay Data](pages/proteomics_assay/proteomics_assay_data.md)

### QC of proteomics data
- [Activities](pages/QC_Workshop/README.md)

### Wrap-up Tuesday
- [Slides](pages/Wrap_up_Tuesday.pptx)

### Networks: from quantitatives to biological insights
- [Overview](pages/Networks/ReadMe.md)

### Proteogenomics
- [Overview](pages/Proteogenomics/README.md)

### Wrap-up Wednesday
- [Slides](pages/Wrap_up_Wednesday.pptx)

### Quantitative clustering and Multivariate analysis
- [Overview](pages/QuantitativeClustering/README.md)

### Wrap-up Thursday
- [Slides](pages/Wrap_up_Thursday.pptx)

### Protein complexes
- [Overview](pages/Protein_Complexes/README.md)


---

### Learning objectives

After the training, participants will be able to critically interpret results, troubleshoot analyses, and will be ready to successfully attend more specialized training e.g. in proteogenomics or biological network analysis.

---

The source for this course webpage is [in github](https://github.com/GTPB/IBIP22).

<br/>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Web_course_template</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">GTPB</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
