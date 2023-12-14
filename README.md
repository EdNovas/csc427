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

