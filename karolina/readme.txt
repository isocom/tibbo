1. Upewniæ siê, ¿e w urz¹dzeniu znajduje siê firmware tios-em1000-3_42_01.bin
Jeœli jest inne to nalezy NAJPIERW zainstalowac firmware z katalogu TiOS.
poprzez upload firmware - plik *.bin

2. Nastepnie wgrywamy jedna z aplikacji z tego katalogu poprzez upload application - plik *.tpc
Data oznacza wersje aplikacji.

-----------------------------------------------------------------------------------------------
Alternatywnie uaktualnij oprogramowanie u¿ywaj¹c pliku 20130811.bin - zawiera on zarówno
firmware, jak i aplikacjê - scalone dla Twojej wygody w jeden plik. Wgrywaæ jako Firmware.
-----------------------------------------------------------------------------------------------

3. Po zainstalowaniu - o ile urz¹dzenie nie jest jeszcze skonfugurowane nale¿y zalogowaæ siê
do chmury, odszukaæ je na liœcie urz¹dzeñ po numerze seryjnym a nastêpnie dokonaæ odpowiedniej
konfiguracji w chmurze.

Poprawnosc instalacji sprawdzamy nastêpuj¹co:
 - musi sie zegar zsynchronizowac
 - do³o¿enie nowej karty powoduje dodanie nowej karty w chmurze

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Jest to pierwsza wersja produkcyjna.
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Zmiany w wersji 2013-08-11:
 - dodano obs³ugê wyœwietlacza przez chmurê - np. komunikat: Witaj Jan Nowak nr karty.
Zmiany w wersji 2013-12-15:
 - obs³uga serwera porttu szeregowego (rejestartor mo¿e pracowaæ jako RS232 po sieci LAN - tcp)
 - obs³uga czytników Mifare firmy TT Soft, pod³¹czonych poprzez port szeregowy.
Zmiany w wersji 2014-02-25 (tylko plik *.tpc - wersja firmware jak w 2013-12-15):
 - obs³uga beepera przez chmurê - mo¿na w obs³udze requestu wys³aæ dowolny wzorzec do odegrania.
 - wysy³anie numeru karty RFID z czytników TT Soft do Google App Engine.
 