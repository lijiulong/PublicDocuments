# Localization Standard

## Introduction

This standard is introduced into this project to avoid chaos and make localization of files be easily understandable.

## File Naming

This standard must be applied to all files with text contents. To apply this standard, names of those text files must
have a suffix consists of two parts. The first part is the code name of ISO 639-1 or ISO 639-3, which specifies the
language of the text. For example, zh and zho are both valid code names for the first part. The second part is the code
name of ISO 15924 for writing systems. For example, Hans, Hant and Latn are valid code names for the second part. The
first part and second part should be connected with one underscore. For documents written in English, the suffix should
be en_Latn. For documents written in Simplified Chinese, the suffix can be zh_Hans, zho_Hans or cmn_Hans to be more
specific.

When file name of one text document does not have a suffix, it means the file name is using default suffix. The default
suffix is en_Latn for this project. Please pay attention, different project may have different default suffix.

File name and suffix should be connected with a hyphen. For example, the alternative file name for this document is
'localization_standard-en_Latn.md'.

## References

* [List of ISO 639-1 codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
* [List of ISO 639-3 codes](https://en.wikipedia.org/wiki/List_of_ISO_639-3_codes)
* [List of ISO 15924 codes](https://en.wikipedia.org/wiki/ISO_15924#List_of_codes)
