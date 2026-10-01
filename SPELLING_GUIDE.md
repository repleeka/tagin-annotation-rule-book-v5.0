# How the Languages in the Tani Corpus Are Spelled and Pronounced

This is a guide to the spelling of each language in `tani_corpus.json`: which letters are used and what sound each one stands for. Sounds are given in IPA between square brackets.

- **Examples** are words that occur in the corpus.
- **Meanings** are given only where a source states them.
- **Unclear values:** where a letter's sound is not documented, the table says "not documented" rather than guessing.
- **Tone:** all these languages have tone, but the corpus text does **not** write it (except for a few accented words in Hruso, §7).

Letters that are pronounced roughly as in English (`b d g k l m n p s t`) are listed only when something about them needs saying.

---

## 1. Tagin (`tgj_Latn`): Modified Roman Script for Tagin (MRST)

Both the Tagin Bible and GinLish are in this standard spelling (*The Tagin Annotation Rule Book*, ed. 5.0).

**Vowels.** There are seven vowels. Each can be short or long, and the difference changes meaning. A long vowel is written double.

| Letter | Sound | Short | Long |
|---|---|---|---|
| `a` | [a] | `abu` father | `aanam` to come |
| `e` | [e] | `kedv` land, `re` (future) | `bee` chant, `seenv` tree |
| `i` | [i] | `jinam` to give | `jiinam` to plant crops, `nyii` person |
| `o` | [o] | `oppo` alcohol | `oo` vegetable |
| `u` | [u] | `usum` urine | `uum` hole |
| `v` | [ə] (schwa) | `vlw` stone, `gv` of | `vvro` go away |
| `w` | [ɨ] (high central) | `lvbw` knee, `hwdw` when | `bww` he, she |

**Consonants**

| Letter | Sound | Example | Note |
|---|---|---|---|
| `ng` | [ŋ] | `ngo` I | |
| `ny` | [ɲ] | `nyii` person | never ends a word |
| `ch` | [tɕ] | `achin` food | never ends a word |
| `j` | [dʑ] | `jinam` to give | never ends a word |
| `y` | [j] | `yalu` | never ends a word |
| `r` | [ɾ] (flap) | `ritola` | |
| `h` | [h] | `hugu` what | only at the start or in the middle of a word |
| `b p m t d k g s l n` | as in English | | no [v]: English *v* → `b`; English *f* → `p` |

**Other conventions**
- **Loanwords:** `f`, `z` and a bare `c` appear only in loanwords and names (`ferrari`, `mozambik`, `cd`).
- **Case:** everything is lowercase, names included.
- **Hyphens:** a hyphen joins the two parts of one compound (`si-donyi`).
- **Punctuation:** in the corpus, punctuation stands apart from words (`vm , ngo chindo .`).

---

## 2. Galo (`adl_Latn`)

Galo has the same sounds as Tagin but writes some of them differently (rule book, Appendix J). Letters not listed below have the same values as in Tagin.

| Letter | Sound | Example | Tagin spelling |
|---|---|---|---|
| `v` | [ə] | `vm`, `bv`, `gv` | `v` |
| `w` | [ɨ] | `bw` he, she | `w` |
| `q` | [ŋ] | `qo` I, `qonu` we | `ng` |
| `x` | [ɲ] | `xi`, `axi` | `ny` |
| `ch` | [tɕ] | `rwlachin`, `chv` | `ch` |
| double vowel | long vowel | `mvvtin`, `doobv` | the same |
| double consonant | a written double consonant | `okkv` and then, `gaddv` | written single (`okv`) |

**Tone:** the Galo spelling system can mark tone with a backtick before the word (`` `la ``). The Galo Bible text in this corpus has **no** tone marks.

---

## 3. Nyishi (`njz_Latn`)

Nyishi has seven vowels [i ɨ u e ə o a] and three tones. The Bible text uses no tone marks.

| Letter | Sound | Example | Evidence |
|---|---|---|---|
| `a e i o u` | [a e i o u] | `hoo`, `ngo`, `nyi` | |
| `v` | [ə] | `lvgab`, `bulv`, `dvb` | cognate with Tagin/Galo `lvga` |
| `w` | [ɨ] | `hwdlo`, `mwwg`, `sw` | cognate with Tagin `hwdw lo` (when) |
| `ng` | [ŋ] | `ngo`, `ngulv` | Nyishi orthography |
| `ny` | [ɲ] | `nyi`, `nyob` | Nyishi orthography |
| `j` | [ɟ] | `jaqb` | Nyishi orthography |
| `y` | [j] | `hiyv` | Nyishi orthography |
| `r` | [ɾ] | `deexa-rara` | Nyishi orthography |
| `kh` | [x] | (rare) | the same sound as `x`; other Nyishi writing uses `kh` |
| double vowel | written double | `hoo`, `ceekol`, `xaalyo` | probably long vowels, as in Tagin |
| `q` | [ʔ] (glottal stop) | `hoq`, `soq`, `ngoqg`, `hoqgv` | per the maintainer; unlike Galo, where `q` is [ŋ] |
| `x` | [x] (the "kh" sound) | `xinam`, `xumk`, `nywxw` | per the maintainer; unlike Galo, where `x` is [ɲ] |
| `c` | [tɕ] (the "ch" sound, as Tagin `ch`) | `nyic`, `ceekol`, `swcw`, `camnyi` | per the maintainer; written `ch` in Tagin, Galo and Apatani |


---

## 4. Apatani (`apt_Latn`)

The corpus text uses the **older, English-style Apatani spelling**, not the newer Apatani alphabet ("Tanw Aguñ"). Names keep their English spelling and capital letters (`Jisu`, `David`, `Jew`).

| Letter | Sound | Example | Note |
|---|---|---|---|
| `a o u` | [a o u] | `ho`, `mo`, `nunu` | |
| `i` | [i] | `mi`, `chindo`, `citi` | |
| `ii` | [ɨ] or long [iː] | `hii`, `pinii`, `hiila`, `niimpalukoda` | in this spelling tradition `ii` also writes [ɨ]; the two are not told apart |
| `e` | [e], and probably [ə] | `kone`, `kendo`, `ke` | the old spelling has no separate letter for [ə] |
| `aa ee oo uu` | long vowels | `putoo`, `amee`, `atuu` | rare |
| `ng` | [ŋ] | `ngo`, `ngunu` | |
| `ny` | [ɲ] | `anye`, `nyima` | |
| `ch` | [tʃ] ~ [c] | `chindo`, `chima` | |
| `j` | [dʒ] | `hojalo`, `abuje` | |
| `kh` | [x] | `hikha`, `akhoo` | |
| `sh` | **not documented** | `shiinii`, `shiido` | |
| `pf` | **not documented** | `ipfyo`, `pfyoari` | |
| `h` after a vowel | **not documented** | `mohmi`, `ahchi`, `attoh` | |
| `k` at the end of a dictionary word | [ʔ] (glottal stop) | `parok` rooster, `lakchi`, `duk` throb, market | written `k` in this corpus instead of an apostrophe; distinguishes words (`duk` ≠ `du` dig); the Bible text does not write it (`paro`) |

**The newer Apatani alphabet** (not used in this corpus) writes:

| Sound | [ə] | [ɨ] | [ŋ] | [x] | [c] | [ʎ] | [ʔ] | nasalisation |
|---|---|---|---|---|---|---|---|---|
| Letter | `v` | `w` | `q` | `x` | `c` | `f` | `’` | `-ñ` |

---

## 5. Adi (`adi_Latn`)

Adi is written in a Roman alphabet going back to the missionary dictionary of 1906. The text is lowercase and has no tone marks.

| Letter | Sound | Example | Note |
|---|---|---|---|
| `a` | [a] | `ka`, `ami` | |
| `e` | usually [ə] | `emla`, `legape`, `de`, `ke` | `emla` = Galo `vmla`; `legape` = Galo/Tagin `lvga`: Adi mostly writes [ə] as plain `e` |
| `é` | [e] ~ [ɛ]; also some [ə] | `shédí`, `séko`, `agér` | the Adi alphabet chart gives [e/ɛ]; but `agér` corresponds to Galo `agvr` [ə] |
| `i` | [i] | `ami`, `idola`, `si` | |
| `í` | [ɨ] | `bí` he, she; `kídí`, `mí` | `bí` = Galo `bw`, Tagin `bww`; the Mising standard also has `í` = [ɨ] |
| `o` | [o] ~ [ɔ] | `ngo`, `do` | |
| `u` | [u] | `ru`, `bulu` | |
| `:` (colon) after a vowel | long vowel | `o:`, `ru:tum`, `do:lung`, `bé:rang` | |
| `ng` | [ŋ] | `ngo`, `among` | |
| `ny` | [ɲ] | — | |
| `j` | [dʒ] | `roja` | |
| `y` | [j] | `teyolo` | |
| `sh` | **not documented** | `shédíke` | |
| `w` | [w] | `tawar` | only in names and loans |

**Note.** Adi sources disagree on these vowel letters. The published Adi alphabet chart (Omniglot, after the CIIL Adi primer) lists `e` = [ə], `é` = [e/ɛ], `i` = [ɨ], `í` = [i]. Comparison with Galo and Tagin supports `e` = [ə] but **`í` = [ɨ]**. An Adi speaker should confirm the values of `e`/`é` and `i`/`í`.

---

## 6. Mising (`mrg_Latn`)

Mising is written in the standard Mising alphabet (Mising Agom Kébang). In this corpus, the source's substitute letters were replaced by the standard ones: source `c` → `é`, source `v` → `í`. The text is lowercase and has no tone marks.

| Letter | Sound | Example |
|---|---|---|
| `a` | [a] | `la`, `ka` |
| `e` | [ɛ] | `ager`, `bera` |
| `é` | [ə] | `pé`, `sé`, `émna`, `odokké` |
| `i` | [i] | `tani`, `kapila` |
| `í` | [ɨ] | `bí` he, she; `kídí` |
| `o` | [o] | `ngo`, `odo` |
| `u` | [u] | `du`, `bulu` |
| `:` (colon) after a vowel | long vowel | `émpige:la`, `me:r`, `gerya:né` |
| `au`, `oi` | diphthongs [au], [oi] | |
| `ng` | [ŋ] | `ngo`, `dung` |
| `ny` | [ɲ] | — |
| `j` | [dʒ] | `jisubí`, `jé` |
| `r` | [ɾ] | `ru`, `bera` |
| `y` | [j] | `yé` |
| `w` | [w] | `awo`, `tawuto` |
| `z` | [z] | — |
| `b d g h k l m n p s t` | as in English | |

Plain `e` [ɛ] occurs 1,206 times in the corpus. A few of these may be [ə] words that the source wrote without its substitute letter.

---

## 7. Hruso / Aka (`hru_Latn`): not a Tani language

Hruso is written in the Hrusso Aka community alphabet (developed from 1999; described in D'Souza 2021). The corpus keeps capital letters and curly quotes as in the source.

**Vowels**

| Letter | Sound | Example |
|---|---|---|
| `a e i o u` | [a e i o u] | `ñe`, `ñu` |
| `ü` | [ɨ] | `nüna`, `sünda`, `ñetrü` /ɲeʈʂɨ/ |
| `á é í ó ú` | accented vowels on a few frequent words (`í`, `ná`, `bá`, `nó`) | the current alphabet does not write tone, and these marks are not described in the alphabet key; an older spelling (Simon 1970) used `í` for [ə] |
| `ã õ ẽ` | nasal vowels (rare) | |

**Consonants** (the alphabet key in D'Souza 2021)

| Letter | Sound | | Letter | Sound |
|---|---|---|---|---|
| `b` | [b] | | `rh` | [ʐ] |
| `d` | [d̪] (dental) | | `s` | [s̪] (dental) |
| `dj` | [d͡z̻] | | `ŝ` | [s̻] (alveolar) |
| `dr` | [ɖ͡ʐ] | | `sh` | [ʂ] |
| `f` | [f] | | `t` | [t̪] (dental) |
| `g` | [ɡ] | | `tch` | [t͡s̻] |
| `ĝ` | [ɣ] | | `tr` | [ʈ͡ʂ] |
| `h` | [h] | | `v` | [v] |
| `ng` | [ŋ] | | `w` | [w] |
| `ñ` | [ɲ] | | `y` | [j] |
| `r` | [r] | | `z` | [z̻] |
| `k l m n p` | as in English | | | |

**Consonant series**

| Series | Letters | Sounds |
|---|---|---|
| Palatalised | `py by my ky gy ĝy ly`; `ch`; `j` | [pʲ bʲ mʲ kʲ ɡʲ ɣʲ ʎ]; [t͡ʃʲ]; [d͡ʒʲ] |
| With a following alveolar | `ps bz ts dz ks gz fs vz` | [p͡s̻ b͡z̻ t̪͡s̪ d̪͡z̪ k͡s̻ ɡ͡z̻ f͡s̻ v͡z̻] |
| With a following retroflex | `pr br kr gr fr vr mr` | [p͡ʂ b͡ʐ k͡ʂ ɡ͡ʐ f͡ʂ v͡ʐ m͡ʐ] |

---

## 8. The same sounds, side by side

| Sound | Tagin | Galo | Nyishi | Apatani (corpus spelling) | Adi | Mising | Hruso |
|---|---|---|---|---|---|---|---|
| [ə] | `v` | `v` | `v` | `e` (probably) | `e` (mostly), `é` | `é` | not documented |
| [ɨ] | `w` | `w` | `w` | `ii` | `í` | `í` | `ü` |
| [e] | `e` | `e` | `e` | `e` | `é` | — | `e` |
| [ɛ] | — | — | — | — | `é` | `e` | — |
| [ŋ] | `ng` | `q` | `ng` | `ng` | `ng` | `ng` | `ng` |
| [ɲ] | `ny` | `x` | `ny` | `ny` | `ny` | `ny` | `ñ` |
| palatal affricate ("ch") | `ch` [tɕ] | `ch` [tɕ] | `c` [tɕ] | `ch` [tʃ] | — | — | `ch` [t͡ʃʲ] |
| [x] ("kh") | — | — | `x` | `kh` | — | — | — |
| long vowel | double | double | double (probably) | double | colon | colon | — |
| glottal stop | — | — | `q` | `k` (dictionary words) | — | — | — |
| tone | not written | backtick (not in this text) | not written | not written | not written | not written | not written |

---

## Sources

- Dugi, Tungon (2026). *The Tagin Annotation Rule Book*, edition 5.0. ai4arunachal. Ch. 2 (sound system), ch. 4 (orthography), App. J (Tagin–Galo correspondences).
- D'Souza, Vijay A. (2021). *Aspects of Hrusso Aka Phonology and Morphology*. DPhil thesis, University of Oxford: "Key to the current orthography of Hrusso Aka", and §10.3 (orthography and tone).
- Simon (1993 [1970]). *Aka Language Guide*, as cited in D'Souza (2021).
- Omniglot: alphabet charts for Adi, Mising (Mising Agom Kébang) and Apatani (Tanw Aguñ), https://www.omniglot.com.
- Wikipedia, "Nishi language" and "Apatani language" (phonology tables; Apatani after Post & Kanno 2013).
- Cognate evidence (Adi, Nyishi): comparison of frequent words in this corpus with Tagin and Galo forms whose sounds are documented in the rule book.
