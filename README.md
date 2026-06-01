# fixfile

convert encoding to UTF-8 and line endings to LF

## Properties

|key|value|
|-:|:-|
|  script:|fixfile|
|   short:|convert encoding to UTF-8 and line endings to LF|
|    type:|bash|
|  author:|Wybo Dekker|
|   email:|[wybodekker@me.com](mailto:wybodekker@me.com)|
| version:|1.03|
| license:|GNU General Public License|
|   intro:|fixfile converts the given files in place, as follows:|
|         |- the encoding is converted to the encoding specified by|
|         |the **--encoding**|
|           |option, UTF8 by default.|
|         |- line endings are replaced with linefeeds (**\xA**), or,|
|           |with the **--crlf** option, with carriage return + line|
|           |feed (**\xD\xA**).|
|         |- If the file appears to be an HTML file, non-ASCII|
|         |characters are replaced|
|           |with their HTML equivalents; so for example ö will be|
|           |replaced with **&#xf6;**.|

## Options

|option|description|
|:-|:-|
|-H,--Help	|print full documentation via less and exit|
|-h,--help	|print short help and exit|
|-V,--version	|print version and exit|
|-c,--crlf	|convert line endings to CRLF; default: LF (unix)|
|-e,--encoding=X	|convert to encoding X|
|-v,--verbose	|be [not] verbose (quiet is the default)|
