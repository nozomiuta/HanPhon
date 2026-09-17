# HanPhon

**HanPhon** is a simple, human readable phoneme notation for **Mandarin Chinese**.

It is designed to represent Mandarin pronunciation as clearly as possible with an easy way to read

## Features

* Simple and readable phoneme names
* Based on standard Mandarin pronunciation and Pinyin
* Includes Mandarin initials, vowels, diphthongs, and nasal finals
* Provides X-SAMPA equivalents for compatibility and reference
* Suitable for speech synthesis, singing synthesis, phonology, and other projects

## Phoneme Format

Each HanPhon phoneme comparsion is documented as:

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

The **HanPhon name** is intended to be the easiest part to read and use. X-SAMPA is provided as a technical reference rather than being required knowledge

## Phoneme Set

HanPhon currently contains **58 phonemes**:

* 21 initials
* 37 finals and vowel units

The inventory includes:

* Initial consonants
* Basic vowels
* The two Mandarin `i` vowels
* Diphthongs
* Nasal finals
* `ü`-based finals
* `er`

## The Two Mandarin "i" Sounds

Mandarin has two distinct vowel sounds commonly represented by `i` in Pinyin:

```text
if = i` = i (zi, ci, si)
ir = i\ = i (zhi, chi, shi, ri)
```

HanPhon gives them separate names so they can be represented unambiguously.

## Why HanPhon?

X-SAMPA is powerful and useful, but its notation can be difficult to read for people who are not already familiar with phonetic transcription.

HanPhon keeps the phoneme names simple while still providing X-SAMPA equivalents when a more technical representation is needed.

## License

See [LICENSE](LICENSE) for the license of this project.
