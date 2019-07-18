# Repository Layout Definition

## Abbreviation

Repository layout definition will be abbreviated as RLD in the rest part of this
document.

## Markdown Standard

The markdown writing standard of this document refers to [CommonMark Spec][1]
0.29. In order to make it convenient for console users, this document will
control line length strictly to 80 columns.

## Version & Revision

### 1.0 July 17th, 2019

1.0 means version 1 revision 0. This will not be explained in the future. This
will be the initial draft of this definition. Any change will be summarized here
in each version & revision record.

## Scope

This layout definition will apply to any repository owned by Frank Li's personal
accounts, or by Grand Electronic Lab's organization accounts.

## Definition

This document will describe RLD as markdown nested list. Each first level
directory can be created as an independent repository. In this situation, the
independent repository should be named as `Root Repository Name`-`First Level
Directory Name`. When in any case the second or even lower level directories
have to be created as independent repositories, the naming rule goes like `Root
Repository Name`-`First Level Directory Name`.`Second Level Directory Name`.
`Third Level Directory Name`... And so on.

* dist
  + cross_platform
  + windows
    - x86
    - x64
    - armv7
    - all_in_one
  + macos
    - x64
    - ppc
    - all_in_one
  + linux
  + ios
  + ipados
  + watchos
* doc
  + gitbook
    - gitbook_1_directory
      - article
      - chapter1
      - chapter2
      - media
    - gitbook_2_directory
  + pdf
    - pdf_file_1_source_project_directory
    - pdf_file_1.pdf
    - pdf_file_2.pdf
  + epub
  + mobi
  + office_doc
  + single_markdowns
  + html
  + text
  + media
  + language1
    - gitbook
    - pdf
    - epub
    - mobi
    - office_doc
    - single_markdowns
    - html
    - text
    - media
  + language2
* misc
* refer
* src
  + cross_platform
  + windows
    - x86
    - x64
    - armv7
    - all_in_one
  + macos
    - x64
    - ppc
    - all_in_one
  + linux
  + ios
  + ipados
  + watchos
* third-party
* tool

[1]: https://spec.commonmark.org "CommonMark Official Site"