# Glossary (Repo Excerpt)

For the full glossary, see: https://github.com/instance001/Whatisthisgithub/blob/main/GLOSSARY.md

This file contains only the glossary entries for this repository. Mapping tag legends and global notes live in the full glossary.

## Frisian_Cadence_PID_Control_Loop
| Term | Alternate term(s) | Alt map | External map | Relation to existing terminology | What it is | What it is not | Source |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Frisian Cadence | Frisian cadence metaphor family | ~ | ~ | Soft PID-like pacing method | Metaphor families used as proportional/integral/derivative cues (metaphor nudges, reflective echoes, human pauses) to stabilize long-form generation pace | Not an actual control system implementation; metaphor-guided prompting only | Frisian_Cadence_PID_Control_Loop/Frisian_Cadence_PID_Control_Loop_Text_v0.2.txt |
| Frisian Pacing Index (FPI) | ΔFPI | ~ | ~ | Stability metric | ΔFPI = k × (σ₀ − σ₁)/σ₀ ± ε, measuring token-rate variance reduction after cadence | Not a standardized ML metric; depends on run logging | Frisian_Cadence_PID_Control_Loop/Frisian_Cadence_PID_Control_Loop_Text_v0.2.txt |
| Conflict Compression Ratio (CCR) | CCR | = | ~ | Coherence metric | CCR = 1 − (edit_distance_with_cadence / edit_distance_baseline); higher means fewer contradictions post-cadence | Not a semantic accuracy guarantee; sensitive to baseline choice | Frisian_Cadence_PID_Control_Loop/Frisian_Cadence_PID_Control_Loop_Text_v0.2.txt |
| Cadence usage recipe | cadence recipe | ~ | ~ | Prompting protocol | Steps: seed cadence family, mirror echoes, insert pauses, log σ/cosine/interrupt/errors per interval, compute ΔFPI & CCR vs baseline | Not automated control; requires manual setup and logging | Frisian_Cadence_PID_Control_Loop/Frisian_Cadence_PID_Control_Loop_Text_v0.2.txt |
