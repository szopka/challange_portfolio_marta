# challange_portfolio_marta

## TASK 1
### Subtask 1
###### 10/10 punktów :smiley:
### Subtask 3
###### Cześć tu Marta! Na wstępie (choć może nie powinnam tak...) strasznie się jaram tym challengem :grinning:.A dlaczego się zdecydowałam - dosłownie 2 miesiące temu weszłam nieśmiało na ścieżkę testerską jako totalny "świeżak", nie umiejąc prawie nic...( i nadal umiem niewiele, dlatego zdobywam co mogę na własną rękę). Dodatkowo po czasie spędzonym z moimi dziećmi w domu czuję głód, wilczy głod wiedzy! Chcę więcej i mocniej! A Dare IT ufam i wiem, że wyniosę dla siebie sporo i wzbogacę swoje doświadczenie!
### Subtask 4
#### Do czego służy aplikacja?
Aplikacja w zamyśle miała służyć do zarządzania graczami oraz meczami piłki nożnej i do tworzenia raportów.
#### Funkcjonalności
- panel logowania
- wyświetlenie listy wszytskich graczy
- dodawanie gracza
 -  dodawanie meczy dla graczy
 - generownie raportów
 - uruchomienie meczu i dodanie informacji o akcji z meczu
 - raport meczowy

#### Ocena interfejsu
Bardzo duży chaos, strona jest prosta, ale wygląda jakby powstała bez planu np. dodawanie gracza nie odbywa się z lewego menu a z linku pomocniczego na środku strony. Wchodząc w zakładkę "gracze" nie można dodać nowego gracza, funkcjonalności pozagnieżdżane, niedostępne ze strony głównej, ciężko znaleźć stworzone raporty

#### Intuicyjność
brak intuicyjności, brak porządku i jakichkolwiek zasad. Strona nie posiada żadnej struktury, dlatego ciężko się po niej poruszać.

#### Błędy
- literówki
- dodawanie zawodnika - kompletnie nie wiem czym są pola pomiedzy buttonami "dodaj język" a "dodaj link z youtuba"
- brak wytycznych dotyczących wpisywania danych o graczach np. brak jednolitego formatu dla wieku, dopuszczone wartości ujemne dla wieku, dopuszone znaki specjalne oraz cyfry w polu imię i nazwisko, brak ograniczen co do liczby znaków
- w funkcjonalości - dodawania gracza w wersji angielskiej nie wszystkie pola przetłumaczone ("łączy nas piłka", "90 minut")
- w polu link możliwe jest zapisanie zwykłego tekstu nie URL
- dodawanie meczu - część formularza po angielsku
- opcja uruchomienia meczu i zapisania w nim akcji gracza (czepiam się, ale placeholder w oknie komentarzy przy dodawaniu akcji za bardzo przyklejony do lewej krawędzi :D) - brak informacji do czego służą buttony nad boiskiem, możliwość dodania wielu połówek meczu
- w wersji mobilnej brak możliwości dodawania akcji podczas meczu


## TASK 2


### Subtask 1 
(patrz zakladki w pliku :upside_down_face:)

https://docs.google.com/spreadsheets/d/1GNO9gsMaKOLFxStR4nERPtgUnJ2K0XqZ8_6cHvbaXXg/edit?usp=share_link

### Subtask 2
https://docs.google.com/spreadsheets/d/1fKoXLa8gdyVTkWsSdMCVouYJ7awFAUQ3F1KGhvhrLCM/edit?usp=share_link

### Subtask 3
###### Po co piszemy test casy?
Piszemy je, żeby zachować porządek, mieć jasność co do tego, co jest do wykonania.
Jeśli pracujemy w grupie, test casy jasno przedstawiają, co jest do wykonania.
Dodatkowo rozpisane TC będą niezastąpione przy retestach lub regresji, gdy trzeba będzie odtworzyć cały lub częściowy cykl testowy.

*To tyle, uprasza się o łagodne traktowanie, jako, że pisanie test casów wykończyło me wątłe zdrowie* :smiling_imp:

![meme](https://s3.memeshappen.com/memes/Enough-Test-cases--meme-40783.jpg)!

## TASK 3


### Subtask 1

[defect sheet](https://docs.google.com/spreadsheets/d/13Aztky405tAc1lmBdkNsgUmOiG10nXpSFx1elPr5YfU/edit?usp=share_link)

### Subtask 2

[Subtask 1](https://docs.google.com/spreadsheets/d/1GNO9gsMaKOLFxStR4nERPtgUnJ2K0XqZ8_6cHvbaXXg/edit?usp=share_link) 
[Subtask 2](https://docs.google.com/spreadsheets/d/1fKoXLa8gdyVTkWsSdMCVouYJ7awFAUQ3F1KGhvhrLCM/edit?usp=share_link

### Subtask 3

[test reprort](https://drive.google.com/file/d/1_p7mlkXooOBLpQMA2XKDWnEl8ptX6ufo/view?usp=share_link)

## TASK 5


### Subtask 1
Zapytania SQL:

CREATE DATABASE nazwa_db

USE nazwa_db

SELECT nazwa_kolumny/ * AS nazwaAliasu
FROM nazwa_tabeli

SELECT * from nazwa_tabeli
ORDER BY nazwa_kolumny

SELECT GETDATE()

SELECT UPPER('jakies tekst')
SELECT LOWER('jakies tekst')

SELECT DATEDIFF(HOUR 'data godzina", 'data godzina')
               (MONTH 'data', 'data')
               (YEAR 'data', 'data')
               
SELECT COUNT(nazwa_columny) from nazwa_tabeli

SELECT MAX(nazwa_columny) from nazwa_tabeli 
SELECT MIN(nazwa_columny) from nazwa_tabeli

SELECT SUM(nazwa_columny) from nazwa_tabeli

SELECT nazwa_kolumny FROM nazwa_tabeli
GROUP BY nazwa_kolumny

grupowanie i agregacja
SELECT kol_1, count(*) FROM nazwa_tabeli
GROUP BY kol_1

łączenie tabel
SELECT * FROM tabela_1
JOIN tabela_2
ON kolumna_tab_1 = kolumna_tab_2

alisy tabel

SELECT t1.nazwa_kolumny, t2.nazwa_kolumny FROM tabela_1 AS t1
JOIN tabela_2 AS t2
ON kolumna_tab_1 = kolumna_tab_2

### Subtask 3

#### Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
 
SELECT * FROM actors
order by surname 

![image](https://user-images.githubusercontent.com/42693051/218572586-a561a041-a446-4235-8fb6-c69fd95c8056.png)

#### Wyświetl film, który powstał w 2019 roku.

SELECT title, year_of_production FROM movies
where year_of_production = 2019;

![image](https://user-images.githubusercontent.com/42693051/218573718-9331ada4-c69a-45e6-8e88-326d8b7eb3d1.png)

#### Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

SELECT title, year_of_production FROM movies
where year_of_production BETWEEN 1900 AND 1999;

![image](https://user-images.githubusercontent.com/42693051/218573977-c3a6845e-5f3e-4337-b208-df79d54402cb.png)

#### Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$

SELECT title, price FROM movies
where price < 7

![image](https://user-images.githubusercontent.com/42693051/218574839-0d177534-3049-4fa6-8bef-9e14d6d6045e.png)

#### Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

SELECT * FROM actors
where actor_id >= 4 AND actor_id <= 7

![image](https://user-images.githubusercontent.com/42693051/218575923-9e775069-02fe-42bf-8720-1091e9ca2ddf.png)


#### Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

SELECT * FROM customers
WHERE customer_id=2 OR customer_id=4 OR customer_id=6

![image](https://user-images.githubusercontent.com/42693051/218578444-2b0a7199-4657-488c-aa2b-dba8e78c55b2.png)


#### Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

SELECT * FROM customers
WHERE customer_id in (1, 3, 5)

![image](https://user-images.githubusercontent.com/42693051/218579166-06dc317c-32d4-45eb-a937-711e7ad82e0d.png)


#### Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”

SELECT * FROM actors
WHERE name LIKE 'An%'

![image](https://user-images.githubusercontent.com/42693051/218579567-1f1c22cc-2d4e-48f7-bf2a-52aa9829b0a2.png)

#### Wyświetl dane klienta, który nie ma podanego adresu email.

SELECT * FROM customers
WHERE email IS null

![image](https://user-images.githubusercontent.com/42693051/218580045-0e0aa3b9-ab9e-4413-88df-35d7869cc3d0.png)

#### Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id

SELECT * FROM movies
WHERE price > 9 and movie_id BETWEEN 2 AND 8

![image](https://user-images.githubusercontent.com/42693051/218580513-0a1bcac7-9429-4627-9181-1d6be625b7e6.png)

## TASK 6

### Subtask 1

#### 11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈
DATE customers
SET surname = 'Miler'
WHERE customer_id = 3

![image](https://user-images.githubusercontent.com/42693051/219623984-ba1894af-4800-4641-b33e-4a54b4c3ec0e.png)

#### 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

select c.name, c.surname, c.email, s.movie_id, s.customer_id
from customers AS c
inner JOIN sale AS s ON c.customer_id = s.customer_id
WHERE c.customer_id = 4

![image](https://user-images.githubusercontent.com/42693051/219788534-b1fab83c-22c5-41a8-93d2-b34f287dbb29.png)

#### 13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com 

UPDATE customers
set email = 'pati@mail.com'
where customer_id = 4

![image](https://user-images.githubusercontent.com/42693051/219790474-06e28d78-9061-4e79-b1b9-43a12596ba45.png)


#### 14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).
SELECT c.name, c.surname, m.title
FROM ((sale as s
INNER JOIN customers as c ON s.customer_id = c.customer_id)
INNER JOIN movies as m on s.movie_id = m.movie_id)


#### 15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag
ALTER TABLE customers
ADD pseudonym varchar(5); 

UPDATE customers
SET pseudonym = concat(LEFT(name,2), RIGHT(surname,1));
 ![image](https://user-images.githubusercontent.com/42693051/219902162-072d0201-9d99-4fb9-bfee-da713808af34.png)


#### 16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

SELECT DISTINCT m.title
from movies as m
INNER JOIN sale as s 
on m.movie_id=s.movie_id;

![image](https://user-images.githubusercontent.com/42693051/219972613-8635cca5-1e41-444c-86a2-9407449d30c7.png)


#### 17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

SELECT name FROM actors
UNION
SELECT name from customers
ORDER BY name;

![image](https://user-images.githubusercontent.com/42693051/219973075-c52dc34f-e152-4c81-8a60-a14b9d1397c5.png)


#### 18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie). 

UPDATE movies
set price=price + 2.5
where year_of_production>2000;

![image](https://user-images.githubusercontent.com/42693051/219975704-1053a21a-ed9a-4a24-a878-3bae5bf1502b.png)


#### 19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał

SELECT  a.actor_id, a.name, a.surname, title
from ((actors as a
INNER JOIN cast as c on a.actor_id=c.actor_id)
INNER JOIN movies as m on m.movie_id=c.movie_id)
WHERE a.actor_id=4;

![image](https://user-images.githubusercontent.com/42693051/219974445-a510b096-54d4-4337-81ed-3634f0391c27.png)


#### 20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa
INSERT INTO customers
VALUES (7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa');

![image](https://user-images.githubusercontent.com/42693051/219976040-7d6a33e4-2925-46be-a0ba-dfdbe35e058e.png)

### Subtask 2 

11/15

### Subtask 3

[PORTFOLIO](https://github.com/szopka/PORTFOLIO)





