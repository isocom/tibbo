-----------------------------------------------------------

rev 0001 - Testy wewnêtrzne
 + Obs³uga serwera UDP
 + Obs³uga klawiatury
 + Obs³uga przekaŸników
 + Obs³uga wbudowanego czytnika kart MIFARE

-----------------------------------------------------------

rev 0002 - Pierwsze publiczne wypuszczenie do klientów (CzeladŸ)
 + Obs³uga sauny - tryb X1

-----------------------------------------------------------

rev 0003 - Poprawki wymuszone przez doœwiadczenie na obiekcie i rozszerzenie funckjonalnoœci
 + funckjonalnoœæ zamiany przekaŸników "Relay swap" (WWW)
 + funkcjonalnoœæ "Display Message" i "Display Text" (UDP)
 + mo¿liwoœæ wyboru czy parametry IPv4 z DHCP czy rêczne (WWW, domyœlnie DHCP)
 + gdy DHCP zawiedzie, przypisywany adres IP domyœlny - zapisany w EEPROM
 + proba reconectu po 25 sekundach braku konwersacji z serwerem (brak odpowidzi na PING). Gdy siê niepowiedzie to cyklicznie co 30 sekund s¹ te próby ponawiane
 + restart po 10 minutach braku konwersacji z serwerem

-----------------------------------------------------------

