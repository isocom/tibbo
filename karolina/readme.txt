1. Upewni� si�, �e w urz�dzeniu znajduje si� firmware tios-em1000-3_42_01.bin
Je�li jest inne to nalezy NAJPIERW zainstalowac firmware z katalogu TiOS.
poprzez upload firmware - plik *.bin

2. Nastepnie wgrywamy jedna z aplikacji z tego katalogu poprzez upload application - plik *.tpc
Data oznacza wersje aplikacji.

-----------------------------------------------------------------------------------------------
Alternatywnie uaktualnij oprogramowanie u�ywaj�c pliku 20130811.bin - zawiera on zar�wno
firmware, jak i aplikacj� - scalone dla Twojej wygody w jeden plik. Wgrywa� jako Firmware.
-----------------------------------------------------------------------------------------------

3. Po zainstalowaniu - o ile urz�dzenie nie jest jeszcze skonfugurowane nale�y zalogowa� si�
do chmury, odszuka� je na li�cie urz�dze� po numerze seryjnym a nast�pnie dokona� odpowiedniej
konfiguracji w chmurze.

Poprawnosc instalacji sprawdzamy nast�puj�co:
 - musi sie zegar zsynchronizowac
 - do�o�enie nowej karty powoduje dodanie nowej karty w chmurze

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Jest to pierwsza wersja produkcyjna.
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Zmiany w wersji 2013-08-11:
 - dodano obs�ug� wy�wietlacza przez chmur� - np. komunikat: Witaj Jan Nowak nr karty.
Zmiany w wersji 2013-12-15:
 - obs�uga serwera porttu szeregowego (rejestartor mo�e pracowa� jako RS232 po sieci LAN - tcp)
 - obs�uga czytnik�w Mifare firmy TT Soft, pod��czonych poprzez port szeregowy.
Zmiany w wersji 2014-02-25 (tylko plik *.tpc - wersja firmware jak w 2013-12-15):
 - obs�uga beepera przez chmur� - mo�na w obs�udze requestu wys�a� dowolny wzorzec do odegrania.
 - wysy�anie numeru karty RFID z czytnik�w TT Soft do Google App Engine.
 