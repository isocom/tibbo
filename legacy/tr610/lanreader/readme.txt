-----------------------------------------------------------

rev 0001 - Testy wewn�trzne
 + Obs�uga serwera UDP
 + Obs�uga klawiatury
 + Obs�uga przeka�nik�w
 + Obs�uga wbudowanego czytnika kart MIFARE

-----------------------------------------------------------

rev 0002 - Pierwsze publiczne wypuszczenie do klient�w (Czelad�)
 + Obs�uga sauny - tryb X1

-----------------------------------------------------------

rev 0003 - Poprawki wymuszone przez do�wiadczenie na obiekcie i rozszerzenie funckjonalno�ci
 + funckjonalno�� zamiany przeka�nik�w "Relay swap" (WWW)
 + funkcjonalno�� "Display Message" i "Display Text" (UDP)
 + mo�liwo�� wyboru czy parametry IPv4 z DHCP czy r�czne (WWW, domy�lnie DHCP)
 + gdy DHCP zawiedzie, przypisywany adres IP domy�lny - zapisany w EEPROM
 + proba reconectu po 25 sekundach braku konwersacji z serwerem (brak odpowidzi na PING). Gdy si� niepowiedzie to cyklicznie co 30 sekund s� te pr�by ponawiane
 + restart po 10 minutach braku konwersacji z serwerem

-----------------------------------------------------------

