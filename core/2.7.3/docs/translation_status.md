# XOOPS 2.7.0 — Translation Status Report

**Generated:** 2026-05-03  
**English baseline:** 1,067 language constants across 25 PHP files + 10 mail templates  
**Total translated files:** 1,295 (925 PHP + 370 mail templates)

---

## Summary

All 37 language packs are **100% complete** against the English 2.7.0 baseline.  
All constants added through version 2.7.0 (including `_BANNERS_NO_FLASH`, `_US_PWDRESETDONE`, `_DB_QUERY_ERROR`, `_ER_UP_MODE_NOT_CHANGED`, and `_AD_WARNING_NO_XML`) are present in every language.

---

## Language Completeness

| Language | Folder | Script | Dir | PHP Defines | Mail Templates | Status |
|---|---|---|---|---|---|---|
| Arabic | `arabic` | Arabic | RTL | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Bosnian | `bosnian` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Brazilian | `brazilian` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Bulgarian | `bulgarian` | Cyrillic | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Catalan | `catalan` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Croatian | `croatian` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Czech | `czech` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Danish | `danish` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Dutch | `dutch` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Finnish | `finnish` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| French | `french` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Galician | `galician` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| German | `german` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Greek | `greek` | Greek | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Gujarati | `gujarati` | Gujarati | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Hebrew | `hebrew` | Hebrew | RTL | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Hungarian | `hungarian` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Italian | `italian` | Latin | LTR | 1069/1067 (100%+) | 10/10 (100%) | ✅ Complete† |
| Japanese | `japanese` | CJK | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Korean | `korean` | Hangul | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Malaysian | `malaysian` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Norwegian | `norwegian` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Persian | `persian` | Arabic | RTL | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Polish | `polish` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Portuguese | `portuguese` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Romanian | `romanian` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Russian | `russian` | Cyrillic | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Simp. Chinese | `schinese` | CJK | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Slovenian | `slovenian` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Spanish | `spanish` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Swedish | `swedish` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Trad. Chinese | `tchinese` | CJK | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Thai | `thai` | Thai | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Turkish | `turkish` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Ukrainian | `ukrainian` | Cyrillic | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Urdu | `urdu` | Arabic | RTL | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |
| Vietnamese | `vietnamese` | Latin | LTR | 1067/1067 (100%) | 10/10 (100%) | ✅ Complete |

† Italian `pmsg.php` carries two legacy constants (`_XOBJ_ERR_INVALID_EMAIL`, `_XOBJ_ERR_INVALID_ENUMERATION`) from XOOPS 2.5.8 that are commented out in the English source. These are harmless and preserved from the prior Italian translation.

---

## Files Per Language Pack

| File | Constants | Notes |
|---|---|---|
| `admin.php` | 16 | |
| `auth.php` | 7 | |
| `backend.php` | 2 | |
| `banners.php` | 41 | Includes `_BANNERS_NO_FLASH` (new in 2.7.0) |
| `calendar.php` | 3 | `_CAL_FORMAT` uses constant reference `_SHORTDATESTRING` |
| `captcha.php` | 5 | |
| `comment.php` | 39 | |
| `countries.php` | 250 | Country names, not translated (proper nouns) |
| `errors.php` | 15 | |
| `findusers.php` | 27 | |
| `formdhtmltextarea.php` | 15 | |
| `global.php` | 191 | Largest core file; includes `_DB_QUERY_ERROR`, `_RTL` |
| `locale.php` | 1 | |
| `logger.php` | 10 | |
| `mail.php` | 8 | |
| `misc.php` | 3 | |
| `notification.php` | 44 | |
| `pmsg.php` | 35 | |
| `search.php` | 8 | |
| `stopwords.php` | 1 | Language-specific stop word list (multi-line concatenated string) |
| `timezone.php` | 1 | |
| `uploader.php` | 18 | Includes `_ER_UP_MODE_NOT_CHANGED` (new in 2.5.11) |
| `user.php` | 116 | Includes `_US_PWDRESETDONE` |
| `xmf.php` | 2 | |
| `xoopsmailerlocal.php` | 1 | Example/template file |
| **mail_template/** | — | 10 `.tpl` files per language |

---

## 2.7.0 New Constants Verification

All languages confirmed to contain these constants added in the 2.7.0 release cycle:

| Constant | File | Added In |
|---|---|---|
| `_BANNERS_NO_FLASH` | `banners.php` | 2.7.0 |
| `_US_PWDRESETDONE` | `user.php` | 2.7.0 |
| `_AD_WARNING_NO_XML` | `admin.php` | 2.5.11-Betas |
| `_DB_QUERY_ERROR` | `global.php` | 2.5.11-RC1 |
| `_ER_UP_MODE_NOT_CHANGED` | `uploader.php` | 2.5.11-Final |

---

## Notes for Translators

- **RTL languages** (Arabic, Hebrew, Persian, Urdu): `_RTL` constant is computed automatically from `_TEXT_DIRECTION`; do not hard-code it.
- **Stop words** (`stopwords.php`): The English word list is replaced with a language-appropriate list. CJK languages (Japanese, Korean, Simplified/Traditional Chinese) use shorter lists — this is expected.
- **Countries** (`countries.php`): Country names are proper nouns. Most languages keep the international form; some (e.g. Russian, Italian) use their native equivalents where standard.
- **Mail templates**: All `{X_PLACEHOLDER}` variables must be preserved verbatim. Variable names are case-sensitive.
- To update this report after adding new constants, re-run the generation script in `docs/`.
