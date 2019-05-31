# Dlaczego?
Powody powstania projektu [demogracja.pl](http://www.demogracja.pl/) [domena w trakcie rejestracji]

Czy i Ty uczestniku gry w **demokrację** zadajesz sobie pytanie dlaczego Twoja drużyna nie otrzymała takiego wyniku jakiego oczekiwałeś ?

Słyszałeś już, że: ["Nieważne, kto głosuje, ważne, kto liczy głosy"](https://pl.wikiquote.org/wiki/J%C3%B3zef_Stalin)?

+ Sami policzmy głosy, zróbmy to razem!
+ Pierwszy raz w historii Polski!

Korzystając z otaczających nas technologii można za pomocą odpowiedniego programu komputerowego udostępnić każdemu kto weźmie udział w takim badaniu Exit Pool online **Aktualne dane o wynikach głosowania**

Docelowo dobrze by było, gdyby projekt nie był ograniczony do stworzenia oprogramowania, ale również do informowania i pomocy poszkodowanym w wyborach, dlatego zachęcamy do kontaktu już istniejące instytucje, które się tym zajmują.

## demoGRAcja, czyli Gra w demokrację

Projekt oprogramowania ma na celu możliwość weryfikowania oddanych głosów.
Dotychczas jest to możliwe indywidualnie lub poprzez szacowanie na podstawie osób wychodzących z miejsca głosowania na podstawie badań typu Exit Pool

## Korzyści
Korzyści są dla wyborców i kandydatów, zwłaszcza przy niskiej ilości głosów w małych okręgach, gdyż wówczas łatwo sprawdzić czy kilka głosów zostało oddanych czy nie.

### dla Wyborców
+ możliwość weryfikacji i oddania sprawy do sądu* (potrzebujemy ekspertów, prawników, którzy by mogli całą drogę opisać)

### dla Kandydatów
+ możliwość weryfikacji


## Aplikacja

aby jak najwięcej osób oddających głos mogło skorzystać z tego programu konieczne będzie udostępnienie go na kilka platform.
+ Android
+ IOS
+ Windows
+ online

### W chwili obecnej są wyróżnione 3 oddzielne aplikacje
+ Aplikacja dla użytkownika na przeglądarkę - [WebApp](https://github.com/demogracja/webapp)
+ Aplikacja na serwer do komunikacji z uzytkownikiem [WebApi](https://github.com/demogracja/webapi)
+ Aplikacja na serwer do do zarządzania [WebServer](https://github.com/demogracja/webserver)

Oprogramowanie wymaga analizy i przygotowania specyfikacji, zapraszamy do współpracy programistów z doświadczeniem w technologiach: 
+ NodeJS
+ Python
+ framework VUE
+ Administracja serwerami, chmury, DEVOPS
 
### Zasada działania

3 poziomy weryfikacji:
+ wybranie okręgu wyborczego w aplikacji oraz kandydata na którego został oddany głos
+ po oddaniu głosu należy wykonać fotografię karty do głosowania
+ jak wyżej + dodanie obok naziska dokumentu tożsamości
+ jak wyżej + zakrycie danych wrażliwych na dokumencie

#### Ograniczenia
+ Ilość oddanych głosów na jednym urządzeniu/aplikacji/nr telefonu powinna być do 3 kart do głosowania
ale wówczas potrzebna jest weryfikacja na podstawie dokumentu

+ W przypadku oddania jednego głosu z jednego numeru można zrezygnować z dokumentu, ale trzeba przemyśleć sposób weryfikacji
+ można też odstąpić od weryfikacji bezpośredniej, pozostając przy numerze telefonu i w przypadku nieprawidłowości zgłosić się
indywidualnie do odpowiedniego organu, gdzie sprawa będzie rozstrzygana.




## Kiedy start ?

Aby nie było możliwe manipulowanie należy odpowiednio zabezpieczyć od strony technicznej nie tylko program ale także serwer.
Jest na to czas, kilka miesięcy
Pierwszy raz można wypróbować ten projekt podczas najbliższych wyborów w Polsce. 


## Plan działania

Do projektu może dołączyć każdy, nawet nieprogramista, bo każdy program potrzebuje odpowiedniej specyfikacji, aby działał wedle oczekiwań, następnie trzeba stworzyć kod testowy i kod docelowy realizujący zadania.

Ze swej strony jako autor tej krótkiej notki będę w wolnej chwili pisał kod w python-ie, gdyż jest to bardzo prosty i klarowny język, pozwalający na szybki start w świat programowania nawet nieprogramistom.


Zapraszam do dołączenia do projektu i zgłaszania wszelkich uwag.

## Finansowanie


Projekt jest inicjatywą oddolną, jest otwarty i darmowy, dlatego bardzo istotne dla jego transparentności, by nie był on finansowany ani autorzy projektu.

Ludzie wspierający projekt: programiści oraz prawnicy to osoby zarabiające wystarczająco, by część swojego prywatnego czasu poświęcić na realizację projektu, który w zasadzie wymaga tylko zaangażowania na kilka tygodni.

Jedna rzecz jaka mogłaby być finansowana to serwer oraz usługi potrzebne do utrzymania infrastruktury i jej zabezpieczenia.

Sponsorowane jest tylko to co generuje koszty na czas przeprowadzenia wyborów, czyli infrastruktura oraz dodatkowe usługi, jeśli będą świadczone darmowo i nikt nie wyrazi takiej woli.
Obecnie kosztem są domeny i serwer testowy, pokryte bezpośrednio przez firmę jednego z autorów.


## i Ty Wyborco możesz pomóc!

Zapoznaj się drogi Wyborco z poniższymi sekcjami projektu, potrzebne są również nie-eksperci!

Być może coś jest źle sforumułowane lub znasz kogoś kto może pomóc.

Przed wyborami na jesieni 2019 będzie przeprowadzany test działania aplikacji i serwerów, dlatego będzie potrzebna większa ilośc osób w celu przeprowadzenia symulacji wyborów i przetestowania całej platformy.

### Informacje

#### Sekcje dla każdego, kto podchodzi krytycznie do wyborów w demokracji, tutaj można zgłosić problemy:

+ [problemy](https://github.com/demogracja/problemy)

+ [Pytania i Odpowiedzi](FAQ.md)


#### Sekcje dla programistów:

+ [webapp](https://github.com/demogracja/webapp)

+ [webapi](https://github.com/demogracja/webapi)

+ [webserver](https://github.com/demogracja/webserver)

+ [serwer](https://github.com/demogracja/serwer)

+ [blockchain](https://github.com/demogracja/blockchain)

+ [kryptografia](https://github.com/demogracja/kryptografia)


#### Sekcja dla prawników i ekspertów od prawa wyborczego w Polsce

+ [lex](https://github.com/demogracja/lex) 

#### Zespół
+ [autorzy](https://github.com/demogracja/autorzy) 

