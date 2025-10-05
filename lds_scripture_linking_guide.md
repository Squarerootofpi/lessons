# LDS Scripture Linking Guide

This guide documents the URL structure for linking to scriptures on churchofjesuschrist.org.

## Base URL Template

All scripture links follow this pattern:
```
https://www.churchofjesuschrist.org/study/scriptures/[canon]/[book]/[chapter]?lang=eng&id=p[verse]#p[verse]
```

## Canon Identifiers

- **Old Testament**: `ot`
- **New Testament**: `nt`
- **Book of Mormon**: `bofm`
- **Doctrine and Covenants**: `dc-testament/dc`
- **Pearl of Great Price**: `pgp`

## Book Abbreviations

### Old Testament Examples
- Genesis: `gen`
- Exodus: `ex`
- Isaiah: `isa`

### New Testament Examples
- John: `john`
- Romans: `rom`
- Revelation: `rev`

### Book of Mormon Complete List
- 1 Nephi: `1-ne`
- 2 Nephi: `2-ne`
- Jacob: `jacob`
- Enos: `enos`
- Jarom: `jarom`
- Omni: `omni`
- Words of Mormon: `w-of-m`
- Mosiah: `mosiah`
- Alma: `alma`
- Helaman: `hel`
- 3 Nephi: `3-ne`
- 4 Nephi: `4-ne`
- Mormon: `morm`
- Ether: `ether`
- Moroni: `moro`

### Doctrine and Covenants
- Uses section numbers directly (e.g., `76` for D&C 76)

### Pearl of Great Price Examples
- Moses: `moses`
- Joseph Smith—History: `js-h`
- Abraham: `abr`
- Articles of Faith: `a-of-f`

## Verse Linking

### Single Verse
Format: `?lang=eng&id=p[verse_number]#p[verse_number]`

Example: `?lang=eng&id=p21#p21` (for verse 21)

### Verse Ranges
For consecutive verse ranges, use the range format in the id parameter:
Format: `?lang=eng&id=p[start_verse]-p[end_verse]#p[start_verse]`

Example: For verses 21-23, use `?lang=eng&id=p21-p23#p21`

### Multiple Non-Consecutive Verses
For multiple specific verses (like 7, 9), use comma separation:
Format: `?lang=eng&id=p[verse1],p[verse2]#p[verse1]`

Example: For verses 7 and 9, use `?lang=eng&id=p7,p9#p7`

## Complete URL Examples

### Old Testament
- **Genesis 1:1**: `https://www.churchofjesuschrist.org/study/scriptures/ot/gen/1?lang=eng&id=p1#p1`

### New Testament
- **John 3:16**: `https://www.churchofjesuschrist.org/study/scriptures/nt/john/3?lang=eng&id=p16#p16`

### Book of Mormon
- **Alma 32:21**: `https://www.churchofjesuschrist.org/study/scriptures/bofm/alma/32?lang=eng&id=p21#p21`
- **1 Nephi 3:7**: `https://www.churchofjesuschrist.org/study/scriptures/bofm/1-ne/3?lang=eng&id=p7#p7`

### Doctrine and Covenants
- **D&C 76:22**: `https://www.churchofjesuschrist.org/study/scriptures/dc-testament/dc/76?lang=eng&id=p22#p22`

### Pearl of Great Price
- **Joseph Smith—History 1:15**: `https://www.churchofjesuschrist.org/study/scriptures/pgp/js-h/1?lang=eng&id=p15#p15`
- **Moses 1:39**: `https://www.churchofjesuschrist.org/study/scriptures/pgp/moses/1?lang=eng&id=p39#p39`

### Examples with Ranges and Multiple Verses
- **Moses 2:26–27**: `https://www.churchofjesuschrist.org/study/scriptures/pgp/moses/2?lang=eng&id=p26-p27#p26`
- **3 Nephi 17:7, 9**: `https://www.churchofjesuschrist.org/study/scriptures/bofm/3-ne/17?lang=eng&id=p7,p9#p7`
- **D&C 76:22-24**: `https://www.churchofjesuschrist.org/study/scriptures/dc-testament/dc/76?lang=eng&id=p22-p24#p22`

## Notes

1. All URLs include `lang=eng` for English language
2. Verse numbers use the format `p[number]` for both the `id` parameter and the anchor
3. For verse ranges, use the range format in the id parameter (e.g., `id=p21-p23#p21`)
4. Book names with numbers use hyphens (e.g., `1-ne` for 1 Nephi)
5. Doctrine and Covenants has a unique path structure with `dc-testament/dc`