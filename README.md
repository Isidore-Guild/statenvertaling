# Statenvertaling *with Apocrypha* (OSIS)

The idea is to have a solid base Statenvertaling module, to which the Apocrypha can be added optionally.

## Statenvertaling (base)
Since the source of the existing Sword module was unavailable when I began this project, I have constructed an alternative base for the Statenvertaling without Apocrypha. In its current state, it compiles to a SWORD module without errors or warnings. I have also manually copied the Chapter headings from the existing Sword module. Through a lot of work, I was also able to integrate the footnotes. This thus also supersedes the commentary module DutKant (Kanttekeningen Statenvertaling).

### New features I have been able to add:
* Strong’s Numbers
* Words added to the translation are marked with transChange (these appear in Italics in the printed text)
* Footnotes by the translator are integrated in the text.

### Other differences:
* I have elected to mark the original versification in square brackets for now. The module's versification follows KJV, like the existing SWORD module does.

### Features I would like to add
* The footnotes should ideally be shuffled around so that they sit next to the relevant words in the verse.
* Red Letter text

## Apocrypha
Strong’s Numbers are absent, for obvious reasons. Because of the presence of 3Macc, I have opted to the NRSVA versification here. It's not pretty, because not all books of the NRSVA are present, but when pasted in STV.xml osis2mod converts it without errors.

This one hasn't been touched in a while, and unlike the base module, I don't deem it ready for use.
