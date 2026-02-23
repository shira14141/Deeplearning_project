# DNA Promoter Identification using Deep Learning

## Project Overview
This project uses neural networks to identify promoter regions in DNA sequences. Promoters are regulatory DNA sequences that control gene expression.

**Dataset**: UCI E. coli Promoter Gene Sequences
- 106 DNA sequences (57 nucleotides each)
- Binary classification: Promoter (+) vs Non-Promoter (-)

**Approach**: We'll compare multiple architectures:
1. Simple Dense Network (baseline)
2. CNN with Batch Normalization (your current model)
3. **Enhanced CNN** (deeper architecture)
4. **Hybrid CNN + LSTM** (captures both motifs and sequential patterns)
