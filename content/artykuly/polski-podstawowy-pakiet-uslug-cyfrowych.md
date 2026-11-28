---
edition: "2"
author: bartosz-marcinkowski
title: Polski Podstawowy Pakiet Usług Cyfrowych
date: 1202-12-20T08:15:00
draft: false
image: images/uploads/02_pakiet-cyfrowy.jpg
image_focus_banner: 50% 50%
image_focus_card: 56% 50%
image_credit: Katarzyna Brzozowska
image_credit_author: katarzyna-brzozowska
noindex: false
---
**Blik odniósł wielki sukces. To realna alternatywa dla kart Mastercard i Visa, powstała dzięki współpracy polskich banków. Zastanówmy się, jak można stworzyć alternatywy dla dominujących rozwiązań zagranicznych platform technologicznych, inspirując się sukcesem rodzimego systemu płatności.**

Rozwój usług elektronicznych i cyfrowych ułatwia nam życie. Niestety, po etapie burzy innowacji często okazuje się, że *de facto* standard kontroluje mała grupa firm, które są w stanie ściągać marżę z pozostałej części gospodarki skuteczniej, niż rządy ściągają podatki. Żeby nie popaść w fatalizm, przyjrzyjmy się, jak polski Blik rzucił wyzwanie amerykańskim gigantom płatności. Być może, inspirując się jego metodą, uda się zwiększyć zakres naszej cyfrowej suwerenności.

## Karty płatnicze i Blik

Rynek kart płatniczych jest zdominowany przez dwie firmy. Gdyby ktoś w 2014 przedstawił mi pomysł polegający na stworzeniu polskiego dostawcy płatności konkurującego z nimi, byłbym pewnie sceptyczny. A jednak Blik okazał się sukcesem. Jak to możliwe?

Jednym z ważnych czynników było dotarcie do konsumentów i przedsiębiorców – dwóch stron płatności. Tradycyjny start-up musiałby mozolnie docierać do obu stron transakcji i przekonywać je do swojego rozwiązania. Na korzyść duopolu Mastercarda i Visy działał efekt sieci – konsumenci wybierają karty płatnicze obsługiwane przez wielu sprzedawców, a dla sprzedawców nie ma sensu obsługiwanie metod płatności, które nie są popularne wśród kupujących.

{{< pullquote >}}
Blika stworzyły polskie banki, które miały dostęp do obu stron transakcji. Już miały aplikacje dla konsumentów i już dostarczały systemy płatności dla przedsiębiorców. Dzięki temu były w stanie jednocześnie dotrzeć do zdecydowanej większości uczestników płatności elektronicznych.
{{< /pullquote >}}

Nasze aplikacje na telefonach zaczęły generować 6-cyfrowe kody Blik, a terminale płatnicze w sklepach je obsługiwały.

## SMS i komunikatory internetowe

Firmy telekomunikacyjne dostarczają nam usługi połączeń telefonicznych i wiadomości SMS. Te protokoły komunikacji mają istotne zalety – są pewnym standardem. Mogę zmienić operatora, zachowując swój numer. Mogę pisać wiadomości do znajomych korzystających z usług innej firmy.

Ten standard wyraźnie się zestarzał – w porównaniu do komunikatorów internetowych brakuje mu wielu funkcjonalności. Dlatego popularny jest WhatsApp, który też używa numeru telefonu jako identyfikatora, ale uzupełnia braki SMS-ów i połączeń telefonicznych: umożliwia m.in. przesyłanie załączników, reakcje, odpowiedzi na konkretną wiadomość, połączenia wideo, rozmowy grupowe i tworzenie ankiet.

Niestety, WhatsApp to nie jest otwarty protokół. Jeżeli uznam, że WhatsApp mi nie odpowiada, i znajdę inną podobną aplikację, nie będę mógł dalej komunikować się w ten sam sposób z jego użytkownikami. Na rzecz *status quo* działa efekt sieciowy – nawet lepsza alternatywa nie przyciąga, ponieważ jest naprawdę użyteczna dopiero wtedy, kiedy używa jej sieć znajomych i współpracowników.

Opracowanie otwartego protokołu wspierającego nowoczesną komunikację jest względnie łatwe – a przynajmniej istnieją już gotowe rozwiązania, choćby [Matrix](https://matrix.org/) i liczne kompatybilne z nim aplikacje na telefony i przeglądarki. Pozostaje problem uzyskania masy krytycznej użytkowników, a także drugi – finansowanie.

## Meta

Produkty takie jak WhatsApp, Facebook i Messenger są dla użytkownika darmowe, ponieważ tworząca je Meta zarabia na reklamach. Przez to też zamyka się na interoperacyjność, czyli możliwość współdziałania z oprogramowaniem poza kontrolą korporacji. Gdyby Meta pozwoliła swobodnie tworzyć własne aplikacje kompatybilne ze swoimi produktami, to moglibyśmy korzystać z tych usług w alternatywnych aplikacjach bez reklam. Wtedy Meta świadczyłaby dla nas darmową usługę przechowywania zdjęć i filmów, którymi dzielimy się ze znajomymi. Dlaczego miałaby to robić?

Możemy liczyć na to, że zrobi to pod przymusem. Unijne regulacje, takie jak Digital Markets Act, są już podstawą do tego, żeby [żądać od WhatsAppa interoperacyjności](https://developers.facebook.com/m/messaging-interoperability/). Życzę tym staraniom jak najlepiej. Mam jednak wątpliwości, czy to wystarczy. Meta zmuszona prawnie, by świadczyć usługi pozwalające na łączenie się z innymi komunikatorami, nie ma motywacji, żeby zrobić to optymalnie dla interoperacyjności – wręcz przeciwnie. W interesie korporacji jest takie zastosowanie się do wytycznych, które maksymalnie opóźni realną zmianę, ale da się obronić prawnie. 

Dla twórców zewnętrznych aplikacji może to oznaczać formalny proces wnioskowania o integrację, w ramach którego należy podpisać specjalną umowę – co nie jest przecież konieczne dla otwartych protokołów, takich jak e-mail. Dla użytkowników może to oznaczać ograniczoną funkcjonalność albo niższą jakość usług. Wystarczy słabiej finansować rozwój i utrzymanie komponentów na granicy między systemem wewnętrznym Mety i zewnętrznymi systemami. Mniej stabilne połączenia i częstsze błędy zniechęcą do opuszczenia dominujących platform, a prawnicy firmy będą w stanie długo bronić się przed zarzutami.

Trudno spodziewać się szczerej współpracy, nawet jeżeli usługa miałaby być płatna. Wartość akcji Mety odzwierciedla pozycję firmy, która zdominowała marketing w mediach społecznościowych. Takiej kapitalizacji nie utrzyma firma świadcząca hosting wiadomości i zdjęć na konkurencyjnym rynku interoperacyjnej komunikacji ze względnie niskim progiem wejścia. Marży uzyskiwanej z monopolu w reklamach w social mediach nie uda się odzyskać na rynku hostingu.

## Konkom

Stosowanie wobec Mety regulacji Digital Markets Act to przykład prawnie wymuszonej, ale jednak kooperacji. Warto wspomnieć o alternatywie, którą Cory Doctorow nazywa *comcom*, od *competitive compatibility*. Po polsku to będzie konkom – konkurencyjna kompatybilność. Chodzi o działanie wbrew intencji dostawcy, jak np. zastosowanie w drukarce tuszu innej firmy pomimo wysiłków producenta, żeby urządzenie nie przyjęło zamiennika.

W przypadku produktów Mety rodzajem konkom byłby skuteczny adblock, pozwalający korzystać z Facebooka z pominięciem reklam i postów sponsorowanych. Bardziej rewolucyjne byłoby stworzenie aplikacji, która w imieniu użytkownika Facebooka uwierzytelniałaby się w systemie i istotne informacje prezentowałaby w formie bardziej odpowiadającej jego preferencjom: np. bez reklam, bez nieskończonego scrollowania, z dodatkowymi filtrami treści.

Meta oczywiście nikomu w tym nie pomoże i nawet będzie przeszkadzać. Techniczne zabezpieczenia zdeterminowany programista będzie w stanie obejść – można otworzyć Facebooka w przeglądarce i analizować jego działanie, żeby później tworzyć własne programy komunikujące się z jego serwerami. Można stworzyć bota obsługującego interfejs w przeglądarce. 

{{< pullquote >}}
Niestety, przed konkurencyjną kompatybilnością broni Metę coś więcej niż wyścig technologicznych blokad i ich obejść – prawo. Jeżeli Meta stworzy jakieś zabezpieczenie Facebooka, to dostarczanie użytkownikom obejścia jest ryzykowne prawnie ze względu na unijną dyrektywę InfoSoc, przyjętą w ślad za Traktatem Światowej Organizacji Własności Intelektualnej o prawie autorskim.
{{< /pullquote >}}

Cory Doctorow namawia Europejczyków do tego, żeby wycofali swoje sądy z udziału w obronie amerykańskiego Big Techu i zaczęli zarabiać na sprzedaży obejść zabezpieczeń. Dla przykładu: podczas pandemicznych lockdownów pewien polski haker [pomógł obchodzić zabezpieczenia respiratorów Medtronic](https://www.vice.com/en/article/why-repair-techs-are-hacking-ventilators-with-diy-dongles-from-poland/), dzięki czemu pilne naprawy w szpitalach były możliwe niezależnie od licencjonowanego serwisu, który nie udzielał koniecznego wtedy wsparcia. Polak nie tylko na tym nie zarobił, ale wręcz musiał ukrywać swoją tożsamość, ponieważ złamał prawo. Niestety, zmiana prawa w tym zakresie to nie jest krok dostępny bezpośrednio nam w Polsce. Na tak wyraźnym ruchu wbrew interesom USA możemy zyskać tylko jako część całego bloku Unii Europejskiej.

## Czego uczy nas Blik

Inną drogę, analogiczną do Blika, widzę we współpracy firm telekomunikacyjnych. One już mają umowy z każdym polskim użytkownikiem karty SIM i otrzymują z tego tytułu płatności. Wyobrażam sobie, że każdy operator mógłby technicznym laikom powiedzieć: „Wszyscy klienci otrzymują dostęp do komunikatora oraz 10 GB przestrzeni na załączniki wiadomości – zwiększenie tej przestrzeni jest możliwe przy droższym abonamencie”. Technicznie biegły klient mógłby zadeklarować przy podpisaniu umowy, że sam sobie zorganizował serwer komunikatora i wskazuje jego adres internetowy – dzięki temu wiadomości kierowane pod numer telefonu mogą trafiać do celu.

Techniczny laik, przenosząc swój numer telefonu, domyślnie zleciłby operatorowi przeniesienie konta komunikatora. Użytkownik zaawansowany technicznie u nowego dostawcy mógłby ponownie wskazać wybrany adres internetowy. Mamy więc swobodę zmiany dostawcy. Mamy natychmiastowe dotarcie z nowym rozwiązaniem do wszystkich Polaków, którzy mają numer telefonu. Przy zastosowaniu standardowego protokołu [Matrix](https://matrix.org/) mamy też gotowe oprogramowanie na serwery, telefony i przeglądarki, a także interoperacyjność z użytkownikami tego protokołu na całym świecie.

Jest w tym rozwiązaniu pewna słabość względem Blika – motywacja finansowa. Dla banków możliwość przejęcia części marży duopolu firm Visa i Mastercard była wystarczającą motywacją. Firmom telekomunikacyjnym w przedstawionym scenariuszu nie oferujemy takich zysków, jakie Meta jest w stanie uzyskać z reklam w social mediach. Zapraszamy do mniej marżowego, bardziej konkurencyjnego hostingu. Do tego mają one utrzymywać system łączący numery telefonów z otwartym, rozproszonym systemem komunikacji.

Jeżeli perspektywa wpływów za dodatkową przestrzeń na załączniki nie wystarczy, może być potrzebny impuls od regulatora. Sądzę, że wystarczy działanie na poziomie krajowym. Rodzime telekomy konkurują między sobą i nałożenie na nie równych obowiązków nie jest dla żadnego zagrożeniem. Jest też jasne uzasadnienie – dla państwa utrzymanie komunikacji obywateli na serwerach lokalnych dostawców zwiększa cyfrową suwerenność.

## RCS

Inicjatywa państwa i uwzględnienie cyfrowej suwerenności mogą być traktowane nie tylko jako uzupełnienie biznesowej motywacji, ale konieczny element chroniący przed przechwyceniem ucieczki od jednego Big Techu przez inny. Pokazuje to przykład protokołu [Rich Communication Services](https://en.wikipedia.org/wiki/Rich_Communication_Services) (RCS) – wdrażanego od dekady rozszerzenia SMS/MMS, które dodaje wiele brakujących funkcji, w tym przesyłanie załączników wysokiej jakości i (od niedawna) prowadzenie rozmów wideo.

RCS wdrażany jest w sposób, który kontrolę nad komunikatorem przekazuje duopolowi systemów mobilnych: Apple i (w jeszcze większym stopniu) Google, który zajął się też dostarczaniem oprogramowania serwerowego dla firm telekomunikacyjnych. Telekomy wdrażają gotowe rozwiązanie [Google RCS](https://docs.jibemobile.com/) z jednej strony. Z drugiej strony twórca aplikacji do wiadomości RCS na Androida musi przyjąć warunki Google na dwóch frontach: współpracy z serwerami wdrożonymi w telekomie i zatwierdzenia aplikacji w Google Play Store. Oczywiście domyślną aplikację na telefon dostarcza Google.

W zaproponowanym rozwiązaniu opartym na protokole Matrix i współpracy telekomów motywowaną suwerennością cyfrową była możliwość korzystania z jednej z wielu wybranych (i istniejących już) aplikacji na telefony i przeglądarki, a także używania serwerów komunikatora dostarczanych przez różne firmy, a nawet przekierowania do serwera działającego we własnym domu. Rozwiązanie, jakie wdraża Google, zdejmuje z polskich telekomów wiele obowiązków, ale za pewną cenę. Nasze telekomy stają się narzędziem wdrażania [Wiadomości Google](https://messages.google.com/web/welcome).

## Polski podstawowy pakiet usług cyfrowych 

Ograniczanie władzy firm dominujących na rynku usług cyfrowych odbywa się na froncie prawnym i technologicznym, na poziomie krajowym i unijnym. Nie jest jasne, jaka kombinacja przyniesie efekt – może będzie to zastosowanie Digital Markets Act do protokołu Rich Communication Services, a może geopolityczny przełom naruszający przywiązanie Unii Europejskiej do traktatów międzynarodowych w obecnej formie. Nie musi to jednak być odległy proces, zupełnie oderwany od naszej krajowej sprawczości.

Jeżeli rozpowszechnienie w Polsce otwartego protokołu komunikacji przez internet przy udziale telekomów się powiedzie, w kolejce stoją kolejne usługi, z którymi mamy podobny problem – media społecznościowe. Tu też powstały standardy pozwalające na tworzenie zdecentralizowanej sieci profili, które mogą się nawzajem obserwować, komentować posty i na nie reagować. Znowu pojawia się problem zebrania masy krytycznej użytkowników, a także płatności za utrzymywanie usługi. Jeżeli dostawcy usług telekomunikacyjnych zgodzą się dołączyć do komunikatora także usługę konta społecznościowego w [Mastodonie](https://joinmastodon.org/), będziemy mieli podstawowy pakiet usług cyfrowych. Być może trudno uwierzyć, że w Polsce można rzucić wyzwanie Big Techom, ale czy łatwo było uwierzyć w szansę na sukces Blika?
