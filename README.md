# METAGenOmic Analysis Workflow CLI

A CLI that aims to automate common metagenome pipeline steps, with a subsequent focus on viral downstream analysis.  This base steps includes read quality control, assembly, gene calling, and should work for most any metagenomic analysis with a little tweaking of the parameters.

# Workflow Overview

## General Steps

1. Quality Control: [BBDuk](https://jgi.doe.gov/data-and-tools/bbtools/bb-tools-user-guide/bbduk-guide/)
2. Assembly: [MegaHit](https://academic.oup.com/bioinformatics/article/31/10/1674/177884)
3. Binning: [Maxbin 2.0](http://sourceforge.net/projects/maxbin/)
4. Gene Calling: [Prodigal](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-11-119) | [EMIRGE (ribosomal reconstruction)](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2011-12-5-r44)
5. Viral Analysis: [VirSorter](https://peerj.com/articles/985/?utm_source=TrendMD&utm_campaign=PeerJ_TrendMD_0&utm_medium=TrendMD) | [VirHostMatcher](https://academic.oup.com/nar/article/45/1/39/2605663)
6. Annotation: [Prokka](https://academic.oup.com/bioinformatics/article/30/14/2068/2390517)

## Resources

1. Micro-Phage Interaction Database: [MVP](http://mvp.medgenius.info/home)
