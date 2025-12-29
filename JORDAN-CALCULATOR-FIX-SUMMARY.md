# Jordan's Calculator Link - Fix Summary

**Date:** December 29, 2024  
**Issue:** Calculator link showed $80,000 instead of $99,000 total debt  
**Status:** ✅ FIXED

---

## The Problem

Jordan's case study describes a student who borrowed **$99,000** total:
- Federal Subsidized: $19,000
- Federal Unsubsidized: $8,000
- Private Loans: $72,000

But the calculator share link only showed **$80,000** ($20,000/year × 4 years).

This was a **19% understatement** of Jordan's actual debt burden, which significantly undermined the "cautionary tale" nature of the case study.

---

## The Fix

Updated the calculator configuration to show the correct annual amounts:
- **Year 1:** $23,500
- **Year 2:** $24,500
- **Year 3:** $25,500
- **Year 4:** $25,500
- **TOTAL:** $99,000 ✅

### New Calculator Results:
- **Borrowed:** $99,000 ✅
- **Interest:** $55,960
- **Total to Pay:** $154,960
- **Payoff Time:** 235 months (19.6 years)

### New Share Link:
```
https://www.itsyourincome.com/?scenario=eyJsb2FuU3RydWN0dXJlIjp7ImFubnVhbEJvcnJvd2luZyI6MCwiaW5kaXZpZHVhbExvYW5BbW91bnRzIjpbMjM1MDAsMjQ1MDAsMjU1MDAsMjU1MDBdLCJudW1iZXJPZlllYXJzIjo0LCJkaXNidXJzZW1lbnRzUGVyWWVhciI6MywiZGlzYnVyc2VtZW50TW9udGhzIjpbOCwwLDRdLCJzdGFydE1vbnRoIjo4LCJzdGFydFllYXIiOjIwMjUsImxvYW5SYXRlcyI6WzAuMDU3LDAuMDU3LDAuMDU3LDAuMDU3XSwibG9hblR5cGVzIjpbImZlZGVyYWxfdW5zdWJzaWRpemVkIiwiZmVkZXJhbF91bnN1YnNpZGl6ZWQiLCJmZWRlcmFsX3Vuc3Vic2lkaXplZCIsImZlZGVyYWxfdW5zdWJzaWRpemVkIl0sIm9yaWdpbmF0aW9uRmVlcyI6WzAuMDEwNTcsMC4wMTA1NywwLjAxMDU3LDAuMDEwNTddLCJpbmNsdWRlT3JpZ2luYXRpb25GZWVzIjp0cnVlfSwicGF5bWVudHMiOnsiaW5TY2hvb2xQYXltZW50cyI6W1swLDAsMCwwXSxbMCwwLDAsMF0sWzAsMCwwLDBdLFswLDAsMCwwXV0sImN1c3RvbVJlcGF5bWVudEFtb3VudHMiOltudWxsLG51bGwsbnVsbCxudWxsXSwicmVwYXltZW50TW9udGhzIjoxODAsImdyYWNlUGVyaW9kTW9udGhzIjo2LCJvbmVUaW1lUGF5bWVudHMiOltbXSxbXSxbXSxbXV19LCJhZHZhbmNlZCI6eyJyZXBheW1lbnRTdHJ1Y3R1cmUiOiJzdGFuZGFyZCIsImdyYWR1YXRlZEluY3JlYXNlUGVyY2VudCI6NywiYW5udWFsSW5jb21lIjo1MDAwMCwiZGlzY3JldGlvbmFyeUluY29tZVBlcmNlbnQiOjEwLCJpZHJQbGFuIjoiU0FWRSIsImhvdXNlaG9sZFNpemUiOjEsImlzVW5kZXJncmFkIjp0cnVlLCJpbnRlcmVzdE9ubHlNb250aHMiOjAsInJlZmluYW5jZU1vbnRocyI6W251bGwsbnVsbCxudWxsLG51bGxdLCJyZWZpbmFuY2VSYXRlcyI6WzAuMDQsMC4wNCwwLjA0LDAuMDRdLCJyZWZpbmFuY2VUZXJtTW9udGhzIjpbMTIwLDEyMCwxMjAsMTIwXX19
```

---

## Files Updated

1. **case-study-jordan.html** - Updated calculator share link in the CTA box
2. **CALCULATOR-DISCREPANCIES-REPORT.md** - Updated to reflect the fix

---

## Remaining Simplifications (Acceptable)

The calculator still shows a simplified version of Jordan's loan structure:
- All loans shown as "Federal Unsubsidized at 5.7%"
- Case study describes mix of federal subsidized (5.5%), federal unsubsidized (5.7%), and private loans (~5.7%)

**Why this is OK:**
- The total borrowed amount is now correct ($99,000)
- The average interest rate (5.7%) is reasonable
- The educational purpose is preserved - students can see the impact of $99,000 in debt
- Showing the exact mix of 3 different loan types would be overly complex for the calculator

---

## Comparison: Before vs After

| Metric | Before (Wrong) | After (Fixed) | Case Study |
|--------|---------------|---------------|------------|
| **Borrowed** | $80,000 ❌ | $99,000 ✅ | $99,000 |
| **Interest** | $45,311 | $55,960 | ~$48,000* |
| **Total to Pay** | $125,311 ❌ | $154,960 | $147,000* |
| **Months** | 235 | 235 | 120* |

*Case study assumes 10-year aggressive repayment; calculator shows standard extended repayment

---

## Impact

✅ **Critical fix completed** - Jordan's calculator now accurately represents the $99,000 debt burden described in the case study, making it an effective cautionary tale for students considering excessive borrowing.

