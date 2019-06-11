# Statenvertaling *with Apocrypha* (OSIS)

The idea is to have a solid base Statenvertaling module, to which the Apocrypha can be added optionally.

## Statenvertaling (base)
Since the source of the existing Sword module is unavailable, I have constructed an alternative base for the Statenvertaling without Apocrypha. In its current state, it compiles to a SWORD module without errors or warnings. I have also manually copied the Chapter headings from the existing Sword module.

### New features I have been able to add:
* Strong’s Numbers
* Words added to the translation are marked with transChange (these appear in Italics in the printed text)

### Other differences:
* I have elected to mark the original versification in square brackets for now. The module's versification follows KJV.

### Features I would like to add
* The commentary module DutKant (Kanttekeningen Statenvertaling) should be merged into this as footnotes, since it concerns translation remarks.
* Red Letter text

## Apocrypha
Strong’s Numbers are absent, for obvious reasons. Because of the presence of 3Macc, I have opted to the NRSVA versification here. It's not pretty, because not all books of the NRSVA are present, but when pasted in STV.xml osis2mod converts it without errors.
