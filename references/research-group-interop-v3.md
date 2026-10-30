# Optional v3 Research-Group Interface

Load only on cross-Skill tasks. This file is an optional interface, not proof of installed agents or shared storage.

**Own:** Comparison against explicitly identified target-journal benchmark papers and journal guidance.
**Exclude:** Predicting acceptance probability or inventing current journal preferences.
**Chinese triggers:** 期刊差距分析、目标期刊对标、论文期刊匹配.
**English triggers:** journal gap analysis, journal benchmark comparison.
**Do not trigger:** unrelated workflows, generic rewording or needless full-pipeline invocation.
**Optional route:** ai-paper-editor for editorial architecture; ai-strict-reviewer for scientific evidence gaps. Only when accessible and materially useful.

**Benchmark safeguards:** record date window, sample/source locators, inclusion reasoning and source access. State when the recent journal corpus was not actually retrieved. Never infer editorial probability from a small sample.

## Evidence-first issue handoff

`ID | owner | file/version/location | precise issue | direct source evidence | source status | assessment | local Severity/Impact or urgency | action | author decision | state`.

Source status `Reported / Documented / Independently checked / Not available`; assessment `Confirmed / Reasoned inference / Unverified`. Keep scientific **Severity** separate from document **Impact**. Workflow state `Open / Waiting for evidence / Awaiting author / Resolved / Recheck needed`. Never claim a result, upload, edit, specialist call or confirmation not actually performed.

## Share minimal ledger context

If useful and actually provided or authorised, pass `Claim ID, Data ID, exact source/figure/table, metric and unit, case/baseline, source version, computation version, verification status, linked issue ID`; do not assume auto-sync. Assign one primary issue owner, reuse prior located evidence if unchanged, and rerun only affected checks after an approved change. Default flexible flow: literature → approved execution → scientific review → editing → quality inspection. Standalone tasks do not require this sequence.
