### Przejrzyj przechwycone dane w programie Wireshark, sprawdź adresy IP i MAC trzech stron internetowych dla których wykonałeś polecenie ping. Poniżej wpisz, docelowy adres IP i MAC dla wszystkich trzech stron internetowych.

| Lokalizacja | IP | MAC |
| ----------- | ----------- | --------- |
| www.yahoo.com | 188.125.89.204 | 94:3c:96:4e:e9:10 |
| www.google.com | 142.251.98.104 | 94:3c:96:4e:e9:10 |
| www.cisco.com | 2.23.244.120 | 94:3c:96:4e:e9:10 |

### b. Co jest istotne w tej informacji?

Adresy IP są różne, a adres MAC ten sam.

### c. Czym różni się ta informacja od informacji uzyskanej w części 2, dotyczącej używania polecenia ping w sieci lokalnej?

jak wyżej

### Dlaczego Wireshark pokazuje aktualny adres MAC dla hostów lokalnych, ale już nie pokazuje aktualnego MAC dla hostów zdalnych?

Pakiety przechodzą przez router, który nadpisuje adres MAC następnych urządzeń na trasie pakietu. Widzimy tylko adresy IP.