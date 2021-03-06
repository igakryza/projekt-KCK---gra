# Komunikacja Człowiek-Komputer :walking: :left_right_arrow: :computer:

*Human-Computer Interaction*


Przedmiot prowadzony jest dla studentów 2-ego roku kierunku kognitywistyka na Uniwersytecie Adama Mickiewicza w Poznaniu. :mortar_board:

### :e-mail: Kontakt do prowadzących

 * dr inż. Marcin Jukiewicz (koordynator) marcin.jukiewicz[at]amu.edu.pl
 * mgr Dawid Ratajczyk, dawid.ratajczyk[at]amu.edu.pl, dyżur czwartek 11:30-12:30, 110
 * mgr Mikołaj Buchwald, mikolaj.buchwald[at]amu.edu.pl, dyżur środy 16:45-17:45, 110

### :books: Z czego składa się kurs?

Kurs składa się z dwóch zasadniczych części:
 1. Tworzenie stron internetowych
 2. Analiza biosygnałów

Podczas realizacji każdej części wykonujemy projekt w grupach dwuosobowych. Oceny wystawiane są indywidualnie.

Ocena końcowa jest wypadkową dwóch ocen z projektów.

###  :scroll: Kryteria oceny projektów

Skala ocen z projektów: 2.0, 3.0, 3.5, 4.0, 4.5, 5.0

Wymagania ogólne:
 * :octocat: projekt znajduje się na GitHubie,
 * :page_with_curl: raport zgodny z wytycznymi z materiałów do wykładu z AiWD ([tutaj](https://www.dropbox.com/s/myy9xeyedng4myb/aiwd-4.pdf?dl=0)).

Wymagania odnośnie raportów:

 * Oceniana będzie wartość merytoryczna projektu oraz strona formalna raportu. Szczegółowe kryteria będą ustalane przy omawianiu projektu. Na ocenę merytoryczną będzie składać się m. in.:
   - kreatywność pomysłu,
   - jakość wykonania,
   - złożoność projektu,
   - estetyka.
 * Przy stronie formalnej raportu należy zwrócić uwagę na:
   - obecność strony tytułowej zgodnej z wytycznymi podanymi na wykładzie,
   - prawidłowo wykonane podpisy pod grafikami,
   - opisy tabel,
   - obecność bibliografii/źródeł.
   
#### Wymaganie szczegółowe dot. projektu II

Projekt zakłada stworzenie interfejsu gry lub oprogramowania użytkowego sterowanego przy pomocy mrugnięć. Zadanie polega na rozwinięciu programu znajdującego się w folderze Templatka_projekt2. Dwie opcje rozwoju projektu to:
 * stworzenie własnego interfejsu (gry) w oparciu o pythona z wykorzytaniem paczek psychopy/pygame/Tkinter i zintegrowanie go z programem do wykrywania mrugnięć(maksymana ocena **5**)
 * znalezenie oprogramowania/gry w języku python i zintegrowanie go z programem do wykrywania mrugnięć (maksymalna ocena **4**)

Głównym plikiem, na którym powinni Państwo bazować, jest *templatka.py*. Plik *filterlib.py* służy do filtracji sygnału, natomiast plik *blink.py* do wykrywania mrugnięć.

* Informacje dotyczące pliku *templatka.py*:
  - Zmienna *SYMULACJA_SYGNALU* ustala (True/False) czy program ma pobierać dane z Ganglionu, czy symulować wcześniej nagrany sygnał (przy pobieraniu danych z Ganglionu należy również odkomentować linijkę *from pyOpenBCI import OpenBCIGanglion*.
  - Po wykryciu mrugnięcia zmienna *blink.value* zmienia wartość na 1.  
  - Główna część programu, która powinna zostać rozszerzona znajduje się pierwotnie pomiędzy 83 a 97 linijką kodu. Tam powinien znaleźć się główny kod interfejsu. 
  - Można używać dodatkowych klas.
 
 :clock8: Pomysł na projekt należy przesłać na maila prowadzącego do **5. stycznia**. 


 **Uwaga** :office: Zgodnie z regulaminem studiów obowiązują dwie obecności, niezależnie od tego, czy są one usprawiedliwione, czy nie. :blue_book:

#### Terminarz zajęć

| lp. | Grupa 1 | Grupa 2 | Grupy 3 i 4 |
| --- | ------- | ------- | ----------- |
| 1   | 07.10   | 08.10   | 03.10       |
| 2   | 14.10   | 15.10   | 10.10       |
| 3   | 21.10   | 22.10   | 17.10       |
| 4   | 28.10   | 29.10   | 24.10       |
| 5   | 04.11   | 05.11   | 07.11       |
| 6   | 18.11   | 12.11   | 14.11       |
| 7   | 25.11*  | 19.11*  | 21.11*      |
| 8   | 02.12   | 26.11   | 28.11       |
| 9   | 09.12   | 03.12   | 05.12       |
| 10  | 16.12   | 10.12   | 12.12       |
| 11  | 13.01   | 17.12   | 19.12       |
| 12  | 20.01   | 07.01   | 09.01       |
| 13  | 27.01   | 14.01   | 16.01       |
| 14  | ---     | 21.01   | 23.01       |
| 15  | ***     | 28.01** | 30.01**     |

_* Do tego dnia należy przesłać raport z projektu webowego. Na zajęciach w tym terminie każda dwuosobowa grupa krótko opowie reszcie grupy zajęciowej o swoim projekcie.

_** Do tego dnia należy przesłać projekt z analizy danych. Na zajęciach w tym terminie każda dwuosobowa grupa krótko opowie reszcie grupy zajęciowej o swoim projekcie.

_*** Grupa zajęciowa nr 1 oraz grupa zajęciowa nr 2 prezentują projekty 28 stycznia.Jeśli ktoś nie będzie mógł być wtedy na zajęciach, projekt bronił będzie na dyżurze 29 stycznia.

#### Informacje dodatkowe

Warto wiedzieć: jeśli nowe zmiany zostaną wypchnięte na GitHub, nbviewer odświeży się automatycznie dopiero po około 10-ciu minutach. Można wymusić to odświeżenie dodając na końcu adresu: `?flush_cache=true`

Gdzie mogę znaleźć te wszystkie wymyślne ikony? [Tutaj](https://gist.github.com/rxaviers/7360908)  :link:

#### Bibliografia, źródła i materiały

[Przykłady aplikacji w Django krok po kroku (Django for beginners)](https://github.com/wsvincent/djangoforbeginners)

[O HTMLu (z tutorialu Django girls)](https://tutorial.djangogirls.org/en/html/), oraz [jak zrobić podstrony](https://github.com/wsvincent/djangoforbeginners/tree/master/ch3-pages-app) z [_Django for beginners_ ](https://github.com/wsvincent/djangoforbeginners)

[Czym są modele w Django (z tutorialu Django girls)](https://tutorial.djangogirls.org/en/django_models/)

[O web-developmencie dla tych, którzy wolą posłuchać/popatrzeć na spokojnie w domu](https://pasja-informatyki.pl/programowanie-webowe/technologie-video-mp3/)

Przykład formularza do odczytywania plików:
 * [Wpis na blogu](https://simpleisbetterthancomplex.com/tutorial/2016/08/01/how-to-upload-files-with-django.html)
 * [Repozytorium na GitHub-ie](https://github.com/sibtc/simple-file-upload.git)
 * [Dokumentacja zarządzania plikami w Django](https://docs.djangoproject.com/en/2.2/ref/files/storage/)
