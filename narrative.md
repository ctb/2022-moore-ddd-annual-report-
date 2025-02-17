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

Most of our research is built in some way on top of these packages.

A brief summary of progress this year:

* our reanalysis of 700 transcriptomes (MMETSP, Lisa Johnson and
  Harriet Alexander) was published! Moreover, Lisa's presentation at
  the 13th International Conference on Genomics in Shenzen won
  the second GigaScience ICG Prize! It was covered in this blog post,
  here: http://gigasciencejournal.com/blog/icg-prize-winner-lisa-johnson-qa/
  
  The main significance of this work is that we show that new
  algorithms can improve results from old data. Note too that the
  MMETSP is a Moore Foundation-generated data set!
  
* our reference independent variant calling software, kevlar, based on
  our k-mer counting library, khmer, was posted as a preprint (and,
  after this reporting period, accepted for publication!).
  
  The initial use for the kevlar software focuses on analyzing novel
  variants in autism quads (father/mother/two children, one with autism),
  where the Human Genome reference will not suffice. The software relies
  on novel statistics for prioritizing differences between the data sets,
  and combines that with a novel approach for extracting and summarizing
  novel sequence data in a (necessarily) reference independent manner.
  
* spacegraphcats, our collaborative work with Dr. Blair Sullivan (another DDD
  Investigator) was submitted to biorxiv!
  
  This project is a 3 year project that emerged from the DDD
  Barnraising in Maine in 2016. Briefly, we are developing novel
  graph-based structures to dig into computationally inaccessible
  regions of complex metagenomes.  This is tremendously exciting work
  that should have major implications for metagenome analysis.
  
* Camille Scott continues to work on streaming assembly of RNAseq as part
  of her doctoral project (https://github.com/camillescott/boink). The
  underlying goal here is to look at sequencing data sets in a streaming
  manner, so that we can make decisions without analyzing the whole data set.
  Decisions can include truncating analysis of the data set, analyzing just
  the data we've collected so far (while continuing to collect new data),
  and avoiding undue collection of noise.
  
  We anticipate posting a preprint and submitting it in the upcoming
  year.

* we continue to work on a massively scalable distributed architecture for
  querying all of the available microbiome data, as part of the
  sourmash project (https://sourmash.readthedocs.io). This will likely
  see submission during the upcoming year as part of Luiz Irber's doctoral
  work.
  
* We made a significant investment in customizable workflows for
  metagenomics (dahak) and transcriptomics (eelpond) that combine our
  tools and approaches with other key pieces of software to produce
  a single configurable pipeline for metagenomic and transcriptomic
  analysis.

* We ran (for the second time) a Summer Institute on bioinformatics
  techniques, called DIBSI (Data Intensive Biology Summer
  Institute). The core two-week workshop attracted 65 learners, along
  with 20 instructors, TAs, and lecturers. It remains one of the most
  visible and well-recognized training programs in biomedical data
  science in the world.

## Awareness and recognition

*Describe evidence of awareness/recognition of you, your projects, and/or your lab members.*

I continue to be utilized for tenure letter writing (three Associate
Professor cases in 2018) and grant panels (in 2019, I served on two
NIH grant panels and two CZI grant panels within the first three
months).  I was invited to attend a KISS workshop at Caltech on LISA,
the space-based gravitational wave detector. And I recently gave the
keynote talk at the 2018 annual meeting of the Dutch Techcentre for Life
Sciences.

Perhaps the biggest recognition I received in 2018 was in being
selected to co-coordinate the NIH Data Commons, a pan-NIH effort to
develop standards and technologies for large scale data analysis in
the cloud. The pilot phase of this project was a $20m 18-month effort
that my team co-coordinated together with Owen White at U Maryland.
While the pilot phase is now over, my visible role in bringing open
science and community engagement methodologies to this project is
likely to result in several other substantial NIH funded projects.

## Expenditures

The major variances were on supplies (we don't really need any more
equipment) and our MSU subcontract (which was all paid in the first year,
and not spread out.)

## No Cost Extension request

We do not expect to have any remaining funds.
