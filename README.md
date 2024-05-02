### Modelowanie Zwinnego Wytwarzania Oprogramowania
# Zarządzanie kodem programów. Narzędzia do wersjonowania, umożliwiające kooperację zespołów.
Skład grupy:
| Imię        |Nazwisko          | Nr indeksu  |
| ------------- |-------------| :-----:|
| Julia      | Łuszkiewicz | 146091 |
| Natalia     | Miller     | 146093 |
| Szymon | Konieczny      |  146099 |

## Wstęp 
W dzisiejszych czasach wytwarzanie oprogramowania odbywa się w niezwykle dynamicznych warunkach. Skuteczne zarządzanie kodem jest kluczowym elementem każdego projektu informatycznego. Niezależnie od jego rozmiaru czy złożoności, prawidłowe wersjonowanie kodu oraz umiejętność współpracy w zespołach są niezbędne do doprowadzenia projektu do końca. W referacie zostanie omówiona istota zarządzania kodem programów oraz różnorodne narzędzia do wersjonowania, które umożliwiają płynną i efektywną kooperację między członkami zespołu programistycznego. W pracy zostaną omówione klasyczne systemy kontroli wersji jak i platformy umożliwiające rozproszoną pracę nad kodem. Analiza tych narzędzi oraz praktyczne wskazówki dotyczące ich wykorzystania, pomogą zrozumieć strategie i techniki niezbędne do efektywnego zarządzania kodem programów w środowisku zespołowym.
## Proces wytwarzania oprogramowania 
### Cykl życia oprogramowania
Cykl życia oprogramowania odzwierciedla kompleksowy proces tworzenia i użytkowania oprogramowania, obejmujący wszystkie jego etapy - od koncepcji przez rozwój, aż po wykorzystanie w praktyce. Można porównać ten proces z mapowaniem drogi prowadzącej od pomysłu do finalnego produktu.
W tym cyklu można dostrzec nie tylko konkretne kroki techniczne, ale także różnorodne role i kompetencje, które współtworzą projekt. Od menedżerów produktu, przez inżynierów oprogramowania po testerów - każdy pełni swoją istotną rolę konieczną do osiągnięcia finalnego efektu w postaci oprogramowania gotowego do użytkowania.
Warto podkreślić, że ten proces rzadko jest liniowy. W trakcie testów i iteracji, oprogramowanie jest ciągle ulepszane, co powoduje, że cykl życia oprogramowania może wielokrotnie powtarzać te same etapy. Istnieje wiele modeli wytwarzania oprogramowania, takich jak Waterfall, metody iteracyjne czy metody zwinne. Każda z tych metod zostaje dobrana zgodnie z cechami projektu, odzwierciedla różnice w podejściu do procesu, specyfikę produktu i charakter działalności firmy.

![Obrazek1](https://github.com/julialuszkiewicz/MZWO2024/assets/164729580/19775d35-0bb7-4c14-ae07-2c29c9065bf3)

###### *Obrazek 1 - Cykl życia oprogramowania*


Wszystkie metody wytwarzania oprogramowania mają wspólny cel - zrozumienie tego, co “stoi” za kodem. Logika i systematyczność procesu pozwalają na skuteczne zarządzanie i tworzenie oprogramowania, niezależnie od wybranej metody.

Poniżej przedstawiono każdą z faz wytwarzania oprogramowania wraz z krótkim opisem na przykładzie aplikacji.
#### Określenie wymagań
Pierwszym etapem jest określenie wymagań. Wymagania są definiowane przez doświadczonych specjalistów, którzy korzystają z badań rynku oraz analizują konkurencję. Informacje pozyskane podczas analiz są wykorzystywane podczas planowania całego projektu, przeprowadzenia studium wykonalności czy analizy ryzyka. Specjaliści potrzebni na tym etapie to Analitycy Biznesowi czy Product Ownerzy. Po zaplanowaniu projektu kolejnym etapem jest zdefiniowanie wartości produktu, poprzez określenie jego grupy docelowej - grupy zainteresowanych produktem użytkowników. Posiadając te informacje, architekci oprogramowania mogą „przenieść” informacje zawarte w analizach do wirtualnego świata, projektując funkcjonalności oprogramowania. 

Przykładowe role: 

![Obrazek2](https://github.com/julialuszkiewicz/MZWO2024/assets/164729580/63842b58-6e31-4020-8ddc-0c02f180652c)
###### *Obrazek 2 - Przykładowe role na etapie określenia wymagań*

#### Projekt 
Faza projektowanie jest drugim krokiem procesu tworzenia oprogramowania, który skupia się na konkretnym kształtowaniu produktu. Tutaj podejmowane są decyzje dotyczące wyglądu i funkcjonalności interfejsu użytkownika. Rozważane jest również, jakie ruchy podejmie użytkownik podczas pierwszego uruchomienia aplikacji i gdzie będzie szukał poszczególnych funkcji.
W tej fazie wybierany jest także język programowania oraz inne techniczne aspekty, takie jak bazy danych i serwery, które najlepiej odpowiadają potrzebom aplikacji. Ważne jest odpowiednie dostosowanie tych elementów, uwzględniając skalę projektu. Na przykład, projekt portalu obsługującego miliardy użytkowników codziennie będzie wymagał innej struktury technicznej niż aplikacja mobilna służąca do jednej konkretnie określonej funkcji.

Przykładowe role: 

![Obrazek3](https://github.com/julialuszkiewicz/MZWO2024/assets/164729580/70fe84aa-2792-47bf-8a4f-2c2756161286)
###### *Obrazek 3 - Przykładowe role na etapie projektu*






#### Implementacja
Faza implementacji to bardzo ważny czas kiedy zaczyna się pisanie programu. Czasami będzie to projekt wykonywany zupełnie od zera z całkiem nowym kodem (wtedy mówimy o tzw. green field development), a innym razem będziei można wykorzystać elementy z innych, istniejących aplikacji (wtedy mamy do czynienia z tzw. legacy code). Programistów specjalizujących się w różnych językach programowania można podzielić na front-endowych (JavaScrpit, HTML, CSS, React.js, Angular) czy back-endowych (Java, Scala, C, C++, C#.net). W niektórych projektach poszukiwani są także Full Stack Developerzy – czyli tacy, którzy potrafią kodować zarówno po stronie klienta, jak i administrować serwerem czy bazą danych. Każda aplikacja ma zdefiniowany stack technologiczny, czyli technologie jakie zostały użyte do jej wytworzenia. Stack technologiczny powinien być dopasowany do głównych założeń oprogramowania.

Przykładowe role: 

![Obrazek4](https://github.com/julialuszkiewicz/MZWO2024/assets/164729580/f0eb6a59-a7bc-4c8c-97b8-e13e37c74fb2)
###### *Obrazek 4 - Przykładowe role na etapie implemantacji*

#### Testowanie 

Kolejnym etapem jest faza testowania, która pozwala na uzyskanie pewności, że system działa poprawnie. Aplikacja jest poddawana różnorodnym testom, obejmującym funkcjonalność, wydajność i optymalizację, zwłaszcza jeśli ma działać w środowisku o dużej skali. Ważne jest również zapewnienie bezpieczeństwa oprogramowania poprzez sprawdzenie zgodności z wymaganiami.
Testerzy analizują, czy wszystkie funkcje działają zgodnie z oczekiwaniami, korzystając zarówno z testów manualnych (wykonanych przez użytkownika) jak i automatycznych (testy automatyczne tworzone przez testerów). Dodatkowo, użytkownicy mogą brać udział w testowaniu, dostarczając informacji zwrotnej, która pozwala na ciągłe doskonalenie produktu i lepsze dopasowanie do ich potrzeb.
W przypadku wykrycia błędów ("bugów"), często konieczny jest powrót do poprzednich etapów, aby dokonać poprawek w kodzie i zapewnić jakość oprogramowania.

Przykładowe role: 

![Obrazek5](https://github.com/julialuszkiewicz/MZWO2024/assets/164729580/d850524c-ebcc-4e01-ba65-a8990261a913)
###### *Obrazek 5 - Przykładowe role na etapie implemantacji*


#### Wdrożenie 
Deployment - wdrożenie to etap, który oznacza, że oprogramowanie jest gotowe do użycia. Po dokładnym zaplanowaniu, kodowaniu i sprawdzeniu, że wszystko działa zgodnie z oczekiwaniami, oprogramowanie przechodzi do etapu wdrożenia. Oznacza to, że użytkownicy mogą zacząć korzystać z aplikacji.
W początkowej fazie wdrożenia mogą wystąpić drobne błędy, które zostaną szybko wykryte i naprawione. Aplikacje, strony internetowe i inne produkty cyfrowe są poddawane ciągłym zmianom i ulepszeniom. Przykładowo Facebook, przeszedł znaczące zmiany w ciągu ostatnich pięciu lat. Jest to naturalne zjawisko, ponieważ technologia rozwija się, pojawiają się nowe możliwości, a trendy w designie oraz oczekiwania użytkowników także się zmieniają. Dzięki innowacjom produkty i usługi stale ewoluują, aby sprostać potrzebom i oczekiwaniom użytkowników.
### Utrzymanie
Ostatnim etapem jest faza utrzymania, gdy aplikacja już działa i użytkownicy z niej korzystają. Pomimo tego, że aplikacja działa, producent musi być czujny, ponieważ mogą pojawić się różne problemy.
W przypadku aplikacji webowych, mogą wystąpić problemy z działaniem na określonych przeglądarkach, być celem ataku złośliwego oprogramowania lub hakera. W miarę wzrostu liczby użytkowników aplikacji, mogą pojawić się problemy z obciążeniem serwerów. W takich sytuacjach konieczne jest podjęcie działań naprawczych, często powracając do odpowiednich etapów cyklu rozwoju oprogramowania.
Naprawa błędów nie zawsze wymaga zaangażowania programistów, ponieważ mogą być to drobne problemy, które można szybko naprawić. Czasem wystarczy wyjaśnić użytkownikowi, jak samemu poradzić sobie z problemem. W takich przypadkach warto skorzystać z pomocy zespołów wsparcia technicznego.

Przykładowe role:

![Obrazek6](https://github.com/julialuszkiewicz/MZWO2024/assets/164729580/9e6271f5-2a57-46d0-9a00-b0b3b9f7ccc1)
###### *Obrazek 6 - Przykładowe role na etapie utrzymania*



## Systemy kontroli wersji
System kontroli wersji można opisać jako aplikację wspomagającą monitorowanie modyfikacji w kodzie źródłowym oraz ułatwiającą programistom łączenie zmian wprowadzonych do plików przez różnych użytkowników w różnym czasie. 
Systemy kontroli wersji dzielą się na:
lokalne, pozwalające na zapisanie danych jedynie na lokalnym komputerze, np. SCCS﻿ oraz RCS,
scentralizowane, oparte na architekturze klient-serwer, np. CVS, Subversion,
rozproszone, oparte na architekturze P2P (Peer to Peer), np. BitKeeper, Code Co-op﻿ Git, svk.
Systemy VCS (Version Control System) zapewniają każdej osobie współtworzące kod ujednolicony i spójny widok projektu, wyświetlając prace, które są już w toku. Wgląd w przejrzystą historię zmian, kto ich dokonał i w jaki sposób przyczyniają się one do rozwoju projektu, pomaga członkom zespołu zachować spójność podczas niezależnej pracy.
W rozproszonym systemie kontroli wersji każdy deweloper ma pełną kopię projektu i jego historii. W przeciwieństwie do popularnych niegdyś scentralizowanych systemów kontroli wersji, DVCS nie wymagają stałego połączenia z centralnym repozytorium. 

### Git
Git jest najpopularniejszym rozproszonym systemem kontroli wersji. Git jest powszechnie używany zarówno do tworzenia oprogramowania open source, jak i komercyjnego, przynosząc znaczące korzyści osobom, zespołom i firmom.

#### Historia Gita
Git jest stosunkowo nowym narzędziem, które stanowi przykład tego jak potrzeba może stymulować innowacje. W 2005 roku twórca BitKeeper, narzędzia do kontroli wersji, używanego przez osoby rozwijające Linuksa, obwieścił iż jego oprogramowanie nie będzie już w pełni darmowe. W odpowiedzi na to Linus Torvalds i inni liderzy projektu postanowili opracować własne narzędzie do zarządzania wersjami, które będzie odznaczać się cechami BitKeepera, a jednocześnie będzie miało otwarty kod. W ten sposób powstał Git, który niezwykle szybko zdobył popularność. Co ciekawe, w 2016 roku BitKeeper stał się oprogramowaniem otwartym, choć wielu uważa, że ten krok nastąpił zbyt późno, by mogło ono konkurować z młodszym rywalem, jakim jest Git autorstwa Torvaldsa.
![Obrazek7](https://github.com/julialuszkiewicz/MZWO2024/assets/164729580/7832c04d-0380-4872-86c6-4673d38b41a1)
###### *Obrazek 7 - Linus Torvalds*








### Źródła:
https://talentplace.pl/blog/dla-rekruterow/cykl-tworzenia-oprogramowania-czyli-co-warto-wiedziec-rekrutujac-w-it/
https://myloview.pl/fototapeta-cykl-zycia-oprogramowania-nr-555C5D0
https://docs.github.com/en/get-started/using-git/about-git
https://pl.wikipedia.org/wiki/System_kontroli_wersji
https://www.w3schools.com/git/git_intro.asp?remote=github
https://www.dobreprogramy.pl/git-system-kontroli-wersji-czyli-szara-eminencja-swiata-it,6628568271157377a





