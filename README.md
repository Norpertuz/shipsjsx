# ShipsJS
Battleship game in Javascript, using jQuery

<h2>Statki by Norpertuz v.1.5</h2>
Instrukcja:<br>
Klasyczna gra w statki. <br> Wygrywa ta osoba co zestrzeli statki drugiej osoby jako pierwsza.<br>
Sterowanie:<br>
PPM - wybieranie kwadratu<br>
LPM - anulowanie wyboru<br>
G - wymazywanie <br>
S - ustawianie statkow<br>
Z - zaznaczanie statków zatopionych <br>
Tylko dla planszy bardzo dużej:<br>
V - Zmiana widoku<br>
L - wyświetlenie logów/menu<br><br>
Wersja Manualna: (Wersja wolna od błędów) <br>
1.Dana jest liczba niebieskich kwadratów,która rózni się zależnie od rozmiaru planszy.<br>
2.Jest również dane jakie statki można ułożyc z dostępnych niebieskich kwadratów. Np. trzy statki "dwukwadratowe" (2x3)<br>
3.Podana jest liczba ułożonych kwadratów niebieskich oraz pozostałych kwadratów niebieskich przeciwnika.<br>
4.Przegrywa ta osoba, której nie zostały żadne niebieskie kwadraty. <br>
5.Na większych planszach zaleca się dopuszczenie większej liczby strzałów przy posiadaniu największych statków, <br>
np. trzy jeśli gracz nie stracił jeszcze statku siedmiokwadratowego, a gdy go straci to dwa strzały, jeśli nie stracił statków sześciokwadratowych<br>

Wersja Automatyczna (beta) <br>
1.Po wybraniu kwadratu należy nacisnąć przycisk zatwierdz.<br>
2.Następnie czekać na odpowiedź kilkając przycisk odpowiadający za sprawdzenie czy udało się trafić.<br>
3.Potem oczekiwać na ruch przeciwnika klikając przycisk,<br> sprawdzający czy druga osoba wykonała ruch. <br>



<h2>Changelog:</h2><br>
21/11/2018 - Początek. <br>
Stworzono prototypową planszę dla jednego z graczy.<br>
Stworzono dwie plansze: strzelania i plansze na statki dla jednego gracza.<br>
Dodano obslugę plików .txt służących do przechowywania informacji o strzelaniu i trafieniach.<br>
22/11/2018<br>
Poprawiono graficzną część strony.<br>
Dodano stronę główną z instrukcją oraz wyborem gracza.<br>
Dodano obsługę dodatkowych plików .txt.<br>
Przeprowadzono testu funkcjonalności gracza pierwszego.<br>
Dodano drugiego gracza.<br>
01/12/2018<br>
Dodano większe plansze<br>
18/11/2019<br>
Poprawiono błędy, wersja manualna działa bez problemu, została ona ulepszona, wersja na plikach posiada błędy na niektorych przeglądarkach. Czasem infromacje z plików nie chcą się wczytać.<br>
08/08/2020<br>
Poprawiono kolorystkę oraz naprawiono związane z nią błędy.<br>
Dodano informacje o kwadratach przeciwnika w wersji manualnej.<br>
Poprawiono błąd - nie można już ustawiać niebieskich kwadratów na planszy przeciwnika w manualnej wersji.<br>
16/08/2020<br>
Zaimplementowano bardzo dużą planszę do wersji manualnej, z osobną funkcjonalnością.<br>
