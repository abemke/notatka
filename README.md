

# UNIWERSYTET GDAŃSKI WYDZIAŁ MATEMATYKI, FIZYKI I INFORMATYKI

Aleksandra Bemke

Kierunek studiów: MATEMATYKA

Numer albumu: 179863

Równowagi Nasha w grach 2x2

PRACA MAGISTERSKA 

wykonana w Zakładzie Analizy Matematycznej pod kierunkiem 

Prof. UG dr. hab. Jarosława Pykacza

Gdańsk 2013




##Wstęp


Matematyka jest dziedziną nauk bardzo potrzebną w życiu. W wielu innych dziedzinach takich jak fizyka, geografia, chemia używa się matematycznych wzorów lub wyliczeń. Teoria gier jest dziedziną wykorzystującą analizę matematyczną i rachunek prawdopodobieństwa do podejmowania decyzji biznesowych.

Tematem niniejszej pracy są równowagi Nasha w grach 2x2.

Odpowiada ona na następujące pytanie: Ile równowg Nasha posiada gra 2x2 i gdzie są one umiejscowione w bimacierzy wypłat? Należy podkreślić, że w istniejącej literaturze brak jest kompleksowego opracowania tego tematu.

Opracowanie to ma charakter teoretyczny i oparte jest na wyliczeniach własnych autorki pracy.

Całą problematykę zawarto w trzech rozdziałach.

W pierwszym rozdziale przybliżona jest historia teorii gier oraz życiorys Johna Nasha. Podane są podstawowe pojęcia teorii gier, a także zaprezentowany jest graficzny sposób szukania rozwiązań gier 2x2.

W drugim rozdziale przeanalizowane są wszystkie możliwe przypadki gier 2x2 w zależności od parametrów występujących w bimacierzy gry.

Ostatni rozdział podsumowywuje wcześniejsze obliczenia i dzieli wszystkie możliwe gry 2x2 ze względu na ilość równowag Nasha.

Pracę podsumowują wnioski zawarte w zakończeniu i konkluzje wynikające z przedstawionych wyliczeń.


##Wprowadzenie do teorii gier



###Rys historyczny teorii gier



Gry towarzyszą człowiekowi od początku istnienia, już w starożystności grano w szachy. Zaczęto także stosować strategie na polach bitewnych oraz szkolić oficerów wojskowych pod kątem strategii rozgrywania bitew.  Pomimo tak dużego udziału gier w życiu człowieka, dopiero od początków XX wieku matematycy i ekonomiści usiłują stworzyć  formuły matematyczne opisujące gry.

Zalążkiem teorii gier jest artykuł Johna von Neumanna z roku 1928, w którym udowodnione było twierdzenie dotyczące gier dwuosobowych o sumie zerowej (tzw. twierdzenie o minimaxie).

Teoria gier jako nauka zajmująca się badaniem sytuacji konfliktowych przy użyciu aparatu matematycznego ma swoje początki w 1944 roku. Jej ojcami są John von Neumann i  Oskar Morgenstern, którzy opublikowali książkę pt. ,,Theory of Games and Economic Behavior'' (Teoria gier i postępowanie ekonomiczne).

Od tego czasu dziedzina ta znajduje zastosowanie w ekonomii i prężnie się rozwija. Uczeni zaczynają rowiązywać coraz bardziej złożone problemy matematyczne. W latach pięćdziesiątych XX wieku John Nash, noblista, rozpoczyna badanie gier o sumie niezerowej i definiuje pojęcie równowagi w grze.

Herbert Simon otrzymał  Nagrodę  Nobla w 1978 roku za wkład w rozwój ewolucyjnej teorii gier, w szczególności za koncepcję ograniczonej racjonalności. Według komitetu nagrody rezultaty te były przełomowe w  badaniach procesu podejmowania decyzji wewnątrz organizacji gospodarczych oraz teorii ich podejmowania. W 1994 roku za duże zaangażowanie w badaniach nad teorią gier i odkrycia naukowe trzej uczeni: John Nash, John Harsány i Reinhard Selten otrzymali Nagrodę Nobla z dziedziny ekonomii za rozwój teorii gier i jej zastosowania w ekonomii.

W 1996r. William Vickrey i James Mirrlees  zostali docenieni w świecie nauki za stworzenie modeli przetargów i badanie konfliktów z niesymetryczną informacją uczestników. 

Od 1983 roku ukazuje się pismo ,,International Journal of Game Theory'', które ugruntowywuje pozycję teorii gier w dziedzinie nauk matematycznych. 

Teoria gier znajduje zastosowanie w coraz większej liczbie dziedzin takich jak ekonomia, nauki polityczne, socjologia, psychologia, biologia, czy informatyka. 

O prężnym i szybkim rozwoju teorii gier świadczą kolejne Nagrody Nobla. W roku 2005 Thomas Crombie Schelling i Israel Robert John Aumann otrzymali tę nagrodę w dziedzinie ekonomii za zastosowanie teorii gier w naukach społecznych i mikroekonomii (dot. zachowania jednostek i rozwiązywania konfliktów). W roku 2007 Nagrodę Nobla z ekonomii za kolejne zastosowania teorii gier w tej dziedzinie dostali Leonid Hurwicz, Eric Stark Maskin i Roger Bruce Myerson.

Tak więc ostatnie 30 lat jest okresem ekspansji teorii gier i wielu jej aspektów, co jest dowodem bogactwa i dużych perspektyw tej nauki.





###John Nash


John Forbes Nash Jr. jest to  amerykański matematyk i ekonomista. Urodził się on 13 czerwca 1928 w Bluefield w Wirginii. Był opisywany przez innych jako indywidualista, samotnik zamknięty w sobie. Dorastał w kochającej rodzinie i miał młodszą siostrę Martę.

Młody John czytał wiele  książek, zaś mało czasu spędzał z rówieśnikami. W związku z taką sytuacją matka Johna entuzjastycznie podeszła do jego nauki, dokształcając go dodatkowo w domu. Z kolei ojciec Johna dawał mu książki naukowe i traktował jak dorosłego. Nauczyciele Johna nie odkryli jego geniuszu. W wieku 12 lat John był bardzo zainteresowany robieniem doświadczeń naukowych. 

14 letni John, zapoznał się z twierdzeniem Fermata, które Eric Temple Bell zamieścił w książce pt.: ,,Człowiek matematyki''. Uwagę chłopca zwrócił kontrast pomiędzy matematyką z książki, a tą ze szkoły. Sytuacja ta była pierwszym objawem geniuszu matematycznego Nasha.

W 1941r. Nash rozpoczął studia w Bluefield College i uczył się tam matematyki na równi z innymi ścisłymi przedmiotami. Wtedy jego pasją była chemia. Nash otrzymał stypendium i dostał się w 1945r. na studia do Carnegie Institute of Technology. Tam zachęcony przez  Johna Synge zajął się matematyką profesjonalnie.

Nash dwukrotnie brał udział w matematycznym konkursie Williama Lowella Putnama. W 1948r. John otrzymał tytuły bakałarza i magistra matematyki. John otrzymał propozycję studiowania matematyki w Harwardzie, Princeton, Chicago i Michigan. W Princeton Nash zainteresował się głównie topologią, geometrią algebraiczną, teorią gier i logiką. W 1949r. napisał pracę, za którą 45 lat później otrzymał Nagrodę Nobla w dziedzinie ekonomii. W 1950r. Nash otrzymał tytuł doktora za pracę pod tytułem: ,,Gry niekooperacyjne''. Dwa lata później John opublikował pracę pt.: ,,Złożoność prawdziwej algebry''.

Od 1952r. Nash uczył w Massachussets Institute of Technology i prowadził badania nad geometrią Riemanna.  W 1954r. opublikował kolejną pracę, która dotyczyła  przestrzeni Euklidesowych, metryk i złożoności Riemanna. W 1958r. w ,,American Journal of Mathematics''  ukazała się jego praca podsumowująca ten temat.

Po roku 1958 karierę Johna na długo przerwała choroba psychiczna. Podczas swej pracy w MIT Nash zaczął mieć problemy w kontaktach międzyludzkich. W 1990 roku Nash wyleczył się ze schizofrenii paranoidalnej, która męczyła go od roku 1959. Jego zdolność do tworzenia matematyki na najwyższym poziomie nie osłabła. Stwierdził wtedy, że nie uznałby siebie za wyleczonego, gdyby nie umiał tworzyć prawidłowych twierdzeń.

 W 1999r. za swój wkład w rozwój badań naukowych dostał Nagrodę Leroy P. Steele od Amerykańskiej Społeczności Matematyków.

Historia życia tego matematyka została opisana w książce biograficznej Sylvii Nasar pt.: ,,Piękny umysł'' i w filmie z roku 2001 o takim samym tytułe. W 2012 roku Nash został członkiem American Mathematical Society. Matematyk ten nadal żyje i jest aktywny naukowo pomimo skończonych 85 lat.

 

##Podstawowe pojęcia teorii gier





###Definicja gry i pojęć z nią powiązanych




Najbardziej podstawowym pojęciem w teorii gier jest pojęcie **gry**. Gra jest sformalizowanym opisem konfliktu. Dokładny opis gry zawiera wskazanie:

- kto?

- w jaki sposób bierze udział w konflikcie?

- jakie są możliwe wyniki?

- kto i w jakiej formie jest zainteresowany możliwymi wynikami?

Charakterystyczne cechy gier są takie same bez względu na rodzaj gry, jej złożoność lub prostotę. Dodatkowo w przypadku każdej gry zakładamy znajomość reguł gry przez wszystkich jej uczestników.

Osoby biorące udział w grze nazywamy **graczami**. Określenie gracz nie zawsze musi oznaczać jedną osobę, może to być grupa ludzi, firma, czy nawet państwo. Zazwyczaj zakładamy skończoną liczbę graczy. W niniejszej pracy rozpatrywać będziemy głównie gry dwuosobowe. 

Działania graczy inaczej nazywamy akcjami, decyzjami, bądź ruchami gracza. Pełen opis postępowania gracza w każdej możliwej sytuacji nazywamy **strategią**. Często w grach opis strategii jest skomplikowany lub strategie nie są od razu widoczne. W niniejszej pracy będziemy na ogół zakładać, że każdy gracz posiada tylko dwie strategie. Zazwyczaj wyróżniamy dwa rodzaje strategii: czyste i mieszane (zostaną one opisane dokładniej w dalszej części pracy). 

 Gra kończy się **wypłatą** lub **wygraną**, która jest wyrażona liczbą rzeczywistą. Każdy gracz ma swój cel, którym jest zmaksymalizowanie swojej wygranej wszystkimi dostępnymi środkami. Wygrana danego gracza zatem zależy od sposobu jego postępowania, ale również od zachowań pozostałych graczy. Wygrane określane są poprzez **funkcję wypłat** poszczególnych graczy.

**Rozwiązaniem gry** jest znalezienie optymalnych strategii gry dla wszystkich graczy biorących udział w grze. Zwykle przyjmujemy, że rozwiązaniem gry dwuosobowej jest para strategii tworząca równowagę Nasha (wyjaśnienie tego pojęcia znajduje się w dalszej części pracy). 

Po nieformalnym przedstawieniu pojecia gry i jej elementów wprowadzimy formalną definicję gry.

**Normalna** forma zapisu gry jest definiowana poprzez określenie listy graczy, zbioru strategii każdego gracza oraz funkcji wypłat. Dodatkowo zakładamy, że gracze wybierają swoje strategie jednocześnie, a więc wybierając je nie wiedzą, jakie strategie wybrali pozostali gracze.



>**Definicja:** 

Rodzinę $$Θ=\left(N,Σ,\pi\right)$$ nazywamy **n-osobową grą w postaci normalnej**, gdzie:

1. N={1,2,...n} jest zbiorem graczy;
1. zbiór

$$Σ_{i}$$ 

jest zbiorem strategii i-tego gracza, $1 \leq i \leq n$;
1. $Σ=Σ_{1}\timesΣ_{2}\times...\timesΣ_{n}$ jest zbiorem stanów w grze $Θ$;
1. funkcja $\pi_{i}:Σ_{1}\timesΣ_{2}\times...\timesΣ_{n} \rightarrow \mathbb{R}$ jest funkcją wypłaty (wygranych) tego gracza,  $1 \leq i \leq n$ oraz $\pi=\left(\pi_1,\pi_2,...,\pi_n\right)$;
1. wektor $\left(\pi_1\left(s\right),\pi_2\left(s\right),...,\pi_n\left(s\right)\right) \in \mathbb{R}^{n}$, nazywamy wektorem wypłat (wygranych) stanu $s=\left(s_1,s_2,...,s_n\right)\inΣ$.

Celem i-tego gracza jest maksymalizacja jego funkcji wypłaty $\pi_i$ przez wybór strategii ze zbioru $Σ_i$.



###Gry 2x2



**Gra 2x2** jest to gra dwóch graczy, w której każdy z graczy posiada dwie strategie. Zapis 2x2 onacza model gry w postaci normalnej, a dokładniej w postaci macierzowej, dlatego pominiemy pozostałe możliwe klasyfikacje modeli gier.

Grę 2x2 w postaci normalnej zapisujemy za pomocą bimacierzy:


$$\left(A,B\right)=
\kbordermatrix{\mbox{ }&I&II
P&(a_{11} ,b_{11} )&(a_{12},b_{12})
L&(a_{21},b_{21})&(a_{22},b_{22})
}$$


Jest to zapis w postaci podwójnej macierzy gry, gdyż bimacierz (A,B) jest parą macierzy 

$$A=\left[\begin{array}{cc}
a_{11}&a_{12}
a_{21}&a_{22}
\end{array}\right]
B=\left[\begin{array}{cc}
b_{11} &b_{12}
b_{21}&b_{22}
\end{array}\right]$$

przedstawiających, odpowiednio, wypłaty dla Gracza 1 (Wiersza) i Gracza 2 (Kolumny). W przedstawionej bimacierzy Wiersz gra jedną z dwóch strategii P lub L i są one reprezentowne prez wiersze. Kolumna gra również jedną z dwóch strategii I lub II oraz odpowiadają im kolumny. W miejscu przecięcia się wiersza i kolumny znajdują się liczby reprezentujące wypłaty dla graczy odpowiadające wybranym przez graczy strategiom. Na przykład jeżeli Wiersz gra według strategii P i Kolumna postępuje zgodnie ze strategią II to wypłatami będą liczby $a_{12}$ i $b_{12}$. Kwota $a_{12}$ jest wypłatą jaką otrzyma Wiersz, natomiast $ b_{12}$ jest wygraną Kolumny.

>Definicja: 
Jeżeli gracz ma do dyspozycji zbiór strategii $\{ s_1,s_2\}$ i wybiera je z prawdopodobieństwami $\{p_1,p_2\}$, $0\leq p_i \leq 1$, $p_1+p_2 =1$, to mówimy, że gra **strategię mieszaną** określoną rozkładem prawdopodobieństwa $\{p_1,p_2\}$. 
Natomiast o strategiach $s_1,s_2$ mówimy, że są to **strategie czyste**.


Inaczej mówiąc strategia mieszana jest rozkładem prawdopodobieństwa określonym na zbiorze strategii czystych. Zauważamy, że strategie czyste są szczególnymi przypadkami strategi mieszanych. W strategiach czystych dla pewnego indeksu \\i=1 lub 2~$p_i=1$, natomiast $ p_j=0~ dla~~ j\ne i$. 

Dla uproszczenia zapisów w pracy zastosowaliśmy skrótową formę zapisu strategii graczy. Strategie obu graczy zapisane w jednym nawiasie $(\overrightarrow{p},\overrightarrow{q})$ oznaczają, że Gracz 1 gra strategię $\overrightarrow{p}=(p,1-p)$, natomiast Gracz 2 gra strategię ${\overrightarrow{q}=(q,1-q)}$. Gdy nie będzie budziło to wątpliwości symbol wektora będziemy pomijać i para strategii $\overrightarrow{p}=(p,1-p)$ oraz $\overrightarrow{q}=(q,1-q)$ będziemy oznaczać (p,q).

>Przykład:

Wektor $\overrightarrow{p}=(p,1-p)=(1,0)$ jest strategią czystą Wiersza, czyli Gracz 1 gra strategię czystą $s_1$ nazwaną w przykładowej bimacierzy strategią P. W tej samej grze Kolumna może grać strategię mieszaną, np. $ \overrightarrow{q}=(q,1-q)=(\frac{1}{2},\frac{1}{2})$, w tym przypadku Gracz 2 wybiera strategię czystą I z prawdopodobieństwem $\frac{1}{2}$ i strategię czystą II z prawdopodobieństwem $\frac{1}{2}$.


>Definicja:

Gdy gracze w grze 2x2 grają strategie mieszane $(\overrightarrow{p},\overrightarrow{q})$, gdzie $\overrightarrow{p}=(p_1,p_2)$, $\overrightarrow{q}=(q_1,q_2)$ funkcjami wypłaty są wartości oczekiwane
$$\pi_1 \left( \overrightarrow{p},\overrightarrow{q} \right)=\sum\limits_{i=1}^2\sum\limits_{j=1}^2 p_iq_ja_{ij},$$ 
$$\pi_2 \left( \overrightarrow{p},\overrightarrow{q} \right)=\sum\limits_{i=1}^2\sum\limits_{j=1}^2 p_iq_jb_{ij}.$$ 


W dalszej części pracy oznaczmy przez $\pi$ funkcję wypłat obu graczy, czyli: $$\pi=(\pi_1 \left( \overrightarrow{p},\overrightarrow{q} \right)),\pi_2 \left( \overrightarrow{p},\overrightarrow{q} \right)).$$

>Przykład:

Jeżeli strategie graczy są następujące $\overrightarrow{q}=(q,1-q)$, $\overrightarrow{p}=(p,1-p)$ i jest to gra 2x2:
$$\left(A,B\right)=
\kbordermatrix{\mbox{ }&I~q&II~1-q\\
P&(a_{11} ,b_{11} )&(a_{12},b_{12})\\
L&(a_{21},b_{21})&(a_{22},b_{22})\\
} 
\begin{array}{c}
\\
p\\
1-p\\ 
\\
\end{array}
$$
\\
to funkcja wypłat dla Wiersza jest następująca:
$$\pi_1 \left( \overrightarrow{p},\overrightarrow{q} \right)=pqa_{11}+p(1-q)a_{12}+(1-p)qa_{21}+(1-p)(1-q)a_{22},$$
a dla Kolumny jest taka:
$$\pi_2 \left( \overrightarrow{p},\overrightarrow{q} \right)=pqb_{11}+p(1-q)b_{12}+(1-p)qb_{21}+(1-p)(1-q)b_{22}.$$






###Równowagi Nasha i ich poszukiwanie metodą graficzną



Niech $A,B \in M_{2x2}\left( \mathbb{R} \right)$ będą dwiema macierzami o współczynnikach rzeczywistych, będącymi wypłatami odpowiednio Wiersza i Kolumny, przy założeniu, że strategiami czystymi pierwszego gracza są wiersze, a drugiego kolumny. Zatem ich wypłaty przy zastosowaniu i-tej oraz j-tej strategii czystej, $i,j=1,2$ wynoszą odpowiednio $\pi_1\left(i,j\right)=a_{ij}$ oraz $\pi_2\left(i,j\right)=b_{ij}$.


>Definicja:

Element $(\overrightarrow{p^*},\overrightarrow{q^*})$ zbioru $Σ_1\timesΣ_2$ nazywamy **stanem równowagi Nasha gry** $Θ=(Σ_1,Σ_2,\pi)$, albo po prostu równowagą Nasha, jeżeli spełnione są nierówności:
$$\pi_1 \left(\overrightarrow{p},\overrightarrow{q^*}\right) \leqslant  \pi_1 \left(\overrightarrow{p^*},\overrightarrow{q^*}\right) \forall ~\overrightarrow{p} \in Σ_1,$$
$$\pi_2 \left(\overrightarrow{p^*},\overrightarrow{q}\right) \leqslant  \pi_2 \left(\overrightarrow{p^*},\overrightarrow{q^*}\right) \forall ~\overrightarrow{q} \in Σ_2.$$

Przez $E(Θ)$ oznaczamy zbiór wszystkich równowag Nasha gry $Θ$.


>Uwaga: 

Gdy Wiersz zamieni strategię $\overrightarrow{p^*} $ na inną, a drugi gracz tego nie zrobi, to jego wygrana nie wzrośnie.


>Uwaga: 

Gdy Kolumna zamieni strategię $\overrightarrow{q^*} $ na inną, a Wiersz tego nie zrobi to jej wygrana nie wzrośnie.


**Metoda graficzna** poszukiwania równowag Nasha w grach 2x2:

>Definicja:

Niech $Θ=(Σ_1,Σ_2,\pi)$ będzie grą dwuosobową. Zbiory: 
$$W_1= \{ \left(\overrightarrow{p^*},\overrightarrow{q} \right) :\pi_1 \left( \overrightarrow{p^*},\overrightarrow{q} \right) =\max_{\overrightarrow{p}}  \pi_1 \left( \overrightarrow{p},\overrightarrow{q} \right), \overrightarrow{q} \in Σ_2 \};$$
$$W_2= \{ \left( \overrightarrow{p},\overrightarrow{q^*} \right) :\pi_2 \left( \overrightarrow{p},\overrightarrow{q^*} \right) =\max_{\overrightarrow{q}}  \pi_2 \left( \overrightarrow{p},\overrightarrow{q} \right) , \overrightarrow{p} \in Σ_1 \};$$
nazywamy **zbiorami najlepszych odpowiedzi**, odpowiednio dla pierwszego i dla drugiego gracza.

>Twierdzenie:

Stan $(\overrightarrow{p^*},\overrightarrow{q^*})$ jest stanem równowagi Nasha wtedy i tylko wtedy, gdy $(\overrightarrow{p^*},\overrightarrow{q^*}) \in W_1 \cap W_2$.

>Dowód:
Wynika z definicji stanu równowagi Nasha, gdyż tworzą go najlepsze na siebie nawzajem odpowiedzi graczy.




###Inwariantność równowag Nasha względem lokalnych przesunięć




>Definicja:

**Lokalnymi przesunięciami** w grze bimacierzowej (A,B) nazywamy dodanie tej samej liczby w poszczególnych wierszach macierzy wypłat Gracza 2:
$$\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{12},b_{12})\\
(a_{21},b_{21})&(a_{22},b_{22})\\
\end{array}\right] 
\\ \to
\left[\begin{array}{cc}
(a_{11} ,b_{11}+d )&(a_{12},b_{12}+d)\\
(a_{21},b_{21}+g)&(a_{22},b_{22}+g)\\
\end{array}\right]$$
\\
i dodanie tej samej liczby w poszczególnych kolumnach macierzy wypłat Gracza 1:
$$\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{12},b_{12})\\
(a_{21},b_{21})&(a_{22},b_{22})\\
\end{array}\right]
\\ \to
\left[\begin{array}{cc}
(a_{11}+c ,b_{11} )&(a_{12}+f,b_{12})\\
(a_{21}+c,b_{21})&(a_{22}+f,b_{22})\\
\end{array}\right]$$
>


>Uwaga:

Definicję zilustrowano przykładami lokalnych przesunięć w grze 2x2, ale obowiązuje ona dla dowolnej gry bimacierzowej.

>Twierdzenie:

Lokalne przesunięcia w grach bimacierzowych nie zmieniają zbiorów najlepszych odpowiedzi i położenia równowag Nasha.

>Dowód:

Dowód zostanie przeprowadzony dla gier 2x2. Dowód w przypadku ogólnym jest analogiczny. Niech w grze wyjściowej spełnione będą nierówności: 
$\pi_1 \left(\overrightarrow{p},\overrightarrow{q^*}\right) \leqslant  \pi_1 \left(\overrightarrow{p^*},\overrightarrow{q^*}\right)$ i $\pi_2 \left(\overrightarrow{p^*},\overrightarrow{q}\right) \leqslant  \pi_2 \left(\overrightarrow{p^*},\overrightarrow{q^*}\right)$, gdzie $\overrightarrow{p}=(p_1,p_2)$ oraz $\overrightarrow{q}=(q_1,q_2)$, czyli:
\\
$p_1q_1^*a_{11}+p_1q_2^*a_{12}+p_2q_1^*a_{21}+p_2q_2^*a_{22}  \le p_1^*q_1^*a_{11}+p_1^*q_2^*a_{12}+p_2^*q_1^*a_{21}+p_2^*q_2^*a_{22}$ i 
$p_1^*q_1b_{11}+p_1^*q_2b_{12}+p_2^*q_1b_{21}+p_2^*q_2b_{22} \le p_1^*q_1^*b_{11}+p_1^*q_2^*b_{12}+p_2^*q_1^*b_{21}+p_2^*q_2^*b_{22}$. \\
Jeżeli zastosujmy lokalne przesunięcia w kolumnach i wierszach, to odpowiadające im nierówności w grze przekształconej będą miały postać:
\\
$p_1q_1^*(a_{11}+c)+p_1q_2^*(a_{12}+f)+p_2q_1^*(a_{21}+c)+p_2q_2^*(a_{22}+f)  \le p_1^*q_1^*(a_{11}+c)+\\p_1^*q_2^*(a_{12}+f)+p_2^*q_1^*(a_{21}+c)+p_2^*q_2^*(a_{22}+f)$,\\
$p_1^*q_1(b_{11}+d)+p_1^*q_2(b_{12}+d)+p_2^*q_1(b_{21}+g)+p_2^*q_2(b_{22}+g) \le p_1^*q_1^*(b_{11}+d)+\\p_1^*q_2^*(b_{12}+d)+p_2^*q_1^*(b_{21}+g)+p_2^*q_2^*(b_{22}+g)$.\\
Oznaczmy przez $L_1$, $L_2$, $L'_1$, $L'_2$ oraz $R_1$, $R_2$, $ R'_1$, $ R'_2$ lewe i prawe strony tych nierówności. Indeksy 1 i 2 odnoszą się, odpowiednio, do nierówności dotyczących wypłat Gracza 1 i 2, symbole nieprimowane odnoszą się do nierówności dotyczących gry wyjściowej, zaś primowane - przekształconej. Po wymnożeniu i pogrupowaniu wyrazów otrzymamy:
$$L'_1=L_1+(p_1+p_2)q^*_1c+(p_1+p_2)q^*_2f=L_1+q^*_1c+q^*_2f,$$
$$R'_1=R_1+(p^*_1+p^*_2)q^*_1c+(p^*_1+p^*_2)q^*_2f=R_1+q^*_1c+q^*_2f,$$
a więc nierówność $L_1\le R_1$ dla gry wyjściowej jest równoważna nierówności \\$L'_1\le R'_1$ dla gry przekształconej. Analogiczny związek zachodzi także dla nierówności dotyczących wypłat Gracza 2: $L_1\le R_2 \Leftrightarrow L'_2 \le R'_2$.
Widzimy więc, że lokalne przesunięcia nie zmieniają nierówności występujących w definicji stanu równowagi Nasha, więc położenie równowag Nasha i zbiorów najlepszych odpowiedzi nie ulega zmianie.


Dzięki powyższemu twierdzeniu dowolną grę 2x2 możemy przekształcić do postaci diagonalnej, co znacznie ułatwia badanie zbiorów równowag Nasha w tych grach.









##Podział gier 2x2 ze względu na wartość parametrów
 
###Sprowadzenie dowolnej gry 2x2 do postaci bimacierzy diagonalnej


Rozważmy grę w postaci normalnej określoną przez bimacierz:
$$\left(A,B\right)=\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{12},b_{12})\\
(a_{21},b_{21})&(a_{22},b_{22})\\
\end{array}\right]$$
\\
Przekształćmy tę bimacierz wykorzystując lokalne przesunięcia w następujący sposób: od pierwszej kolumny Gracza 1 odejmujemy wartość $a_{21}$ i od drugej kolumny tego samego gracza odejmujemy wartość $a_{12}$. Równocześnie w macierzy wypłat Gracza 2 od pierwszego wiersza odejmujemy wartość $b_{12}$, natomiast od drugiego wiersza odejmujemy wartość $b_{21}$. Przekształcenia te prezentuje poniższy schemat:
$$\left(A,B\right)=\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{12},b_{12})\\
(a_{21},b_{21})&(a_{22},b_{22})\\
\end{array}\right]
\\ \to
\left[\begin{array}{cc}
(a_{11}-a_{21} ,b_{11}-b_{12} )&(a_{12}-a_{12},b_{12}-b_{12})\\
(a_{21}-a_{21},b_{21}-b_{21})&(a_{22}-a_{12},b_{22}-b_{21})\\
\end{array}\right]$$
\\
Efektem tych przekształceń jest:
$$\left[\begin{array}{cc}
(a_{11}-a_{21} ,b_{11}-b_{12} )&(0,0)\\
(0,0)&(a_{22}-a_{12},b_{22}-b_{21})\\
\end{array}\right]
\\ =
\left[\begin{array}{cc}
( α , γ )&(0,0)\\
(0,0)&(β , δ)\\
\end{array}\right]$$
\\
Gdzie zastosowaliśmy podstawienie:
$$α=a_{11}-a_{21};$$
$$β=a_{22}-a_{12};$$
$$γ=b_{11}-b_{12};$$
$$δ=b_{22}-b_{21};$$
\\
Jest to bimacierz diagonalna.




###Graficzne wyznaczanie równowag Nasha w grach 2x2 sprowadzonych do postaci diagonalnej


Rozbijamy bimacierz gry 2x2 sprowadzonej do postaci diagonalnej  na dwie macierze:
$$(A^{\prime},B^{\prime})=\left[\begin{array}{cc}
( α , γ )&(0,0)\\
(0,0)&(β , δ)\\
\end{array}\right]
\\ \to
A^{\prime}=\left[\begin{array}{cc}
α&0\\
0&β\\
\end{array}\right]
\\, 
B^{\prime}=\left[\begin{array}{cc}
γ&0\\
0&δ\\
\end{array}\right]$$
Dla ułatwienia późniejszych obliczeń wyznaczamy wypłaty osiagane przy poszczególnych strategiach  Gracza 1  i Gracza 2 :
$$\pi_1(1,q)=α q+0(1-q)=α q$$
$$\pi_1(0,q)=0q+β (1-q)=β - β q$$
$$\pi_2(p,1)=γ p+0(1-p)=γ p$$
$$\pi_2(p,0)=0p+δ (1-p)=δ-δ p$$

Sprawdzamy dla jakich  wartości q spełniona jest nierówność pomiędy wypłatami Gracza 1:
$$\pi_1(1,q) \ge \pi_1(0,q).$$
Rozwiązanie tej nierówności pokaże nam, kiedy najlepszą odpowiedzią Gracza 1 na strategię q Gracza 2 jest strategia czysta p=1. Przedział do jakiego należy q otrzymamy poprzez wstawienie za $\pi_1(1,q)=α q$ i $\pi_1(0,q)=β (1-q)$:
$$α q \ge β (1-q),$$
$$α q + β q \ge β.$$
Dostajemy ostatecznie:
$$q ( α + β) \ge β.$$
A więc zbiór $\{q:q(α + β )\ge β \} \cap [0,1]$ jest zbiorem tych wartości q, dla których najlepszą odpowiedzią Gracza 1 na strategię q Gracza 2 jest strategia czysta p=1.

Oczywiście równość:
 $$\pi_1(1,q) = \pi_1(0,q)$$
oznacza, że obie strategie czyste Gracza 1: p=1 oraz p=0, a więc także każda jego strategia mieszana, są najlepszymi odpowiedziami Gracza 1 na strategię q Gracza 2. Jest tak wtedy, gdy $q ( α + β) = β.$ 

Ostatecznie wywnioskujemy, że odwzorowanie najlepszych odpowiedzi Gracza 1 na wszystkie możliwe strategie $q \in [0,1]$ Gracza 2 określamy następująco:
$$
W_1(q)= \begin{cases}
1 & \text{gdy } q\in [0,1] \text{ jest takie, że } q(α + β )\ge β\\
[0,1] & \text{gdy } q\in [0,1] \text{ jest takie, że } q(α + β )= β\\
0 & \text{gdy } q\in [0,1] \text{ jest takie, że } q(α + β )\le β\\
\end{cases}
.$$

Postępując analogicznie znajdujemy odwzorowanie najlepszych odpowiedzi Gracza 2 na wszystkie możliwe strategie $p \in [0,1]$ Gracza 1:
$$
W_2(p)= \begin{cases}
1 & \text{gdy } p\in [0,1] \text{ jest takie, że } p(γ + δ )\ge δ\\
[0,1] & \text{gdy } p\in [0,1] \text{ jest takie, że } p(γ + δ )= δ\\
0 & \text{gdy } p\in [0,1] \text{ jest takie, że } p(γ + δ )\le δ\\
\end{cases}
.$$

Aby znaleźć zbiór równowag Nasha gry 2x2 należy wykresy odwzorowań najlepszych odpowiedzi $W_1(q)~ i~ W_2(p)$ wykonać w jednym układzie współrzędnych. Zgodnie z Twierdzeniem \ref{rNasha}. zbiór równowag Nasha jest reprezentowany przez część wspólną wykresów odwzorowań $W_1(q)~ i~ W_2(p)$.

W zależności od wartości jakie przyjmują parametry α, $β$, γ, δ  (parametry te mogą być ujemne, równe zero lub dodatnie) otrzymamy do rozpatrzenia 81 przypadków.

Dzielimy je na przypadki niedegenerowne, gdy żaden z parmetrów nie jest zerowy i zdegenerowane, gdy chociażby jeden z parametrów α, $β$, γ, δ przyjmuje wartość zero.


###Przypadki niezdegenerowane




Rozpoczynamy od znalezienia odwzorowania $W_1(q)$ w zależności od warości parametrów α i $β$:



1. α>0, $β > 0$, co daje $q ( α + β) \ge β \Leftrightarrow q \ge \frac{β}{α+β} \in [0,1]$.
Otrzymamy więc odwzorowanie najlepszych odpowiedzi Gracza 1:
$
W_1(q)=  \begin{cases}
1 & \text{dla } \frac{β}{α +β} \le q \le 1\\
[0,1] & \text{dla } q=\frac{β}{α +β}\\
0 & \text{dla } 0\le q \le \frac{β}{α +β}\\
\end{cases}
.$
2. α>0, $β < 0$. Wówczas nierówność $q(α + β)\ge β$ jest spełniona dla każdego $q \in [0,1]$, gdyż jeżeli $α < |β|$ to $q(α + β)\ge β \Leftrightarrow q \le \frac{β}{α+β}$, ale $\frac{β}{α+β}>1$. Jeżeli zaś $α \ge |β|$, to lewa strona nierówności $q(α + β)\ge β$ jest nieujemna, prawa zaś ujemna. Widzimy więc, że gdy α>0, β<0, to $W_1(q)=1$ dla każdego $q\in [0,1]$.

3. α<0, $β > 0$. Wówczas łatwo sprawdzimy, że dla każdego $q\in [0,1]$ spełniona jest nierówność  $q(α + β)\le β$, a więc $W_1(q)=0$ dla każdego $q\in [0,1]$.

4. α<0, $β < 0$, więc $q ( α + β) \ge β \Leftrightarrow q\le \frac{β}{α+β} \in [0,1]$, co daje: \\ ${W_1(q)= \begin{cases}
1 & \text{dla } 0 \le q \le \frac{β}{α +β}\\
[0,1] & \text{dla } q=\frac{β}{α +β}\\
0 & \text{dla } \frac{β}{α +β} \le q \le 1\\
\end{cases}
.}$



Następnie znajdujemy odworownie $W_2(p)$ w zależności od parametrów γ i δ:


1. γ>0, δ>0, dlatego $p ( γ +δ) \ge δ \Leftrightarrow p\ge\frac{δ}{γ+δ}$. Więc odwzorowanie najlepszych odpowiedzi Gracza 2 jest następujące: ${W_2(p)= \begin{cases}
1 & \text{dla } \frac{δ}{γ +δ} \le p \le 1\\
[0,1] & \text{dla } p=\frac{δ}{γ +δ}\\
0 & \text{dla } 0 \le p \le \frac{δ}{γ +δ}\\
\end{cases}
.}$

2.  γ>0, δ<0. Wówczas nierówność $p (γ +δ) \ge δ$ jest spełniona dla każdego $p\in [0,1]$, gdyż jeżeli $γ<|δ|$ to  $p (γ +δ) \ge δ \Leftrightarrow p\le \frac{δ}{γ +δ}$, ale $\frac{δ}{γ +δ}>1$. Jeżeli zaś $γ \ge |δ|$, to lewa strona nierówności  $p (γ +δ) \ge δ$ jest nieujemna, prawa zaś ujemna. Widzimy więc, że gdy γ>0, δ<0, to $W_2(p)=1$ dla każdego $p\in [0,1]$.

3.  γ<0, δ>0. Wówczas łatwo sprawdzamy, że dla każdego $p \in [0,1]$ spełniona jest nierówność $p ( γ +δ) \le δ$, a więc $W_2(p)=0$ dla każdego $p\in [0,1]$.

4.  γ<0, δ<0. Wówczas $p ( γ +δ) \ge δ \Leftrightarrow p\le \frac{δ}{γ+δ}$.
Co daje odwzorowanie najlepszych odpowiedzi Gracza 2:
${W_2(p)= \begin{cases}
1 & \text{dla } 0 \le p \le \frac{δ}{γ +δ}\\
[0,1] & \text{dla } p=\frac{δ}{γ +δ}\\
0 & \text{dla } \frac{δ}{γ +δ} \le p \le 1\\
\end{cases}
.}$


Wcześniejsze obliczenia możemy przedstawić w tabeli:



|α | $β$ | $W_1(q)$ | wykres|
| :--------: |:---------:| -------------------|---------------|
|+ | +| $\begin{cases} 
1 & \text{dla } \frac{β}{α +β} \le q \le 1\\
[0,1] & \text{dla } q=\frac{β}{α +β}\\
0 & \text{dla } 0\le q \le \frac{β}{α +β}\\
\end{cases}$ |  (wykre100.png)|
|+ | - | 1 dla $q\in[0,1]$ | (wykre101.png)|
|- | + | 0 dla $q\in[0,1]$ | (wykre102.png)|
|- | - | $\begin{cases}
1 & \text{dla } 0 \le q \le \frac{β}{α +β}\\
[0,1] & \text{dla } q=\frac{β}{α +β}\\
0 & \text{dla } \frac{β}{α +β} \le q \le 1\\
\end{cases}$ |(wykre103.png)|



|γ | δ | $W_2(p)$ | wykres|
| :--------: |:---------:| -------------------|---------------|
|+ | + | $\begin{cases}
1 & \text{dla } \frac{δ}{γ +δ} \le p \le 1\\
[0,1] & \text{dla } p=\frac{δ}{γ +δ}\\
0 & \text{dla } 0 \le p \le \frac{δ}{γ +δ}\\
\end{cases}$ | (wykre104.png) |
|+ | - | 1 dla $p\in[0,1]$ | (wykre106.png) |
|- | + | 0 dla $p\in[0,1]$ | (wykre107.png) |
|- | - | $\begin{cases}
1 & \text{dla } 0 \le p \le \frac{δ}{γ +δ}\\
[0,1]  \text{dla } p=\frac{δ}{γ +δ}\\
0 & \text{dla } \frac{δ}{γ +δ} \le p \le 1\\
\end{cases}$ |(wykre105.png)|



Wykorzystując wcześniejsze obliczenia możemy narysować wykresy odwzorowań $W_1(q)$ i $W_2(p)$ w jednym układzie współrzędnych oraz zaznaczyć zbiór równowag Nasha określony jako $W_1(q) \cap W_2(p)$ w zależności od wartości parametrów: α, $β$, γ, δ:


1. α>0, $β > 0$, γ>0, δ>0.
![width=0.3\textwidth](wykre1.png)
W tym przypadku otrzymamy trzy równowagi Nasha:
\\
$NE_1=(1,1)$ odpowiada jej wektor wypłat $\overrightarrow{\pi}= (α, γ)$,
\\
$NE_2=(\frac{δ}{γ+δ},\frac{β}{α+β})$ odpowiada jej wektor wypłat $\overrightarrow{\pi}= (\frac{α β}{α+β},\frac{γ δ}{γ+ δ})$, gdyż
\begin{eqnarray*}
\pi_1 & = & α \frac{δ}{γ+δ} \frac{β}{α+β}+ β (1-\frac{δ}{γ+δ})(1- \frac{β}{α+β}) \\ & = & \frac{α δ β}{(γ+δ)(α+β)}+\frac{β γ α}{(γ+δ)(α+β)} \\ & =&  \frac{α β (δ+γ)}{(γ+δ)(α+β)} \\ & = & \frac{α β}{α+β}
\end{eqnarray*}
\begin{eqnarray*}
\pi_2 & = & γ \frac{δ}{γ+δ} \frac{β}{α+β}+δ(1-\frac{δ}{γ+δ})(1- \frac{β}{α+β}) \\ & = & \frac{γ δ β}{(γ+δ)(α+β)}+ \frac{δ γ α}{(γ+δ)(α+β)} \\&=& \frac{δ γ(α + β)}{(γ+δ)(α+β)}\\&=& \frac{γ δ}{γ+ δ}.
\end{eqnarray*}
\\
$NE_3=(0,0)$ odpowiada jej wektor wypłat $\overrightarrow{\pi}=(β, δ)$.
W dalszej części pracy zastosujemy skrót $NE_1$ dla onaczenia równowagi \\$NE_1=(1,1)$. Analogicznie zastosujemy skróty dla równowag Nasha $NE_2$, $NE_3$, $NE_4$ i $NE_5$.

2. α>0, β>0, γ>0, δ<0. Otrzymamy jedną równowagę Nasha: $NE_1$:
 ![width=0.3\textwidth](wykre2.png).
3. α>0, β>0, γ<0, δ>0. Otrzymamy jedną równowagę Nasha: $NE_3$.
![width=0.3\textwidth](wykre3.png)
4. α>0, β>0, γ<0, δ<0. Rysujemy wykres i odczytujemy z niego, iż jest tylko jedna równowaga Nasha: $NE_2$.
![width=0.33\textwidth](wykre4.png)
5. α>0, β<0, γ>0, δ>0. Otrzymamy jedną równowagę Nasha: $NE_1$.
![width=0.3\textwidth] (wykre16.png)
6. α>0, β<0, γ>0, δ<0. Otrzymamy jedną równowagę Nasha: $NE_1$.
![width=0.3\textwidth](wykre17.png)
7. α>0, β<0, γ<0, δ>0. Otrzymamy jedną równowagę Nasha: $NE_5=(1,0)$, odpowiada jej wektor wypłat $\overrightarrow{\pi}=(0,0)$.
![width=0.3\textwidth](wykre14.png)
8. α>0, β<0, γ<0, δ<0. Otrzymamy jedną równowagę Nasha: $NE_5$.
![width=0.3\textwidth](wykre18.png)
9. α<0, β>0, γ>0, δ>0. Otrzymamy jedną równowagę Nasha: $NE_3$.
![width=0.3\textwidth](wykre5.png)
10. α<0, β>0, γ>0, δ<0. Otrzymamy jedną równowagę Nasha: 
$NE_4=(0,1)$, odpowiada jej wektor wypłat $\overrightarrow{\pi}=(0,0)$.
![width=0.3\textwidth](wykre7.png)
11. α<0, β>0, γ<0, δ>0. Otrzymamy jedną równowagę Nasha: 
$NE_3$.
![width=0.3\textwidth](wykre8.png)
12. α<0, β>0, γ<0, δ<0. Otrzymamy  nieskończenie wiele równowag Nasha: $NE=\{(p,0): \frac{δ}{γ+δ}\le p \le 1\}$.
![width=0.3\textwidth](wykre10.png)
Symbolem NE oznaczamy zbiór par strategii jakich wynikiem jest równowaga Nasha.
13. α<0, β<0, γ>0, δ>0. Z wykresu odczytamy: $NE_2$.
![width=0.3\textwidth](wykre11.png)
14. α<0, β<0, γ>0, δ<0. Otrzymamy jedną równowagę Nasha: $NE_4$.
![width=0.3\textwidth](wykre12.png)
15. α<0, β<0, γ<0, δ>0. Otrzymamy jedną równowagę Nasha: $NE_5$.
![width=0.3\textwidth](wykre15.png)
16. α<0, β<0, γ<0, δ<0. Otrzymamy trzy równowagi Nasha: $NE_2$, $NE_4$ i $NE_5$.
![width=0.3\textwidth](wykre13.png)







###Przypadki zdegenerowane




Rozpoczynamy od znaleznienia zbiorów $W_1(q)$ w zależności od wartości parametrów α i $β$:


1. α>0, $β = 0$. Mamy $q ( α + β) \ge β \Leftrightarrow q α \ge 0 \Leftrightarrow q\ge0$.
Więc 
\\${W_1(q)= \begin{cases}
1 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=0\\
\end{cases}
.}$
2. α<0, $β = 0$. Mamy $q ( α + β) \le β \Leftrightarrow q α \le 0 \Leftrightarrow \ge0$.
Więc \\${W_1(q)= \begin{cases}
0 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=0\\
\end{cases}
.}$
3. α=0, $β > 0$. Mamy $q ( α + β) \le β \Leftrightarrow  β \le β \Leftrightarrow q\le1$.
Więc \\${W_1(q)= \begin{cases}
0 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=1\\
\end{cases}
.}$
4. α=0, $β < 0$. Mamy $q ( α + β) \ge β \Leftrightarrow q β \ge β \Leftrightarrow q\le1$.
Więc \\${W_1(q)= \begin{cases}
1 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=1\\
\end{cases}
.}$
5. α=0, $β = 0$, Wówczas $q(α+β)=β$ dla dowolnego $q\in [0,1]$, więc 
\\${W_1(q)= [0,1]  \text{ dla } q\in [0,1].}$
Zauważamy, że α=0 i β=0 oznacza, że $a_{11}=a_{21}$ oraz $a_{22}=a_{21}$, a więc bimacierz gry wyjściowej wygląda tak:
$$\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{22},b_{12})\\
(a_{11},b_{21})&(a_{22},b_{22})\\
\end{array}\right].$$
Widzimy więc, że Graczowi 1 jest obojętne, czy gra strategię czystą p=1, czy p=0, czy jakąkolwiek strategię mieszaną. Gdy $a_{11}\ne a_{22}$, jego wypłata zależy nie od niego, lecz od wyboru strategii przez Gracza 2.



Następnie wyznaczamy zbiór $W_2(p)$ w zależności od parametrów γ i δ dla przypadków zdegenerowanych:


1. γ>0, δ=0. Mamy $p ( γ +δ) \ge δ \Leftrightarrow pγ \ge 0 \Leftrightarrow p\ge 0$. Co daje \\${W_2(p)= \begin{cases}
1 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=0\\
\end{cases}
.}$

2. γ<0, δ=0. Mamy $p ( γ +δ) \le δ \Leftrightarrow γ p \le 0 \Leftrightarrow p \ge 0$. Więc \\${W_2(p)= \begin{cases}
0 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=0\\
\end{cases}
.}$

3. γ=0, δ>0. Mamy $p(γ+δ)\leδ \Leftrightarrow δ p \le δ \Leftrightarrow p \le 1$. Więc \\${W_2(p)= \begin{cases}
0 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=1\\
\end{cases}
.}$

4. γ=0, δ<0. Mamy $p(γ+δ)  \ge δ  \Leftrightarrow p δ \ge δ \Leftrightarrow p\le 1$. Co daje \\${W_2(p)= \begin{cases}
1 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=1\\
\end{cases}
.}$

5. γ=0, δ=0. Mamy $p(γ+δ)  \ge δ $ dla dowolnego $p\in[0,1]$, co daje \\${W_2(p)=[0,1]  \text{ dla } p\in [0,1].}$
Znowu zauważamy, że w tym przypadku $b_{11}=b_{21}$ oraz $b_{22}=b_{21}$, a więc bimacierz gry wyjściowej wygląda tak:
$$\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{22},b_{12})\\
(a_{11},b_{21})&(a_{22},b_{22})\\
\end{array}\right].$$
Widzimy więc, że Graczowi 2 jest obojętne, czy gra strategię czystą q=1, czy q=0, czy jakąkolwiek strategię mieszaną. Gdy $b_{11}\ne b_{22}$, jego wypłata zależy nie od niego, lecz od wyboru strategii przez Gracza 1.



Wcześniejsze obliczenia możemy przedstawić w tabeli:
\\
\begin{center}
\begin{tabular}{|c|c|c|c|}
\hline
α & $β$ & $W_1(q)$ & wykres\\
\hline
\hline
+ & 0 & $\begin{cases}
1 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=0\\
\end{cases}$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre108.png}}\\
\hline
- & 0 & $\begin{cases}
0 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=0\\
\end{cases}$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre109.png}}\\
\hline
0 & + & $\begin{cases}
0 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=1\\
\end{cases}$ &\raisebox{-\height}{ \includegraphics [width=0.2\textwidth] {wykre110.png}}\\
\hline
0 & - & $\begin{cases}
1 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=1\\
\end{cases}$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre111.png}}\\
\hline
0 & 0 & $ [0,1]  \text{ dla } q\in [0,1]$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre112.png}}\\
\hline
\end{tabular}
\end{center}

\begin{center}
\begin{tabular}{|c|c|c|c|}
\hline
γ & δ & $W_2(p)$ & wykres\\
\hline
\hline
+ & 0 & $\begin{cases}
1 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=0\\
\end{cases}$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre113.png}}\\
\hline
- & 0 & $\begin{cases}
0 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=0\\
\end{cases}$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre114.png}}\\
\hline
0 & + & $\begin{cases}
0 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=1\\
\end{cases}$ &\raisebox{-\height}{ \includegraphics [width=0.2\textwidth] {wykre115.png}}\\
\hline
0 & - & $\begin{cases}
1 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=1\\
\end{cases}$ &\raisebox{-\height}{ \includegraphics [width=0.2\textwidth] {wykre116.png}}\\
\hline
0 & 0 & $[0,1]  \text{ dla } p\in [0,1]$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre117.png}}\\
\hline
\end{tabular}
\end{center}

Wykorzystując wcześniejsze obliczenia możemy narysować wykresy odwzorowań $W_1(q)$ i $W_2(p)$ w jednym układzie współrzędnych oraz zaznaczyć zbiór równowag Nasha określony jako $W_1(q) \cap W_2(p)$ w zależności od wartości parametrów: α, $β$, γ, δ:


1. α>0, β>0, γ>0, δ=0, $NE=NE_1 \cup \{ (0,q):0\le q\le \frac{β}{α+β}\}$.


![width=0.3\textwidth] (wykre21.png)


2. α>0, β>0, γ<0, δ=0, $NE=\{ (0,q):0\le q\le \frac{β}{α+β}\}$.

![width=0.3\textwidth](wykre22.png)

3. α>0, β>0, γ=0, δ>0, $NE=NE_3 \cup \{ (1,q):\frac{β}{α+β} \le q\le 1\}$.


![width=0.3\textwidth](wykre32.png)

4. α>0, β>0, γ=0, δ<0, $NE=\{ (1,q):\frac{β}{α+β} \le q\le 1\}$.

![width=0.3\textwidth](wykre33.png)

5. α>0, β>0, γ=0, δ=0, \\$NE=\{(0,q):0\le q \le \frac{β}{α+β}\} \cup \{ (p,\frac{β}{α+β}): 0 \le p \le 1\} \cup\{ (1,q):\frac{β}{α+β} \le q\le 1\}$.

![width=0.3\textwidth](wykre34.png)

6. α>0, β<0, γ>0, δ=0. Otrzymamy jedną równowagę Nasha: $NE_1$.
![width=0.3\textwidth](wykre29.png)

7.α>0, β<0, γ<0, δ=0. Otrzymamy jedną równowagę Nasha: $NE_5$.
![width=0.3\textwidth](wykre30.png)

8. α>0, β<0, γ=0, δ>0, $NE=\{(1,q):0\le q \le 1 \}$.
![width=0.3\textwidth] (wykre42.png)

9. α>0, β<0, γ=0, δ<0, $NE=\{(1,q):0\le q \le 1 \}$.
![width=0.3\textwidth](wykre43.png)


10. α>0, β<0, γ=0, δ=0, $NE=\{(1,q):0\le q \le 1 \}$.
![width=0.3\textwidth](wykre44.png)
	
11. α>0, β=0, γ>0, δ>0, $NE=NE_1 \cup\{(p,0):0 \le p \le \frac{δ}{γ+δ} \}$.
![width=0.3\textwidth](wykre45.png)

12. α>0, β=0, γ>0, δ<0. Otrzymamy jedną równowagę Nasha: $NE_1$.
![width=0.3\textwidth](wykre46.png)

13. α>0, β=0, γ>0, δ=0. Otrzymamy dwie równowagi Nasha: $NE_1$ i $NE_3$.
![width=0.3\textwidth](wykre48.png)


14. α>0, β=0, γ<0, δ>0, $NE=\{(p,0): 0\le p \le 1 \}$.
![width=0.3\textwidth](wykre49.png)
		
16. α>0, β=0, γ<0, δ<0, $NE=\{(p,0): \frac{δ}{γ+ δ}\le p \le 1 \}$.
![width=0.3\textwidth](wykre47.png)

17. α>0, β=0, γ<0, δ=0, $NE=\{(p,0): 0\le p \le 1 \}$.
![width=0.3\textwidth](wykre50.png)


18. α>0, β=0, γ=0, δ>0, $NE=\{(p,0): 0\le p \le 1 \} \cup \{(1,q):0\le q \le 1\}$.
![width=0.3\textwidth](wykre51.png)

19. α>0, β=0, γ=0, δ<0, $NE=\{(1,q):0\le q \le 1\}$.
![width=0.3\textwidth](wykre52.png)

20. α>0, β=0, γ=0, δ=0, $NE=\{(p,0): 0\le p \le 1 \} \cup \{(1,q):0\le q \le 1\}$.
![width=0.3\textwidth](wykre53.png)

21. α<0, β>0, γ>0, δ=0, $NE=\{ (0,q):0\le q\le 1\}$.
![width=0.3\textwidth](wykre23.png)

22.α<0, β>0, γ<0, δ=0, $NE=\{ (0,q):0\le q\le 1\}$.
![width=0.3\textwidth](wykre25.png)

23. α<0, β>0, γ=0, δ>0. Otrzymamy jedną równowagę Nasha: $NE_3$.
![width=0.3\textwidth](wykre36.png)

24. α<0, β>0, γ=0, δ<0. Otrzymamy jedną równowagę Nasha: $NE_4$.
![width=0.3\textwidth](wykre37.png)

25. α<0, β>0, γ=0, δ=0, $NE=\{ (0,q):0 \le q\le 1\}$.
![width=0.3\textwidth](wykre38.png)

26. α<0, β<0, γ>0, δ=0, $NE=\{ (0,q):\frac{β}{α+β} \le q\le 1\}$.
![width=0.3\textwidth](wykre27.png)

27. α<0, β<0, γ<0, δ=0, $NE=NE_5 \cup \{ (0,q):\frac{β}{α+β} \le q\le 1\}$.
![width=0.3\textwidth](wykre28.png)

28. α<0, β<0, γ=0, δ>0, $NE=\{ (1,q): 0\le q\le \frac{β}{α+β}\}$.
![width=0.3\textwidth](wykre40.png)

29. α<0, β<0, γ=0, δ<0, $NE=NE_4 \cup\{ (1,q): 0\le q\le \frac{β}{α+β}\}$.
![width=0.3\textwidth](wykre41.png)

30. α<0, β<0, γ=0, δ=0, \\$NE=\{(0,q): \frac{β}{α+β} \le q \le1\} \cup \{ (p,\frac{β}{α+β}): 0 \le p \le 1\} \cup\{ (1,q):0 \le q\le \frac{β}{α+β}\}$.
![width=0.3\textwidth](wykre39.png)

31. α<0, β=0, γ>0, δ>0, $NE=\{(p,0): 0\le p \le 1 \}$.
![width=0.3\textwidth](wykre54.png)

32. α<0, β=0, γ>0, δ<0. Otrzymamy jedną równowagę Nasha: $NE_4$.
![width=0.3\textwidth](wykre55.png)

33.α<0, β=0, γ>0, δ=0, $NE=NE_4 \cup\{(p,0): 0\le p \le 1 \}$.
![width=0.3\textwidth](wykre57.png)

34. α<0, β=0, γ<0, δ>0, $NE=\{(p,0):0\le p \le 1\}$.
![width=0.3\textwidth](wykre58.png)

35. α<0, β=0, γ<0, δ<0, $NE=NE_4 \cup\{(p,0): \frac{δ}{γ+δ}\le p \le 1 \}$.
![width=0.3\textwidth](wykre56.png)

36. α<0, β=0, γ<0, δ=0, $NE=\{(0,q):0\le q\le 1\} \cup \{(p,0): 0 \le p \le 1 \}$.
![width=0.3\textwidth](wykre59.png)

37. α<0, β=0, γ=0, δ>0, $NE=\{(p,0: 0 \le p \le 1 \}$.
![width=0.3\textwidth](wykre60.png)

38. α<0, β=0, γ=0, δ<0. Otrzymamy tu dwie równowagi: $NE_4$ i $NE_5$.
![width=0.3\textwidth](wykre61.png)

39. α<0, β=0, γ=0, δ=0, $NE=\{(0,q):0\le q\le 1\} \cup \{(p,0): 0 \le p \le 1 \}$.
![width=0.3\textwidth](wykre62.png)

40. α=0, β>0, γ>0, δ>0, $NE=NE_3 \cup \{(p,1): \frac{δ}{γ+δ} \le p \le 1\}$.
![width=0.3\textwidth](wykre63.png)

41. α=0, β>0, γ>0, δ<0, $NE=\{(p,1): 0\le p \le 1 \}$.
![width=0.3\textwidth](wykre64.png)
		
42. α=0, β>0, γ>0, δ=0, $NE=\{(0,q):0\le q \le 1\}\cup\{(p,1): 0\le p \le 1 \}$.
![width=0.3\textwidth](wykre88.png)

43. α=0, β>0, γ<0, δ>0, $NE=\{(0,q):0\le q \le 1\}$.
![width=0.3\textwidth](wykre67.png)
		
44. α=0, β>0, γ<0, δ<0, $NE=\{(p,1): 0 \le p \le \frac{δ}{γ+δ}\}$.
![width=0.3\textwidth](wykre65.png)

45. α=0, β>0, γ<0, δ=0, $NE=\{(0,q): 0 \le q \le 1\}$.
![width=0.3\textwidth](wykre66.png)

46. α=0, β>0, γ=0, δ>0. Otrzymamy tu dwie równowagi: $NE_1$ i $NE_3$.
![width=0.3\textwidth](wykre74.png)


47. α=0, β>0, γ=0, δ<0, $NE=\{(p,1):0\le p \le 1\}$.
![width=0.3\textwidth](wykre75.png)

48. α=0, β>0, γ=0, δ=0, $NE=\{(0,q):0 \le q \le 1 \} \cup \{(p,1):0\le p \le 1\}$.
![width=0.3\textwidth](wykre76.png)

49. α=0, β<0, γ>0, δ>0, $NE=\{(p,1): \frac{δ}{γ+δ} \le p \le 1\}$.
![width=0.3\textwidth](wykre69.png)

50. α=0, β<0, γ>0, δ<0, $NE=\{(p,1): 0 \le p \le 1\}$.
![width=0.3\textwidth](wykre70.png)
		
51. α=0, β<0, γ>0, δ=0, $NE=\{(p,1): 0 \le p \le 1\}$.
![width=0.3\textwidth](wykre72.png)

52. α=0, β<0, γ<0, δ>0. Otrzymamy jedną równowagę Nasha: $NE_5$.
![width=0.3\textwidth](wykre71.png)

53. α=0, β<0, γ<0, δ<0, $NE=\{(p,1): 0 \le p \le \frac{δ}{γ+δ}\}$.
![width=0.3\textwidth](wykre89.png)

54. α=0, β<0, γ<0, δ=0. Otrzymamy tu dwie równowagi: $ NE_4$ i $NE_5$.
![width=0.3\textwidth](wykre73.png)

55. α=0, β<0, γ=0, δ>0, $NE=\{(1,q):0 \le q \le 1 \}$.
![width=0.3\textwidth](wykre77.png)

56. α=0, β<0, γ=0, δ<0, $NE=\{(p,1):0\le p \le 1\}\cup \{(1,q):0 \le q \le 1 \}$.
![width=0.3\textwidth](wykre78.png)

57. α=0, β<0, γ=0, δ=0, $NE=\{(p,1):0\le p \le 1\}\cup \{(1,q):0 \le q \le 1 \}$.
![width=0.3\textwidth](wykre79.png)
58. α=0, β=0, γ>0, δ>0, \\$NE=\{(p,0):0\le p \le\frac{δ}{γ+δ}\}\cup \{(\frac{δ}{γ+δ},q):0 \le q \le 1 \} \cup \{(p,1): \frac{δ}{γ+δ}\le p \le 1\}$.
![width=0.3\textwidth](wykre80.png)

59. α=0, β=0, γ>0, δ<0, $NE=\{(p,1):0\le p \le 1\}$.
![width=0.3\textwidth](wykre81.png)

60. α=0, β=0, γ>0, δ=0, $NE=\{(0,q):0\le q\le1\}\cup\{(p,1):0\le p\le1\}$.
![width=0.3\textwidth](wykre83.png)

61. α=0, β=0, γ<0, δ>0, $NE=\{(p,0):0\le p\le1\}$.
![width=0.3\textwidth](wykre84.png)

62. α=0, β=0, γ<0, δ<0, \\$NE=\{(p,1):0\le p \le\frac{δ}{γ+δ}\}\cup \{(\frac{δ}{γ+δ},q):0 \le q \le 1 \} \cup \{(p,0): \frac{δ}{γ+δ}\le p \le 1\}$.
![width=0.3\textwidth](wykre82.png)

63. α=0, β=0, γ<0, δ=0, $NE=\{(0,q):0\le q \le1\}\cup\{(p,0):0\le p \le 1\}$.
![width=0.3\textwidth](wykre85.png)

64. α=0, β=0, γ=0, δ>0, $NE=\{(p,0):0\le p \le 1 \} \cup \{(1,q):0\le q \le 1 \}$.
![width=0.3\textwidth](wykre86.png)

65. α=0, β=0, γ=0, δ<0, $NE=\{(p,1):0\le p \le 1 \} \cup \{(1,q):0\le q \le 1 \}$.
![width=0.3\textwidth](wykre79.png)

66. α=0, β=0, γ=0, δ=0, $NE=\{(p,q):0\le p \le 1, 0\le q \le 1\}$.
![width=0.3\textwidth](wykre87.png)

Możemy zauważyć w tym przypadku, że jest to bardzo mocno zdegenerowany przypadek, gdyż bimacierz gry wyjściowej wygląda następująco:
$$(A,B)=\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{22},b_{11})\\
(a_{11},b_{22})&(a_{22},b_{22})\\
\end{array}\right].$$
Widzimy, że żaden z graczy nie ma wpływu na to, ile będzie wynosiła jego wygrana, natomiast każdy z graczy ma wpływ na to, ile będzie wynosić wygrana przeciwnika. Ponieważ w żadnej możliwej sytuacji żaden z graczy nie może podwyższyć swojej wygranej poprzez jednostronną zmianę strategii na jakąkolwiek inną, wszystkie możliwe pary strategii są równowagami Nasha tej gry.






##Podział gier 2x2 ze względu na ilość równowag Nasha

Podsumowując wcześniejsze rozpatrywania poszczególnych przypadków zauważamy, iż gry 2x2 mają tylko i wyłącznie jedną, dwie, trzy lub nieskończenie wiele równowag Nasha.

Rozdział ten jest poświęcony na zebranie poszczególnych przypadków pod kątem ilości równowag Nasha i ich rozmieszczenia w kwadracie jednostkowym \\$\{(p,q): p,q\in[0,1]\}$.

###Jedna równowaga Nasha

Gier 2x2, które posiadają tylko jedną równowagę Nasha jest pięć rodzajów w zależności od jej umiejscowienia w macierzy gry.
Są cztery postacie gier, których rozwiązaniem są pary strategii czystych nazwanych w pracy: $NE_1$, $NE_3$, $NE_4$ i $NE_5$, oraz jedna do  której rozwiązania prowadzi para strategii mieszanych nazwana $NE_2$.

Poniżej wymieniamy poszczególne przypadki, jakie dają pierwszą rownowagę Nasha nazwaną 
$NE_1$. Odpowiada jej para strategii czystych obu graczy $(1,1)$:

1. α>0, β>0, γ>0, δ<0,
2. α>0, β<0, γ>0, δ>0,
3. α>0, β<0, γ>0, δ<0,
4. α>0, β>0, γ<0, δ=0,
5. α>0, β=0, γ>0, δ<0.

 
>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(4,6 )&(1, 2)\\
(1,0)&(2,-2)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(3,4)&(0,0)\\
(0,0)&(1,-2)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek gry postaci:
α>0, β>0, γ>0, δ<0.
 Posiada więc ona jedną równowagę Nasha, która osiągana jest przy strategii graczy (1,1) i daje ona wygrane w wysokości $\overrightarrow{\pi}=(4,6)$.



Nstępnym rozwiązaniem jest równowaga  $NE_2 $, prowadzi do niej para strategii $(\frac{δ}{γ+δ},\frac{β}{α+β})$. Uzyskamy ją w dwóch przypadkach: α>0, β>0, γ<0, δ<0, lub α<0, β<0, γ>0, δ>0.

>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(-1,1 )&(0, -1)\\
(0,-1)&(-2,1)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(-1 ,2)&(0,0)\\
(0,0)&(-2,2)\\
\end{array}\right].$$
Zauważmy, iż jest to przypadek postaci:
α<0, β<0, γ>0, δ>0.
Więc jego rozwiązaniem jest jedna równowaga Nasha. Prowadzi do niej para strategii $(\frac{1}{2},\frac{2}{3})$, a wypłata jaką osiągną gracze jest równa $\overrightarrow{\pi}=(\frac{-5}{6},0)$.


Kolejną pojedyńczą równowagą Nasha jest $NE_3$, odpowiadająca jej para strategii to $(0,0)$. Jest ona wynikiem w przypadkach:

1. α>0, β>0, γ<0, δ>0,
2. α<0, β>0, γ>0, δ>0,
3. α<0, β>0, γ<0, δ>0,
4. α<0, β>0, γ=0, δ>0.


>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(4,0 )&(-1, 1)\\
(2,0)&(2,1)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(2,-1)&(0,0)\\
(0,0)&(3,1)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
α>0, β>0, γ<0, δ>0.
Posiada on jedną równowagę Nasha i prowadzi do niej para strategii (0,0). Daje ona wypłaty w wysokości $\overrightarrow{\pi}=(2,1)$.


Przedostatnią pojedyńczą równowagą Nasha w grach 2x2 jest $NE_4$, która osiagana jest przy strategiach graczy $(0,1)$. Takie rozwiązanie gry otrzymujemy w przypadkach:

1. α<0, β>0, γ>0, δ<0,
2. α<0, β<0, γ>0, δ<0,
3. α<0, β>0, γ=0, δ<0, 
4. α<0, β=0, γ>0, δ<0.


>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(1,2 )&(3, 0)\\
(2,0)&(1,-2)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(-1,2)&(0,0)\\
(0,0)&(-2,-2)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
α>0, β<0, γ>0, δ<0.
Rozwiązaniem tej gry są wypłaty $\overrightarrow{\pi}=(2,0)$ osiągane przy parze strategii graczy (0,1).


Ostanim rodzajem gier 2x2, których rozwiązaniem jest tylko jedna równowaga to gry, w których jedyną równowagą Nasha jest $NE_5$. Gracze kierują się wówczas strategiami $(1,0)$. Efekt ten jest osiągnięty w przypadkach:

1. α<0, β<0, γ<0, δ>0,
2. α>0, β<0, γ<0, δ>0,
3. α>0, β<0, γ<0, δ=0,
4. α=0, β<0, γ<0, δ>0,
5. α>0, β<0, γ<0, δ<0.


>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(-1,-2 )&(3,1)\\
(0,1)&(-2,2)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(-1,-3)&(0,0)\\
(0,0)&(-2,1)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
α<0, β<0, γ<0, δ>0.
Rozwiązaniem tej gry jest wypłata $\overrightarrow{\pi}=(0,1)$ osiągana przy strategiach graczy (1,0).



###Dwie równowagi Nasha



Gier 2x2, posiadających dwie równowagi Nasha są tylko dwa rodzaje.

Pierwszy rodzaj to gry, mające równowagi nazwane w pracy $NE_1$ i $NE_3$. Strategie graczy prowadzące do nich zostały już szczegółowo opisane wcześniej. Przypadkami gier, których rozwiązaniami opytymalnymi są konkretnie te dwie równowagi są gry, w których α>0, β=0, γ>0, δ=0, lub α=0, β>0, γ=0, δ>0.

>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(1,2 )&(1,2)\\
(1,1)&(2,3)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(0,0)&(0,0)\\
(0,0)&(1,2)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
α=0, β>0, γ=0, δ>0.
Są tutaj dwie równowagi Nasha. Pierwsza równowaga daje wypłatę $\overrightarrow{\pi}=(1,2)$ i otrzymamy ją przy strategiach (1,1), natomiast druga równowaga jest osiągana dzięki strategiom (0,0) i wygrana wynosi $\overrightarrow{\pi}=(2,3)$.


Drugim rodzajem takich gier są gry, których rowiązanie znajduje się w punktach $NE_4$ i $NE_5$. Otrzymamy je w przypadku α<0, β=0, γ=0, δ<0, lub α=0, β<0, γ<0, δ=0.

>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(2,-1 )&(1,1)\\
(2,1)&(-1,1)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(0,-2)&(0,0)\\
(0,0)&(-2,0)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
α=0, β<0, γ<0, δ=0.
Są tutaj dwie równowagi Nasha. Pierwsza równowaga daje wypłaty $\overrightarrow{\pi}=(1,1)$ i otrzymamy ją przy parze  strategii (1,0), natomiast druga równowaga jest osiągana dzięki parze strategii (0,1) i wygrana wynosi $\overrightarrow{\pi}=(2,1)$.



###Trzy równowagi Nasha

Gier 2x2, których rozwiązaniami są trzy równowagi Nasha, są dwa rodzaje.

Pierwszy rodzaj takich gier ma równowagi nazwane $NE_1$, $NE_2$ i $NE_3$. Są one wynikami gry, w której wartości wszystkich parametrów są dodatnie (α>0, β>0, γ>0, δ>0).

>PRZYKŁAD: Gra ,,Problem koordynacji''.
\\
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(2, 2 )&(0, 0)\\
(0,0)&(1,1)\\
\end{array}\right].$$
Nie trzeba jej przekształcać, gdyż jest ona od razu w postaci diagonalnej.
Zauważamy, iż jest to przypadek postaci:
α>0, β>0, γ>0, δ>0.
Więc rozwiązaniem są trzy równowagi Nasha:
\begin {enumerate}
\item $NE_1$: strategie graczy wyglądają następująco: $(1,1)$. Osiągają oni wypłaty \\$\overrightarrow{\pi}=(a_{11}, b_{11})=(2,2)$,
\item $NE_2$: strategie graczy wyglądają następująco: \\$(\frac{δ}{γ+δ},\frac{β}{α+β})=(\frac{1}{2+1},\frac{1}{2+1})=(\frac{1}{3},\frac{1}{3})$. Osiągają oni wypłaty $\overrightarrow{\pi}=(\frac{2}{3},\frac{2}{3})$,
\item $NE_3$: strategie graczy wyglądają następująco: $(0,0)$. Osiągają oni wypłaty \\$\overrightarrow{\pi}=(a_{22}, b_{22})=(1,1)$.
\end{enumerate}


Inny rodzaj takich gier to gry, które kończą się równowagami w punktach $NE_2$, $NE_4$ i $NE_5$. Prowadzi do takiego rozwiązania  przypadek α<0, β<0, γ<0, δ<0.

>PRZYKŁAD: Gra  ,,Jastrząb i gołąb".
\\
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(-1,-1 )&(4, 0)\\
(0,4)&(2,2)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(-1 ,-1)&(0,0)\\
(0,0)&(-2,-2)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
α<0, β<0, γ<0, δ<0.
Więc jego rozwiązaniem są trzy równowagi Nasha:
\begin {enumerate}
\item $NE_4$: strategie graczy wyglądają następująco: $(0,1)$. Osiągają oni wypłaty \\$\overrightarrow{\pi}=(0, 4)$,
\item $NE_2$: strategie graczy wyglądają następująco: $(\frac{δ}{γ+δ},\frac{β}{α+β})=(\frac{-2}{-2-1},\frac{-2}{-2-1})=(\frac{2}{3},\frac{2}{3})$. Osiągają oni wypłaty $\overrightarrow{\pi}=(\frac{2}{3}, \frac{2}{3})$,
\item $NE_5$:strategie graczy wyglądają następująco: $(1,0)$. Osiągają oni wypłaty \\$\overrightarrow{\pi}=(4,0)$.
\end {enumerate}


Pojedyncze równowagi Nasha możemy przedstawić na jednym wykresie:
![width=0.33\textwidth](wykre200.png)



###Continuum równowag Nasha


Jeżeli gra 2x2 nie należy do którejś z wymienionych wcześniej klas, to ma nieskończenie wiele równowag Nasha. Gry takie możemy podzielić na kilka grup. Takie, w których równowagi Nasha tworzą odcinek i punkt, takie w których tworzą tylko odcinek, łamaną i w końcu cały kwadrat jednostkowy.

Pierwszą grupą będą gry, w których równowagi Nasha tworzą odcinek i punkt. Możemy wyniki wcześniejszych obliczeń podzielić ze względu na zbiory strategii.
W ten sposób otrzymamy pierwszy zbiór składający sie ze strategii: (1,1) i \\$(0,q): q\in [0,\frac{β}{α+β}]$. Takie rozwiązanie otrzymamy w przypadku: α>0, β>0, γ>0, δ=0.
![width=0.33\textwidth](wykre201.png)

Następny zbiór równowag Nasha składa się ze strategii $(0,0)$ i \\$(p,1): p\in [\frac{δ}{γ+δ},1]$, otrzymamy go w przypadku: α=0, β>0, γ>0, δ>0.
![width=0.33\textwidth](wykre202.png)

Kolejnym przykładem zbioru równowag Nasha składającego się z odcinka i punktu jest zbiór strategii (0,1) i $(p,0): p\in [\frac{δ}{γ+δ},1]$, otrzymamy go w przypadku: α<0, β=0, γ<0, δ<0.
![width=0.33\textwidth](wykre203.png)

Innym przykładem analogicznego zbioru równowag Nasha są strategie (1,1) i $(p,0):p \in [0,\frac{δ}{γ+δ}]$. Osiągamy je w przypadku: α>0, β=0, γ>0, δ>0.
![width=0.33\textwidth](wykre204.png)

Jeszcze inny rodzaj zbioru równowag Nasha postaci odcinek i punkt dają strategie (0,1) i $(1,q): q\in [0,\frac{β}{α+β}]$. Jest to efekt przypadku: α<0, β<0, γ=0, δ<0.
![width=0.33\textwidth](wykre205.png)

Przedostatnim zbiorem równowag Nasha postaci odcinek i punkt są strategie (0,0) i $(1,q): q\in [\frac{β}{α+β},1]$. Powstaje on w przypadku: α>0, β>0, γ=0, δ>0,.
![width=0.33\textwidth](wykre206.png)

Ostatnim zbiorem równowag Nasha  jest zbiór strategii postaci \\(1,0) i $(0,q):q\in [\frac{β}{α+β},1]$, jest tak w przypadku: α<0, β<0, γ<0, δ=0.
![width=0.33\textwidth](wykre207.png)

>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(1,1 )&(4, 2)\\
(2,2)&(4,1)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(-1 ,-1)&(0,0)\\
(0,0)&(0,-1)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
α<0, β=0, γ<0, δ<0.
Więc jego rozwiązaniem jest zbiór równowag Nasha postaci: 
strategie (0,1) i wypłaty \\$\overrightarrow{\pi}=(4,1)$ oraz kombinacja strategii $(p,0): p\in [\frac{1}{2},1]$ i daje ona wypłatę \\$\overrightarrow{\pi}=(4,p+1),p\in [\frac{1}{2},1]$.


Drugą grupą gier są gry, w których równowagi Nasha tworzą odcinek. Otrzymamy kilka rodzajów odcinków. Pierwym rodzajem są odcinki postaci \\$(p,1):p\in [0,\frac{δ}{γ+δ}]$. Powstają one w dwóch przypadkach: α=0, β>0, γ<0, δ<0, lub α=0, β<0, γ<0, δ<0.
![width=0.33\textwidth](wykre208.png)

Następnym rodzajem są odcinki postaci $(1,q):q\in [0,\frac{β}{α+β}]$ i jest tak w przypadku 
 α<0, β<0, γ=0, δ>0.
![width=0.33\textwidth](wykre209.png)

Kolejnym są odcinki postaci $(p,0):p\in [\frac{δ}{γ+δ},1]$ i osiągamy je w dwóch przypadkach:
 α<0, β>0, γ<0, δ<0, lub α>0, β=0, γ<0, δ<0.
![width=0.33\textwidth](wykre210.png)

Inne odcinki równowag Nasha uzyskamy ze strategii $(0,q): q\in [\frac{β}{α+β},1]$. Dzieje się tak w przypadku: α<0, β<0, γ>0, δ=0.
![width=0.33\textwidth](wykre211.png)

Kolejne odcinki powstają ze strategii $(1,q):q\in [\frac{β}{α+β},1]$ i osiągamy je w przypadku: 
α>0, β>0, γ=0, δ<0.
![width=0.33\textwidth](wykre212.png)

Następny rodzaj równowag Nasha powstaje ze strategii $(p,0):p\in [0,\frac{δ}{γ+δ}]$. Powstają one w przypadku: α<0, β=0, γ>0, δ>0.
![width=0.33\textwidth](wykre213.png)

Jeszcze inny rodzaj odcinków tworzą strategie $(p,1):p\in [\frac{δ}{γ+δ},1]$ i jest tak w przypadku:
 α=0, β<0, γ>0, δ>0.
![width=0.33\textwidth](wykre214.png)

Kolejne odcinki uzyskamy ze strategii $(0,q):q\in [0,\frac{β}{α+β}]$. Zbiór tych strategii możemy otrzymać w przypadku:  α>0, β>0, γ<0, δ=0.
![width=0.33\textwidth](wykre215.png)

Następne odcinki powstają ze strategii $(p,0:p\in [0,1]$ i jest tak w przypadkach:

1. α>0, β=0=0, γ<0, δ>0,
2. α>0, β=0=0, γ<0, δ=0,
3. α<0, β=0=0, γ<0, δ>0,
4. α<0, β=0=0, γ=0, δ>0,
5. α=0, β=0=0, γ<0, δ>0.

![width=0.33\textwidth](wykre216.png)

Inny rodzaj odcinków jest efektem zagrania strategii postaci: $(0,q):q\in [0,1]$ i uzyskamy je w poniższych przypadkach:

1. α<0, β=0>0, γ>0, δ=0,
2. α<0, β=0>0, γ<0, δ=0,
3. α<0, β=0>0, γ=0, δ=0,
4. α<0, β=0=0, γ>0, δ=0,
5. α=0, β=0>0, γ<0, δ>0,
6. α=0, β=0>0, γ<0, δ=0.

![width=0.33\textwidth](wykre217.png)

Przedostatni rodzaj odcinków tworzą strategie $(1,q)):q\in [0,1]$ i uzyskamy je w przypadkach:

1. α>0, β=0<0, γ=0, δ>0,
2. α>0, β=0<0, γ=0, δ<0,
3. α>0, β=0<0, γ=0, δ=0,
4. α>0, β=0=0, γ=0, δ<0,
5. α=0, β=0<0, γ=0, δ>0.

![width=0.33\textwidth](wykre218.png)

Ostatni zbiór równowag Nasha uzyskamy jako zbiór strategii $(p,1):p\in[0,1]$. Jest to efekt rozwiązania przypadków postaci: 

1. α=0, β=0>0, γ>0, δ<0,
2. α=0, β=0<0, γ>0, δ<0,
3. α=0, β=0<0, γ>0, δ=0,
4. α=0, β=0>0, γ=0, δ<0,
5. α=0, β=0=0, γ>0, δ<0.

![width=0.33\textwidth](wykre219.png)

>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(1,1 )&(1, 1)\\
(2,1)&(1,2)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(-1 ,0)&(0,0)\\
(0,0)&(0,1)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
α<0, β=0, γ=0, δ>0.
Więc jego rozwiązaniem jest zbiór równowag Nasha postaci: 
strategie $(p,0):p\in [0,1]$ i wypłaty $\overrightarrow{\pi}=(1,p+2), p\in [0,1]$.


Zbiory rozwiązań w postaci łamanej możemy podzielić na osiem rodzajów. Pierwszy zbiór składa się ze strategii $(p,1):p\in [0,1]$ i $(1,q)):q\in [0,1]$ i jest to wynik rozwiązania przypadków:

1. α=0, β=0<0, γ=0, δ<0,
2. α=0, β=0<0, γ=0, δ=0,
3. α=0, β=0=0, γ=0, δ<0.

![width=0.3\textwidth](wykre220.png)

Drugim zbiorem postaci łamanej jest zbiór strategii $(p,0):p\in [0,1]$ i \\$(1,q):q\in[0,1]$. Jest to wynik przypadków:

1. α>0, β=0=0, γ=0, δ>0,
2. α>0, β=0=0, γ=0, δ=0,
3. α=0, β=0=0, γ=0, δ>0.

![width=0.3\textwidth](wykre221.png})

Trzecim zbiorem równowag Nasha jest zbiór strategii postaci $(0,q):q\in[0,1]$ i \\$(p,0):p\in[0,1]$, który powstaje w rezultacie przypadków:

1. α<0, β=0=0, γ=0, δ=0,
2. α<0, β=0=0, γ<0, δ=0,
3. α=0, β=0=0, γ<0, δ=0.

![width=0.3\textwidth](wykre222.png)

Czwartym rodzajem łamamnej są zbiory strategii $(p,1)):p\in[0,1]$ i \\$(0,q):q\in[0,1]$, które są rezultatem przypadków:

1.  α=0, β>0, γ>0, δ=0,
2.  α=0, β>0, γ=0, δ=0,
3. α=0, β=0, γ>0, δ=0.

![width=0.3\textwidth](wykre223.png)

Kolejnym zbiorem rozwiązań opisanym łamaną tworzą strategie postaci \\$(0,q):q\in[\frac{β}{α+β},1]$, $(p,\frac{β}{α+β}):p\in[0,1]$ i $(1,q):q\in[0,\frac{β}{α+β}]$. Dzieje się tak w dwóch przypadkach: α<0, β<0, γ=0, δ=0, lub α>0, β<0, γ=0, δ=0 i $|α|<|β|$.
![width=0.3\textwidth](wykre224.png)

Następnym zbiorem rozwiązań tworzących łamaną tworzą strategie postaci \\$(0,q):q\in[0,\frac{β}{α+β}]$, $(p,\frac{β}{α+β}):p\in[0,1]$ i $(1,q):q\in[\frac{β}{α+β},1]$. Jest to efekt przypadku: α>0, β>0, γ=0, δ=0.
![width=0.3\textwidth](wykre225.png)

Innym zbiorem rozwiązań opisanym łamaną tworzą strategie postaci \\$(p,0):p\in[0,\frac{δ}{γ+δ}]$, $(\frac{δ}{γ+δ},q):q\in[0,1]$ i $(p,1):p\in[\frac{δ}{γ+δ},1]$. Dzieje się tak w przypadku: α=0, β=0, γ>0, δ>0.
![width=0.3\textwidth](wykre226.png)

Ostatnim zbiorem rozwiązań opisanym łamaną tworzą strategie postaci \\$(p,1):p\in[0,\frac{δ}{γ+δ}]$, $(\frac{δ}{γ+δ},q):q\in[0,1]$ i $(p,0):p\in[\frac{δ}{γ+δ},1]$. Jest ona uzyskiwana w przypadku:
 α=0, β=0, γ<0, δ<0.
![width=0.3\textwidth](wykre227.png)


>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(1,2 )&(0, 2)\\
(1,1)&(-1,1)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(0 ,0)&(0,0)\\
(0,0)&(-1,0)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
α=0, β<0, γ=0, δ=0.
Więc jego rozwiązaniem jest zbiór równowag Nasha postaci: strategie $(p,0):p\in [0,1]$ i wypłaty $\overrightarrow{\pi}=(1,1+p), p\in[0,1]$ oraz kombinacja strategii $(1,q):q\in [0,1]$ i daje ona wypłatę $\overrightarrow{\pi}=(q,2),q\in [0,1]$.


Ostatnia grupa rozwiązań to wszystkie możliwe strategie mieszane i czyste jakie mogą zastosować gracze w grze. Ogólnie możemy je zapisać jako \\$(p,q):p\in [0,1], q\in[0,1]$ i są one rezultatem przypadku: $α=0$, $β=0$, $γ=0$, $δ=0$.
![width=0.3\textwidth](wykre228.png)

>PRZYKŁAD:
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(7,1)&(8,1)\\
(7,-3)&(8,-3)\\
\end{array}\right].$$
Przekształcamy ją do postaci diagonalnej i otrzymamy:
$$
\left[\begin{array}{cc}
(0 ,0)&(0,0)\\
(0,0)&(0,0)\\
\end{array}\right].$$
Zauważamy, iż jest to przypadek postaci:
$α=0$, β=0, γ=0, δ=0.
Więc każda możliwa para strategii graczy $(p,q)$, $p,q \in [0,1]$ jest równowagą Nasha tej gry i daje ona wypłaty wysokości $\overrightarrow{\pi}=(8-q,-3+4p):p\in[0,1],q\in[0,1]$.


Uzyskane wyniki przedstawiamy zbiorczo w tabeli pokazującej zaleźność ilości rownówag Nasha gry 2x2 od wartości parametrów charakteryzujacych daną grę. W tabeli został zastosowany symbol $|NE|$ oznaczający ilość równowag Nasha. Symbol ,,+"~oznacza, iż parametr jest większy od 0, ,,-", że mniejszy od 0, a ,,0'' oznacza, iż wartość parametru jest równa 0. Ostatnia kolumna w tabeli podaje, jaki to przypadek z rodziału drugiego pracy. ,,N'' oznacza przypadek niezdegenerowany, a ,,Z'' oznacza zdegenerowany.



| α | β | γ | δ | NE | Lp. |
| :--------: | :------: | :-------: | :--------: | :-----: | :----: |
| + | + | + | + | 3 | N1 |
| + | + | + | - | 1 | N2 |
| + | + | - | + | 1 | N3 |
| + | + | - | +| 1 | N4 |
| + | - | + | + | 1| N5 |
| + | - | + | - | 1 | N6 |
| + | - | - | + | 1 | N7 |
| + | - | - | - | 1 | N8 |
| - | + | + | + | 1 | N9 |
| - | + | + | - | 1 | N10 |
| - | + | - | + | 1 | N11|
| - | + | - | - | ∞ | N12 |
| - | - | + | + | 1 | N13 |
| - | - | + | - | 1 | N14 |
| - | - | - | + | 1 | N15 |
| - | - | - | - | 3 | N16 |
| + | + | + | 0 |  ∞ | Z1 |
| + | + | - | 0 |  ∞ | Z2 |
| + | + | 0 | + |  ∞ | Z3 |
| + | + | 0 | - |  ∞ | Z4 |
| + | + | 0 | 0 |  ∞ | Z5 |
| + | - | + | 0 |  1 | Z6 |
| + | - | - | 0 |  1 | Z7 |
| + | - | 0 | + |  ∞ | Z8 |
| + | - | 0 | - |  ∞ | Z9 |
| + | - | 0 | 0 |  ∞ | Z10 |
| + | 0 | + | + |  ∞ | Z11 |
| + | 0 | + | - |  ∞ | Z12 |
| + | 0 | + | 0 |  2 | Z13 |
| + | 0 | - | + |  ∞ | Z14 |
| + | 0 | - | - |  ∞ | Z15 |
| + | 0 | - | 0 |  ∞ | Z16 |
| + | 0 | 0 | + |  ∞ | Z17 |
| + | 0 | 0 | - |  ∞ | Z18 |
| + | 0 | 0 | 0 |  ∞ | Z19 |
| - | + | + | 0 |  ∞ | Z20 |
| - | + | - | 0 |  ∞ | Z21 |
| - | + | 0 | + |  1 | Z22 |
| - | + | 0 | - |  ∞ | Z23 |
| - | + | 0 | 0 |  ∞ | Z24 |
| - | - | + | 0 |  ∞ | Z25 |
| - | - | - | 0 |  ∞ | Z26 |
| - | - | 0 | + |  ∞ | Z27 |
| - | - | 0 | - |  ∞ | Z28 |
| - | - | 0 | 0 |  ∞ | Z29 |
| - | 0 | + | + |  ∞ | Z30 |
| - | 0 | + | - |  1 | Z31 |
| - | 0 | + | 0 |  ∞ | Z32 |
| - | 0 | - | + |  ∞ | Z33 |
| - | 0 | - | - |  ∞ | Z34 |
| - | 0 | - | 0 |  ∞ | Z35 |
| - | 0 | 0 | + |  ∞ | Z36 |
| - | 0 | 0 | - |  2 | Z37 |
| - | 0 | 0 | 0 |  ∞ | Z38 |
| 0 | + | + | + |  ∞ | Z39 |
| 0 | + | + | - |  ∞ | Z40 |
| 0 | + | + | 0 |  ∞ | Z41 |
| 0 | + | - | + |  ∞ | Z42 |
| 0 | + | - | - |  ∞ | Z43 |
| 0 | + | - | 0 |  ∞ | Z44 |
| 0 | + | 0 | + |  2 | Z45 |
| 0 | + | + | 0 |  ∞ | Z46 |
| 0 | + | 0 | 0 |  ∞ | Z47 |
| 0 | - | + | + |  ∞ | Z48 |
| 0 | - | + | - |  ∞ | Z49 |
| 0 | - | + | 0 |  ∞ | Z50 |
| 0 | - | - | + |  ∞ | Z51 |
| 0 | - | - | - |  ∞ | Z52 |
| 0 | - | - | 0 |  2 | Z53 |
| 0 | - | 0 | + |  ∞ | Z54 |
| 0 | - | 0 | - |  ∞ | Z55 |
| 0 | - | 0 | 0 |  ∞ | Z56 |
| 0 | 0 | + | + |  ∞ | Z57 |
| 0 | 0 | + | + |  ∞ | Z57 |
| 0 | 0 | + | - |  ∞ | Z58 |
| 0 | 0 | + | 0 |  ∞ | Z59 |
| 0 | 0 | - | + |  ∞ | Z60 |
| 0 | 0 | - | - |  ∞ | Z61 |
| 0 | 0 | - | 0 |  ∞ | Z62 |
| 0 | 0 | 0 | + |  ∞ | Z63 |
| 0 | 0 | 0 | - |  ∞ | Z64 |
| 0 | 0 | 0 | 0 |  ∞ | Z65 |
		



##Zakończenie



Celem niniejszej pracy było systematyczne przebadanie wszystkich możliwych typów gier 2x2 pod kątem ilości i rozmieszczenia równowag Nasha. Problem ten nie był dotychczas poruszany w literaturze.

W pierwszym rozdziale przybliżona została historia teorii gier oraz życiorys Johna Nasha. Pokazano także definicję gry i pojęć z nią powiązanych. Zostały w nim zdefiniowane równowagi Nasha i pokazano sposób ich poszukiwania metodą graficzną. Zostały wprowadzone definicje i twierdzenia związane z innwariantnością równowag Nasha względem loklnych przesunięć.

W drugim rozdziale pokazano jak sprowadzić dowolną grę 2x2 do postaci bimacierzy diagonalnej. Otrzymane gry podzielono ze względu na wartości parametrów na przypadki zdegenerowane i niezdegenerowane oraz zbadano ile równowag posiadają gry tworzące poszczególne przypadki. 

Na podstawie wcześniejszego rozdziału w trzecim rozdziale pogrupowano wcześniesze przypadki ze względu na ilość równowag Nasha w bimacierzy wypłat.

Na końcu zaprezentowano tabelę przedstawiającą zależność ilość równowag Nasha gry 2x2 od wartości parametrów charakteryzujących daną grę.



##Bibliografia

1. Kałuski J.,*Teoria gier*, Wydawnictwo Politechniki Śląskiej, Gliwice 2002. 
2. Peters H., *Game Theory*. A Multi-Leveled Approach}, Springer-Verlag, Berlin 2008. 
3. Płonka E., *Wykłady z teorii gier*, Wydawnictwo Politechniki Śląskiej, Gliwice 2001.
4. Watson J., *Strategia. Wprowadzenie do teorii gier*, Wydwnictwo Naukowo-Techniczne, Warszawa 2002.











