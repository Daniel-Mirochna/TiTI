# Zadanie 1

### Dane
> transfer: 10 Mb/s\
> czas: 12 godzin

### Obliczenia
> narzut protokołu ~5%

1h = 3600s\
3 600s * 12 = 43200s\
43 200 * 10 Mb = 432 000 Mb\
432 000 / 8 = 54 000 MB\
54 000 / 1024 = 52,734 GB -> teoretyczna maksymalna wielkość pliku \
52.734 * 0.94 = 49,57 GB -> (korekta o retransmisję i narzut protokołu)

> Przepustowość łącza rzędu 10 Mb/s pozwala na pobranie pliku wielkości około 49,57 GB w ciągu 12 godzin.

## Wnioski
- Maksymalna transmisja danych jest mniejsza niz oczekiwana ze względu na narzut protokołu oraz retransmisję danych.
- Przepustowość 10 Mb/s jest niską wartością jak na te lata. 