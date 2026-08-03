---
"@biomejs/biome": patch
---

Fixed a panic when formatting TypeScript declared class properties with string literal names, such as `declare "role-admin": Array<number>;`.
