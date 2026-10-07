# ATP003 — Kyverno Certified Associate (KCA)

An Astrona **training path**: a course track that groups training series
(`ATSxxx`) as its domains. Each stage in `path.yaml` is one exam domain and
points at the repository that teaches it:

| Stage | Domain | Weight | Content |
| --- | --- | --- | --- |
| STG001 | Fundamentals of Kyverno | 18 % | [ATS007](https://github.com/astrona-io/ATS007) |
| STG002 | Installation, Configuration, and Upgrades | 18 % | [ATS008](https://github.com/astrona-io/ATS008) |
| STG003 | Kyverno CLI | 12 % | [ATS009](https://github.com/astrona-io/ATS009) |
| STG004 | Applying Policies | 10 % | [ATS010](https://github.com/astrona-io/ATS010) |
| STG005 | Writing Policies | 32 % | [ATS011](https://github.com/astrona-io/ATS011) |
| STG006 | Policy Management | 10 % | [ATS012](https://github.com/astrona-io/ATS012) |

The site picks it up through [astrona-content](https://github.com/astrona-io/astrona-content):
`courses/kyverno-certified-associate-kca.yaml` points at this repository, and
the content sync builds the course — one section per stage, with the readings
and labs each stage repository lists in its `astrona.yaml`.
