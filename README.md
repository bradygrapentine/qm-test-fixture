# qm-test-fixture

Fixture PRs for live-testing PR Quick Merge. Each PR exercises a different
state combination (clean, behind, draft, large, comments, failing CI).

| PR | What to look for |
|----|------------------|
| Clean small | Ready highlight + Squash/Merge/Rebase buttons + S size badge |
| Behind base | "Update" button + auto-rebase toggle |
| Draft | Hide drafts toggle catches it; size XS |
| Large diff | XL size badge in warning color |
| With comments | Comments badge + jump-to-comments link |
| Failing CI | Red ✕ in CI dot + failing-check tooltip |

After testing, close all with the bulk-close action (also a test target).
