# column-tsv

Print a tab-separated-value (TSV) text file in columns.

Syntax:

    column-tsv <file>

Example:

    column-tsv example.tsv | less

This script works on both typical Debian and typical macOS.

The `column` command on vanilla macOS is missing the flag `-n`,
so our implementation looks for any missing column entry and
replace the entry with a blank space, so the display works.


## Tracking

  * Program: column-tsv
  * Version: 1.0.0
  * Created: 2018-01-29
  * Updated: 2018-01-29
  * License: GPL
  * Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)