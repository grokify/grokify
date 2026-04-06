# GitHub Statistics - grokify

Public repository contribution statistics.

## Q1 2026 Summary

| Metric | Total |
|--------|------:|
| Commits | 3,561 |
| Releases | 304 |
| Additions | 1,696,636 |
| Deletions | 689,678 |
| Net Additions | 1,006,958 |
| Repos Contributed | 249 (unique monthly) |

## Monthly Breakdown

### Commits

| Month | Commits | Repos |
|-------|--------:|------:|
| January 2026 | 1,091 | 72 |
| February 2026 | 984 | 82 |
| March 2026 | 1,486 | 95 |
| **Q1 Total** | **3,561** | |

### Code Changes

| Month | Additions | Deletions | Net |
|-------|----------:|----------:|----:|
| January 2026 | 744,988 | 294,379 | +450,609 |
| February 2026 | 387,169 | 97,226 | +289,943 |
| March 2026 | 564,479 | 298,073 | +266,406 |
| **Q1 Total** | **1,696,636** | **689,678** | **+1,006,958** |

### Releases

| Month | Releases |
|-------|-------:|
| January 2026 | 108 |
| February 2026 | 88 |
| March 2026 | 108 |
| **Q1 Total** | **304** |

## Monthly Details

### March 2026

- **Commits:** 1,486 across 95 repositories
- **Releases:** 108
- **Lines changed:** +564,479 / -298,073 (net +266,406)

### February 2026

- **Commits:** 984 across 82 repositories
- **Releases:** 88
- **Lines changed:** +387,169 / -97,226 (net +289,943)

### January 2026

- **Commits:** 1,091 across 72 repositories
- **Releases:** 108
- **Lines changed:** +744,988 / -294,379 (net +450,609)

---

## Data Source

Statistics generated from GitHub API using [gogithub](https://github.com/grokify/gogithub).

**Query parameters:**

- Visibility: public
- Include releases: yes

**Raw data files:**

- [grokify_github_public_2026-01.json](grokify_github_public_2026-01.json)
- [grokify_github_public_2026-02.json](grokify_github_public_2026-02.json)
- [grokify_github_public_2026-03.json](grokify_github_public_2026-03.json)

**Regenerate command:**

```bash
gogithub profile --user grokify \
  --from 2026-01-01 --to 2026-01-31 \
  --visibility public --include-releases \
  --output-monthly-dir ./stats/
```
