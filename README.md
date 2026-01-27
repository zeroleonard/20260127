# CoIN Benchmark: a Co-augmented multimodal representation benchmark for e-commerce representation learning and evaluation.
## Introduction
The CoIN Benchmark is a co-augmented multimodal representation benchmark designed specifically for representation learning and evaluation in e-commerce scenarios.
Our data originates from one of the largest e-commerce platforms in China. By collecting and processing user interaction logs spanning from January 1, 2023, to June 30, 2025, we have constructed dedicated training and test sets.
Following internal open-source approval procedures, we hereby release the complete test set of the CoIN Benchmark. Due to repository size limitations imposed by the anonymous submission system, we provide a representative subset of 10,000 samples. The full training set and associated model checkpoints are currently undergoing internal review. We commit to releasing the complete dataset and models within three months of the paper’s acceptance.
##Test Set Structure
```plain text
testset/  
├── testset_index.txt          # TSV-formatted index file. Each line contains:  
                               # - A hash-anonymized query–document pair ID  
                               # - Query item title  
                               # - Query item image filename  
                               # - Document (candidate) item title  
                               # - Document item image filename  
                               # - Document item category  
                               # - Document item attribute values  
├── query_img/                 # Directory containing query item images  
└── doc_img/                   # Directory containing document (candidate) item images
```
