# Task1 

Link do [Folderu projektowego](https://drive.google.com/drive/folders/1c4sKS66uCayTp5wvnn-Ec3eMAT5dYItf?usp=drive_link)


## **Subtask 1**

*5/10*


## **Subtask 3**

*Challenge jest dla mnie być może początkiem kariery w IT. Testowanie już pojawiało się w moim życiu na poziomie amatorskim i zawsze mnie irytowały błędy na stronie. Po kursie może przyczynię się do zredukowania ich ilości.*

## **Subtask 4**

Aplikacja służy do przeglądania umiejętności, wskaźników i pozycji graczy, hehe. A tak serio, to do testowej zabawy.

**Funkcjonalności:**

Link do kontaktu z Dev Team, który przenosi na Slacka. - Mógłby lepiej przenosić do zakładki na stronie z podanym mailem/numerem telefonu do odpowiedniej osoby.

Zakładka "Gracze" przenosi do listy graczy. Każdą pozycję gracza można otworzyć poprzez pojedyncze kliknięcie. Wtedy przenosi nas do danych wprowadzonych na temat gracza. Pod zakładką "Gracze" wysuwają się podzakładki "Mecze" i "Raporty". Klikając w każdą z nich, zostajemy kolejno przeniesieni do listy meczy i raportów na temat gracza.

Z poziomu Strony Głównej klikając w link "Dodaj gracza" zostajemy przeniesieni do formularza, w którym trzeba uzupełnić odpowiednie dane. Formularz przyjmuje niepoprawnie wprowadzone dane, w tym: 

- adres e-mail bez znaku @

- numer telefonu wprowadzony literami oraz za małą liczbą znaków

- parametry wagi i wzrostu przyjmują wartości przekraczające wartości trzycyfrowe

  **BUG**

- pole daty urodzenia w parametrach dnia i miesiąca urodzenia reaguje jedynie na wpisanie jednej cyfry (jeżeli przekracza się realną wartość) , co powoduje, że dzień i miesiąc urodzenia nie może być większy, niż 9. Jeżeli wpisywana jest możliwa wartość dnia i miesiąca, pole dnia po wpisaniu daty płynnie przeskakuje do pola mieisąca, a następnie roku. Natomiast rok urodzenia można wprowadzić dowolny, od 0000 do 27..60.
  
- po kliknięciu w ikonę kalendarza można wybrać rok od 27..60 w dół, a datę dowolną klikając w odpowiednio podświwtlone nazwy miesięcy i liczby dni.

- okienko "Łączy nas piłka" pozostaje w języku polskim po zmianie języka strony na angielski
  
- w polu "link do YouTube" można wpisać dowolny tekst, który jest przepuszczony przez formularz

- Jednak po tak błędnie wprowadzonych danych dodanie gracza nie powiodło się - formularz nie pokazuje, które pola są źle wypełnione.

- Po poprawieniu jedynie poprawnie wpisanego maila i daty urodzenia - dodanie gracza powiodło się. Pokazuje się komunikat koloru zielonego w prawym górnym rogu. Parametry wagi i wzrostu nadal pozostają nierealnie wysokie.
  
- W trakcie poprawiania daty urodzenia, pole podświetla się na czerwono. Po wpisaniu poprawnej daty - dodanie gracza powiodło się.
  
- Kliknąwszy w zakładkę "Gracze" nowo dodany gracz nie wyświetla się.
  
- Kliknąwszy w "Strona Główna" nowo dodany graczy wyświetla się w liście "Aktualności"

  **Zakładka Mecze**

  - możliwa do znalezienia po otwarciu karty danego gracza
 
    **BUG**
    
  - w formularzu dodawania meczu przepuszczane są niepoprawnie wpisywane dane: liczby zdobytych i utraconych goli, daty.
 
  - Cały formularz jes w języku polskim, ale pojawiają się dwa okienka w języku angielskim: "Web match" i "General"
 
  - można wprowadzić datę przyszłą, niż obecna wybierając poprzez ikonkę kalendarza
 
  **Zakładka Raporty**

  **BUG**

  - kliknąwszy w "dodaj mecz" jesteśmy przekierowani do zakładki "Mecze" danego gracza
 

# Task 2

## **Subtask 1**

[Link do Subtask1.](https://docs.google.com/spreadsheets/d/1T3_R22yGdqxJsbpXPG28u_gK6QOLF6qPWk_xrSxX5rE/edit?usp=drive_link)


## **Subtask 2**

[Link do Subtask2.](https://docs.google.com/document/d/106BkGkVR6ybQhSErXewnJ49jk-t8r5nKzeorQRtviko/edit?usp=drive_link)


## **Subtask 3**

Przypadki testowe pisane są po to, żeby tester mógł bez problemu, krok po kroku przetestować daną funkcjonalność i docelowo, aby wyeliminować wszelkie defekty/błędy na stronie/w aplikacji.

## **Subtask 4**

[Link do Subtask4](https://docs.google.com/spreadsheets/d/15VfjP6AsxuIDrHiARE14TpvZYTjIqo8LWIOzHe5AiLE/edit?usp=sharing)


# Task 3

## ** Subtask 2**

[Odświeżone test case'y](https://docs.google.com/document/d/106BkGkVR6ybQhSErXewnJ49jk-t8r5nKzeorQRtviko/edit?usp=drive_link)

## **Subtask 3**

[Raport błędów](https://docs.google.com/document/d/1tA4LZHMmo20s-RcLRZ7eAZTM_g4U8caUtoYuNz30HnU/edit?usp=drive_link)


