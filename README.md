# Sequence Alignment Viewer
Google Colab notebook for downloading and viewing aligned sequence reads via IGV, all in browser.

[Link to Colab Notebook](https://colab.research.google.com/drive/14AGlKiMbd7U-jjSmj3j-eI_nr-5kTMby?usp=sharing)

![image](https://github.com/WolfgangNS/Sequence-Alignment-Viewer/blob/main/SAV_banner.png?raw=true)


## Motivation

I am currently an undergraduate research volunteer in a lab that studies East African cichlid brains. When I began in October, I found out we have data, but I had to wait to be granted access to our lab's gene expression files. To my surprise, I found several projects on NCBI GEO that had publicly available datasets on cichlid brains already. I knew that whatever code I used to analyze that public data would extend to our lab's private data, as well.  

I was searching all around the web for a notebook that simply runs IGV, with no luck. By sheer force (and lots of trial and error), I found all of the packages, resources, and pipeline that would consolidate my steps into a single notebook, rather than having several confusing files and folders on my hard drive. This also saves me some disk space, as some reference genomes can be up to 8GB. I'm hoping this will save some other researchers/enthusiasts some headaches. 

## Features

- **Download SRA Data**: Access raw genetic sequencing data from NCBI's Sequence Read Archive (SRA).

- **Genome Alignment**: Align SRA data to a reference genome, providing insights into gene locations and variations.

- **IGV Visualization**: Utilize the Integrative Genomics Viewer (IGV) to visualize sequencing data directly in your browser.

## Screenshot

![image](https://github.com/WolfgangNS/Sequence-Alignment-Viewer/blob/main/screenshot.png?raw=true)

## Data pipeline

<img src="https://github.com/WolfgangNS/Sequence-Alignment-Viewer/blob/main/file_flowchart.png?raw=true" width="20%" height="20%">


## Research Significance

- Analyze gene expression patterns.

- Investigate non-coding genome regions.
  
- Identify genetic variations (mutations, SNPs).

## Ideas for further exploration

- Compare genomes across species or strains.
