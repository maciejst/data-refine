no_sql
======

Skrypt do pobierania kodów wraz z danymi(.json) oraz wersja .csv utworzona przy pomocy narzędzia google-refine.
Dane to kody-pocztowe gmin.


Skrypt php wykorzystuje api strony sejmometr.pl, po zarejestrowaniu się na stronie, pobraniu kluczy ściągamy bibliotekę do api (folder ep_API), osadzamy klucze. Po załączeniu biblioteki do skryptu możemy już korzystać z wszystkich funkcjonalności udostępnianych przez sejmometr.

Fragment CSV:
```csv
kod,kod_int,liczba_gmin,wojewodztwo_id,liczba_powiatow,gminy,wojewodztwo,miejscowosci_str

00-002,2,1,7,1,Warszawa,mazowieckie,Warszawa (Śródmieście)

00-003,3,1,7,1,Warszawa,mazowieckie,Warszawa (Śródmieście)

00-004,4,1,7,1,Warszawa,mazowieckie,Warszawa (Śródmieście)

00-005,5,1,7,1,Warszawa,mazowieckie,Warszawa (Śródmieście)

00-006,6,1,7,1,Warszawa,mazowieckie,Warszawa (Śródmieście)

00-007,7,1,7,1,Warszawa,mazowieckie,Warszawa (Śródmieście)

00-008,8,1,7,1,Warszawa,mazowieckie,Warszawa (Śródmieście)
```
