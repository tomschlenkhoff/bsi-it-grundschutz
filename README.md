# BSI IT-Grundschutz

## ePUB / AZW3 / mobi Version des aktuellen Entwurfs des BSI IT-Grundschutzes

Stand: Final Draft vom 27.10.2017

Weitere Informationen zum [BSI IT-Grundschutz / ISO27001](https://www.bsi.bund.de/DE/Themen/ITGrundschutz/itgrundschutz_node.html).
Ich habe lediglich die Original-Fassung von dort in die gängigen eBook-Formate gewandelt damit die Praktiker leichter nachlesen und suchen können.
Das Urheberrecht liegt vollständig beim BSI.

Die Konvertierung erfolgt per [calibre](https://calibre-ebook.com/) mit folgendem Kommando:

	/Applications/calibre.app/Contents/MacOS/ebook-convert HTML/startseite_it_grundschutz/startseite.html big.epub --output-profile kindle_voyage --search-replace replace_patterns.txt --author-sort BSI --authors BSI --book-producer BSI --title-sort IT-Grundschutz --title IT-Grundschutz --language de

	/Applications/calibre.app/Contents/MacOS/ebook-convert HTML/startseite_it_grundschutz/startseite.html big.mobi --output-profile kindle_voyage --search-replace replace_patterns.txt --author-sort BSI --authors BSI --book-producer BSI --title-sort IT-Grundschutz --title IT-Grundschutz --language de

[calibre Settings](https://manual.calibre-ebook.com/generated/en/ebook-convert.html#metadata)

Auf dem Mac ist das Programm 'ebook-convert' typischerweise unter "/Applications/calibre.app/Contents/MacOS/" zu finden.

Besser lesbar wird das Ergebnis wenn die CSS-Styles vorher noch entfernt werden.

Fragen und Anregungen zur Konvertierung bitte per GitHub Issue an mich.

## Download
<a href="https://github.com/tomschlenkhoff/bsi-it-grundschutz/blob/master/big.mobi" download="download">mobi</a>
<a href="https://github.com/tomschlenkhoff/bsi-it-grundschutz/blob/master/big.epub" download="download">ePUB</a>

_Bei Fragen und Anregungen rund um den IT-Grundschutz wenden Sie sich bitte an:_

	Bundesamt für Sicherheit in der Informationstechnik
	Referat CK 31
	Postfach 20 03 63
	53133 Bonn
	Telefon: 0228 99 9582-5369
	+49 228 99 9582-5369
	E-Mail: grundschutz@bsi.bund.de

[IT-Grundschutz Gruppe im Xing Forum](https://www.xing.com/net/itgrundschutz)

