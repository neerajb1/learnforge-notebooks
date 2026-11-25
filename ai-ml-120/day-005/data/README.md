# Day 5 datasets

| File | Rows | What it is |
| --- | --- | --- |
| `student_data_clean.csv` | 8 | Day 4's cleaned file, unchanged. Used in Sections 1–2. |
| `student_data_150.csv` | 150 | The same 8 students (`Source` = `original`) plus 142 **synthetic** students (`Source` = `synthetic`, IDs G001–G142). Used in Sections 3–6. |

The synthetic students are simulated educational data, not observations of real students. They were generated once
by `scripts/generate_student_data_150.py` with a fixed seed, so every learner sees the same values; the script
reproduces this file byte for byte, and a test checks that. Their relationships (for example, more study hours with
higher exam scores) are plausible but deliberately noisy. Use them to practise exploratory data analysis, not as
evidence about how students learn.
