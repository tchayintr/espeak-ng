# Phoneme Features

- [Phoneme Type](#phoneme-type)
- [Consonants](#consonants)
  - [Voicing](#voicing)
  - [Place of Articulation](#place-of-articulation)
  - [Manner of Articulation](#manner-of-articulation)
- [Vowels](#vowels)
  - [Height](#height)
  - [Backness](#backness)
  - [Rounding](#rounding)
- [Additional Features](#additional-features)
- [References](#references)

----------

Evan Kirshenbaum created an ASCII transcription of the International Phonetic
Alphabet<sup> \[<a href="#ref1">1</a>\]</sup>. As well as using ASCII
characters for specific IPA phonemes, this transcription provides a set of
3-letter feature abbreviations allowing a phoneme to be described as a sequence
of features.

This document describes the features used by Kirshenbaum.

## Phoneme Type

| Feature | Kirshenbaum | Name            |
|---------|-------------|-----------------|
| `vwl`   | `vwl`       | vowel           |

## Consonants

### Voicing

| Feature | Kirshenbaum | Name            |
|---------|-------------|-----------------|
| `vcd`   | `vcd`       | voiced          |
| `vls`   | `vls`       | voiceless       |

### Place of Articulation

| Feature | Kirshenbaum | Name            |
|---------|-------------|-----------------|
| `blb`   | `blb`       | bilabial        |
| `lbd`   | `lbd`       | labio-dental    |
| `dnt`   | `dnt`       | dental          |
| `alv`   | `alv`       | alveolar        |
| `rfx`   | `rfx`       | retroflex       |
| `pla`   | `pla`       | palato-alveolar |
| `pal`   | `pal`       | palatal         |
| `vel`   | `vel`       | velar           |
| `lbv`   | `lbv`       | labio-velar     |
| `uvl`   | `uvl`       | uvular          |
| `phr`   | `phr`       | pharyngeal      |
| `glt`   | `glt`       | glottal         |

### Manner of Articulation

| Feature | Kirshenbaum | Name            |
|---------|-------------|-----------------|
| `stp`   | `stp`       | stop            |
| `frc`   | `frc`       | fricative       |
| `nas`   | `nas`       | nasal           |
| `orl`   | `orl`       | oral            |
| `apr`   | `apr`       | approximant     |
| `lat`   | `lat`       | lateral         |
| `ctl`   | `ctl`       | central         |
| `trl`   | `trl`       | trill           |
| `flp`   | `flp`       | tap/flap        |
| `clk`   | `clk`       | click           |
| `ejc`   | `ejc`       | ejective        |
| `imp`   | `imp`       | implosive       |

## Vowels

### Height

| Feature | Kirshenbaum | Name            |
|---------|-------------|-----------------|
| `hgh`   | `hgh`       | high            |
| `smh`   | `smh`       | semi-high       |
| `umd`   | `umd`       | upper-mid       |
| `mid`   | `mid`       | mid             |
| `lmd`   | `lmd`       | lower-mid       |
| `low`   | `low`       | low             |

### Backness

| Feature | Kirshenbaum | Name            |
|---------|-------------|-----------------|
| `fnt`   | `fnt`       | front           |
| `cnt`   | `cnt`       | center          |
| `bck`   | `bck`       | back            |

### Rounding

| Feature | Kirshenbaum | Name            |
|---------|-------------|-----------------|
| `unr`   | `unr`       | unrounded       |
| `rnd`   | `rnd`       | rounded         |

## Additional Features

| Feature | Kirshenbaum | Name            |
|---------|-------------|-----------------|
| `asp`   | `asp`       | aspirated       |
| `unx`   | `unx`       | unexploded      |
| `syl`   | `syl`       | syllabic        |
| `mrm`   | `mrm`       | murmured        |
| `lng`   | `lng`       | long            |
| `vzd`   | `vzd`       | velarized       |
| `lzd`   | `lzd`       | labialized      |
| `pzd`   | `pzd`       | palatalized     |
| `rzd`   | `rzd`       | rhoticized      |
| `nzd`   | `nzd`       | nasalized       |
| `fzd`   | `fzd`       | pharyngealized  |

## References

1. <a name="ref1"></a> Kirshenbaum, Evan,
   [http://www.kirshenbaum.net/IPA/ascii-ipa.pdf](Representing IPA phonetics in ASCII). 2001.