# crc32
Berechnet den CRC-32 für Dateien entsprechend dem Verfahren ISO 3309, das auch bei PKZIP eingesetzt wird.

crc("123456789") = 0xCBF43926

CRCs eignen sich gut, um schnell Dateien zu vergleichen.
Da WINDOWS Zeilenenden in Textdateien mit einem Zeichen mehr codiert, gibt es eine Option, um das fehlende Zeichen bei UNIX-Dateien zu ergänzen.
Eine weitere Option ermöglicht es, Leerzeichen am Zeilenende nicht in die Berechnung einzubeziehen.
