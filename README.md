# Tail-root dairy cow behaviour annotations

De-identified interval labels for tail-root inertial recordings of dairy cows A–I.

## Contents

| Path | Description |
|---|---|
| `dataset/annotations.csv` | 1,410 included intervals |
| `dataset/cow_disjoint_folds.json` | Nine leave-one-cow-out folds, letters only |
| `dataset/DATA_DICTIONARY.md` | Column definitions |

`annotations.csv` columns: `public_id`, `cow`, `layer`, `label`, `label_en`, `code`, `protocol`, `t_start_rel_ms`, `t_end_rel_ms`, `duration_ms`, `session_in_cow`. `session_in_cow` is an index within that cow, not a clock time. Each fold names its test, validation, and training cows by letter.

## Animals

Letters A–I only. The table has no farm identifiers, device addresses, staff names, video file names, or letter-to-record key. Cows J–M are not included.

## Citation

Jiao, T., Zhang, J., Zhang, X., Zhang, Y., Jiang, Q., Yang, Z., Zhang, Y. Tail-root dairy cow behaviour annotations (letters A–I).

Also cite the manuscript when it is published.

Annotation software: [COWMATA Pro](https://github.com/zxq309/COWMATA-Pro).

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
