# FOLLOW-UP EDITORIAL REVIEW: PCI for Stable Angina Evidence Analysis

**Reviewer**: Journal Editor (Second Review)
**Date**: 2025-11-17
**Document**: pci-stable-angina-evidence.md (Revised Version)
**Previous Recommendation**: MAJOR REVISION REQUIRED
**Current Recommendation**: **MINOR REVISION REQUIRED**

---

## OVERALL ASSESSMENT

The authors have made substantial improvements to address the major concerns from the initial review. The document is now significantly more balanced, includes critical missing trials (ORBITA-2, FAME-2), uses appropriate statistical terminology, and maintains a professional scientific tone.

**However**, several issues remain that must be addressed before acceptance:

---

## REMAINING ISSUES TO FIX

### 1. CRITICAL: Inconsistent NNH Values

**Severity**: ⚠️ **MUST FIX**

**Problem**: The document contains **contradictory NNH values** in two different sections:

**Early section (line 48)**:
> **Combined NNH**: **20-50** (2-5% risk of major complications)

**Later section (line 341)**:
> | **Major complications (composite)** | **~2-3%** | **NNH ≈ 33-50** |

**Issue**: These cannot both be correct. The document claims:
- Line 48: 2-5% complications → NNH 20-50
- Line 341: 2-3% complications → NNH 33-50

**The Math**:
- If complications = 2%, then NNH = 1/0.02 = 50
- If complications = 3%, then NNH = 1/0.03 = 33
- If complications = 5%, then NNH = 1/0.05 = 20

The later section (line 341) is correct and properly cited. The early section (line 48) appears to be a remnant from the original document.

**Required Action**:
**Option 1 (Recommended)**: Remove the entire early "Procedural Risks and Complications" section (lines 44-58). It's redundant with the more detailed and accurate section that appears later (lines 328-356).

**Option 2**: Update line 48 to match the corrected values:
- Change "2-5% risk" to "2-3% risk"
- Change "NNH: 20-50" to "NNH ≈ 33-50"
- Add the same citations as the later section

**Impact**: This is a mathematical error that undermines credibility. Must be fixed.

---

### 2. MODERATE: Redundant "Procedural Risk" Sections

**Severity**: ⚠️ **SHOULD FIX**

**Problem**: Procedural risks and complications are discussed in **two separate sections**:

1. **Early section** (lines 44-58): Brief, lacks detail, appears before any trial evidence
2. **Later section** (lines 328-356): Detailed, properly cited, integrated into evidence summary

**Issues with Current Organization**:
- The early section appears BEFORE the trials are presented, so readers don't have context
- The early section is superficial (just lists complications)
- The later section is comprehensive (includes rates, sources, modern techniques)
- Having both is redundant and confusing

**Recommended Action**: **Remove the early section** (lines 44-58) entirely.

**Rationale**:
- The detailed procedural risk assessment (lines 328-356) is better positioned after presenting trial evidence
- It includes specific complication rates with sources
- It's integrated with the evidence summary
- Discussing harms before presenting evidence is poor organization

**Alternative**: If you want to keep an early mention of risks, reduce it to 2-3 sentences noting that PCI has procedural risks that will be detailed after presenting the evidence.

---

### 3. MODERATE: Duplicate "Historical Context" Sections

**Severity**: ⚠️ **SHOULD FIX**

**Problem**: Two sections titled "Historical Context" appear at different locations:

1. **Line 12**: "The Historical Context: The 'Plaque-Busting' Doctrine"
   - Discusses the 1990s-2000s foundation of interventional cardiology
   - Covers RITA-2, original evidence base, the resulting doctrine

2. **Line 360**: "Historical Context: Evolution of Medical Therapy and Evidence"
   - Discusses historical control bias in early trials
   - Covers causal model evolution
   - Discusses how statins changed the paradigm

**Issue**: Having two sections with the same primary title is confusing. While the content is different, the naming suggests they should be one integrated section.

**Recommended Action**:

**Option 1**: Consolidate into a single comprehensive "Historical Context" section that covers both topics

**Option 2**: Rename the second section to better reflect its content:
- Change "Historical Context: Evolution of Medical Therapy and Evidence"
- To: "**The Paradigm Shift: How Medical Therapy Changed the Evidence**"
- Or: "**Why Old Evidence Became Obsolete: The Medical Therapy Revolution**"

**Option 3**: Make the second section a subsection of the first:
```
## The Historical Context: The "Plaque-Busting" Doctrine
### [existing subsections]
### Evolution of Medical Therapy and the Evidence Paradigm Shift
```

---

### 4. MINOR: Organizational Flow

**Severity**: ℹ️ **OPTIONAL BUT RECOMMENDED**

**Current Structure**:
```
1. Executive Summary
2. Historical Context: Plaque-Busting Doctrine
3. Procedural Risks [BEFORE showing evidence]
4. Evolution of Medical Therapy
5. Major Clinical Trials
6. Summary of Trial Evidence [includes ANOTHER procedural risk section]
7. Historical Context: Evolution of Medical Therapy [redundant with #4?]
8. Methodological Lessons
9. Limitations
10. Current Guidelines
11. Understanding Common Sense Intuition
12. Clinical Implications
13. References
14. Summary and Clinical Recommendations
```

**Issues**:
- Procedural risks appear before trials (reader has no context)
- Historical context split across two sections
- "Evolution of Medical Therapy" appears twice (line 62 and line 360)
- Having TWO summary sections (#6 and #14) is redundant

**Recommended Structure**:
```
1. Executive Summary
2. Historical Context (consolidated)
   - The "plaque-busting" doctrine
   - Evolution of medical therapy
   - Why the paradigm shifted
3. Major Clinical Trials
4. Summary of Evidence (with procedural risks integrated)
5. Methodological Lessons
6. Limitations and Uncertainties
7. Current Guidelines
8. Clinical Recommendations
9. References
```

**Impact**: Would improve readability and reduce redundancy.

---

### 5. MINOR: Methodological Section Placement

**Severity**: ℹ️ **OPTIONAL**

**Current Placement**: "Methodological Lessons" appears at line 393, AFTER "Historical Context: Evolution of Medical Therapy"

**Issue**: This creates an odd flow where you go:
- Trial Evidence → Summary → Historical Context → Methodological Lessons → Limitations

**Suggested Reordering**:
- Trial Evidence → Summary → Methodological Lessons → Historical Context (why old model failed) → Limitations

**Rationale**: Methodological lessons flow more naturally from the trial evidence, while historical context explains why the old model became obsolete.

---

### 6. VERY MINOR: Section Title Consistency

**Severity**: ℹ️ **OPTIONAL**

Some section titles use different formatting:

- "The Historical Context: The 'Plaque-Busting' Doctrine" (with article "The")
- "Procedural Risks and Complications" (no article)
- "The Evolution of Optimal Medical Therapy" (with article "The")
- "Major Clinical Trials" (no article)

**Recommendation**: Choose one style and apply consistently throughout.

---

## STRENGTHS OF REVISED VERSION

### Excellent Improvements:

1. ✅ **ORBITA-2 included**: Comprehensive coverage with appropriate interpretation
2. ✅ **FAME-2 included**: Well-integrated discussion of FFR-guided approach
3. ✅ **Statistical terminology fixed**: "NNT = infinity" removed; proper language used
4. ✅ **Tone dramatically improved**: Professional, balanced, scientific
5. ✅ **Patient selection addressed**: Detailed discussion of when PCI is/isn't appropriate
6. ✅ **Limitations section added**: Transparent about trial limitations and uncertainties
7. ✅ **Conclusions balanced**: Evidence-based recommendations, not advocacy
8. ✅ **Citations improved**: Specific references added
9. ✅ **Evidence summary table**: Excellent visual comparison of trials

### Particularly Strong Sections:

**Lines 301-326** - Evidence summary table and conclusions by category: This is excellent. Clear, organized, evidence-based.

**Lines 423-488** - Limitations and Areas of Uncertainty: Outstanding transparency about what we know and don't know.

**Lines 419-481** - Clinical Approach to Stable Angina: Practical, evidence-based guidance that clinicians can actually use.

**Lines 178-217** - ORBITA-2 section: Well-presented with appropriate context about difference from ORBITA.

**Lines 250-293** - FAME-2 section: Good discussion of FFR-guided approach and its implications.

---

## COMPARISON TO ORIGINAL VERSION

### What Changed (For the Better):

| Aspect | Original | Revised |
|--------|----------|---------|
| **Trials included** | 3 | 6 |
| **Tone** | Polemical | Balanced |
| **Statistical accuracy** | "NNT = ∞" (incorrect) | Proper terminology |
| **Patient selection** | Minimal | Comprehensive |
| **Limitations** | None | 66 lines |
| **Clinical guidance** | "Statins not stents" | Individualized algorithm |
| **Acknowledgment of PCI benefit** | None | Yes (ORBITA-2, FAME-2) |

---

## REQUIRED CHANGES FOR ACCEPTANCE

### Must Fix:
1. ✅ **Fix NNH inconsistency** (line 48 vs line 341)
   - Either remove early section OR update to match corrected values

### Should Fix:
2. ✅ **Remove redundant procedural risk section** (lines 44-58)
3. ✅ **Rename or consolidate duplicate "Historical Context" sections**

### Optional (Recommended):
4. ⭕ Consider reorganizing to improve flow
5. ⭕ Standardize section title formatting

---

## EDITORIAL DECISION

**Previous Verdict**: MAJOR REVISION REQUIRED

**Current Verdict**: **MINOR REVISION REQUIRED**

**Rationale**: The authors have successfully addressed all major scientific and methodological concerns. The remaining issues are primarily organizational and one mathematical inconsistency (NNH). These are straightforward to fix.

**Expected Timeline**: These minor revisions should take <1 hour to complete.

**Next Steps**:
1. Fix the NNH inconsistency (critical)
2. Remove redundant procedural risk section (recommended)
3. Address duplicate historical context sections (recommended)
4. Resubmit for final review

**Anticipated Final Verdict**: ACCEPT (pending minor revisions)

---

## SUMMARY FOR AUTHORS

**Congratulations on a significantly improved manuscript.** You have successfully:
- Added critical missing evidence (ORBITA-2, FAME-2)
- Corrected statistical misuse
- Adopted appropriate scientific tone
- Provided balanced, evidence-based conclusions
- Added comprehensive limitations section

**One critical issue remains**: The NNH value inconsistency (line 48 vs 341). This must be fixed.

**Two organizational issues should be addressed**: Redundant procedural risk section and duplicate historical context sections.

With these minor revisions, the manuscript will be suitable for publication.

---

**Reviewer**: Journal Editor
**Date**: 2025-11-17
**Recommendation**: **MINOR REVISION REQUIRED**
**Anticipated Final Status**: **ACCEPT** (pending fixes)
