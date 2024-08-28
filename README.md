# PacBio Sexome Manuscript

Microbiome analysis for sexome microbiome data.

Processing PacBio pilot data for manuscript.

To quickly load pre-processed sequence data I have created [phyloseq](https://joey711.github.io/phyloseq/) objects and [ampvis2](https://madsalbertsen.github.io/ampvis2/) objects.     

See the RData directory
```
├── RData/
│   └── pacbio_ampvis.RData/
│   └── pacbio_phyloseq.RData/
```

Complete project directory currently set out as followed.
```
sexome-manuscript/
├── code/
│   └── Data_Visualization.Rmd
├── data/
│   └── pacbio-sexome-metadata.csv
├── PacBio-Sexome.Rproj
├── output/
│   └── Figures
│   └── seqtab.nochim.csv
│   └── asv.fasta
│   └── taxa.csv
│   └── tax_table.csv
│   └── readtracking.csv
├── raw-data/
├── RData/
│   └── pacbio_ampvis.RData/
│   └── pacbio_phyloseq.RData/
└── README.md
```
