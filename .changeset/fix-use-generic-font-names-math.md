---
"@biomejs/biome": patch
---

Fixed [`useGenericFontNames`](https://biomejs.dev/linter/rules/use-generic-font-names/) to recognize the CSS Fonts Level 4 generic font families `math`, `fangsong`, and `emoji`. Previously, a declaration such as `font-family: math` was incorrectly reported as missing a generic font family.
