# japonicLJ

## About this data

The file `dat.tsv` is a database of cognate coded basic vocabulary in the Japonic languages. The database contains words for 102 concepts. It is based on the Leipzig-Jakarta list, which originally contains 100 items, but two items were split: hand/arm, and to do/to make. The vocabulary comes from 95 linguistic varieties: 65 Japanese, 28 Ryukyuan, and 2 extinct varieties. Some varieties occur multiple times with data from different sources. Information about the linguistic varieties can be found in the file `languages.tsv`. Information about the concepts can be found in the file `concepts.tsv`. A bibliography of the data sources can be found in the file `sources.bib`.

## The vocabulary database

### Columns in dat.tsv

- **lj_id**: the item rank on the original Leipzig-Jakarta list. Items that had the same rank on the original list are given a suffix *.x* where *x* is a number denoting the order in which they appeared. 
- **lj_item**: the item name as it appeared on the original Leipzig-Jakarta list.
- **item**: the concept name.
- **source**: the source of the lexical data.
- **xsampa**: transcription of the word in X-SAMPA (as it appears in the original source).
  - Symbols not defined in X-SAMPA used in this database are F\ for ꜰ (U+A730; Latin Letter Small Capital F) commonly used in Japanese dialectology to denote a voiceless bilabial fricative, and T\ for ᴛ (U+1D1B; Latin Letter Small Capital T) commonly used in Japanese dialectology to denote a geminate onset in word-final position.
- **ipa**: transcription of the word in International Phonetic Alphabet (as it appears in the original source).
- **cognacy**: cognacy of the word. 
- **notes**: additional notes about the data
