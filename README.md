# Jitendex Japanese–Indonesian Dictionary — Common 20%

An unofficial Indonesian localization of [Jitendex](https://jitendex.org) for Yomitan-compatible browser dictionary extensions. Japanese headwords, readings, tags, images, source material, and attribution are retained from the upstream dictionary. The most frequent entries have Indonesian translations; the long tail keeps the original English definitions.

**Download:** [Latest release](https://github.com/greyindex/jitendex-yomitan-id/releases/latest) · [Direct ZIP download](https://github.com/greyindex/jitendex-yomitan-id/releases/latest/download/jitendex-yomitan-id-common20pct-luna.zip)

Other language edition: [Japanese–Chinese dictionary](https://github.com/greyindex/jitendex-yomitan-zh).

## Coverage

The upstream dictionary contains **211,107 distinct JMdict IDs with definitions**, represented by **296,919 spelling/reading variant records**. This release localizes the frequency-selected top 20% by distinct entry count:

| Measure | Indonesian release |
| --- | ---: |
| Distinct JMdict IDs localized | 42,222 / 211,107 (**20.00%**) |
| Variant records with localized fields | 65,279 / 296,919 (**21.99%**) |
| Translated fields after expanding translations across variants | 305,351 |
| Distinct IDs that retain English | 168,885 / 211,107 (**80.00%**) |

The frequency ranking uses Jiten Global's 2026-09-19 list and matches Japanese spelling/reading forms to dictionary entries. Of the 211,107 IDs, 171,601 matched the frequency data and 39,506 did not. The selected 42,222 are the top-ranked matched IDs needed to reach approximately 20% of the full dictionary population. Among the 168,885 IDs outside the Indonesian scope, 129,379 matched the frequency list but fall below the cutoff; the other 39,506 could not be matched. An unmatched ID is **not necessarily rare**—it only means this frequency source did not provide a usable match.

Here, “20%” means 20% of distinct dictionary IDs, **not** 20% of words in real-world Japanese text. A frequency match is based on a spelling and reading, not a sense-specific probability, so homographs can make the ranking imperfect.

## What remains in English

The other **168,885 distinct IDs** keep their upstream English definitions. This includes the matched long tail below the cutoff and the IDs unmatched to the frequency list. Their dictionary entries remain available; they are not removed. Across spelling/reading variants, 231,640 of the 296,919 records remain untranslated. No claim is made that the selected 20% covers a particular share of reading material.

## Install

1. Download the ZIP from [Releases](https://github.com/greyindex/jitendex-yomitan-id/releases/latest).
2. In Yomitan, open **Settings → Dictionaries → Import** and select the downloaded ZIP.
3. This is a static offline dictionary package; check Releases manually for newer versions.

## Translation and limitations

Indonesian translations were drafted with GPT-6 Luna for the selected fields, including definitions, examples, notes, and auxiliary explanations. They have **not** been reviewed by an Indonesian native speaker, so errors and unnatural phrasing may remain. The scope and build checks verify coverage and preservation of dictionary structure; they do not certify translation accuracy.

The package is based on Jitendex v2026.08.11.0. The full build summary is available in [`reports/build_report.json`](reports/build_report.json). Release asset SHA-256: `63dace5908385acd66a2b8060fc11d9e1fee2be1b7533d2417a359173fe3da66`.

## Atribusi dan lisensi

Kamus ini adalah lokalisasi komunitas tidak resmi untuk Jitendex. Data kamus dan terjemahan turunannya dibagikan berdasarkan [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). Atribusi lengkap disertakan di dalam ZIP. Jitendex mencakup data JMdict dari Electronic Dictionaries Research Group dan contoh kalimat dari Tatoeba.

## English summary

This package translates the frequency-selected top **42,222 of 211,107 distinct JMdict IDs (20.00%)** into Indonesian. It covers 65,279 spelling/reading variant records. The remaining **168,885 IDs (80.00%)** retain English. Of those, 39,506 could not be matched to the Jiten Global frequency data; that does not prove they are rare. “20%” is an entry-count target, not a measure of text coverage. The AI-generated Indonesian has not received native-speaker review.

## 中文说明

此版本将 211,107 个有释义的 JMdict ID 中按 Jiten Global 词频筛选的前 42,222 个（20.00%）本地化为印尼语，展开覆盖 65,279 条拼写/读音变体记录。其余 168,885 个 ID（80.00%）保留上游英文释义，其中 39,506 个未能匹配到该词频表；未匹配不代表它们一定是低频词。这里的 20% 按词典 ID 数量计算，不代表覆盖了日常文本中 20% 的词。印尼语译文由模型生成，尚未经过母语者校订。
