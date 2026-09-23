## nixie clock
Brak kodu źródłowego, pozostał na mim starym PC do którego aktualnie nie mam dostępu.

Projekt jest moim pierwszym projektem z wykorzystaniem mikrokontrolera. Zegar zbudowałem w ciuągu 1 miesiąca na 30 urodziny mojej siostry. Moim pierwotnym celem było zbudowanie wyjątkowego prezentu ręcznie wykonanego z zachowaniem pełnej estetyki w stylu retro.

## Wyzwania Inżynierskie
* to mój pierwszy projekt embedded (wcześniej pisałem jedynie skrypty Autohotkey)
* zaprojektowanie układu PCB w eaglu na siatce zgodnej z rastem płytki uniwersalnej z zachowaniem jak najmniejszej ilości zworek i kątów prostych
* każda ścieżka jest wzmocniona drucikiem miedzianym, polutowanie całości w estetyczny sposób zajęło mi prawie tydzień za pomocą lutownicy transformatorowej
* lampy pozyskałem ze starych multimetrów na allegro
* kilkukrotna wymiana sekcji HV do zasilania lamp, przetwornice nie działały za 1 razem
* całość była napisana w arduino IDE, komunikcja z RTC odbywała się poprzez I2C i już wtedy konieczne były drobne poprawki w bibliotece I2C
* w ramach edukacji obsługę enkodera napisałem od 0 samodzielnie
* opracowanie metody sterującej lampami z wykorzystaniem SPI i rejestrów przesównych
* opracowanie efektu do odświeżania lamp (catode poisoning), w każdej pełnej minucie wszystkie znaki są zapalane sekwencyjnie

## Stan projektu
* zegar działa nieprzerwanie od 2018r. Nie wymagał żadnych aktualizacji w programie a elektronika nie zawodzi a katody w lampach nie wypalają się. Pierwotnie myślałem, że wytrzyma to max 2 lata a póki co cieszy oko ;)
* jedyną wadą jest przekłamywanie pomiaru temperatury na plus z powodu lokalizacji czujnika pod obudową

## film na YT pokazujący zegar w akcji
[![Watch the video](https://img.youtube.com/vi/NN6xQ5y-V2Y/maxresdefault.jpg)](https://youtu.be/NN6xQ5y-V2Y)

## galeria kilku poglądowych zdjęć
![1](images/IMG_20180215_072054.jpg)
![2](images/IMG_20180226_105730.jpg)
![3](images/IMG_20180328_061403.jpg)
![4](images/IMG_20180401_085340.jpg)
![5](images/IMG_20180401_085501.jpg)
