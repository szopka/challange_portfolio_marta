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

### Subtask 2

https://docs.google.com/spreadsheets/d/1FJpszWl1i7Sr17xxEeJMNroumkMNNFEDECX1vSWQblc/edit?usp=sharing

### Subtask 3

Na wstępie napiszę, że cieżko w mojej odpowiedzi brakować będzie świeżości, bo olx towarzyszy nam od wielu lat i poniekąd zakorzenił się już trochę w naszej świadomości. No więc - jest to aplikacja do sprzedaży/wymiany (pierwotnie lokalnie) lub poszukiwania pracownika. Użytkownikiem ma być każdy, umiejący obsłużyć urządzenie mobilne oraz (ewentualnie) płatność i wysyłkę. Aplikacja sama w sobie nie jest skomplikowana, nawigacja jest dość prosta. Jeśli chodzi o usprawnienia  - mi osobiście przeszkadzją reklamy - zaśmiecają wizualnie i treściowo - ale to bolączka chyba wielu aplikacji. 

Jeśli chodzi o testowanie mobilne od webowego to różnicą dla mnie jest zwracanie uwagi na inne aspekt, przy testowaniu mobilnym przedewszystkim responsywność, zeby wszytsko dobrze wyglądało na małych ekranach, żeby było intuicyjne i poniekąd ergonomiczne oraz do ogarnięcia jedna ręką. Pewną trudnością testowania mobilnego i przy tym także różnicą jest konieczność (w przypadku aplikacji natywnych) testowania urządzeń działających na innych systemach operacyjnych - oddzielny kod pisany dla każdego systemu operacyjnego.

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





