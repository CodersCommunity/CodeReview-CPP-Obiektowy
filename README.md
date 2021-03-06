#Code Review - Obiektowy C++

* [Code Review - o co chodzi?](http://forum.pasja-informatyki.pl/125757/code-reviews-moich-odcinkow-na-yt-dlaczego-istnieja) kursu obiektowego C++.
* [CR - Podstawy](https://github.com/CodersCommunity/CodeReview-CPP-Podstawy)

Kod jest podzielony na 2 branche:
1. **master** - zawierający oryginalny kod
2. **refactor** - zawierający kod po poprawkach

Poszczególne odcinki są do podzielone na foldery, wg konwencji: *odc-XX*, gdzie *XX* to nr odcinka.

Do aplikacji okienkowych użyłem biblioteki [Qt](https://www.qt.io/), która moim zdaniem nadaje się lepiej do demonstacji obiektowego
C++ i pisania aplikacji okienkowych.

Zapraszam do *pull request'ów* z wlasnymi propozycjami (np na nowych branchach lub w przypadku bledu z mojej strony dorzucania poprawek na **refactor**).


## Spis treści

1. [odc 1 - Podejście obiektowe. Klasy. Obiekty](odc-01/)
1. [odc 2 - Struktura projektu obiektowego](odc-02/)
1. [odc 3 - Konstruktory. Destruktory. Dostęp: public, private, protected](odc-03/)
1. [odc 4 - Funkcje zaprzyjaźnione](odc-04/)
1. [odc 5 - Dziedziczenie. Klasy pochodne](odc-05/)
1. [odc 6 - Funkcje wirtualne. Polimorfizm](odc-06/)
1. [odc 7 - Instalacja Buildera. Okienkowy Hello World](odc-07/)
1. [odc 8 - Własny Notatnik w Builderze](odc-08/)
1. [odc 9 - Tic-tac-toe - gra w kółko i krzyżyk](odc-09/)
1. [odc 10 - Timery. Własny zegar. Gra Arkanoid](odc-10/)
1. [odc 11 - Dźwięk w programie. Gra w pamięć](odc-11/)


## Uwagi ogolne

### Odcinki 1-6

Ogolnie nie jest zle, jednakze notorycznie powtarzaja sie globalne uzycia `using namespace` co w przypadku wiekszych projektow jest zla praktyka.

Oprocz tego kod lubi byc malo czytelny poprzez np brak odstepow pomiedzy operatorami albo ich nadmierne uzycie.

Nie liczac tych drobnych potkniec potrafia sie znalezc rzeczy typu przkombinowanie rozwiazania lub niestosowanie sie  do oglnie przyjetych konwencji.


### Odcinki 7-8

Implementacje do tych odcinkow zostaly zrealizowane w bibliotece *Qt*, goraco zachecam do przeczytania wpisu: [Dlaczego Qt, a nie Builder](dlaczego-qt.md).

...TODO...


### Odcinki 9-11

Implementacje do tych odcinkow zostaly zrealizowane w bibliotece *SFML*, goraco zachecam do przeczytania wpisu: [Dlaczego SFML, a nie Builder](dlaczego-qt.md).

...TODO...


## Literatura warta uwagi

Na tym etapie nauki warto miec za soba lekture:

1. [C++ Best Practices](https://lefticus.gitbooks.io/cpp-best-practices/content/)
2. [Czysty Kod](http://lubimyczytac.pl/ksiazka/83492/czysty-kod-podrecznik-dobrego-programisty)
3. Dowolny *Style Guide*, np. [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)


## Dziennik zmian
1. 21.02.2017 - (shead) Wrzucam poprawiony kod do odcinkow 1-6, jezeli ktos ma dodatkowe uwagi do tych zmian to oczywiscie smialo ;)
2. 25.02.2017 - (shead) Odcinki 7, 8; [artykul](dlaczego-qt.md) wyjasniajacy wybor innych narzerzi niz C++ Builder

