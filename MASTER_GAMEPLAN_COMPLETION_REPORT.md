# Master Gameplan Workbook — Completion Report

Download the workbook: [MASTER_GAMEPLAN_CHEAT_SHEET_WORKBOOK.xlsx](https://github.com/ndhammondsm/Opponent-Breakdown/raw/refs/heads/codex/defensive-self-scout-safe-formatted/MASTER_GAMEPLAN_CHEAT_SHEET_WORKBOOK.xlsx)

## 1. Opponent data imported

The supplied **Master Opponent Breakdown.xlsx** provided the ten requested completed output sections: MASTER_STRATEGY_CARD, MASTER_SIGNAL_BOARD, MASTER_SNAPSHOT, MASTER_IDENTITY_BOARD, MASTER_DD_CONCEPT_IDENTITY, MASTER_DD_PLAYCALL_IDENTITY, MASTER_DD_PERSONNEL_CONCEPT, MASTER_DD_STRUCTURE_CONCEPT, MASTER_DD_PER_PLAYCALL and MASTER_DD_STRUCTURE_PLAYCALL. MASTER_INPUT and the source FORMULA_CHECK are also retained as value snapshots with source-row references.

The eligible opponent sample contains 165 plays, 71 distinct actual playcalls, 56 strategy alerts and 559 statistical-support rows. Source usage, lift, p-values, statistical support and coach interpretations are retained where available.

## 2. Defensive data imported

The supplied **Master Defensive Self Scout.xlsx** provided DEF_INPUT, all 23 summary outputs—including DEF_SNAPSHOT, DEF_ALL, DEF_D&D, DEF_CONCEPT, personnel, structure and situational summaries—and DEF_FORMULA_CHECK. Normalized calculation flags preserve the source's existing eligibility, defensive success, explosive and context logic.

The defensive sample contains 274 clean reps and 13 excluded records. The source contains no actual offensive playcall field. Neither source workbook was changed or overwritten; their file hashes were checked after the build.

## 3. Tabs created

- START_HERE
- OPPONENT_IMPORT
- DEF_SELF_SCOUT_IMPORT
- CALL_LOOKUP_BOARD
- DEF_CALL_DECISION_SUPPORT
- HOT_CALL_RESPONSE_CARD
- GAMEPLAN_CHEAT_SHEET
- PRACTICE_SCRIPT_BOARD
- FORMULA_CHECK

START_HERE provides clickable navigation, weekly workflow, matching definitions, input guidance and formula-protection guidance. Import and formula cells are protected; coach selections, confirmed concept proxies and designated notes remain editable. There are no freeze panes, split panes or custom views. Light fills and readable text avoid the earlier black-fill issue. The printable cheat sheet fits two landscape Letter pages.

## 4. How CALL_LOOKUP_BOARD works

Select a situation, concept, minimum reps and opponent actual-play watch in the controls at the top. Read the quick candidate cards or jump to the concept, D&D + concept, exact-play watch, risk and sample sections. Detailed rows show reps, defensive success, explosives allowed, average gain, score, confidence, label, matching scope and coach caution.

Candidate ranking first considers the chosen minimum sample, then avoids problem/explosive labels when supported alternatives exist, then compares fit score and reps. The default minimum is four reps. A result below that threshold remains a sample watch rather than an established gameplan answer. Confidence is TRACK for 1–2 reps, LOW for 3, MEDIUM for 4–6 and HIGH for 7 or more.

Call Fit Score = ROUND(SuccessRate × 70 + (1 − ExplosiveRate) × 20 + MAX(0, MIN(1, (10 − AvgGain) / 10)) × 10, 1).

## 5. Concept and actual-play evidence

Defensive recommendations are **Concept Call-Fit Candidates**. MATCHING SCOPE distinguishes Exact Context Match, D&D + Concept Match, Personnel + Concept Match, Structure + Concept Match, Broad Concept Proxy, Sample Watch, Film Review Required and No Defensive Exact-Play Sample as applicable. Exact Context Match means the recorded situational/presentation/concept tags match; it does not mean exact offensive playcall proof.

Actual opponent playcalls appear in **OPPONENT EXACT PLAY WATCH / CONCEPT PROXY** sections and as film/practice alerts on the response card, cheat sheet and practice board. A uniquely tagged opponent play can suggest a concept proxy; it never establishes defensive exact-play performance.

Six ambiguous names—FLOOD, ZONE WK READ, VERTS TB SEAM, VERTS, STICKS and DOUBLE SPOT ARROW—have blank confirmed-concept fields and show **Film Review Required**. Ambiguity is retained even when a narrower D&D slice contains a single concept. A coach may confirm a concept after film review; the resulting recommendation remains a concept proxy. Clear scope and cautions are preferred over filling every row with a call.

## 6. External workbook links

Zero. Imported outputs are local value snapshots; calculations reference local data. The downloaded workbook stands alone. To refresh a new week, regenerate it from both updated completed source scouts, as explained on START_HERE.

## 7. Formula errors and wrapper functions

Zero visible formula errors and zero executable Google Sheets wrapper functions were found. ZIP integrity and all package XML passed validation.

## 8. FORMULA_CHECK and functional validation

FORMULA_CHECK works. Its 20 main checks show **17 PASS and 3 intentional REVIEW**: no defensive exact-play sample, six ambiguous mappings and an existing source missing-concept warning. These evidence limitations remain visible; checks were not weakened to hide them.

All **26,308 formula results** were compared with independently calculated expectations after a forced full LibreOffice recalculation. Disposable-copy tests confirmed that changing lookup controls updates the candidate, ambiguous plays remain unresolved, a deliberately injected formula error produces FAIL, and a hidden wrapped unsupported function is detected even when IFERROR suppresses its visible error. Six confidence boundaries and four score boundaries also passed. All nine tabs, all 35 required source sections and 80 internal navigation links were verified.

## 9. Microsoft Excel validation

Actual Microsoft Excel was unavailable. Excel open-without-repair was **not confirmed**. Validation comprised ZIP/XML/package checks, independent formula comparisons, forced LibreOffice recalculation, functional fault tests and print-layout inspection. The delivered file is the original generated and validated workbook, not the LibreOffice-resaved validation copy.

## 10. Final saved filename

**MASTER_GAMEPLAN_CHEAT_SHEET_WORKBOOK.xlsx** — 888,633 bytes.

Validated workbook SHA-256: `3157709cb03478ae85695dd7927481f3b96c76bd86dcae84cb4b6bb749d83f22`.

## 11. GitHub file path

Repository: `ndhammondsm/Opponent-Breakdown`  
Branch: `codex/defensive-self-scout-safe-formatted`  
Root file: `MASTER_GAMEPLAN_CHEAT_SHEET_WORKBOOK.xlsx`

Only this new workbook and this report are added by the delivery commit. Existing source and previously delivered workbooks are preserved.

## 12. GitHub download

[Direct workbook download](https://github.com/ndhammondsm/Opponent-Breakdown/raw/refs/heads/codex/defensive-self-scout-safe-formatted/MASTER_GAMEPLAN_CHEAT_SHEET_WORKBOOK.xlsx)

The completion message supplies the immutable commit-specific download link after confirming that the committed and downloaded bytes match the validated SHA-256 above.
