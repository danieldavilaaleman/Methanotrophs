### Following testing section from ReadFish

1. Download the R10 fast5 file for playback Nanopore feature [here](https://github.com/LooseLab/readfish/tree/main?tab=readme-ov-file#configuring-bulk-fast5-file-playback) and move it to the MinKNOW data directory.
```
/Library/MinKNOW/data/
```
2. Download the human genome reference [hg38](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000001405.26/) for testing.
3. Create a minimap2 index of the human reference genome fasta file
```
minimap2 -d hg38.mmi GCF_000001405.26_GRCh38_genomic.fna
```
4. 
