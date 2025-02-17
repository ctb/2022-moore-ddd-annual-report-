# 2022 / Final report / Narrative / C. Titus Brown / Moore DDD Investigator

## Progress

*Describe your project's overall progress. Please reference your initial project objectives when possible.*

Award purpose:

>In support of demonstrating the high level of scientific impact
>that data scientists deliver through their focus on
>interdisciplinary data-driven research; funds from this award will
>be used to better understand gene function in non-model organisms
>through the development of new workflows and better data sharing
>technology for large-scale data analysis.

We focus on developing reusable libraries, command line tools, and workflows
(and workflow systems) for analyzing gene transcription and genome function
based on large shotgun sequencing data sets.

During this grant, we further developed,  released, and published two major software packages: sourmash and spacegraphcats. We also continued maintaining a previous software package, khmer for a select period of time.

sourmash is a lightweight software package that uses MinHash-style
sketch representations of k-mers to enable many different bacterial
genome analysis functions, including massively scalable searching of
genome databases and decomposition of microbial community sequencing
into known genomes. We have implemented several novel
algorithms in it. It has attracted more contributors than our previous software
because it is simpler underneath. We are developing it actively as we
work to explore these novel algorithms, develop new data structures,
and implement decentralized bacterial genome database search on an
Internet scale.

spacegraphcats is a compressive graph indexing system built on top of dominating sets. It is the result of a collaboration with Dr. Blair Sullivan, another Moore DDD Investigator. spacegraphcats supports large-scale graph "neighborhood" query, which we developed in order to make use of meagenomic information not captured by current assembly-based approaches.

Most of our research is built in some way on top of these packages.

My major accomplishments from this funding were:

* we created and released multiple (~dozens) versions of the sourmash software, which is slowly gaining recognition as a well-engineered, well-maintained piece of bioinformatics software that enables novel research using massively scalable approaches to k-mer analysis.

* on top of sourmash, we built a massively scalable distributed architecture for querying all available microbiome data, now hosted by JGI - see https://branchwater.jgi.doe.gov/. This is a unique resource.

* We ran three Summer Institutes on bioinformatics
  techniques, called DIBSI (Data Intensive Biology Summer
  Institute). This core two-week workshop attracted 65 learners each year, along
  with approximately 20 instructors, TAs, and lecturers. It remains one of the most
  visible and well-recognized training programs in biomedical data
  science in the world.
  
We also submitted five distinct preprints resulting from novel research using our various tools.

## Awareness and recognition

*Describe evidence of awareness/recognition of you, your projects, and/or your lab members.*

During this period I was promoted to Professor (from Associate Professor) - a vote of confidence from my university for my research program. A number of my letter writers stressed the importance and value of the three major software platforms supported by the Moore DDD grant, including especially sourmash.

Also doing this period the two major software developers on these projects progressed towards their PhD, with Dr. Luiz Irber receiving his degree in late 2022. In addition, Dr. Taylor Reiter, one of the main drivers of the spacegraphcats software, received her PhD in 2022.

## Expenditures

No major variants in expenditures - it was largely personnel and travel.

## No Cost Extension request

We do not expect to have any remaining funds.
