
# CoNLL-2012 Reader

Reader for CoNLL-2012 using Ontonotes-5.0 documents.

Generates `.conll` files by reading the `.skel` files from the CoNLL-2012 dataset and the documents from Ontonotes-5.0.

1. In the script `setup_training.sh` change the `ontonotes_path` to the directory containing Ontonotes-5.0.

2. Run by replacing `OUTPUT_DIR` with the path where the processed files will be kept.
 
```
bash setup_training.sh OUTPUT_DIR
```

`OUTPUT_DIR` will contain 
(a) `conll-2012` directory contains the conll files in the `v4` directory.
(b) `{train, dev, test}.english.jsonlines` files contain the training, development, and test data  for CoNLL-2012.

The code is from [Kenton Lee](https://github.com/kentonl/e2e-coref)
