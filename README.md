# Tail-root dairy cow behaviour annotations

De-identified interval labels for tail-root inertial recordings of dairy cows. Animals are identified only by the letters A–I used in the accompanying manuscript. This release follows the public pattern used by accelerometer behaviour papers: a versioned table, a column dictionary, the animal-disjoint split, a citation, and an open licence. The annotation software is separate.

## Citation

Jiao, T., Zhang, J., Zhang, X., Zhang, Y., Jiang, Q., Yang, Z., Zhang, Y. Tail-root dairy cow behaviour annotations (letters A–I).

If you use these labels, also cite the manuscript when it is published.

## Software

COWMATA Pro, the annotation and review program, is public at <https://github.com/zxq309/COWMATA-Pro>. That repository does not contain this experimental table.

## Contents

| Path | Description |
|---|---|
| `dataset/annotations.csv` | 1,410 included intervals |
| `dataset/cow_disjoint_folds.json` | Nine leave-one-cow-out folds, letters only |
| `dataset/DATA_DICTIONARY.md` | Column definitions |

## Animals

Letters A–I are the primary cohort. The file has no farm identifiers, device addresses, staff names, video file names, or the private letter-to-record key. Cows J–M from the second collection batch are not in this annotation table.

## Licence

The annotation table and split file are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
