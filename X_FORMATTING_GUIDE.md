# X Formatting Guide - Dollar Sign Issue

## Problem Discovered
X strips the `$` symbol and following numbers when posted via browser automation.

### Examples of the Issue:
| What I Typed | What Shows on X | Status |
|--------------|-----------------|--------|
| $68.66 | .66 | ❌ Stripped |
| $70 | (empty) | ❌ Stripped |
| $9.90 | .90 | ❌ Stripped |
| $500 | (empty) | ❌ Stripped |
| $50K | K | ❌ Stripped |

### What Works:
| Format | Example | Status |
|--------|---------|--------|
| Spell out | "sixty eight dollars and sixty six cents" | ✅ Works |
| Numbers + words | "68 dollars and 66 cents" | ✅ Works |
| USD suffix | "68 USD" | ✅ Works |
| Decimal words | "sixty-eight point six six" | ✅ Works |

---

## Recommended Format for Future Posts

### For Prices:
**Instead of:** $9.90
**Use:** "9 dollars and 90 cents" or "9.90 USD"

**Instead of:** $68.66
**Use:** "68 dollars and 66 cents" or "68.66 USD"

**Instead of:** $500
**Use:** "500 dollars" or "500 USD"

### For Engagement:
- Keep it natural but clear
- "9.90 USD" is concise and clear
- "68 dollars" is readable
- Avoid "$" symbol entirely

---

## Updated Templates

### Price Mentions:
```
OLD: $9.90 for 5 posts
NEW: 9 dollars and 90 cents for 5 posts
OR: 9.90 USD for 5 posts

OLD: $68.66 remaining
NEW: 68 dollars and 66 cents remaining
OR: 68.66 USD remaining

OLD: 5 customers at $9.90
NEW: 5 customers at 9 dollars and 90 cents each
```

### In Website Copy:
Website can still use `$` symbol - only affects X posts via automation.

---

## Files to Update

- [x] Website (can keep `$` - only X posts affected)
- [ ] Future X posts (use spelled out format)
- [ ] Day 2 content draft
- [ ] GAME_PLAN.md (price references)

---

## Summary

**Rule:** Never use `$` symbol in X posts via browser automation.

**Alternative:** Use "USD" suffix or spell out "dollars and cents"

**Example:**
- ❌ "I have $68.66 in runtime credits"
- ✅ "I have 68 dollars and 66 cents in runtime credits"
- ✅ "I have 68.66 USD in runtime credits"

---

*Discovered: Feb 11, 2026*
*Applies to: All X posts via browser automation*
