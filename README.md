# Lila

A unified benchmark for math reasoning.

The `lila` directory contains the data for the Lila benchmark.
The `original` directory contains the data used in the paper. 
This data is lower quality, but we include it for reproducibility.

Please contact matthewf@allenai.org for questions

```
├── README.md
├── data.zip
│   ├── all
│   │   └── *.json
│   └── multi
│       ├── iid
│       │   ├── dev.json
│       │   ├── test.json
│       │   └── train.json
│       └── ood
│           ├── dev.json
│           ├── test.json
│           └── train.json
└── original.zip
    ├── all
    │   └── *.json
    ├── multi
    │   ├── multi_dev_iid.json
    │   ├── multi_test_iid.json
    │   ├── multi_test_ood.json
    │   └── multi_train_iid.json
    └── robust
        ├── original.json
        └── perturbed.json
```
