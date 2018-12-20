# if
Index Factor

Unique `=UNIQUE({'2014A'!B:B;'2015IF'!B:B;'2015A'!B:B;'2016A'!B:B;'2016B'!B:B;'2017A'!B:B})`

usun dodatkowe linie: `^(?!\d+,.*,.\d+)(\d+.*)\n` -> `\1`

usun cudzyslowy `(\d+,)"(.*)"(,.*)` -> `\1\2\3`

przecinki na sredniki: `(^\d+),(.*),(.*),(.*),(\d+)` -> `\1;\2;\3;\4;\5`

Szukanie po ISSN
http://journalseek.net/cgi-bin/journalseek/journalsearch.cgi?query=1937-3341&field=title&editorID=&send=Search+Title%2FISSN+Only
