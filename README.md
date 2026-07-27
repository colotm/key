# Open Source Keyman keyboards

## File Layout

Keyboards are grouped into three folders:

  * `release` - keyboards with full source that pass our stringent quality checks, Unicode only
  * `legacy` - binary distributions of keyboards, migrated from Tavultesoft servers, Unicode and
    non-Unicode
  * `experimental` - keyboards that have not yet passed the quality check, available from the
    'experimental' category in Keyman apps with Keyman 10 and later. Unicode only.

Within each of the folders, keyboards are further grouped by first letter or by prefix, where
multiple keyboards share the same prefix indicating provenance, for example `sil` or `gff`.
