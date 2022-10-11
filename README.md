# Lila

A unified benchmark for math reasoning.

The `original` directory contains the data used in the Lila paper. 
We include it for reproducibility.
The `lila` directory contains the data for the official Lila benchmark, 
which has undergone quality improvements since the paper.

You will need [git-lfs](https://git-lfs.github.com/) to clone these, 
or you can download them manually (e.g., `lila.zip > download`).

Please contact matthewf@allenai.org with questions.

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
    │   └── ...
    ├── single
    │   └── ...
    ├── cross
    │   └── ...
    └── robust
        ├── original.json
        └── perturbed.json
```
