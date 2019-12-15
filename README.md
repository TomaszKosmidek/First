##	Baza danych
###	Firebird
Plik bazy danych Firebird powinien znajdować się w lokalizacji „C:\fbDB\database.fdb”. Serwer powinien być udostępniony na hoście localhost na porcie 3050. Nazwa użytkownika do bazy SYSDBA z hasłem password. Aplikacja testowana z wersją Firebird 3.0.4. Możliwe działanie z innymi podwersjami 3.0 niewykluczone. Wersje wcześniejsze niż 3.0 nie będą działać ze względu na użyte funkcje dostępne tylko od wersji 3.0.
###	ClickHouse
Serwer bazy ClickHouse powinien się znajdować na hoście localhost na porcie 8123. Nazwa użytkownika bazy default bez hasła. Aplikacja testowana z bazą w wersji 19.17.2. Działanie 
z innymi wersjami niewykluczone.

##	Wykorzystane technologie
*	Język Java 8
  -	Będzie to główny język wykorzystany do pisania aplikacji. 
*	JavaFX
  -	Będzie to narzędzie do tworzenia graficznego interfejsu użytkownika.
*	Baza danych ClickHouse
  -	Będzie to baza, w której będą przechowywane informacje potrzebne do poprawnego działania aplikacji.
*	Baza danych FireBird
  -	Będzie to baza, w której będą przechowywane informacje potrzebne do poprawnego działania aplikacji.
*	Scene Builder
  -	Będzie używany do projektowania interfejsu użytkownika
*	Maven
  -	Dzięki Mavenowi będzie możliwe kompilowanie projektu bez konieczności dostarczania plików .jar potrzebnych do kompilacji.
*	Hibernate
  -	Będzie służyć do do mapowania obiektowo-relacyjnego
*	Dia
  -	Projektowanie diagramów UML
*	Draw.io
  -	Projektowanie diagramu ERD
