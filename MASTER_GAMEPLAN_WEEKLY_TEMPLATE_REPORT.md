# Reusable Weekly Gameplan Template — Completion Report

The template refreshes from two local value pastes. You do not need Codex, macros, Power Query or external workbook links each week. START_HERE is the instruction manual. Keep a clean master and use Save As for each week's gameplan.

## Download all three working files

- [MASTER_GAMEPLAN_CHEAT_SHEET_TEMPLATE.xlsx](https://github.com/ndhammondsm/Opponent-Breakdown/raw/refs/heads/codex/defensive-self-scout-safe-formatted/MASTER_GAMEPLAN_CHEAT_SHEET_TEMPLATE.xlsx)
- [MASTER_OPP_BREAKDOWN_WITH_GAMEPLAN_EXPORT.xlsx](https://github.com/ndhammondsm/Opponent-Breakdown/raw/refs/heads/codex/defensive-self-scout-safe-formatted/MASTER_OPP_BREAKDOWN_WITH_GAMEPLAN_EXPORT.xlsx)
- [DEFENSIVE_SELF_SCOUT_WITH_GAMEPLAN_EXPORT.xlsx](https://github.com/ndhammondsm/Opponent-Breakdown/raw/refs/heads/codex/defensive-self-scout-safe-formatted/DEFENSIVE_SELF_SCOUT_WITH_GAMEPLAN_EXPORT.xlsx)

The final delivery message contains verified, immutable commit-specific links. Files are at the repository root in `ndhammondsm/Opponent-Breakdown`, branch `codex/defensive-self-scout-safe-formatted`.

## 1. Can the married workbook refresh by copy/paste?

**Yes.** It discovers the pasted week's concepts, defensive hot calls, D&D groups and actual opponent play names with local formulas. CALL_LOOKUP_BOARD, DEF_CALL_DECISION_SUPPORT, HOT_CALL_RESPONSE_CARD, GAMEPLAN_CHEAT_SHEET, PRACTICE_SCRIPT_BOARD and FORMULA_CHECK recalculate from the imports. New names do not require a rebuild. The included records are a demonstration sample; replace both imports for your week.

Use desktop Excel with Automatic calculation. Current Microsoft 365 / Excel 2021 or later is recommended. If results appear stale, use Calculate Now; Ctrl+Alt+F9 forces a full recalculation in Windows Excel. The workbook uses ordinary local formulas and named ranges rather than a dynamic-array or external-refresh dependency.

## 2–3. Exactly what to copy from Opponent Breakdown and where to paste

Open **MASTER_OPP_BREAKDOWN_WITH_GAMEPLAN_EXPORT.xlsx**. Update raw inputs on MASTER_INPUT in columns **A:B and D:I**, leaving C and J:O helpers intact. When replacing a sample, clear previous raw inputs that should no longer be included. Keep source input in rows 2–1000, recalculate and review the source FORMULA_CHECK.

Go to **OPP_GAMEPLAN_EXPORT**. Set **B4** to your week/opponent key. Click the Name Box, type **GAMEPLAN_EXPORT** and press Enter; it selects **A1:R1100**. Copy that entire range, including headers, blank rows and the END marker.

In **MASTER_GAMEPLAN_CHEAT_SHEET_TEMPLATE.xlsx**, open **OPPONENT_IMPORT**, click **A1**, and choose **Paste Special → Values**. The destination is exactly **OPPONENT_IMPORT!A1:R1100**. Do not use an ordinary formula/format paste, select only visible plays, or stack weeks underneath each other.

The export includes normalized opponent records with source eligibility/scoring flags; the four source strategy-alert families for all 17 D&D situations; usage, lift, p-values, statistical support and coach interpretations from the selected source signal rows; and source-section, source-check and capacity markers. Identity, concept and exact-play watch summaries recalculate locally from these values.

## 4–5. Exactly what to copy from Defensive Self Scout and where to paste

Open **DEFENSIVE_SELF_SCOUT_WITH_GAMEPLAN_EXPORT.xlsx**. Update raw inputs on DEF_INPUT in columns **A:F and K:L**, leaving G:J and M:O helpers intact. Use the history window your staff intends to scout; clear old raw inputs when replacing that window. Keep source input in rows 2–1000, recalculate and review DEF_FORMULA_CHECK.

Go to **DEF_GAMEPLAN_EXPORT**. Set **B4** to the SAME week/opponent key used in the opponent export. Use the Name Box **GAMEPLAN_EXPORT** to select **A1:R1100**, then copy the entire range including all blank rows and the END marker.

In the template, open **DEF_SELF_SCOUT_IMPORT**, click **A1**, and choose **Paste Special → Values**. The destination is exactly **DEF_SELF_SCOUT_IMPORT!A1:R1100**.

The export carries source-normalized D&D, personnel, structure, concept and hot-call tags; original results and gains; existing clean/excluded, success and explosive flags; play groups and source cautions; and source-section/check/capacity markers. Defensive summaries recalculate locally. The source scoring rules are not rewritten.

## Finish the weekly process

1. Set **START_HERE!B6** to that same week/opponent key.
2. Wait for calculation and open **FORMULA_CHECK**.
3. Fix FAIL results. Read REVIEW cautions; Film Review Required is an evidence limit, not a broken formula.
4. Open **CALL_LOOKUP_BOARD** and choose this week's situation, concept, minimum reps and actual-play watch. Old selections can become absent after refresh; select a current value from the dropdown.
5. Review **HOT_CALL_RESPONSE_CARD**, then **GAMEPLAN_CHEAT_SHEET** and **PRACTICE_SCRIPT_BOARD**. Print the selected cheat sheet in landscape Letter; it is two pages.
6. Clear old manual staff/gameplan notes, add this week's notes, and save the weekly copy.

A full A1:R1100 value paste clears last week's trailing imported plays. Week-key checks compare the batch you declare; they cannot independently prove that you updated the source data by date.

## 6. Were source export tabs added?

**Yes.** OPP_GAMEPLAN_EXPORT was added to a new opponent copy, and DEF_GAMEPLAN_EXPORT was added to a new defensive copy. Both define the same easy-to-select GAMEPLAN_EXPORT range. The original uploads were not overwritten or changed. All existing source worksheet XML—including formulas, view settings and DEF_FORMULA_CHECK tests—is byte-identical in the delivered copies; only the new export tab and required package/style/name configuration were added. DEF_4TH's original filter remains intact.

## Coach-facing logic and instructions

All nine requested tabs are present. START_HERE explains the two scouts, exact copy/paste steps, inputs and helpers, each coaching board, PASS / REVIEW / FAIL, sample limits, protection, troubleshooting and film confirmation. Imports are green unlocked paste areas; helpers and formulas are protected without a password against accidental edits. Coach controls and note areas are yellow. No freeze panes, split panes or custom views were added.

Defensive recommendations remain **Concept Call-Fit Candidates** or explicitly scoped context signals. Opponent actual plays remain **Opponent Exact-Play Watches** or **Concept Proxies**. No defensive actual-play field is available, so none of these metrics proves a defensive answer against an exact play. MATCHING SCOPE is visible on the lookup and response card. Globally ambiguous names remain Film Review Required even when one D&D slice contains a unique concept; no match is forced.

Confidence remains TRACK at 1–2 reps, LOW at 3, MEDIUM at 4–6 and HIGH at 7 or more. The default candidate minimum is four reps. Call Fit Score retains 70% defensive success, 20% explosive prevention and 10% capped average-gain control. Low samples remain watches even when their score is high. The workbook guides the football conversation and does not automatically call defenses.

## 7. External workbook links

**Zero.** There are no external workbook formula references or external-link package parts. No macros or Power Query connections are required. Weekly calculations work from pasted local values.

## 8. Does FORMULA_CHECK work?

**Yes.** The delivered sample has **20 PASS and four intentional REVIEW** results, with no FAIL results. REVIEW covers no defensive exact-play sample, six ambiguous opponent names, one missing defensive concept and a sample-watch summary containing more than 100 groups. The detail support keeps full group coverage; the summary shows its first 100 items and warns about the limit.

Checks cover populated imports and declared week keys, complete export/schema/end markers, values-only pastes, board population, defensive rep reconciliation, required source sections and tabs, formula errors, Google wrappers, external workbook formulas, data cautions, capacity, confidence boundaries and score boundaries.

Validation passed:

- Forced full LibreOffice recalculation of the source export copies and the template.
- Independent metrics and candidate rankings for **2,019 populated defensive context/call groups** across ten support scopes.
- **17,103 opponent and 18,012 defensive export formula results** compared with expected source values.
- A smaller test week with entirely new calls/concepts and literal punctuation in an ambiguous play name: full value pastes cleared the old week and updated all coaching boards.
- A concept appearing ONLY on defensive source row 1000 reached the dropdown and support calculations.
- A new four-rep NEW FIT candidate produced a score of 99 and MEDIUM confidence; the ambiguous exact play remained unresolved.
- Disposable negative tests detected wrong week keys, incomplete exports, formula pastes, visible formula errors and an unsupported Google wrapper hidden by IFERROR.
- Zero visible formula errors, zero executable Google wrapper functions, zero external workbook links, valid ZIP/XML, valid cell-style references, and unchanged original uploads.
- A two-page landscape cheat-sheet render, with section 5 kept together and section 6 starting page 2.

## 9. Was Microsoft Excel validation available?

**No.** Actual Microsoft Excel was unavailable, so Excel opening without repair is **not confirmed**. Validation used forced LibreOffice recalculation, independent calculations, functional refresh/fault tests, print inspection and ZIP/XML/package checks. Delivered files retain their generated/source worksheet structure; recalculated caches were copied back without resaving original source worksheets or changing their view settings.

## 10. Final filenames, paths and hashes

All three workbooks are committed at the repository root on the branch above. Their direct download links appear at the top of this report.

| File | Bytes | Validated SHA-256 |
| --- | ---: | --- |
| `MASTER_GAMEPLAN_CHEAT_SHEET_TEMPLATE.xlsx` | 5,737,179 | `1830e2192fcb6780c58b923b528ef76e632c4ad35c4825e19ba5be622e659660` |
| `MASTER_OPP_BREAKDOWN_WITH_GAMEPLAN_EXPORT.xlsx` | 3,876,948 | `3708fd717648f7d28857c425ba6a5fd354446c6f505c9a23432b84d0b4068819` |
| `DEFENSIVE_SELF_SCOUT_WITH_GAMEPLAN_EXPORT.xlsx` | 5,714,054 | `3c4c3a737bb84d14880e5b6183a73d2a2f1cfc5c4f66fa5962199e750fd37ff3` |

The completion message confirms that the committed GitHub files and downloaded bytes match these validated files.
