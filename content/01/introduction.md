Introduction
=========================================================

Science is an incremental progress towards creating and organizing knowledge through theories and testable predictions. Reproducibility is a core part of science: being able to repeat or recreate scientific results is essential for the complex process of knowledge accumulation. Due to its relevance, different terms have been introduced to describe specific aspects of the process (e.g., “reproducibility” when the same data and methods are used, “replicability” when new data and potentially new methods are used, “robustness” when the same data but different methods are used, and “generalizability” when new data and methods are used) {cite:p}`The_Turing_Way_Community2019-be`. Here, we will use “reproducibility” as an umbrella term comprising them together to refer to the ability of recreating scientific results {cite:p}`Poldrack2020-ht`. Open science tools and practices have been developed to advance reproducibility, as well as accessibility and transparency at all stages of the research cycle and across all levels of society. Together, they remove barriers to sharing and facilitate collaboration, with the goal of improving reproducibility and, ultimately, accelerating scientific discoveries.

```{admonition} Issue
Empirical observations of how labs conduct research indicate that the adoption rate of open practices and tools for reproducible and collaborative science, unfortunately, remains in its infancy.
```

Even when members of a specific scientific community have taken a central role in open science advocacy and tool development, like in the neuroimaging community, the impact on the rest of the very same community is limited. A recent survey {cite:p}`Paret2021-ky` including researchers who are senior and likely to hold a positive attitude towards open science, indicated that 42% have never pre-registered a neuroimaging study and 34% have never shared their raw neuroimaging data. Many of those who indicated that they pre-registered or shared their data at least once likely did not do so in all their studies, and thus, the actual rate of pre-registration and data sharing in neuroimaging is likely much lower.

The limited adoption of open science practices is at odds with the overwhelming evidence that a lack of open practices and tools can hinder reproducibility with costs for scientific progress and for society. Indeed, reproducibility issues have been undermining the foundation of scientific research in several fields, such as psychology {cite:p}`Open_Science_Collaboration2015-rc, Klein2018-wn` social sciences {cite:p}`Camerer2016-ge,Camerer2018-cb`, neuroimaging {cite:p}`Munafo2017-sm,Botvinik-Nezer2020-hx,Li2021-pk`, preclinical cancer biology research {cite:p}`Errington2021-mw,Errington2021-xl`, and more {cite:p}`Hutson2018-wy,Nissen2016-bl,Serra-Garcia2021-pf`. As a response, there has been a rise in the development of tools and approaches to facilitate reproducibility and open science, in the spirit of Findability, Accessibility, Interoperability, and Reusability principles (FAIR) {cite:p}`Clayson2022-gh,Gorgolewski2016-iy,Nosek2012-lx,Nosek2019-zt,Poldrack2017-xt,Poldrack2019-fn,Poldrack2020-vp,Wilkinson2016-fm`. Beyond their potential to mitigate transparency and reproducibility issues, these practices provide important benefits for individual researchers by increasing exposure, reputation, chances of publication, number of citations, media attention, potential collaborations, and position and funding opportunities {cite:p}`Allen2019-cb,Hunt2019-sd,Markowetz2015-la,McKiernan2016-jy,Nosek2022-hh`. Hence, one could have expected a higher uptake for such beneficial practices and tools.
 
Recently, there is a parallel top-down change of policies to further support the adoption of open science practices and tools. For example, funding agencies are now enforcing the implementation of certain open data practices for publicly funded research ({cite:p}`De_San_Roman2021-xr`; e.g., the NIH in the U.S. and the ERC in Europe; {cite:p}`De_Jonge2021-jy`), and some require a plan for research data storage and sharing, openly accessible publication formats and dissemination plans beyond the classical journal publication. Additionally, they provide funding for the development of necessary software, hardware, and collaborative infrastructure) to support the transition to open and reproducible neuroscience (e.g., the NIH BRAIN Initiative, NIH ReproNim project {cite:p}`Kennedy2019-jy`, NSF CRCNS, EU Human Brain Project, German NFDI). These efforts by funding agencies are complemented by stakeholder institutions like the OHBM, the International Neuroinformatics Coordinating Facility (INCF), the Chinese Open Science Network (COSN), and the Open Science Framework (OSF), who provide platforms for the development of standards and best practices of open and FAIR neuroscience research, assemble training material, quality control, and promote open science practices. Moreover, journals have started changing their policies with regard to open access options and data sharing. Together, these institutional measures aim at fostering the benefits of open science practices, and the adoption of open and reproducible science standards will be increasingly required for labs and individual researchers. 

```{admonition} Issue
Nevertheless, multiple barriers of entry to open science practices are driving the modest rate of adoption in the general research community. Among them are lack of knowledge or training and lack of skills or resources.
```

A survey by Borghi and Van Gulick {cite:t}`Borghi2018-nt` found that 65% of researchers reported openness and reproducibility as motivation for implementing research data management in MRI, but between 40-50% pointed to the lack of best practices/tools and knowledge/training as main obstacles for embracing these practices. Likewise, a more recent survey indicated that similar percentages of researchers in neuroimaging have never learned how to pre-register or share their data online and that they know too little about pre-registration platforms and suitable data repositories {cite:p}`Paret2021-ky`. These later challenges could be alleviated by a simplified overview of the open resources available. However, information required for implementing open science practices over the full research cycle is currently scattered among many different sources. Even experienced researchers in the topic often find it hard to navigate the ecosystem of community-developed tools and to make sustainable choices.

```{admonition} What do we provide
This manuscript provides **an integrated overview of community-developed resources critical to support open and reproducible neuroimaging** throughout the entire research cycle and across different neuroimaging modalities (particularly MRI, MEG, EEG, and PET). 
```

Most previous reviews on the topic have focused on the importance and benefits of open and reproducible science {cite:p}`McKiernan2016-yn,Munafo2017-sm,Nosek2012-lx,Poldrack2017-xt`. Here, we instead focus on a detailed overview, which we believe is urgently needed to accelerate the wider adoption of open science tools and practices by the general research community. The goal is to increase scientific reproducibility and openness by making it easier for scientists to select the best instruments offered by open science at every step of their research workflow. We provide justification on why each of them implements good practices and information on how to access and how to integrate them in the research workflow. 

```{admonition} What do we not provide
**We do not recommend particular tools over others in this review, as the ideal tools may depend on many factors that vary between researchers.** However, we can recommend points to consider when selecting tools. Typically we want to choose tools that integrate with tools and practices already established in the lab, have a steep learning curve, and a long benefit.
```

In order to increase the likelihood of tools being sustainable, they should be relatively mature, well maintained, and supported by an active community. Another indicator is whether the tools and practices are integrated in already established toolboxes or supported by one of the larger openscience organizations. If still multiple tools meet these criteria, then it might be advantageous to choose one that is used by peers and collaboration partners. When we recommend practices, we state the problems they are supposed to address.
 
We also encourage the readers to join the development teams and leadership of those tools, becoming an active part of the open neuroimaging community. Contributions from individuals who are experiencing barriers to the uptake of specific practices are particularly encouraged, since they can help mitigate these barriers for the benefit of everyone.
 
```{admonition} Resources table
To further guide the readers, the manuscript is accompanied by a detailed table containing links and pointers to the resources featured in the text of each section (see the [resources table](../09/table.md)).
```

:::{dropdown} References on this page
```{bibliography}
:filter: docname in docnames
:labelprefix: A
```
:::



