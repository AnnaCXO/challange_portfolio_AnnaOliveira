# **Task 1**
## Subtask 2  
7/10 :slightly_smiling_face:
## Subtask 3
Cześć! Nazywam się Ania i postanowiłam wziąć udział w projekcie żeby dowiedzieć się więcej na temat pracy testera manualnego i przekonać się czy jest to dla mnie ciekawa kariera. Mam nadzieję, że ten kurs pomoże mi nauczyć się czegoś nowego i przygotuje do poszukiwań pracy w IT. :blush:

**Ania**
## Subtask 4
* Scouts panel służy do zarządzania graczami, meczami i do tworzenia raportów.
* W aplikacji można dodać graczy, edytować ich profile, a także sprawdzać i edytować raporty dotyczące meczów. Najmniej zrozumiałą częścią aplikacji jest dla mnie strona, która otwiera się po kliknięciu przycisku "Rozpocznij mecz". Na stronie nie ma instrukcji jak działa ta funkcjonalność.
* Interfejs aplikacji jest bardzo prosty. Aplikacja na pierwszy rzut oka wygląda bardzo nieprofesjonalnie. Na stronie brakuje kolorów. Na stronie głównej poszczególne sekcje są rozmieszczone dosyć nieintuicyjnie, na stronie jest bardzo dużo pustych przestrzeni. Ze strony głównej nie można do końca wywnioskować jaki jest cel tej aplikacji. Aplikacja jest dopasowana do wersji mobilnej. Strona główna wygląda lepiej w wersji mobilnej niż w wersji podstawowej. Lista graczy jest bardziej czytelna w wersji na komputer.
* Niektóre elementy aplikacji są intuicyjne. Na stronie głównej łatwo można znaleźć przycisk otwierający formularz dodawania nowego zawodnika. W formularzu przeszkadza mi, że nie wszystkie pozycje można wybrać z listy rozwijanej, np. poziom rozgrywek, główna pozycja i pozycja alternatywna. Istnieje przez to ryzyko, że w te pola zostaną wpisane niewłaściwe dane. Poza tym, tak jak wspomniałam wcześniej, najmniej intuicyjną częścią aplikacji jest symulator meczu otwierający się po kliknięciu przycisku "Rozpocznij mecz", ponieważ trudno jest zrozumieć jak dokładnie działa.
* Wiele błędów występuje w formularzu dodawania/edycji gracza. W niektórych polach nie zostały zastosowane odpowiednie reguły dlatego też możliwe jest wprowadzanie nieprawidłowych danych, np.: 
     * pole "Telefon" akceptuje zarówno litery jak i cyfry, 
  
     ![image](https://user-images.githubusercontent.com/122388964/212731218-8d35eb92-d061-43b7-aaab-897415132eeb.png)
     * w polach "Waga" i Wzrost" można wpisać dowolne liczby (również ujemne), 
     * w polu "email" można dodawać cyfry i litery bez "@",
     
     ![image](https://user-images.githubusercontent.com/122388964/212731338-5022c240-99d2-4db7-8169-c000d66d839b.png)
     * w polach przeznaczonych na wklejanie linków do innych stron można wpisać dowolne znaki; poza tym pola te moga być nieco mylące co do tego co jest oczekiwane od użytkownika dlatego sugerowałabym dodanie "(URL)" w tytule pola,
     * pole "Data urodzenia" jest przetłumaczone na język angielski jako "Age" co może być mylące dla użytkownika,
     * w niektórych polach powinna być zastosowana lista rozwijana żeby ograniczyć możliwość wybierania błędnych odpowiedzi.
 * Inne błędy to:
     * Przy rozgrywaniu meczu, po naciśnięciu przycisku timera wartość pola "Połowa" wzrasta za każdym razem podczas gdy jedyne dopuszczalne liczby jakie powinny się tam wyświetlać to 1 i 2.
   ![image](https://user-images.githubusercontent.com/122388964/212731525-3a6342ac-7b48-48da-a012-577ce5bd0bcf.png)
     * na stronie głównej link "Wróć do raportu" w polu "Niezapisany mecz" nie działa; w DevTools pojawia się poniższy błąd:
   ![image](https://user-images.githubusercontent.com/122388964/212730994-41b28e2e-2e6b-4d21-8852-609e242be39c.png)
   
 # **Task 2**
 ## Subtask 1
 https://docs.google.com/spreadsheets/d/1keXRuWVqGCo2SdvVVEflmbq8yQtR3toCkysqf5P-JM8/edit?usp=sharing
 ## Subtask 2
 https://docs.google.com/spreadsheets/d/1c8rf0i5nKH54h1kjnUt9ije0AIYEWUfWXuAGjU4WrK0/edit?usp=sharing
 ## Subtask 3
 **Po co piszemy test case'y?**
   
 Uważam, że piszemy przypadki testowe w celu usystematyzowania naszej pracy. Widząc przygotowany przez nas test case, inny tester może postępować zgodnie z instrukcjami i przeprowadzić test. Dzięki test case'om możemy być pewni, że każdy test będzie przygotowany w ten sam sposób oraz sprawdzić jakie są oczekiwane rezultaty.
## Subtask 4
https://docs.google.com/spreadsheets/d/13AvTZHPUZB0LJtrLYVHj0qyKZV1nVi8n0ZVp4iLLjeg/edit?usp=sharing

 # **Task 3**
 ## Subtask 2
 https://docs.google.com/spreadsheets/d/1v2JlFgRZ2DXRsIvM8OhzJD9L08Zkp_L5tyLj00l7_GI/edit?usp=share_link
 
 ## Subtask 3
 https://docs.google.com/document/d/1_mSgTB-UuMUhViiBT-GMvgbn2fkMf6leX1a0Qy9d9Uo/edit?usp=share_link
 
 # **Task 4**
 ## Subtask 1 i 2
 https://docs.google.com/spreadsheets/d/1rEfvQtyQG8CO99SwYetzjPegZIBCsdyLLrtfu9OT8fc/edit?usp=share_link
 
 ## Subtask 3
 **Do czego służy ta aplikacja?**
 1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?
 
 Aplikacja OLX służy do publikowania ofert sprzedaży, wymiany, oddania różnych produktów i usług oraz umożliwia zakup tych usłu i produktów poprzez kontakt ogłoszeniodawcy z użytkownikiem.
 
 2. Kto ma być użytkownikiem końcowym aplikacji?
 
 Użytkownikami aplikacji są osoby które chcą sprzedać, oddać zamienić produkty lub usługi oraz osoby które tych produktów lub usług poszukują.
 
 3. Czy według Ciebie aplikacja jest user friendly?
 
 Uważam, że aplikacja jest przyjazna dla użytkownika. Szczególnie przydatne są duże przyciski z nazwami kategorii wyszukiwania oraz różne możliwości filtrowania i sortowania wyników.
 
 4. Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?
 
 Nie znalazłam w aplikacji opcji zmiany języka na angielski, co według mnie jest dużym minusem. Myślę również, że przydatną opcją przynajmniej w niektórych kategoriach byłaby możliwość bezpośredniego zakupu przedmiotów bez konieczności kontaktu ze sprzedawcą (tak jak w przypadku Allegro).
 
 5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?
 
 Myślę, że bardzo ważnym czynnikiem jest wygląd aplikacji i sprawdzenie czy konwersja z wersji komputerowej na mobilną przebiegła pomyślnie, czy wszystkie przyciski i opcje są dobrze widoczne. W aplikacji natywnej istotne jest sprawdzić czy jest ona dopasowana do różnej wielkości ekranów. Ważne jest również aby przetestować czy wszystkie przyciski można łatwo wybrać za pomocą palce, który jest mniej precyzyjny niż kursor myszki. Dużą róznicą w testowaniu aplikacji jest także to, że w aplikacji internetowej łatwiej jest sprawdzić kod i wyłapać w nim na bieżąco błędy w trakcie wykonywania test casów. W przypadku testowania aplikacji natywnych nie ma takiej możliwości.

## Subtask 4
https://wannai.atlassian.net/jira/software/projects/DIT/boards/2

https://wannai.atlassian.net/browse/DIT-12?atlOrigin=eyJpIjoiYjc0OWQ3MzYyNzExNGJmNmFkOGExYzAwZmFlM2M3MjQiLCJwIjoiaiJ9
![image](https://user-images.githubusercontent.com/122388964/216930754-5227f391-66ff-4256-9efe-8331fa87cf50.png)

![image](https://user-images.githubusercontent.com/122388964/216930816-713f2e9c-ba03-41bb-9886-9efaa607bdaa.png)

# **Task 5**
## Subtask 1
* SELECT GETDATE() - wyświetla aktualną datę
* SELECT @@version - wyświetla wersję oprogramowania
* SELECT TOP () - wyświetla pierwsze wartości
* SELECT * FROM nazwa tabeli - wyświetla zawartość całej tabeli
* SELECT nazwy kolumn FROM nazwa tabeli- wyświetla wybrane kolumny z tabeli
* CREATE TABLE nazwa (id int) - tworzy nową tabelę
* ORDER BY nazwa kolumny - sortuje dane w tabeli według danej kolumny
* ORDER BY nazwa kolumny DESC - sortuje dane w tabeli malejąco według danej kolumny
* SELECT nazwy kolumn

  FROM nazwa tabeli
  
  WHERE nazwa kolumny =<> BETWEEN - filtrowanie danych
  
* SELECT COUNT, SELECT SUM, SELECT MIN - funkcje agregujące zliczające ilość, sumę, liczbę minimalną
* SELECT *
FROM nazwa tabeli
JOIN nazwa tabeli - łączenie tabeli

## Subtask 3
1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

SELECT * FROM actors
ORDER BY surname

![image](https://user-images.githubusercontent.com/122388964/218054095-3ba0a7f2-0787-4e30-a171-183a1dba7be0.png)

2. Wyświetl film, który powstał w 2019 roku.

SELECT * FROM movies
WHERE year_of_production = 2019

![image](https://user-images.githubusercontent.com/122388964/218054732-ef46de0e-0ea9-44d1-a91a-1d309bdbe827.png)

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

SELECT * FROM movies
WHERE year_of_production BETWEEN 1900 AND 1999

![image](https://user-images.githubusercontent.com/122388964/218055087-7171a41c-9216-4ab1-b177-767cedfd06a8.png)

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$

SELECT title, price FROM movies
WHERE price < 7

![image](https://user-images.githubusercontent.com/122388964/218055871-166c7e4c-f5ba-40f4-9113-eab177932cc8.png)

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

SELECT * FROM actors
WHERE actor_ID >= 4 AND actor_ID <= 7

![image](https://user-images.githubusercontent.com/122388964/218057822-62a981bd-de8b-4493-83c1-eb9cc72a84ac.png)

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

SELECT * FROM customers
WHERE customer_ID = 2 OR customer_ID = 4 OR customer_ID = 6

![image](https://user-images.githubusercontent.com/122388964/218058618-9b0c4943-d2c6-4593-a7f7-456063cdd584.png)

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

SELECT * FROM customers
WHERE customer_ID IN (1, 3, 5)

![image](https://user-images.githubusercontent.com/122388964/218058842-32276401-687d-406b-99cc-dcb99e0dbe0b.png)

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

SELECT * FROM actors
WHERE name LIKE 'An%'

![image](https://user-images.githubusercontent.com/122388964/218059310-51f7a545-90c3-4442-b6c2-b4d25ddeb724.png)

9. Wyświetl dane klienta, który nie ma podanego adresu email.

SELECT * FROM customers
WHERE email IS NULL

![image](https://user-images.githubusercontent.com/122388964/218059584-23e0fa5a-b27b-4266-a951-9212f5ea4806.png)

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

SELECT * FROM movies
WHERE price > 9 AND movie_ID BETWEEN 2 AND 8

![image](https://user-images.githubusercontent.com/122388964/218060467-6079cf4a-3bbe-4d85-97f4-1fbde410b704.png)

# **Task 6**
## Subtask 1
11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd

UPDATE customers SET surname = 'Miler' WHERE surname = 'Muler'

SELECT * FROM customers

![image](https://user-images.githubusercontent.com/122388964/219615820-cc530a6e-d029-408a-bd99-8e106dcf8cef.png)

12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

SELECT sale.customer_id, movie_id,name, surname, email
FROM customers, sale
where customers.customer_id = sale.customer_id AND movie_id = 4

![image](https://user-images.githubusercontent.com/122388964/219618550-78ce6e5f-91f5-4c99-a750-d4e93e417c92.png)

13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com

UPDATE customers set email = 'pati@mail.com' WHERE name = 'Patrycja'

SELECT * FROM customers

![image](https://user-images.githubusercontent.com/122388964/219619365-ccee81e4-cf53-4a77-9ea0-8094f2a3154d.png)

14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

SELECT customers.name, customers.surname, movies.title
FROM customers
inner JOIN sale
ON customers.customer_id = sale.customer_id
inner JOIN movies
ON movies.movie_id = sale.movie_id

![image](https://user-images.githubusercontent.com/122388964/219622807-8c711171-67ce-4fc3-bd37-767510bf1da5.png)

15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

ALTER TABLE customers ADD COLUMN pseudonym varchar(10)

UPDATE customers SET pseudonym = concat(LEFT(name,2) + (RIGHT(surname,1))

SELECT * FROM customers

![image](https://user-images.githubusercontent.com/122388964/219634494-1e4b1edc-6081-43cc-bd9f-457e532d2856.png)

16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

SELECT DISTINCT movies.title
from sale, movies
WHERE movies.movie_id = sale.movie_id

![image](https://user-images.githubusercontent.com/122388964/219651015-fa6c113b-f804-4a8d-b833-6419df598f74.png)

17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

SELECT actors.name
from actors
UNION
SELECT customers.name
from customers
order by name

![image](https://user-images.githubusercontent.com/122388964/220057719-14729e7c-c489-4726-917a-d6c7055694af.png)

18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

UPDATE movies set price = price + 2.5 WHERE year_of_production > 2000

![image](https://user-images.githubusercontent.com/122388964/220058958-f2a5b300-a6cc-437a-a6e9-60618dfcabf0.png)

19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał

select cast.actor_id, actors.name, actors.surname, movies.title
FROM actors, movies, cast
WHERE cast.actor_id = actors.actor_id AND cast.movie_id = movies.movie_id and cast.actor_id = '4'

![image](https://user-images.githubusercontent.com/122388964/220060321-a3ef4a21-7796-4bdc-a872-f28807b71806.png)

20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa

insert into customers (customer_id, name, surname, email, pseudonym)
VALUES (7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')

SELECT * FROM customers

![image](https://user-images.githubusercontent.com/122388964/220062886-62dd7d4a-a2e6-4932-9597-e98044bbd721.png)

## Subtask 2
8\15

## Subtask 3
https://github.com/AnnaCXO/Portfolio_AnnaOliveira.git


