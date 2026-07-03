# Development Log

## 2026-07-02

Continued the documentation cleanup by fixing the File Structure example in the top-level README so it reflects how the example projects are actually laid out. The scene outline files shown in the tree used an old naming scheme (scenes_act_1_chN.md) when the real files are named scenes_chapter_N.md, and the story_outline_files/ listing was missing characters_enhanced.md, a file every example project contains alongside characters.md.

**Decisions & notes:** Documentation-only change, following on from the chapter-count fix the day before; the README's example tree is now aligned with the real repo layout rather than an earlier naming convention.

## 2026-07-01

Corrected two stale chapter counts in the top-level README after a full-audit docs sweep caught them disagreeing with the actual repository contents. Starbound Legacy was listed as 13 chapters but only has 12 files (its outline and combined novel both end at Chapter 12: New Horizons), and Project Chimera was listed as 26 but has 25 (its outline runs Chapters 1-25). Word counts were already accurate and left untouched.

**Decisions & notes:** Documentation-only fix; no story or content files changed. The discrepancies were counting errors in the README rather than missing chapters, so the fix was to align the numbers with what's on disk.
