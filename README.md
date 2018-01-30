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

