Centrala to aplikacja służąca do zarządzania i koordynacji elementów systemu telekomunikacyjnego. 
Projekt został zaprojektowany tak, aby umożliwić szybkie uruchomienie kompletnego środowiska wraz z domyślną konfiguracją,
dzięki czemu użytkownik może natychmiast rozpocząć pracę bez konieczności ręcznego ustawiania parametrów.
Wykorzystuje FreePBX.

Centrala automatyzuje:

instalację i konfigurację środowiska,
przygotowanie usług telekomunikacyjnych,
tworzenie podstawowych rozszerzeń (extension),
uruchomienie funkcji nagrywania i odsłuchu wiadomości głosowych.
Po instalacji system jest gotowy do działania z predefiniowanymi ustawieniami, takimi jak:

extension 100 z hasłem 123,
numer *777 do nagrywania i odsłuchu wiadomości.

Projekt jest przeznaczony dla środowisk, które wymagają szybkiego wdrożenia centrali do testów telefonów VoIP.

Instalacja:
git clone https://github.com/Emka98/Centrala.git
cd Centrala
chmod +x Install
./Install

Po instalacji w terimanulu wpisz:
sudo centrala -help
Wyświetli to opcje Centrali.

Uwaga! 
Centrala podczas działania przejmuje fizyczny interfejs sieciowy.

Oznacza to, że:
interfejs zostaje skonfigurowany i używany wyłącznie przez Centralę,
może to spowodować utratę połączenia sieciowego na tym interfejsie,

