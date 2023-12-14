# Project for CSC 427 reimplement LAVA in codon

LAVA:

https://cb.csail.mit.edu/cb/lava/

https://github.com/arshajii/lava

# Usage

## Preprocessing: 

```
codon run -plugin seq main.codon dict <input FASTA> <input SNP list> <output ref dict> <output SNP dict>
```

## Processing：

```
codon run -plugin seq main.codon lava <input ref dict> <input SNP dict> <input FASTQ> <output file>
```

## Unfortunate

We failed to reimplement all and work as the lava program, however, most of the functions are made to perform the main process. Nevertheless, there are still bugs and failure if you run it. Hope to fix these if we could. 
