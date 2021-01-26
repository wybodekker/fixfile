# fixfile
|     key | description
|     ---:|:---
|  script | fixfile - convert encoding to UTF-8 and line endings to LF
|    type | bash
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 1.02
| license | GNU General Public License

fixfile converts the given files in place, as follows:
- the encoding is converted to the encoding specified by the --encoding
option, UTF8 by default.
- line endings are replaced with linefeeds (
), or,
with the --crlf option, with carriage return + line feed (
).
- If the file appears to be an HTML file, non-ASCII characters are replaced
with their HTML equivalents; so for example ö will be replaced with &
