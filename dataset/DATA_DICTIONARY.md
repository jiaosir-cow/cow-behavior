# Column dictionary

`dataset/annotations.csv`

| Column | Meaning |
|---|---|
| `public_id` | Row identifier in this public file, `P0001` onward |
| `cow` | Animal letter, A–I |
| `layer` | Annotation layer, such as `body_state`, `posture_transition`, or `objective_event` |
| `label` | Original Chinese behaviour name |
| `label_en` | English behaviour name |
| `code` | Stable behaviour code, such as `STANDING`, `LYING`, `WALKING`, `FEEDING`, `STANDING_UP`, `LYING_DOWN` |
| `protocol` | Label protocol, `v3` or `v4` |
| `t_start_rel_ms` | Start time relative to the recording segment, milliseconds |
| `t_end_rel_ms` | End time relative to the recording segment, milliseconds |
| `duration_ms` | Interval duration, milliseconds |
| `session_in_cow` | Session index within that cow. It does not encode a clock time or a device |

`dataset/cow_disjoint_folds.json` lists nine folds. Each fold names the test, validation, and training cows by letter. A cow listed as test does not appear in that fold's training or validation lists.
