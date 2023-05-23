# portfolio_martyna_brodka

#   Task 1: Testy eksploracyjne
  ## Subtask 1
  
  10/10 punktów
  
  ## Subtask 3
  
  Witam, mam na imię Martyna. Jestem przekonana, że udział w challenge portfolio pozwoli mi w czytelny i przejrzysty sposób przedstawić moje dotychczasowe dokonania na ścieżce testerskiej oraz uświadomi mi, co jeszcze muszę uzupełnić, aby moje portfolio było pełniejsze, czyli lepsze.
  
  Udział w projekcie Challenge Dare IT wydawał mi się kolejnym trafnym krokiem w samokształceniu jako tester, ale pod okiem wykwalifikowanych i motywujących instruktorów-kobiet. Forma tego wyzwania wpasowała się w moje obecne możliwości czasowe, co ostatecznie mam nadzieję, przełoży się na sukces. Zamierzam ukończyć kurs i wynieść z niego jak najwięcej, by móc ze spokojem startować na wymarzone stanowisko.

## Subtask 4

### I
Aplikacja PANEL SKAUTINGOWY została stworzona dla scautów piłki nożnej, służy do zarządzania meczami, przeglądania zawodników, tworzenia raportów z meczy, opisywania akcji w meczach.

### II
W aplikacji zawarte są szczegółowe informacje o zawodnikach. Oprócz imienia i nazwiska, jest również adres e-mail, telefon, wiek, wzrost, pozycja na boisku, klub do którego przynależy zawodnik, ocena (recenzja), liczba meczy, w których grał oraz inne dane dotyczące zawodnika.

Po wybraniu konkretnego gracza widoczne są zakładki:
- "Mecze" (mecze, w których grał). Do każdego meczu przypisane są dane: drużyna zawodnika, zdobyte gole, stracone gole, drużyna przeciwnika, data meczu, czas gry, recenzja, wprowadzający informacje o meczu (autor);
- "Raporty". W raportach znajdziemy: drużyna zawodnika, zdobyte gole, drużyna przeciwnika, data, ostatnia modyfikacja oraz wprowadzający informacje o meczu (autor), Akcje (gdzie można edytować raport meczowy). Raport meczowy zawiera między poniższe informacje: Wstęp, Inteligencja boiskowa, Mentalność, Podsumowanie, Recenzja, Dane statystyczne.

W każdej chwili można przełączyć język z polskiego na angielski poprzez stale widoczną zakładkę.

### III
Użytkownik aplikacji może:
- dodawać zawodnika (Gracza) i modyfikować jego dane,
- dodawać mecze, edytować dane z meczu, tworzyć raport meczowy, tworzyć dokładną wizualizację meczu w czasie rzeczywistym, zaznaczać akcje, które się dzieją w konkretnym miejscu na boisku,
- dodawać, edytować szczegółowe raporty z gry zawodnika.

W mojej ocenie aplikacja nie jest czytelna, ani intuicyjna. Wymaga dokładnego przeklikiwania, by móc się dowiedzieć, co jeszcze się w niej znajduje. Strona główna wymagałaby poprawek wizualnych, np. więcej grafik. Brakuje zdjęć zawodników.

### IV
Znalezione błędy w aplikacji:
* W zakładce **"Gracze"**:
  * Jest możliwość wpisania ujemnych wartości wagi, wzrostu, wieku
  * Można wybrać rok urodzenia gracza z datą przyszłą
  * Przy wpisywaniu zarówno imienia jak i nazwiska są dozwolone znaki specjalne, cyfry, wyrazy zaczynające się z małej litery, całe nazwy z wielkiej litery, tylko jedna litera
  * Możliwość wpisania wieku w liczbie: 0 lat, 1022 lata
  * Pole "waga" nie ma określonej miary, nie wiadomo czy należy wpisywać w kg, w funtach?
  * Pole "link do YouTube" przyjmuje wartość zwykłego napisu, bez linku
  * Niezrozumiałe pole "łączy nas piłka" oraz "90 minut". Nie wiadomo, jaką treść może/ma zawierać
  * Pole "Pozycja" powinno być wybierane z listy, są to powtarzalne funkcje, a jest możliwość wpisania samodzielnie jakiegokolwiek wyrazu
  * Nie powinno być możliwości wielokrotnego wpisywania tego samego zawodnika (np. Adam Kowalski)
  * Nie ma możliwości przewinięcia listy graczy do ostatniej, konkretnej lub pierwszej strony, co przy ilości kilku tysięcy stron jest utrudnieniem w wyszukiwaniu
  * Zdobyte/stracone gole można zapisać w formacie liczby szesnastkowej
  * Pole "Telefon" przyjmuje wartości literowe, jest nieprecyzyjnie nazwane pole. Zamiast tego powinno być: "Numer telefonu"

* W zakładce **Mecze"**:
  * Po kliknięciu ikony "Rozpocznij mecz" brakuje opisów ikon, po najechaniu na nie myszką. Przez co nie wiadomo, do czego służą
  * Po kliknięciu ikony "Rozpocznij mecz", następnie kliknięciu ikony do rozpoczęcia meczu oraz wybraniu ikony "Strata" są pokazane dwie możliwośći do wyboru: "Zle przyjecie" oraz "Holowanie piłki". Brakuje polskich znaków w ikonie o nazwie "Zle przyjecie".

* W zakładce **"Raporty"**:
  * Przy dodawaniu raportu w punkcie "V. Dane statystyczne" nie można nic dodać. Nie wiadomo, czy to są dane z pozostałych raportów, czy w konkretnym meczu, który dodajemy powinna być możlwiwość wpisania danych np. o "Strzałach", "Pojedynkach" lub innych
  * W "Raporcie meczowym" możliwe jest wpisanie: ujemnego czasu gry, linku do meczu bez linku, ujemnego numeru na koszulce, koloru koszulki w ilości znaków wykraczających poza obszar pola
  * Po kliknięciu zakładki "Raporty" nie ma możliwosći zobaczenia raportu meczowego, dopiero po kliknięciu z prawej strony tabeli "Akcje" jest możliwość zobaczenia raportu o zawodniku, ale już w trybie edycji.

* Pozostałe:
  * W czasie korzystania z aplikacji zakładka "Mecze" oraz "Raporty" widoczna jest dopiero po wybraniu konkretnego "Gracza", przez co użytkownik nie wie, czy to są "Mecze", w kórych tylko ten jeden zawodnik brał udział i czy "Raporty" dotyczą tylko tego jednego gracza, czy jednak nie powinny być te zakładki widoczne na "Stronie głównej"
  
  
#   Task 2: Przypadki testowe (Test cases)
  ## Subtask 1
  
  [Pisanie przypadków testowych na podstawie User Story](https://docs.google.com/spreadsheets/d/17wW2EmyXQof2-13uWYF5mfNGfczgWw1K5h5nRc2g9DA/edit?usp=share_link)
  
  ## Subtask 2
  
  [Pisanie przypadków testowych na podstawie własnych doświadczeń](https://docs.google.com/spreadsheets/d/1qhqq7gvB1-uo2Hk41foYMNccAh6UfEV9Ui-XiaKFGCY/edit?usp=share_link)
  
  ## Subtask 3 - W jakim celu piszemy przypadki testowe?
  
  Przypadki testowe piszemy w celu udokumentowania w czytelny, przejrzysty sposób różnych możliwości obsługiwania modułów w ramach testowanej aplikacji. Wypisując przypadki testowe łatwiej zorientować się, czy nie pominęliśmy jakiejś ważnej funkcjonalności, czy może jednak pominęliśmy coś, co powinno zostać sprawdzone. Przypadki testowe są również dobrym źródłem informacji dla nowej osoby w zespole o pracy zespołu oraz o samej aplikacji. Przypadki testowe można także wykorzystać w celu potwierdzenia działania aplikacji zgodnie z oczekiwaniami.
  
  ## Subtask 4
  
  [Link do zadania grupowego](https://docs.google.com/spreadsheets/d/1VgJt98b6bYua1-8JfPPsxL6sXEJKsAZaQiAxdqr93Bk/edit?usp=share_link)
  
#   Task 3: Raportowanie błędów

  ## Subtask 1
  
  [Zaraportowane błędy](https://docs.google.com/spreadsheets/d/1haXh73EnlIF2jbQ_I6-51CpYrvwtagGsznB-xxmbrRk/edit?usp=share_link)
  
  ## Subtask 2
  
  [Testowanie według przypadków testowych napisanych na podstawie User Story](https://docs.google.com/spreadsheets/d/17wW2EmyXQof2-13uWYF5mfNGfczgWw1K5h5nRc2g9DA/edit?usp=share_link)
  
  [Testowanie według przypadków testowych napisanych na podstawie własnych doświadczeń](https://docs.google.com/spreadsheets/d/1qhqq7gvB1-uo2Hk41foYMNccAh6UfEV9Ui-XiaKFGCY/edit?usp=share_link)
  
  ## Subtask 3
  
  [Raport z testów](https://docs.google.com/spreadsheets/d/1jttRvw_sA15w4ZhtyLvgy9YZXiXuAco_H5eXO2VMW-I/edit?usp=share_link)
  
#   Task 4: Testowanie aplikacji mobilnych
  
  ## Subtask 1 i 2
  
  [Zaraportowane błędy aplikacji OLX](https://docs.google.com/spreadsheets/d/11Pi6VLGrnI0tyeVno8IfymIVcD4892X5/edit#gid=1470010360)
  
  ## Subtask 3
  
  * Aplikacja OLX służy do umieszczania ogłoszeń. Przedmioty można wystawić w kilkunastu kategoriach głównych, takich jak: Antyki i Kolekcje, Motoryzacja, Nieruchomości, Dom i Ogród, Elektronika, Moda, Rolnictwo, Zwierzęta, Dla dzieci, Sport i Hobby, Muzyka i Edukacja, Zdrowie i Uroda, Dla Ogrodu, Rowery. Dostępne są również ogłoszenia dla osób poszukujących pracy bądź pracowników (kategoria Praca lub Praca dodatkowa), a także znajdziemy tam oferty różnych usług (kategoria Usługi i Firmy, Dla Firm, Usługi ogrodnicze). Aplikacja oferuje możliwość zamieszczenia oferty/znalezienia noclegu (kategoria Noclegi), wypożyczalnię rzeczy (kategoria Wypożyczalnia) lub ogłoszenia oddania przedmiotu (kategoria Oddam za darmo). Celem aplikacji jest umożliwienie sprzedawania/kupowania przedmiotów lokalnie lub na obszarze Polski (np. z możliwością wysyłki).
  * Użytkownikiem końcowym aplikacji jest szerokie grono osób: sprzedający, firmy oferujące usługi, pracę, kupujący, osoby chcące oddać przedmioty, obdarowani.
  * Aplikacja nie do końca jest przyjazna dla użytkownika. Znajdując się na stronie głównej nie jestem w stanie wydedukować, czego można się spodziewać dalej. Pojawia się informacja, że znaleziono 1000 ogłoszeń, ale nie wiadomo jaki jest klucz wyboru właśnie tych, czy są one z jakiejś konkretnej kategorii, na jakiej podstawie zostały wyświetlone użytkownikowi. Gdy wchodzę do aplikacji, to muszę ją najpierw przeklikać, by się nauczyć funkcjonalności. W mojej opinii korzystanie z aplikacji natywnej OLX jest znacznie wygodniejsze niż z aplikacji mobilnej OLX. 
  * Co wymaga usprawnienia w aplikacji?
    * Zdecydowanie czas ładowania stron. Wersja mobilna aplikacji długo się ładuje, nie tylko przy dodawaniu ogłoszenia.
    * Nie zawsze pojawiają się powiadomienia o otrzymaniu wiadomości z aplikacji, więc użytkownik jest wprowadzany w błąd, myśląc, że nie czeka na niego żadna wiadomość w aplikacji, jednak po wejściu w nią okazuje się, że wiadomość jest.
    * Po dodaniu zdjęć do ogłoszenia, po jakimś czasie zdjęcia się obracają, mimo, że w czasie dodawania ich widok był w porządku.
  * Jak bym usprawniła aplikację?
    * Zdecydowanie czas ładowania stron w aplikacji powinien zostać skrócony.
  * Co bym w niej poprawiła?
    * Uważam, że nie powinno być możliwośći dodawania opinii przez osoby, które nie zawarły z nami transakcji, a tylko wysłały wiadomość do nas, o coś się zapytały. Opinia takiej osoby jest bezpodstawna, nie jest pełna.
    * Następnie dodałabym możliwość wpisania lokalizacji sprzedającego domyślnie na stałe, w chwili obecnej dodając ogłoszenie za każdym razem trzeba lokalizację wybierać ręcznie, natomiast adres mailowy, imię i telefon są domyślnie uzupełnione.
  * Przy testowaniu aplikacji natywnej trzeba zwrócić uwagę, aby przetestować aplikację na wielu urządzeniach, co jest kosztowne oraz pracochłonne. Ważne jest określenie, którą wersję aplikacji się testuje. Aplikacja natywna daje również możliwość korzystania z zasobów własnego urządzenia mobilnego. Przy testowaniu aplikacji internetowej nie trzeba jej instalować na urządzeniu oraz aktualizować, natomiast trzeba mieć bieżące połączenie internetowe, a także aplikacja nie ma dostępu do zasobów naszego urządzenia.
  
#   Task 5: SQL - part 1
  
  ## Subtask 1
  
  W ramach tego zagadnienia opanowałam zapytania SQL, takie jak: SELECT (służące do znalezienia danych z bazy danych), INSERT INTO (dodawanie danych do tabeli), UPDATE (aktualizacja tabeli), DELETE (usuwanie danych z tabeli). Przy zapytaniu SELECT używałam warunku WHERE do filtrowania rekordów, grupowałam rekordy (operator GROUP BY), sortowałam wyniki (operator ORDER BY), wyszukiwałam dane o określonych zapisach (operator LIKE), dane o wartościach najmniejszych (funkcja MIN), dane o wartościach maksymalnych (funkcja MAX), używałam funkcji AVG w celu zwrócenia średniej wartości kolumny numerycznej, funkcji SUM w celu zwrócenia całkowitej sumy kolumny numerycznej, także wyszukiwałam wartości z określonego zakresu za pomocą operatora BETWEEN.
  
  ## Subtask 3
  
**1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.**
  
  `SELECT * FROM 'actors' ORDER BY surname`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/f2b1ab75-cd80-480f-bd82-b4b3a4c6ce82)
  
**2. Wyświetl film, który powstał w 2019 roku.**

  `SELECT * FROM 'movies' WHERE year_of_production='2019'`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/3f65d551-55b6-4e1e-8a67-7f1d8f9a378f)
  
**3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.**

  `SELECT * FROM 'movies' WHERE year_of_production BETWEEN 1900 AND 1999`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/b10c1a95-4661-4e63-8f5c-72e0da6c1704)

**4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$**

  `SELECT title,price FROM 'movies' WHERE price < '7'`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/3e0d2665-4cf8-4c97-a9c8-f71c22b825ca)

**5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.**

  `SELECT * FROM 'actors' WHERE actor_id >= 4 AND actor_id <= 7`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/7fef63b3-9850-4672-b134-1dcc09aee6f7)

**6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.**

  `SELECT * FROM 'customers' WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/c8251209-b99f-4f93-acc1-48d657c837a1)

**7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.**

  `SELECT * FROM 'customers' WHERE customer_id IN (1, 3, 5)`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/0133e64a-2253-4156-9867-8c6a37c91d75)
  
**8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.**

  `SELECT * FROM 'actors' WHERE name LIKE 'An%'`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/329e5a5d-fdbc-4869-88e5-9b6696379d64)

**9. Wyświetl dane klienta, który nie ma podanego adresu email.**

  `SELECT * FROM customers WHERE email IS NULL`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/2f82f77f-523c-48df-8eef-1c88e028b1e1)
  
**10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.**

  `SELECT * FROM 'movies' WHERE price > 9 AND movie_id >= 2 AND movie_id <= 8`
  
  ![image](https://github.com/martynabrodka/portfolio_martyna_brodka/assets/95524252/92cd0b54-a7a9-41f6-b5b7-57896887acef)
