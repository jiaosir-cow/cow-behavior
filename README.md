<p align="center">
  <img src="assets/brand/cowmata-logo.svg" width="280" alt="COWMATA">
</p>

<h1 align="center">cow-behavior</h1>

<p align="center"><b>De-identified tail-root behaviour intervals for dairy cows A–I.</b></p>

<p align="center">
  <a href="https://github.com/zxq309/COWMATA-Pro"><b>COWMATA Pro</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/jiaosir-cow/cowtail"><b>CowTail-4</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/jiaosir-cow/cow-behavior/issues"><b>Questions</b></a>
</p>

<p align="center">
  <img alt="data licence" src="https://img.shields.io/badge/data-CC%20BY%204.0-2ea44f">
  <img alt="intervals" src="https://img.shields.io/badge/intervals-1410-555555">
  <img alt="cows" src="https://img.shields.io/badge/cows-A%E2%80%93I-555555">
</p>

Public interval labels released with [COWMATA Pro](https://github.com/zxq309/COWMATA-Pro).

## Contents

| Path | Description |
|---|---|
| [`dataset/annotations.csv`](dataset/annotations.csv) | 1,410 included intervals |
| [`dataset/cow_disjoint_folds.json`](dataset/cow_disjoint_folds.json) | Nine leave-one-cow-out folds, letters only |
| [`dataset/DATA_DICTIONARY.md`](dataset/DATA_DICTIONARY.md) | Column definitions |

`annotations.csv` columns: `public_id`, `cow`, `layer`, `label`, `label_en`, `code`, `protocol`, `t_start_rel_ms`, `t_end_rel_ms`, `duration_ms`. Each fold names its test, validation, and training cows by letter.

## Animals

The behaviour annotations are released with this repository. Training settings, intermediate results, and materials on data acquisition and device development are available from the corresponding author on request.

## Citation

Jiao, T., Zhang, J., Zhang, X., Zhang, Y., Jiang, Q., Yang, Z., Zhang, Y. Tail-root dairy cow behaviour annotations (letters A–I).

Also cite the manuscript when it is published.

Annotation software: [COWMATA Pro](https://github.com/zxq309/COWMATA-Pro).

## Licence

The annotation table and the cow-disjoint split are [CC BY 4.0](LICENSE). The COWMATA name and logo remain company brand assets.

## Contact

Xiangqing Zhang (corresponding author) — jiaosirty@stu.yau.edu.cn

Questions: open a GitHub issue.
