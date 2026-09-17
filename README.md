# HanPhon

**HanPhon** is a simple, human-readable phoneme notation for **Mandarin Chinese**

It is designed to make Mandarin phonemes easy to read and use while still providing **X-SAMPA equivalents** for compatibility and reference

## Features

* Simple and readable phoneme names
* Based on standard Mandarin pronunciation and Pinyin
* Mandarin initials, vowels, diphthongs, and nasal finals
* Separate notation for the two Mandarin `i` sounds
* X-SAMPA equivalents for reference
* Suitable for speech synthesis, singing synthesis, phonology, and other projects

## Format

Phoneme comparisons are written as:

```text
HanPhon = X-SAMPA = Pinyin
```

For example:

```text
b = p = b
p = p_h = p
j = tS = j
q = tS_h = q
x = s\ = x

zh = ts` = zh
ch = ts`_h = ch
sh = s` = sh
```

## Phoneme Set

The current HanPhon inventory contains Mandarin initials, vowels, diphthongs, nasal finals, and tone entries.

The phoneme list is available in [`phonemes`](phonemes).

### Initials

```text
b p m f
d t n l
g k h
j q x
zh ch sh r
z c s
y w
```

### Vowels

```text
a o e i u Y
er
if ir
```

### Diphthongs and vowel combinations

```text
ay ey aw ow
ia ie ua uo Ye
iaw iu uay uey
```

### Nasal finals

```text
an en in ian
uan un Yn Yan

ang eng ing iang
uang ong iong
```

### Tone entries

The current phoneme list also contains:

```text
1 (tone)
2 (tone)
3 (tone)
4 (tone)
```

These are listed separately from the segmental phonemes.

## The Two Mandarin "i" Sounds

Mandarin has two distinct vowel sounds commonly represented by `i` in Pinyin.

HanPhon represents them separately:

```text
if = i` = i (zi, ci, si)
ir = i\ = i (zhi, chi, shi, ri)
```

This avoids treating both sounds as the same phoneme.

## X-SAMPA

X-SAMPA is included as a technical reference for users who need a standardized phonetic notation.

HanPhon itself is intended to be easier to read:

```text
HanPhon:  zh
X-SAMPA:  ts`
Pinyin:   zh
```

The complete comparison table is available in [`comparisions`](comparisions).

## License

This project is licensed under **CC0 1.0 Universal**.

See [`LICENSE`](LICENSE) for details.
