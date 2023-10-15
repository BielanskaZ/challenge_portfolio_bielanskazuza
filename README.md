# Task 1 

Link do [Folderu projektowego](https://drive.google.com/drive/folders/1c4sKS66uCayTp5wvnn-Ec3eMAT5dYItf?usp=drive_link)


## **Subtask 1**

*5/10*


## **Subtask 3**

*Challenge jest dla mnie być może początkiem kariery w IT. Testowanie już pojawiało się w moim życiu na poziomie amatorskim i zawsze mnie irytowały błędy na stronie. Po kursie może przyczynię się do zredukowania ich ilości.*

## **Subtask 4**

*Aplikacja służy do przeglądania umiejętności, wskaźników i pozycji graczy, hehe. A tak serio, to do testowej zabawy.*

**Funkcjonalności:**

*Link do kontaktu z Dev Team, który przenosi na Slacka. - Mógłby lepiej przenosić do zakładki na stronie z podanym mailem/numerem telefonu do odpowiedniej osoby.*

*Zakładka "Gracze" przenosi do listy graczy. Każdą pozycję gracza można otworzyć poprzez pojedyncze kliknięcie. Wtedy przenosi nas do danych wprowadzonych na temat gracza. Pod zakładką "Gracze" wysuwają się podzakładki "Mecze" i "Raporty". Klikając w każdą z nich, zostajemy kolejno przeniesieni do listy meczy i raportów na temat gracza.*

*Z poziomu Strony Głównej klikając w link "Dodaj gracza" zostajemy przeniesieni do formularza, w którym trzeba uzupełnić odpowiednie dane. Formularz przyjmuje niepoprawnie wprowadzone dane, w tym: *

*- adres e-mail bez znaku @*

*- numer telefonu wprowadzony literami oraz za małą liczbą znaków*

*- parametry wagi i wzrostu przyjmują wartości przekraczające wartości trzycyfrowe*

  **BUG**

*- pole daty urodzenia w parametrach dnia i miesiąca urodzenia reaguje jedynie na wpisanie jednej cyfry (jeżeli przekracza się realną wartość) , co powoduje, że dzień i miesiąc urodzenia nie może być większy, niż 9. Jeżeli wpisywana jest możliwa wartość dnia i miesiąca, pole dnia po wpisaniu daty płynnie przeskakuje do pola mieisąca, a następnie roku. Natomiast rok urodzenia można wprowadzić dowolny, od 0000 do 27..60.*
  
*- po kliknięciu w ikonę kalendarza można wybrać rok od 27..60 w dół, a datę dowolną klikając w odpowiednio podświwtlone nazwy miesięcy i liczby dni.*

*- okienko "Łączy nas piłka" pozostaje w języku polskim po zmianie języka strony na angielski*
  
*- w polu "link do YouTube" można wpisać dowolny tekst, który jest przepuszczony przez formularz*

*- Jednak po tak błędnie wprowadzonych danych dodanie gracza nie powiodło się - formularz nie pokazuje, które pola są źle wypełnione.*

*- Po poprawieniu jedynie poprawnie wpisanego maila i daty urodzenia - dodanie gracza powiodło się. Pokazuje się komunikat koloru zielonego w prawym górnym rogu. Parametry wagi i wzrostu nadal pozostają nierealnie wysokie.*
  
*- W trakcie poprawiania daty urodzenia, pole podświetla się na czerwono. Po wpisaniu poprawnej daty - dodanie gracza powiodło się.*
  
*- Kliknąwszy w zakładkę "Gracze" nowo dodany gracz nie wyświetla się.*
  
*- Kliknąwszy w "Strona Główna" nowo dodany graczy wyświetla się w liście "Aktualności"*

  **Zakładka Mecze**

  *- możliwa do znalezienia po otwarciu karty danego gracza*
 
    **BUG**
    
 * - w formularzu dodawania meczu przepuszczane są niepoprawnie wpisywane dane: liczby zdobytych i utraconych goli, daty.*
 
  *- Cały formularz jes w języku polskim, ale pojawiają się dwa okienka w języku angielskim: "Web match" i "General"*
 
  *- można wprowadzić datę przyszłą, niż obecna wybierając poprzez ikonkę kalendarza*
 
  **Zakładka Raporty**

  **BUG**

  *- kliknąwszy w "dodaj mecz" jesteśmy przekierowani do zakładki "Mecze" danego gracza*
 

# Task 2

## **Subtask 1**

[Link do Subtask1.](https://docs.google.com/spreadsheets/d/1T3_R22yGdqxJsbpXPG28u_gK6QOLF6qPWk_xrSxX5rE/edit?usp=drive_link)


## **Subtask 2**

[Link do Subtask2.](https://docs.google.com/document/d/106BkGkVR6ybQhSErXewnJ49jk-t8r5nKzeorQRtviko/edit?usp=drive_link)


## **Subtask 3**

*Przypadki testowe pisane są po to, żeby tester mógł bez problemu, krok po kroku przetestować daną funkcjonalność i docelowo, aby wyeliminować wszelkie defekty/błędy na stronie/w aplikacji.*

## **Subtask 4**

[Link do Subtask4](https://docs.google.com/spreadsheets/d/15VfjP6AsxuIDrHiARE14TpvZYTjIqo8LWIOzHe5AiLE/edit?usp=sharing)


# Task 3

## ** Subtask 2**

[Odświeżone test case'y](https://docs.google.com/document/d/106BkGkVR6ybQhSErXewnJ49jk-t8r5nKzeorQRtviko/edit?usp=drive_link)

## **Subtask 3**

[Raport błędów](https://docs.google.com/document/d/1tA4LZHMmo20s-RcLRZ7eAZTM_g4U8caUtoYuNz30HnU/edit?usp=drive_link)

# Task 4

## **Subtask 1,2**

[Testy eksploracyjne + raportowanie błędów](https://docs.google.com/spreadsheets/d/1Hc_evp5BGB846c2DbLYQv77qv65HhbuXkujkkrkrQeA/edit?usp=drive_link)

## **Subtask 3**

*Testowana wyżej aplikacja OLX.com służy do sprzedaży oraz kupna rzeczy na skalę prywatną, a także do wystawiania ogłoszeń transakcyjnych takich jak:*

*- adopcja zwierząt*

*- wynajem nieruchomości*

*- oddanie rzeczy za darmo*

 * Końcowym użytkownikiem aplikacji ma być dosłownie każdy. Osoba, która chce coś kupić, sprzedać, oddać. Osoba, która nie chce obowiązać się umową kupna/sprzedaży i osoba, która musi obowiązać się takową umową. Wszystko w granicach dozwolonego prawa.*

  *Aplikacja natomiast jest nie do końca user friendly. Tak, ma nawigację położoną nisko, dzięki czemu można łatwo dodać ogłoszenie, wrócić na stronę główną, wejść w zakładkę polubionych. Łatwo też można odnaleźć kafelki prowadzące do kategorii ogłoszeń, a także wybrać sortowanie ustawiając konkretne filtry. Jest jednak kilka mankamentów, które można by było poprawić tak, aby użytkownik nie był wprowadzany w błąd, np. informacja o ZAlogowaniu przy próbie WYlogowania, sprawniejsze ładowanie strony, bug typu pojawienie się niebieskiej ikony przy ikonie dzwoneczka, prowadzącej do powiadomień, a w powiadomieniach brak żadnych. Jest też kwestia sekcji "Profil kandydata", która jest dostępna tylko dla zalogowanych użytkowników, jednak kiedy klikamy w zakładki "Nowa praca", "Moje aplikacje", bez żadnego powiadomienia jesteśmy przenoszeni na aplikację internetową do ponownego logowania, co może zaniepokoić użytkownika.
  W zakładce "Praca" przydałoby się wprowadzić możliwość wybrania widełek płacowych do filtrowania ogłoszeń.*

 *Testowanie aplikacji internetowej jest dla mnie w odczuciu łatwiejsze i przebiega szybciej, gdyż w aplikacji natywnej jest sporo nagromadzonej treści na małej przestrzeni ekranu. Przynajmniej w przypadku testowanych przeze mnie wyżej aplikacji. Było ich niewiele, dlatego ciężko jest wyciągnąć wspólne cechy i uogólnić, ale wydaje mi się, że aplikacja natywna jest jednak cięższa do testowania choćby dlatego, że nie da się za bardzo sprawdzić, czy coś nie działa jedynie ze względu na system operacyjny, czy jest w niej szerszy problem, dopóki nie ma się urządzeń z różnymi systemami operacyjnymi.*


# Task 5/6

## **Subtask 1**

*SQL - operatory/zapytania:*

*- 'SELECT * FROM' (nazwa schematu{.nazwa tabeli})*

*- wsad = więcej, niż jedno zapytanie*

*- 'GO' pod pierwszym zapytaniem = oddziela dwa zapytania we wsadzie --> pozwala na sprawniejsze wykonanie skryptu*

*- [] Nawiasy kwadratowe po 'SELECT * FROM': kiedy używamy spacji w nazwie shematu*

*- 'SELECT (nazwy kolumn), FROM (nazwa tabeli)'*

*- Zmienianie nazw danych kolumn: 'AS'. Np.: 'SELECT (obecna nazwa) AS (przyszła nazwa)'*

*- 'ORDER BY' = sortowanie rosnąco*

*- 'ORDER BY (nazwa kolumny) DESC' = sortowanie malejąco*

*- filtrowanie danej wartości z tabeli: SELECT (nazwa kolumny/tabeli) FROM (nazwa kolumny/tabeli) WHERE (wpisujemy nazwy kolumn, które mają spełniać warunki filtrowania, gdzie używamy operatorów '=', '<', '>', '<>' lub '!=' 'OR' lub 'IN (kilka wartości)' lub 'AND', jeżeli chcemy filtrować więcej, niż zawartość jednej kolumny)*

## **Subtask 2-3**
![Zrzut ekranu 2023-10-7 o 09 42 45](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/9a3c78ce-203d-4d5e-b1e2-a807c925a447)


![Zrzut ekranu 2023-10-7 o 09 31 38](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/89875212-357b-4de4-9be7-89e495d03ddb)

![Zrzut ekranu 2023-10-7 o 09 55 27](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/931d34a7-848d-411f-a831-c2012eb800f5)

![Zrzut ekranu 2023-10-7 o 09 59 02](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/d75c15fe-cb5d-4d7a-9956-bf77839c9bec)

![Zrzut ekranu 2023-10-7 o 10 01 37](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/79af2ca5-f056-45ca-9508-cd23c83ec3a8)

![Zrzut ekranu 2023-10-7 o 10 02 21](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/febd6541-e738-49c3-9ffe-4829c7101bfd)

![Zrzut ekranu 2023-10-7 o 10 22 48](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/4f46ceb3-8b40-4e2a-872c-c1a7d8e12364)

![Zrzut ekranu 2023-10-7 o 10 29 38](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/ac2d1dff-f670-41ba-b4d4-874317d6ff78)

![Zrzut ekranu 2023-10-7 o 10 36 25](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/49af89ef-8ddf-4626-b8b4-6748c050f8d0)

![Zrzut ekranu 2023-10-7 o 10 38 06](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/f87fed6e-22fb-4caa-b4bc-9643420e2a8d)

![Zrzut ekranu 2023-10-7 o 10 40 08](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/083a4a9b-504b-475f-b21f-b29dad325c8c)

![Zrzut ekranu 2023-10-7 o 10 46 46](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/bdb4b772-80da-4e7e-b62f-c9e89f905c4d)

![Zrzut ekranu 2023-10-13 o 13 43 17](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/fb11162b-c11c-47ee-a9e1-bdce418e5443)

![Zrzut ekranu 2023-10-13 o 13 45 27](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/b569158e-42d8-4c79-8231-d181246b1895)


![Zrzut ekranu 2023-10-13 o 13 49 31](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/9cca5949-ea17-49f7-890e-87577f2c1cdb)

![Zrzut ekranu 2023-10-13 o 13 50 18](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/428528a6-7617-4556-b578-bb01626973a6)


![Zrzut ekranu 2023-10-13 o 14 11 08](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/b1b741c4-8a51-4fff-b87b-d5526cc8ba9d)

![Zrzut ekranu 2023-10-13 o 19 20 05](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/469144d0-036b-421d-98cd-f8c53f01e236)

![Zrzut ekranu 2023-10-13 o 19 28 41](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/dcdc9721-fb80-4359-9a9e-5a00d8f7ca0d)

![Zrzut ekranu 2023-10-13 o 19 30 55](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/cb468613-87c2-4498-9895-48a638173bde)

![Zrzut ekranu 2023-10-13 o 19 34 55](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/851a803b-7fa2-4200-a872-c252c257dbd9)

![Zrzut ekranu 2023-10-13 o 19 35 43](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/597d4f26-6324-4d25-9011-147f8a8734bc)

![Zrzut ekranu 2023-10-13 o 19 46 26](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/7e3b7439-906c-40f6-ba20-75d6a7b2f738)

![Zrzut ekranu 2023-10-13 o 19 46 39](https://github.com/BielanskaZ/challenge_portfolio_bielanskazuza/assets/143724852/8ddde11b-0b4f-46ed-be70-2d910c6ade86)
