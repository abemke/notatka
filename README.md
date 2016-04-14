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




Najbardziej podstawowym pojęciem w teorii gier jest pojęcie \textbf{gry}. Gra jest sformalizowanym opisem konfliktu. Dokładny opis gry zawiera wskazanie:
\\
- kto?
\\
- w jaki sposób bierze udział w konflikcie?
\\
- jakie są możliwe wyniki?
\\
- kto i w jakiej formie jest zainteresowany możliwymi wynikami?
\\
Charakterystyczne cechy gier są takie same bez względu na rodzaj gry, jej złożoność lub prostotę. Dodatkowo w przypadku każdej gry zakładamy znajomość reguł gry przez wszystkich jej uczestników.

Osoby biorące udział w grze nazywamy \textbf{graczami}. Określenie \textit{gracz} nie zawsze musi oznaczać jedną osobę, może to być grupa ludzi, firma, czy nawet państwo. Zazwyczaj zakładamy skończoną liczbę graczy. W niniejszej pracy rozpatrywać będziemy głównie gry dwuosobowe. 

Działania graczy inaczej nazywamy akcjami, decyzjami, bądź ruchami gracza. Pełen opis postępowania gracza w każdej możliwej sytuacji nazywamy \textbf{strategią}. Często w grach opis strategii jest skomplikowany lub strategie nie są od razu widoczne. W niniejszej pracy będziemy na ogół zakładać, że każdy gracz posiada tylko dwie strategie. Zazwyczaj wyróżniamy dwa rodzaje strategii: czyste i mieszane (zostaną one opisane dokładniej w dalszej części pracy). 

 Gra kończy się \textbf{wypłatą} lub \textbf{wygraną}, która jest wyrażona liczbą rzeczywistą. Każdy gracz ma swój cel, którym jest zmaksymalizowanie swojej wygranej wszystkimi dostępnymi środkami. Wygrana danego gracza zatem zależy od sposobu jego postępowania, ale również od zachowań pozostałych graczy. Wygrane określane są poprzez \textbf{funkcję wypłat} poszczególnych graczy.

\textbf{Rozwiązaniem gry} jest znalezienie optymalnych strategii gry dla wszystkich graczy biorących udział w grze. Zwykle przyjmujemy, że rozwiązaniem gry dwuosobowej jest para strategii tworząca równowagę Nasha (wyjaśnienie tego pojęcia znajduje się w dalszej części pracy). 

Po nieformalnym przedstawieniu pojecia gry i jej elementów wprowadzimy formalną definicję gry.

\textbf{Normalna} forma zapisu gry jest definiowana poprzez określenie listy graczy, zbioru strategii każdego gracza oraz funkcji wypłat. Dodatkowo zakładamy, że gracze wybierają swoje strategie jednocześnie, a więc wybierając je nie wiedzą, jakie strategie wybrali pozostali gracze.

\begin{df} 

Rodzinę $\Theta=\left(N,\Sigma,\pi\right)$ nazywamy \textbf{n-osobową grą w postaci normalnej}, gdzie:
\begin{enumerate}
\item N={1,2,...n} jest zbiorem graczy;
\item zbiór $\Sigma_{i}$ jest zbiorem strategii i-tego gracza, $1 \leq i \leq n$;
\item $\Sigma=\Sigma_{1}\times\Sigma_{2}\times...\times\Sigma_{n}$ jest zbiorem stanów w grze $\Theta$;
\item funkcja $\pi_{i}:\Sigma_{1}\times\Sigma_{2}\times...\times\Sigma_{n} \rightarrow \mathbb{R}$ jest funkcją wypłaty (wygranych) i-tego gracza,  $1 \leq i \leq n$ oraz $\pi=\left(\pi_1,\pi_2,...,\pi_n\right)$;
\item wektor $\left(\pi_1\left(s\right),\pi_2\left(s\right),...,\pi_n\left(s\right)\right) \in \mathbb{R}^{n}$, nazywamy wektorem wypłat (wygranych) stanu $s=\left(s_1,s_2,...,s_n\right)\in\Sigma$.
\end{enumerate}
Celem i-tego gracza jest maksymalizacja jego funkcji wypłaty $\pi_i$ przez wybór strategii ze zbioru $\Sigma_i$.
 \end{df}



###Gry 2x2



\textbf{Gra 2x2} jest to gra dwóch graczy, w której każdy z graczy posiada dwie strategie. Zapis 2x2 onacza model gry w postaci normalnej, a dokładniej w postaci macierzowej, dlatego pominiemy pozostałe możliwe klasyfikacje modeli gier.

Grę 2x2 w postaci normalnej zapisujemy za pomocą bimacierzy:


$$\left(A,B\right)=
\kbordermatrix{\mbox{ }&I&II\\
P&(a_{11} ,b_{11} )&(a_{12},b_{12})\\
L&(a_{21},b_{21})&(a_{22},b_{22})\\
}$$
\\
Jest to zapis w postaci podwójnej macierzy gry, gdyż bimacierz (A,B) jest parą macierzy 
$$A=\left[\begin{array}{cc}
a_{11}&a_{12}\\
a_{21}&a_{22}\\
\end{array}\right]
\\
B=\left[\begin{array}{cc}
b_{11} &b_{12}\\
b_{21}&b_{22}\\
\end{array}\right]$$
\\
przedstawiających, odpowiednio, wypłaty dla Gracza 1 (Wiersza) i Gracza 2 (Kolumny). W przedstawionej bimacierzy Wiersz gra jedną z dwóch strategii P lub L i są one reprezentowne prez wiersze. Kolumna gra również jedną z dwóch strategii I lub II oraz odpowiadają im kolumny. W miejscu przecięcia się wiersza i kolumny znajdują się liczby reprezentujące wypłaty dla graczy odpowiadające wybranym przez graczy strategiom. Na przykład jeżeli Wiersz gra według strategii P i Kolumna postępuje zgodnie ze strategią II to wypłatami będą liczby $a_{12}$ i $b_{12}$. Kwota $a_{12}$ jest wypłatą jaką otrzyma Wiersz, natomiast $ b_{12}$ jest wygraną Kolumny.

\begin{df}  
Jeżeli gracz ma do dyspozycji zbiór strategii $\{ s_1,s_2\}$ i wybiera je z prawdopodobieństwami $\{p_1,p_2\}$, $0\leq p_i \leq 1$, $p_1+p_2 =1$, to mówimy, że gra \textbf{strategię mieszaną} określoną rozkładem prawdopodobieństwa $\{p_1,p_2\}$. 
Natomiast o strategiach $s_1,s_2$ mówimy, że są to \textbf{strategie czyste}.
\end{df}
Inaczej mówiąc strategia mieszana jest rozkładem prawdopodobieństwa określonym na zbiorze strategii czystych. Zauważamy, że strategie czyste są szczególnymi przypadkami strategi mieszanych. W strategiach czystych dla pewnego indeksu \\i=1 lub 2~$p_i=1$, natomiast $ p_j=0~ dla~~ j\ne i$. 

Dla uproszczenia zapisów w pracy zastosowaliśmy skrótową formę zapisu strategii graczy. Strategie obu graczy zapisane w jednym nawiasie $(\overrightarrow{p},\overrightarrow{q})$ oznaczają, że Gracz 1 gra strategię $\overrightarrow{p}=(p,1-p)$, natomiast Gracz 2 gra strategię ${\overrightarrow{q}=(q,1-q)}$. Gdy nie będzie budziło to wątpliwości symbol wektora będziemy pomijać i para strategii $\overrightarrow{p}=(p,1-p)$ oraz $\overrightarrow{q}=(q,1-q)$ będziemy oznaczać (p,q).

\begin{ex} Wektor $\overrightarrow{p}=(p,1-p)=(1,0)$ jest strategią czystą Wiersza, czyli Gracz 1 gra strategię czystą $s_1$ nazwaną w przykładowej bimacierzy strategią P. W tej samej grze Kolumna może grać strategię mieszaną, np. $ \overrightarrow{q}=(q,1-q)=(\frac{1}{2},\frac{1}{2})$, w tym przypadku Gracz 2 wybiera strategię czystą I z prawdopodobieństwem $\frac{1}{2}$ i strategię czystą II z prawdopodobieństwem $\frac{1}{2}$.
\end{ex}

\begin{df}
Gdy gracze w grze 2x2 grają strategie mieszane $(\overrightarrow{p},\overrightarrow{q})$, gdzie $\overrightarrow{p}=(p_1,p_2)$, $\overrightarrow{q}=(q_1,q_2)$ funkcjami wypłaty są wartości oczekiwane
$$\pi_1 \left( \overrightarrow{p},\overrightarrow{q} \right)=\sum\limits_{i=1}^2\sum\limits_{j=1}^2 p_iq_ja_{ij},$$ 
$$\pi_2 \left( \overrightarrow{p},\overrightarrow{q} \right)=\sum\limits_{i=1}^2\sum\limits_{j=1}^2 p_iq_jb_{ij}.$$ 
\end{df}
W dalszej części pracy oznaczmy przez $\pi$ funkcję wypłat obu graczy, czyli: $$\pi=(\pi_1 \left( \overrightarrow{p},\overrightarrow{q} \right)),\pi_2 \left( \overrightarrow{p},\overrightarrow{q} \right)).$$

\begin{ex}
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
\end{ex}





###Równowagi Nasha i ich poszukiwanie metodą graficzną



Niech $A,B \in M_{2x2}\left( \mathbb{R} \right)$ będą dwiema macierzami o współczynnikach rzeczywistych, będącymi wypłatami odpowiednio Wiersza i Kolumny, przy założeniu, że strategiami czystymi pierwszego gracza są wiersze, a drugiego kolumny. Zatem ich wypłaty przy zastosowaniu i-tej oraz j-tej strategii czystej, $i,j=1,2$ wynoszą odpowiednio $\pi_1\left(i,j\right)=a_{ij}$ oraz $\pi_2\left(i,j\right)=b_{ij}$.


\begin{df} 
Element $(\overrightarrow{p^*},\overrightarrow{q^*})$ zbioru $\Sigma_1\times\Sigma_2$ nazywamy \textbf{stanem równowagi Nasha gry} $\Theta=(\Sigma_1,\Sigma_2,\pi)$, albo po prostu równowagą Nasha, jeżeli spełnione są nierówności:
$$\pi_1 \left(\overrightarrow{p},\overrightarrow{q^*}\right) \leqslant  \pi_1 \left(\overrightarrow{p^*},\overrightarrow{q^*}\right) \forall ~\overrightarrow{p} \in \Sigma_1,$$
$$\pi_2 \left(\overrightarrow{p^*},\overrightarrow{q}\right) \leqslant  \pi_2 \left(\overrightarrow{p^*},\overrightarrow{q^*}\right) \forall ~\overrightarrow{q} \in \Sigma_2.$$
Przez $E(\Theta)$ oznaczamy zbiór wszystkich równowag Nasha gry $\Theta$.
\end{df}

\begin{uw}  
Gdy Wiersz zamieni strategię $\overrightarrow{p^*} $ na inną, a drugi gracz tego nie zrobi, to jego wygrana nie wzrośnie.
\end{uw}

\begin{uw}  
Gdy Kolumna zamieni strategię $\overrightarrow{q^*} $ na inną, a Wiersz tego nie zrobi to jej wygrana nie wzrośnie.
\end{uw}

\textbf{Metoda graficzna} poszukiwania równowag Nasha w grach 2x2:
\begin{df}
Niech $\Theta=(\Sigma_1,\Sigma_2,\pi)$ będzie grą dwuosobową. Zbiory: 
$$W_1= \{ \left(\overrightarrow{p^*},\overrightarrow{q} \right) :\pi_1 \left( \overrightarrow{p^*},\overrightarrow{q} \right) =\max_{\overrightarrow{p}}  \pi_1 \left( \overrightarrow{p},\overrightarrow{q} \right), \overrightarrow{q} \in \Sigma_2 \};$$
$$W_2= \{ \left( \overrightarrow{p},\overrightarrow{q^*} \right) :\pi_2 \left( \overrightarrow{p},\overrightarrow{q^*} \right) =\max_{\overrightarrow{q}}  \pi_2 \left( \overrightarrow{p},\overrightarrow{q} \right) , \overrightarrow{p} \in \Sigma_1 \};$$
nazywamy \textbf{zbiorami najlepszych odpowiedzi}, odpowiednio dla pierwszego i dla drugiego gracza.
\end{df}
\begin{tw}
\label{rNasha}
Stan $(\overrightarrow{p^*},\overrightarrow{q^*})$ jest stanem równowagi Nasha wtedy i tylko wtedy, gdy $(\overrightarrow{p^*},\overrightarrow{q^*}) \in W_1 \cap W_2$.
\end{tw}
\begin{dw}
Wynika z definicji stanu równowagi Nasha, gdyż tworzą go najlepsze na siebie nawzajem odpowiedzi graczy.
\end{dw}



###Inwariantność równowag Nasha względem lokalnych przesunięć




\begin{df}\textbf{Lokalnymi przesunięciami} w grze bimacierzowej (A,B) nazywamy dodanie tej samej liczby w poszczególnych wierszach macierzy wypłat Gracza 2:
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
\end{df}
\begin{uw}
Definicję zilustrowano przykładami lokalnych przesunięć w grze 2x2, ale obowiązuje ona dla dowolnej gry bimacierzowej.
\end{uw}
\begin{tw}
Lokalne przesunięcia w grach bimacierzowych nie zmieniają zbiorów najlepszych odpowiedzi i położenia równowag Nasha.
\end{tw}
\begin{dw}
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
\end{dw}

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
( \alpha , \gamma )&(0,0)\\
(0,0)&(\beta , \delta)\\
\end{array}\right]$$
\\
Gdzie zastosowaliśmy podstawienie:
$$\alpha=a_{11}-a_{21};$$
$$\beta=a_{22}-a_{12};$$
$$\gamma=b_{11}-b_{12};$$
$$\delta=b_{22}-b_{21};$$
\\
Jest to bimacierz diagonalna.




###Graficzne wyznaczanie równowag Nasha w grach 2x2 sprowadzonych do postaci diagonalnej


Rozbijamy bimacierz gry 2x2 sprowadzonej do postaci diagonalnej  na dwie macierze:
$$(A^{\prime},B^{\prime})=\left[\begin{array}{cc}
( \alpha , \gamma )&(0,0)\\
(0,0)&(\beta , \delta)\\
\end{array}\right]
\\ \to
A^{\prime}=\left[\begin{array}{cc}
\alpha&0\\
0&\beta\\
\end{array}\right]
\\, 
B^{\prime}=\left[\begin{array}{cc}
\gamma&0\\
0&\delta\\
\end{array}\right]$$
Dla ułatwienia późniejszych obliczeń wyznaczamy wypłaty osiagane przy poszczególnych strategiach  Gracza 1  i Gracza 2 :
$$\pi_1(1,q)=\alpha q+0(1-q)=\alpha q$$
$$\pi_1(0,q)=0q+\beta (1-q)=\beta - \beta q$$
$$\pi_2(p,1)=\gamma p+0(1-p)=\gamma p$$
$$\pi_2(p,0)=0p+\delta (1-p)=\delta-\delta p$$

Sprawdzamy dla jakich  wartości q spełniona jest nierówność pomiędy wypłatami Gracza 1:
$$\pi_1(1,q) \ge \pi_1(0,q).$$
Rozwiązanie tej nierówności pokaże nam, kiedy najlepszą odpowiedzią Gracza 1 na strategię q Gracza 2 jest strategia czysta p=1. Przedział do jakiego należy q otrzymamy poprzez wstawienie za $\pi_1(1,q)=\alpha q$ i $\pi_1(0,q)=\beta (1-q)$:
$$\alpha q \ge \beta (1-q),$$
$$\alpha q + \beta q \ge \beta.$$
Dostajemy ostatecznie:
$$q ( \alpha + \beta) \ge \beta.$$
A więc zbiór $\{q:q(\alpha + \beta )\ge \beta \} \cap [0,1]$ jest zbiorem tych wartości q, dla których najlepszą odpowiedzią Gracza 1 na strategię q Gracza 2 jest strategia czysta p=1.

Oczywiście równość:
 $$\pi_1(1,q) = \pi_1(0,q)$$
oznacza, że obie strategie czyste Gracza 1: p=1 oraz p=0, a więc także każda jego strategia mieszana, są najlepszymi odpowiedziami Gracza 1 na strategię q Gracza 2. Jest tak wtedy, gdy $q ( \alpha + \beta) = \beta.$ 

Ostatecznie wywnioskujemy, że odwzorowanie najlepszych odpowiedzi Gracza 1 na wszystkie możliwe strategie $q \in [0,1]$ Gracza 2 określamy następująco:
$$
W_1(q)= \begin{cases}
1 & \text{gdy } q\in [0,1] \text{ jest takie, że } q(\alpha + \beta )\ge \beta\\
[0,1] & \text{gdy } q\in [0,1] \text{ jest takie, że } q(\alpha + \beta )= \beta\\
0 & \text{gdy } q\in [0,1] \text{ jest takie, że } q(\alpha + \beta )\le \beta\\
\end{cases}
.$$

Postępując analogicznie znajdujemy odwzorowanie najlepszych odpowiedzi Gracza 2 na wszystkie możliwe strategie $p \in [0,1]$ Gracza 1:
$$
W_2(p)= \begin{cases}
1 & \text{gdy } p\in [0,1] \text{ jest takie, że } p(\gamma + \delta )\ge \delta\\
[0,1] & \text{gdy } p\in [0,1] \text{ jest takie, że } p(\gamma + \delta )= \delta\\
0 & \text{gdy } p\in [0,1] \text{ jest takie, że } p(\gamma + \delta )\le \delta\\
\end{cases}
.$$

Aby znaleźć zbiór równowag Nasha gry 2x2 należy wykresy odwzorowań najlepszych odpowiedzi $W_1(q)~ i~ W_2(p)$ wykonać w jednym układzie współrzędnych. Zgodnie z Twierdzeniem \ref{rNasha}. zbiór równowag Nasha jest reprezentowany przez część wspólną wykresów odwzorowań $W_1(q)~ i~ W_2(p)$.

W zależności od wartości jakie przyjmują parametry $\alpha$, $\beta$, $\gamma$, $\delta$  (parametry te mogą być ujemne, równe zero lub dodatnie) otrzymamy do rozpatrzenia 81 przypadków.

Dzielimy je na przypadki niedegenerowne, gdy żaden z parmetrów nie jest zerowy i zdegenerowane, gdy chociażby jeden z parametrów $\alpha$, $\beta$, $\gamma$, $\delta$ przyjmuje wartość zero.


###Przypadki niezdegenerowane




Rozpoczynamy od znalezienia odwzorowania $W_1(q)$ w zależności od warości parametrów $\alpha$ i $\beta$:

\begin {enumerate}

	\item $\alpha > 0$, $\beta > 0$, co daje $q ( \alpha + \beta) \ge \beta \Leftrightarrow q \ge \frac{\beta}{\alpha+\beta} \in [0,1]$.
Otrzymamy więc odwzorowanie najlepszych odpowiedzi Gracza 1:
$
W_1(q)=  \begin{cases}
1 & \text{dla } \frac{\beta}{\alpha +\beta} \le q \le 1\\
[0,1] & \text{dla } q=\frac{\beta}{\alpha +\beta}\\
0 & \text{dla } 0\le q \le \frac{\beta}{\alpha +\beta}\\
\end{cases}
.$
	\item $\alpha > 0$, $\beta < 0$. Wówczas nierówność $q(\alpha + \beta)\ge \beta$ jest spełniona dla każdego $q \in [0,1]$, gdyż jeżeli $\alpha < |\beta|$ to $q(\alpha + \beta)\ge \beta \Leftrightarrow q \le \frac{\beta}{\alpha+\beta}$, ale $\frac{\beta}{\alpha+\beta}>1$. Jeżeli zaś $\alpha \ge |\beta|$, to lewa strona nierówności $q(\alpha + \beta)\ge \beta$ jest nieujemna, prawa zaś ujemna. Widzimy więc, że gdy $\alpha>0$, $\beta<0$, to $W_1(q)=1$ dla każdego $q\in [0,1]$.

	\item $\alpha < 0$, $\beta > 0$. Wówczas łatwo sprawdzimy, że dla każdego $q\in [0,1]$ spełniona jest nierówność  $q(\alpha + \beta)\le \beta$, a więc $W_1(q)=0$ dla każdego $q\in [0,1]$.

	\item $\alpha < 0$, $\beta < 0$, więc $q ( \alpha + \beta) \ge \beta \Leftrightarrow q\le \frac{\beta}{\alpha+\beta} \in [0,1]$, co daje: \\ ${W_1(q)= \begin{cases}
1 & \text{dla } 0 \le q \le \frac{\beta}{\alpha +\beta}\\
[0,1] & \text{dla } q=\frac{\beta}{\alpha +\beta}\\
0 & \text{dla } \frac{\beta}{\alpha +\beta} \le q \le 1\\
\end{cases}
.}$
\end {enumerate}


Następnie znajdujemy odworownie $W_2(p)$ w zależności od parametrów $\gamma$ i $\delta$:
\begin {enumerate}

	\item $\gamma > 0$, $\delta > 0$, dlatego $p ( \gamma +\delta) \ge \delta \Leftrightarrow p\ge\frac{\delta}{\gamma+\delta}$. Więc odwzorowanie najlepszych odpowiedzi Gracza 2 jest następujące: ${W_2(p)= \begin{cases}
1 & \text{dla } \frac{\delta}{\gamma +\delta} \le p \le 1\\
[0,1] & \text{dla } p=\frac{\delta}{\gamma +\delta}\\
0 & \text{dla } 0 \le p \le \frac{\delta}{\gamma +\delta}\\
\end{cases}
.}$

	\item  $\gamma > 0$, $\delta < 0$. Wówczas nierówność $p (\gamma +\delta) \ge \delta$ jest spełniona dla każdego $p\in [0,1]$, gdyż jeżeli $\gamma<|\delta|$ to  $p (\gamma +\delta) \ge \delta \Leftrightarrow p\le \frac{\delta}{\gamma +\delta}$, ale $\frac{\delta}{\gamma +\delta}>1$. Jeżeli zaś $\gamma \ge |\delta|$, to lewa strona nierówności  $p (\gamma +\delta) \ge \delta$ jest nieujemna, prawa zaś ujemna. Widzimy więc, że gdy $\gamma>0$, $\delta<0$, to $W_2(p)=1$ dla każdego $p\in [0,1]$.

	\item  $\gamma < 0$, $\delta > 0$. Wówczas łatwo sprawdzamy, że dla każdego $p \in [0,1]$ spełniona jest nierówność $p ( \gamma +\delta) \le \delta$, a więc $W_2(p)=0$ dla każdego $p\in [0,1]$.

	\item  $\gamma < 0$, $\delta < 0$. Wówczas $p ( \gamma +\delta) \ge \delta \Leftrightarrow p\le \frac{\delta}{\gamma+\delta}$.
Co daje odwzorowanie najlepszych odpowiedzi Gracza 2:
${W_2(p)= \begin{cases}
1 & \text{dla } 0 \le p \le \frac{\delta}{\gamma +\delta}\\
[0,1] & \text{dla } p=\frac{\delta}{\gamma +\delta}\\
0 & \text{dla } \frac{\delta}{\gamma +\delta} \le p \le 1\\
\end{cases}
.}$
\end {enumerate}

Wcześniejsze obliczenia możemy przedstawić w tabeli:

\begin{center}
\begin{tabular}{|c|c|c|c|}
\hline
$\alpha$ & $\beta$ & $W_1(q)$ & wykres\\
\hline
\hline
+ & + & $\begin{cases} 
1 & \text{dla } \frac{\beta}{\alpha +\beta} \le q \le 1\\
[0,1] & \text{dla } q=\frac{\beta}{\alpha +\beta}\\
0 & \text{dla } 0\le q \le \frac{\beta}{\alpha +\beta}\\
\end{cases}$ & \includegraphics [width=0.2\textwidth] {wykre100.png}\\
\hline
+ & - & 1 dla $q\in[0,1]$ &\raisebox{-\height}{ \includegraphics [width=0.2\textwidth] {wykre101.png}}\\
\hline
- & + & 0 dla $q\in[0,1]$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre102.png}}\\
\hline
- & - & $\begin{cases}
1 & \text{dla } 0 \le q \le \frac{\beta}{\alpha +\beta}\\
[0,1] & \text{dla } q=\frac{\beta}{\alpha +\beta}\\
0 & \text{dla } \frac{\beta}{\alpha +\beta} \le q \le 1\\
\end{cases}$ & \includegraphics [width=0.2\textwidth] {wykre103.png}\\
\hline
\hline
$\gamma$ & $\delta$ & $W_2(p)$ & wykres\\
\hline
\hline
+ & + & $\begin{cases}
1 & \text{dla } \frac{\delta}{\gamma +\delta} \le p \le 1\\
[0,1] & \text{dla } p=\frac{\delta}{\gamma +\delta}\\
0 & \text{dla } 0 \le p \le \frac{\delta}{\gamma +\delta}\\
\end{cases}$ & \includegraphics [width=0.2\textwidth] {wykre104.png}\\
\hline
+ & - & 1 dla $p\in[0,1]$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre106.png}}\\
\hline
\end{tabular}
\end{center}

\begin{center}
\begin{tabular}{|c|c|c|c|}
\hline
$\gamma$ & $\delta$ & $W_2(p)$ & wykres\\
\hline
\hline
- & + & 0 dla $p\in[0,1]$ & \raisebox{-\height}{\includegraphics [width=0.2\textwidth] {wykre107.png}}\\
\hline
- & - & $\begin{cases}
1 & \text{dla } 0 \le p \le \frac{\delta}{\gamma +\delta}\\
[0,1] & \text{dla } p=\frac{\delta}{\gamma +\delta}\\
0 & \text{dla } \frac{\delta}{\gamma +\delta} \le p \le 1\\
\end{cases}$ & \includegraphics [width=0.2\textwidth] {wykre105.png}\\
\hline
\end{tabular}
\end{center}


Wykorzystując wcześniejsze obliczenia możemy narysować wykresy odwzorowań $W_1(q)$ i $W_2(p)$ w jednym układzie współrzędnych oraz zaznaczyć zbiór równowag Nasha określony jako $W_1(q) \cap W_2(p)$ w zależności od wartości parametrów: $\alpha$, $\beta$, $\gamma$, $\delta$:

\begin {enumerate}
		\item $\alpha > 0$, $\beta > 0$, $\gamma > 0$, $\delta > 0$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre1.png}

W tym przypadku otrzymamy trzy równowagi Nasha:
\\
$NE_1=(1,1)$ odpowiada jej wektor wypłat $\overrightarrow{\pi}= (\alpha, \gamma)$,
\\
$NE_2=(\frac{\delta}{\gamma+\delta},\frac{\beta}{\alpha+\beta})$ odpowiada jej wektor wypłat $\overrightarrow{\pi}= (\frac{\alpha \beta}{\alpha+\beta},\frac{\gamma \delta}{\gamma+ \delta})$, gdyż

\begin{eqnarray*}
\pi_1 & = & \alpha \frac{\delta}{\gamma+\delta} \frac{\beta}{\alpha+\beta}+ \beta (1-\frac{\delta}{\gamma+\delta})(1- \frac{\beta}{\alpha+\beta}) \\ & = & \frac{\alpha \delta \beta}{(\gamma+\delta)(\alpha+\beta)}+\frac{\beta \gamma \alpha}{(\gamma+\delta)(\alpha+\beta)} \\ & =&  \frac{\alpha \beta (\delta+\gamma)}{(\gamma+\delta)(\alpha+\beta)} \\ & = & \frac{\alpha \beta}{\alpha+\beta}
\end{eqnarray*}

\begin{eqnarray*}
\pi_2 & = & \gamma \frac{\delta}{\gamma+\delta} \frac{\beta}{\alpha+\beta}+\delta(1-\frac{\delta}{\gamma+\delta})(1- \frac{\beta}{\alpha+\beta}) \\ & = & \frac{\gamma \delta \beta}{(\gamma+\delta)(\alpha+\beta)}+ \frac{\delta \gamma \alpha}{(\gamma+\delta)(\alpha+\beta)} \\&=& \frac{\delta \gamma(\alpha + \beta)}{(\gamma+\delta)(\alpha+\beta)}\\&=& \frac{\gamma \delta}{\gamma+ \delta}.
\end{eqnarray*}
\\
$NE_3=(0,0)$ odpowiada jej wektor wypłat $\overrightarrow{\pi}=(\beta, \delta)$.

W dalszej części pracy zastosujemy skrót $NE_1$ dla onaczenia równowagi \\$NE_1=(1,1)$. Analogicznie zastosujemy skróty dla równowag Nasha $NE_2$, $NE_3$, $NE_4$ i $NE_5$.


		\item $\alpha>0$, $\beta>0$, $\gamma>0$, $\delta<0$. Otrzymamy jedną równowagę Nasha: $NE_1$:

%wykres
\includegraphics [width=0.3\textwidth] {wykre2.png}.
		
		\item $\alpha>0$, $\beta>0$, $\gamma<0$, $\delta>0$. Otrzymamy jedną równowagę Nasha: $NE_3$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre3.png}

		\item $\alpha>0$, $\beta>0$, $\gamma<0$, $\delta<0$. Rysujemy wykres i odczytujemy z niego, iż jest tylko jedna równowaga Nasha: $NE_2$.

%wykres
\includegraphics [width=0.33\textwidth] {wykre4.png}


		\item $\alpha>0$, $\beta<0$, $\gamma>0$, $\delta>0$. Otrzymamy jedną równowagę Nasha: $NE_1$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre16.png}

		\item $\alpha>0$, $\beta<0$, $\gamma>0$, $\delta<0$. Otrzymamy jedną równowagę Nasha: $NE_1$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre17.png}

			\item $\alpha>0$, $\beta<0$, $\gamma<0$, $\delta>0$. Otrzymamy jedną równowagę Nasha: $NE_5=(1,0)$, odpowiada jej wektor wypłat $\overrightarrow{\pi}=(0,0)$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre14.png}

		\item $\alpha>0$, $\beta<0$, $\gamma<0$, $\delta<0$. Otrzymamy jedną równowagę Nasha: $NE_5$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre18.png}

		\item $\alpha<0$, $\beta>0$, $\gamma>0$, $\delta>0$. Otrzymamy jedną równowagę Nasha: $NE_3$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre5.png}


		\item $\alpha<0$, $\beta>0$, $\gamma>0$, $\delta<0$. Otrzymamy jedną równowagę Nasha: 
$NE_4=(0,1)$, odpowiada jej wektor wypłat $\overrightarrow{\pi}=(0,0)$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre7.png}

		
		\item $\alpha<0$, $\beta>0$, $\gamma<0$, $\delta>0$. Otrzymamy jedną równowagę Nasha: 
$NE_3$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre8.png}


		\item $\alpha<0$, $\beta>0$, $\gamma<0$, $\delta<0$. Otrzymamy  nieskończenie wiele równowag Nasha: $NE=\{(p,0): \frac{\delta}{\gamma+\delta}\le p \le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre10.png}

Symbolem NE oznaczamy zbiór par strategii jakich wynikiem jest równowaga Nasha.

		\item $\alpha<0$, $\beta<0$, $\gamma>0$, $\delta>0$. Z wykresu odczytamy: $NE_2$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre11.png}

		\item $\alpha<0$, $\beta<0$, $\gamma>0$, $\delta<0$. Otrzymamy jedną równowagę Nasha: $NE_4$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre12.png}
		
		\item $\alpha<0$, $\beta<0$, $\gamma<0$, $\delta>0$. Otrzymamy jedną równowagę Nasha: $NE_5$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre15.png}

			\item $\alpha<0$, $\beta<0$, $\gamma<0$, $\delta<0$. Otrzymamy trzy równowagi Nasha: $NE_2$, $NE_4$ i $NE_5$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre13.png}

\end {enumerate}





###Przypadki zdegenerowane




Rozpoczynamy od znaleznienia zbiorów $W_1(q)$ w zależności od wartości parametrów $\alpha$ i $\beta$:

\begin {enumerate}

	\item $\alpha > 0$, $\beta = 0$. Mamy $q ( \alpha + \beta) \ge \beta \Leftrightarrow q \alpha \ge 0 \Leftrightarrow q\ge0$.
Więc 
\\${W_1(q)= \begin{cases}
1 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=0\\
\end{cases}
.}$


	\item $\alpha < 0$, $\beta = 0$. Mamy $q ( \alpha + \beta) \le \beta \Leftrightarrow q \alpha \le 0 \Leftrightarrow \ge0$.
Więc \\${W_1(q)= \begin{cases}
0 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=0\\
\end{cases}
.}$

	\item $\alpha = 0$, $\beta > 0$. Mamy $q ( \alpha + \beta) \le \beta \Leftrightarrow  \beta \le \beta \Leftrightarrow q\le1$.
Więc \\${W_1(q)= \begin{cases}
0 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=1\\
\end{cases}
.}$

	\item $\alpha = 0$, $\beta < 0$. Mamy $q ( \alpha + \beta) \ge \beta \Leftrightarrow q \beta \ge \beta \Leftrightarrow q\le1$.
Więc \\${W_1(q)= \begin{cases}
1 & \text{dla }  q \in [0,1]\\
[0,1] & \text{dla } q=1\\
\end{cases}
.}$


	\item $\alpha = 0$, $\beta = 0$, Wówczas $q(\alpha+\beta)=\beta$ dla dowolnego $q\in [0,1]$, więc 
\\${W_1(q)= [0,1]  \text{ dla } q\in [0,1].}$
Zauważamy, że $\alpha=0$ i $\beta=0$ oznacza, że $a_{11}=a_{21}$ oraz $a_{22}=a_{21}$, a więc bimacierz gry wyjściowej wygląda tak:
$$\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{22},b_{12})\\
(a_{11},b_{21})&(a_{22},b_{22})\\
\end{array}\right].$$
Widzimy więc, że Graczowi 1 jest obojętne, czy gra strategię czystą p=1, czy p=0, czy jakąkolwiek strategię mieszaną. Gdy $a_{11}\ne a_{22}$, jego wypłata zależy nie od niego, lecz od wyboru strategii przez Gracza 2.

\end {enumerate}


Następnie wyznaczamy zbiór $W_2(p)$ w zależności od parametrów $\gamma$ i $\delta$ dla przypadków zdegenerowanych:
\begin {enumerate}

	\item $\gamma > 0$, $\delta = 0$. Mamy $p ( \gamma +\delta) \ge \delta \Leftrightarrow p\gamma \ge 0 \Leftrightarrow p\ge 0$. Co daje \\${W_2(p)= \begin{cases}
1 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=0\\
\end{cases}
.}$

	\item $\gamma < 0$, $\delta = 0$. Mamy $p ( \gamma +\delta) \le \delta \Leftrightarrow \gamma p \le 0 \Leftrightarrow p \ge 0$. Więc \\${W_2(p)= \begin{cases}
0 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=0\\
\end{cases}
.}$

	\item $\gamma = 0$, $\delta > 0$. Mamy $p(\gamma+\delta)\le\delta \Leftrightarrow \delta p \le \delta \Leftrightarrow p \le 1$. Więc \\${W_2(p)= \begin{cases}
0 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=1\\
\end{cases}
.}$

	\item $\gamma = 0$, $\delta < 0$. Mamy $p(\gamma+\delta)  \ge \delta  \Leftrightarrow p \delta \ge \delta \Leftrightarrow p\le 1$. Co daje \\${W_2(p)= \begin{cases}
1 & \text{dla }  p \in [0,1]\\
[0,1] & \text{dla } p=1\\
\end{cases}
.}$

	\item $\gamma = 0$, $\delta = 0$. Mamy $p(\gamma+\delta)  \ge \delta $ dla dowolnego $p\in[0,1]$, co daje \\${W_2(p)=[0,1]  \text{ dla } p\in [0,1].}$
Znowu zauważamy, że w tym przypadku $b_{11}=b_{21}$ oraz $b_{22}=b_{21}$, a więc bimacierz gry wyjściowej wygląda tak:
$$\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{22},b_{12})\\
(a_{11},b_{21})&(a_{22},b_{22})\\
\end{array}\right].$$
Widzimy więc, że Graczowi 2 jest obojętne, czy gra strategię czystą q=1, czy q=0, czy jakąkolwiek strategię mieszaną. Gdy $b_{11}\ne b_{22}$, jego wypłata zależy nie od niego, lecz od wyboru strategii przez Gracza 1.
\end {enumerate}


Wcześniejsze obliczenia możemy przedstawić w tabeli:
\\
\begin{center}
\begin{tabular}{|c|c|c|c|}
\hline
$\alpha$ & $\beta$ & $W_1(q)$ & wykres\\
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
$\gamma$ & $\delta$ & $W_2(p)$ & wykres\\
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

Wykorzystując wcześniejsze obliczenia możemy narysować wykresy odwzorowań $W_1(q)$ i $W_2(p)$ w jednym układzie współrzędnych oraz zaznaczyć zbiór równowag Nasha określony jako $W_1(q) \cap W_2(p)$ w zależności od wartości parametrów: $\alpha$, $\beta$, $\gamma$, $\delta$:

\begin {enumerate}
\item $\alpha>0$, $\beta>0$, $\gamma>0$, $\delta=0$, $NE=NE_1 \cup \{ (0,q):0\le q\le \frac{\beta}{\alpha+\beta}\}$.
%wykres

![width=0.3\textwidth] (wykre21.png)


\item $\alpha>0$, $\beta>0$, $\gamma<0$, $\delta=0$, $NE=\{ (0,q):0\le q\le \frac{\beta}{\alpha+\beta}\}$.

\includegraphics [width=0.3\textwidth] {wykre22.png}

\item $\alpha>0$, $\beta>0$, $\gamma=0$, $\delta>0$, $NE=NE_3 \cup \{ (1,q):\frac{\beta}{\alpha+\beta} \le q\le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre32.png}

\item $\alpha>0$, $\beta>0$, $\gamma=0$, $\delta<0$, $NE=\{ (1,q):\frac{\beta}{\alpha+\beta} \le q\le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre33.png}

\item $\alpha>0$, $\beta>0$, $\gamma=0$, $\delta=0$, \\$NE=\{(0,q):0\le q \le \frac{\beta}{\alpha+\beta}\} \cup \{ (p,\frac{\beta}{\alpha+\beta}): 0 \le p \le 1\} \cup\{ (1,q):\frac{\beta}{\alpha+\beta} \le q\le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre34.png}

\item $\alpha>0$, $\beta<0$, $\gamma>0$, $\delta=0$. Otrzymamy jedną równowagę Nasha: $NE_1$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre29.png}

\item $\alpha>0$, $\beta<0$, $\gamma<0$, $\delta=0$. Otrzymamy jedną równowagę Nasha: $NE_5$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre30.png}

\item $\alpha>0$, $\beta<0$, $\gamma=0$, $\delta>0$, $NE=\{(1,q):0\le q \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre42.png}

\item $\alpha>0$, $\beta<0$, $\gamma=0$, $\delta<0$, $NE=\{(1,q):0\le q \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre43.png}


\item $\alpha>0$, $\beta<0$, $\gamma=0$, $\delta=0$, $NE=\{(1,q):0\le q \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre44.png}
	
\item $\alpha>0$, $\beta=0$, $\gamma>0$, $\delta>0$, $NE=NE_1 \cup\{(p,0):0 \le p \le \frac{\delta}{\gamma+\delta} \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre45.png}

\item $\alpha>0$, $\beta=0$, $\gamma>0$, $\delta<0$. Otrzymamy jedną równowagę Nasha: $NE_1$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre46.png}

\item $\alpha>0$, $\beta=0$, $\gamma>0$, $\delta=0$. Otrzymamy dwie równowagi Nasha: $NE_1$ i $NE_3$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre48.png}


\item $\alpha>0$, $\beta=0$, $\gamma<0$, $\delta>0$, $NE=\{(p,0): 0\le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre49.png}
		
\item $\alpha>0$, $\beta=0$, $\gamma<0$, $\delta<0$, $NE=\{(p,0): \frac{\delta}{\gamma+ \delta}\le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre47.png}

\item $\alpha>0$, $\beta=0$, $\gamma<0$, $\delta=0$, $NE=\{(p,0): 0\le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre50.png}


\item $\alpha>0$, $\beta=0$, $\gamma=0$, $\delta>0$, $NE=\{(p,0): 0\le p \le 1 \} \cup \{(1,q):0\le q \le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre51.png}

\item $\alpha>0$, $\beta=0$, $\gamma=0$, $\delta<0$, $NE=\{(1,q):0\le q \le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre52.png}

\item $\alpha>0$, $\beta=0$, $\gamma=0$, $\delta=0$, $NE=\{(p,0): 0\le p \le 1 \} \cup \{(1,q):0\le q \le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre53.png}

\item $\alpha<0$, $\beta>0$, $\gamma>0$, $\delta=0$, $NE=\{ (0,q):0\le q\le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre23.png}

\item $\alpha<0$, $\beta>0$, $\gamma<0$, $\delta=0$, $NE=\{ (0,q):0\le q\le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre25.png}

\item $\alpha<0$, $\beta>0$, $\gamma=0$, $\delta>0$. Otrzymamy jedną równowagę Nasha: $NE_3$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre36.png}

\item $\alpha<0$, $\beta>0$, $\gamma=0$, $\delta<0$. Otrzymamy jedną równowagę Nasha: $NE_4$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre37.png}

\item $\alpha<0$, $\beta>0$, $\gamma=0$, $\delta=0$, $NE=\{ (0,q):0 \le q\le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre38.png}

\item $\alpha<0$, $\beta<0$, $\gamma>0$, $\delta=0$, $NE=\{ (0,q):\frac{\beta}{\alpha+\beta} \le q\le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre27.png}

\item $\alpha<0$, $\beta<0$, $\gamma<0$, $\delta=0$, $NE=NE_5 \cup \{ (0,q):\frac{\beta}{\alpha+\beta} \le q\le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre28.png}

\item $\alpha<0$, $\beta<0$, $\gamma=0$, $\delta>0$, $NE=\{ (1,q): 0\le q\le \frac{\beta}{\alpha+\beta}\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre40.png}

\item $\alpha<0$, $\beta<0$, $\gamma=0$, $\delta<0$, $NE=NE_4 \cup\{ (1,q): 0\le q\le \frac{\beta}{\alpha+\beta}\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre41.png}

\item $\alpha<0$, $\beta<0$, $\gamma=0$, $\delta=0$, \\$NE=\{(0,q): \frac{\beta}{\alpha+\beta} \le q \le1\} \cup \{ (p,\frac{\beta}{\alpha+\beta}): 0 \le p \le 1\} \cup\{ (1,q):0 \le q\le \frac{\beta}{\alpha+\beta}\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre39.png}

\item $\alpha<0$, $\beta=0$, $\gamma>0$, $\delta>0$, $NE=\{(p,0): 0\le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre54.png}

\item $\alpha<0$, $\beta=0$, $\gamma>0$, $\delta<0$. Otrzymamy jedną równowagę Nasha: $NE_4$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre55.png}

\item $\alpha<0$, $\beta=0$, $\gamma>0$, $\delta=0$, $NE=NE_4 \cup\{(p,0): 0\le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre57.png}

\item $\alpha<0$, $\beta=0$, $\gamma<0$, $\delta>0$, $NE=\{(p,0):0\le p \le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre58.png}

\item $\alpha<0$, $\beta=0$, $\gamma<0$, $\delta<0$, $NE=NE_4 \cup\{(p,0): \frac{\delta}{\gamma+\delta}\le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre56.png}

\item $\alpha<0$, $\beta=0$, $\gamma<0$, $\delta=0$, $NE=\{(0,q):0\le q\le 1\} \cup \{(p,0): 0 \le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre59.png}

\item $\alpha<0$, $\beta=0$, $\gamma=0$, $\delta>0$, $NE=\{(p,0: 0 \le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre60.png}

\item $\alpha<0$, $\beta=0$, $\gamma=0$, $\delta<0$. Otrzymamy tu dwie równowagi: $NE_4$ i $NE_5$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre61.png}

\item $\alpha<0$, $\beta=0$, $\gamma=0$, $\delta=0$, $NE=\{(0,q):0\le q\le 1\} \cup \{(p,0): 0 \le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre62.png}

\item $\alpha=0$, $\beta>0$, $\gamma>0$, $\delta>0$, $NE=NE_3 \cup \{(p,1): \frac{\delta}{\gamma+\delta} \le p \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre63.png}

\item $\alpha=0$, $\beta>0$, $\gamma>0$, $\delta<0$, $NE=\{(p,1): 0\le p \le 1 \}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre64.png}
		
\item $\alpha=0$, $\beta>0$, $\gamma>0$, $\delta=0$, $NE=\{(0,q):0\le q \le 1\}\cup\{(p,1): 0\le p \le 1 \}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre88.png}

\item $\alpha=0$, $\beta>0$, $\gamma<0$, $\delta>0$, $NE=\{(0,q):0\le q \le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre67.png}
		
\item $\alpha=0$, $\beta>0$, $\gamma<0$, $\delta<0$, $NE=\{(p,1): 0 \le p \le \frac{\delta}{\gamma+\delta}\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre65.png}

\item $\alpha=0$, $\beta>0$, $\gamma<0$, $\delta=0$, $NE=\{(0,q): 0 \le q \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre66.png}

\item $\alpha=0$, $\beta>0$, $\gamma=0$, $\delta>0$. Otrzymamy tu dwie równowagi: $NE_1$ i $NE_3$.
%wykres
\includegraphics [width=0.3\textwidth] {wykre74.png}


\item $\alpha=0$, $\beta>0$, $\gamma=0$, $\delta<0$, $NE=\{(p,1):0\le p \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre75.png}

\item $\alpha=0$, $\beta>0$, $\gamma=0$, $\delta=0$, $NE=\{(0,q):0 \le q \le 1 \} \cup \{(p,1):0\le p \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre76.png}

\item $\alpha=0$, $\beta<0$, $\gamma>0$, $\delta>0$, $NE=\{(p,1): \frac{\delta}{\gamma+\delta} \le p \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre69.png}

\item $\alpha=0$, $\beta<0$, $\gamma>0$, $\delta<0$, $NE=\{(p,1): 0 \le p \le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre70.png}
		
\item $\alpha=0$, $\beta<0$, $\gamma>0$, $\delta=0$, $NE=\{(p,1): 0 \le p \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre72.png}

\item $\alpha=0$, $\beta<0$, $\gamma<0$, $\delta>0$. Otrzymamy jedną równowagę Nasha: $NE_5$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre71.png}

\item $\alpha=0$, $\beta<0$, $\gamma<0$, $\delta<0$, $NE=\{(p,1): 0 \le p \le \frac{\delta}{\gamma+\delta}\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre89.png}

\item $\alpha=0$, $\beta<0$, $\gamma<0$, $\delta=0$. Otrzymamy tu dwie równowagi: $ NE_4$ i $NE_5$.
%wykres
\includegraphics [width=0.3\textwidth] {wykre73.png}

\item $\alpha=0$, $\beta<0$, $\gamma=0$, $\delta>0$, $NE=\{(1,q):0 \le q \le 1 \}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre77.png}

\item $\alpha=0$, $\beta<0$, $\gamma=0$, $\delta<0$, $NE=\{(p,1):0\le p \le 1\}\cup \{(1,q):0 \le q \le 1 \}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre78.png}

\item $\alpha=0$, $\beta<0$, $\gamma=0$, $\delta=0$, $NE=\{(p,1):0\le p \le 1\}\cup \{(1,q):0 \le q \le 1 \}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre79.png}
\item $\alpha=0$, $\beta=0$, $\gamma>0$, $\delta>0$, \\$NE=\{(p,0):0\le p \le\frac{\delta}{\gamma+\delta}\}\cup \{(\frac{\delta}{\gamma+\delta},q):0 \le q \le 1 \} \cup \{(p,1): \frac{\delta}{\gamma+\delta}\le p \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre80.png}

\item $\alpha=0$, $\beta=0$, $\gamma>0$, $\delta<0$, $NE=\{(p,1):0\le p \le 1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre81.png}

\item $\alpha=0$, $\beta=0$, $\gamma>0$, $\delta=0$, $NE=\{(0,q):0\le q\le1\}\cup\{(p,1):0\le p\le1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre83.png}

\item $\alpha=0$, $\beta=0$, $\gamma<0$, $\delta>0$, $NE=\{(p,0):0\le p\le1\}$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre84.png}

\item $\alpha=0$, $\beta=0$, $\gamma<0$, $\delta<0$, \\$NE=\{(p,1):0\le p \le\frac{\delta}{\gamma+\delta}\}\cup \{(\frac{\delta}{\gamma+\delta},q):0 \le q \le 1 \} \cup \{(p,0): \frac{\delta}{\gamma+\delta}\le p \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre82.png}

\item $\alpha=0$, $\beta=0$, $\gamma<0$, $\delta=0$, $NE=\{(0,q):0\le q \le1\}\cup\{(p,0):0\le p \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre85.png}

\item $\alpha=0$, $\beta=0$, $\gamma=0$, $\delta>0$, $NE=\{(p,0):0\le p \le 1 \} \cup \{(1,q):0\le q \le 1 \}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre86.png}

\item $\alpha=0$, $\beta=0$, $\gamma=0$, $\delta<0$, $NE=\{(p,1):0\le p \le 1 \} \cup \{(1,q):0\le q \le 1 \}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre79.png}

\item $\alpha=0$, $\beta=0$, $\gamma=0$, $\delta=0$, $NE=\{(p,q):0\le p \le 1, 0\le q \le 1\}$.

%wykres
\includegraphics [width=0.3\textwidth] {wykre87.png}

Możemy zauważyć w tym przypadku, że jest to bardzo mocno zdegenerowany przypadek, gdyż bimacierz gry wyjściowej wygląda następująco:
$$(A,B)=\left[\begin{array}{cc}
(a_{11} ,b_{11} )&(a_{22},b_{11})\\
(a_{11},b_{22})&(a_{22},b_{22})\\
\end{array}\right].$$
Widzimy, że żaden z graczy nie ma wpływu na to, ile będzie wynosiła jego wygrana, natomiast każdy z graczy ma wpływ na to, ile będzie wynosić wygrana przeciwnika. Ponieważ w żadnej możliwej sytuacji żaden z graczy nie może podwyższyć swojej wygranej poprzez jednostronną zmianę strategii na jakąkolwiek inną, wszystkie możliwe pary strategii są równowagami Nasha tej gry.

\end {enumerate}




##Podział gier 2x2 ze względu na ilość równowag Nasha

Podsumowując wcześniejsze rozpatrywania poszczególnych przypadków zauważamy, iż gry 2x2 mają tylko i wyłącznie jedną, dwie, trzy lub nieskończenie wiele równowag Nasha.

Rozdział ten jest poświęcony na zebranie poszczególnych przypadków pod kątem ilości równowag Nasha i ich rozmieszczenia w kwadracie jednostkowym \\$\{(p,q): p,q\in[0,1]\}$.

###Jedna równowaga Nasha

Gier 2x2, które posiadają tylko jedną równowagę Nasha jest pięć rodzajów w zależności od jej umiejscowienia w macierzy gry.
Są cztery postacie gier, których rozwiązaniem są pary strategii czystych nazwanych w pracy: $NE_1$, $NE_3$, $NE_4$ i $NE_5$, oraz jedna do  której rozwiązania prowadzi para strategii mieszanych nazwana $NE_2$.

Poniżej wymieniamy poszczególne przypadki, jakie dają pierwszą rownowagę Nasha nazwaną 
$NE_1$. Odpowiada jej para strategii czystych obu graczy $(1,1)$:
\begin {enumerate}
\item $\alpha>0$, $\beta>0$, $\gamma>0$, $\delta<0$,
\item $\alpha>0$, $\beta<0$, $\gamma>0$, $\delta>0$,
\item $\alpha>0$, $\beta<0$, $\gamma>0$, $\delta<0$,
\item $\alpha>0$, $\beta>0$, $\gamma<0$, $\delta=0$,
\item $\alpha>0$, $\beta=0$, $\gamma>0$, $\delta<0$.
\end {enumerate}
 
\begin{ex}
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
$\alpha>0$, $\beta>0$, $\gamma>0$, $\delta<0$.
 Posiada więc ona jedną równowagę Nasha, która osiągana jest przy strategii graczy (1,1) i daje ona wygrane w wysokości $\overrightarrow{\pi}=(4,6)$.
\end{ex}


Nstępnym rozwiązaniem jest równowaga  $NE_2 $, prowadzi do niej para strategii $(\frac{\delta}{\gamma+\delta},\frac{\beta}{\alpha+\beta})$. Uzyskamy ją w dwóch przypadkach: $\alpha>0$, $\beta>0$, $\gamma<0$, $\delta<0$, lub $\alpha<0$, $\beta<0$, $\gamma>0$, $\delta>0$.

\begin{ex}
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
$\alpha<0$, $\beta<0$, $\gamma>0$, $\delta>0$.
Więc jego rozwiązaniem jest jedna równowaga Nasha. Prowadzi do niej para strategii $(\frac{1}{2},\frac{2}{3})$, a wypłata jaką osiągną gracze jest równa $\overrightarrow{\pi}=(\frac{-5}{6},0)$.
\end{ex}

Kolejną pojedyńczą równowagą Nasha jest $NE_3$, odpowiadająca jej para strategii to $(0,0)$. Jest ona wynikiem w przypadkach:
\begin {enumerate}
\item $\alpha>0$, $\beta>0$, $\gamma<0$, $\delta>0$,
\item $\alpha<0$, $\beta>0$, $\gamma>0$, $\delta>0$,
\item $\alpha<0$, $\beta>0$, $\gamma<0$, $\delta>0$,
\item $\alpha<0$, $\beta>0$, $\gamma=0$, $\delta>0$.
\end {enumerate}

\begin{ex}
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
$\alpha>0$, $\beta>0$, $\gamma<0$, $\delta>0$.
Posiada on jedną równowagę Nasha i prowadzi do niej para strategii (0,0). Daje ona wypłaty w wysokości $\overrightarrow{\pi}=(2,1)$.
\end{ex}

Przedostatnią pojedyńczą równowagą Nasha w grach 2x2 jest $NE_4$, która osiagana jest przy strategiach graczy $(0,1)$. Takie rozwiązanie gry otrzymujemy w przypadkach:
\begin {enumerate}
\item $\alpha<0$, $\beta>0$, $\gamma>0$, $\delta<0$,
\item $\alpha<0$, $\beta<0$, $\gamma>0$, $\delta<0$,
\item $\alpha<0$, $\beta>0$, $\gamma=0$, $\delta<0$, 
\item $\alpha<0$, $\beta=0$, $\gamma>0$, $\delta<0$.
\end {enumerate}

\begin{ex}
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
$\alpha>0$, $\beta<0$, $\gamma>0$, $\delta<0$.
Rozwiązaniem tej gry są wypłaty $\overrightarrow{\pi}=(2,0)$ osiągane przy parze strategii graczy (0,1).
\end{ex}

Ostanim rodzajem gier 2x2, których rozwiązaniem jest tylko jedna równowaga to gry, w których jedyną równowagą Nasha jest $NE_5$. Gracze kierują się wówczas strategiami $(1,0)$. Efekt ten jest osiągnięty w przypadkach:
\begin {enumerate}
\item $\alpha<0$, $\beta<0$, $\gamma<0$, $\delta>0$,
\item $\alpha>0$, $\beta<0$, $\gamma<0$, $\delta>0$,
\item $\alpha>0$, $\beta<0$, $\gamma<0$, $\delta=0$,
\item $\alpha=0$, $\beta<0$, $\gamma<0$, $\delta>0$,
\item $\alpha>0$, $\beta<0$, $\gamma<0$, $\delta<0$.
\end {enumerate}

\begin{ex}
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
$\alpha<0$, $\beta<0$, $\gamma<0$, $\delta>0$.
Rozwiązaniem tej gry jest wypłata $\overrightarrow{\pi}=(0,1)$ osiągana przy strategiach graczy (1,0).
\end{ex}


###Dwie równowagi Nasha



Gier 2x2, posiadających dwie równowagi Nasha są tylko dwa rodzaje.

Pierwszy rodzaj to gry, mające równowagi nazwane w pracy $NE_1$ i $NE_3$. Strategie graczy prowadzące do nich zostały już szczegółowo opisane wcześniej. Przypadkami gier, których rozwiązaniami opytymalnymi są konkretnie te dwie równowagi są gry, w których $\alpha>0$, $\beta=0$, $\gamma>0$, $\delta=0$, lub $\alpha=0$, $\beta>0$, $\gamma=0$, $\delta>0$.

\begin{ex}
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
$\alpha=0$, $\beta>0$, $\gamma=0$, $\delta>0$.
Są tutaj dwie równowagi Nasha. Pierwsza równowaga daje wypłatę $\overrightarrow{\pi}=(1,2)$ i otrzymamy ją przy strategiach (1,1), natomiast druga równowaga jest osiągana dzięki strategiom (0,0) i wygrana wynosi $\overrightarrow{\pi}=(2,3)$.
\end{ex}

Drugim rodzajem takich gier są gry, których rowiązanie znajduje się w punktach $NE_4$ i $NE_5$. Otrzymamy je w przypadku $\alpha<0$, $\beta=0$, $\gamma=0$, $\delta<0$, lub $\alpha=0$, $\beta<0$, $\gamma<0$, $\delta=0$.

\begin{ex}
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
$\alpha=0$, $\beta<0$, $\gamma<0$, $\delta=0$.
Są tutaj dwie równowagi Nasha. Pierwsza równowaga daje wypłaty $\overrightarrow{\pi}=(1,1)$ i otrzymamy ją przy parze  strategii (1,0), natomiast druga równowaga jest osiągana dzięki parze strategii (0,1) i wygrana wynosi $\overrightarrow{\pi}=(2,1)$.
\end{ex}


###Trzy równowagi Nasha

Gier 2x2, których rozwiązaniami są trzy równowagi Nasha, są dwa rodzaje.

Pierwszy rodzaj takich gier ma równowagi nazwane $NE_1$, $NE_2$ i $NE_3$. Są one wynikami gry, w której wartości wszystkich parametrów są dodatnie ($\alpha>0$, $\beta>0$, $\gamma>0$, $\delta>0$).

\begin{ex} Gra ,,Problem koordynacji''.
\\
Mamy grę w postaci macierzowej:
$$\left[\begin{array}{cc}
(2, 2 )&(0, 0)\\
(0,0)&(1,1)\\
\end{array}\right].$$
Nie trzeba jej przekształcać, gdyż jest ona od razu w postaci diagonalnej.
Zauważamy, iż jest to przypadek postaci:
$\alpha>0$, $\beta>0$, $\gamma>0$, $\delta>0$.
Więc rozwiązaniem są trzy równowagi Nasha:
\begin {enumerate}
\item $NE_1$: strategie graczy wyglądają następująco: $(1,1)$. Osiągają oni wypłaty \\$\overrightarrow{\pi}=(a_{11}, b_{11})=(2,2)$,
\item $NE_2$: strategie graczy wyglądają następująco: \\$(\frac{\delta}{\gamma+\delta},\frac{\beta}{\alpha+\beta})=(\frac{1}{2+1},\frac{1}{2+1})=(\frac{1}{3},\frac{1}{3})$. Osiągają oni wypłaty $\overrightarrow{\pi}=(\frac{2}{3},\frac{2}{3})$,
\item $NE_3$: strategie graczy wyglądają następująco: $(0,0)$. Osiągają oni wypłaty \\$\overrightarrow{\pi}=(a_{22}, b_{22})=(1,1)$.
\end{enumerate}
\end{ex}

Inny rodzaj takich gier to gry, które kończą się równowagami w punktach $NE_2$, $NE_4$ i $NE_5$. Prowadzi do takiego rozwiązania  przypadek $\alpha<0$, $\beta<0$, $\gamma<0$, $\delta<0$.

\begin{ex}Gra  ,,Jastrząb i gołąb".
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
$\alpha<0$, $\beta<0$, $\gamma<0$, $\delta<0$.
Więc jego rozwiązaniem są trzy równowagi Nasha:
\begin {enumerate}
\item $NE_4$: strategie graczy wyglądają następująco: $(0,1)$. Osiągają oni wypłaty \\$\overrightarrow{\pi}=(0, 4)$,
\item $NE_2$: strategie graczy wyglądają następująco: $(\frac{\delta}{\gamma+\delta},\frac{\beta}{\alpha+\beta})=(\frac{-2}{-2-1},\frac{-2}{-2-1})=(\frac{2}{3},\frac{2}{3})$. Osiągają oni wypłaty $\overrightarrow{\pi}=(\frac{2}{3}, \frac{2}{3})$,
\item $NE_5$:strategie graczy wyglądają następująco: $(1,0)$. Osiągają oni wypłaty \\$\overrightarrow{\pi}=(4,0)$.
\end {enumerate}
\end{ex}

Pojedyncze równowagi Nasha możemy przedstawić na jednym wykresie:
%wykres

\includegraphics [width=0.33\textwidth] {wykre200.png}



###Continuum równowag Nasha


Jeżeli gra 2x2 nie należy do którejś z wymienionych wcześniej klas, to ma nieskończenie wiele równowag Nasha. Gry takie możemy podzielić na kilka grup. Takie, w których równowagi Nasha tworzą odcinek i punkt, takie w których tworzą tylko odcinek, łamaną i w końcu cały kwadrat jednostkowy.

Pierwszą grupą będą gry, w których równowagi Nasha tworzą odcinek i punkt. Możemy wyniki wcześniejszych obliczeń podzielić ze względu na zbiory strategii.
W ten sposób otrzymamy pierwszy zbiór składający sie ze strategii: (1,1) i \\$(0,q): q\in [0,\frac{\beta}{\alpha+\beta}]$. Takie rozwiązanie otrzymamy w przypadku: $\alpha>0$, $\beta>0$, $\gamma>0$, $\delta=0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre201.png}

Następny zbiór równowag Nasha składa się ze strategii $(0,0)$ i \\$(p,1): p\in [\frac{\delta}{\gamma+\delta},1]$, otrzymamy go w przypadku: $\alpha=0$, $\beta>0$, $\gamma>0$, $\delta>0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre202.png}

Kolejnym przykładem zbioru równowag Nasha składającego się z odcinka i punktu jest zbiór strategii (0,1) i $(p,0): p\in [\frac{\delta}{\gamma+\delta},1]$, otrzymamy go w przypadku: $\alpha<0$, $\beta=0$, $\gamma<0$, $\delta<0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre203.png}

Innym przykładem analogicznego zbioru równowag Nasha są strategie (1,1) i $(p,0):p \in [0,\frac{\delta}{\gamma+\delta}]$. Osiągamy je w przypadku: $\alpha>0$, $\beta=0$, $\gamma>0$, $\delta>0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre204.png}

Jeszcze inny rodzaj zbioru równowag Nasha postaci odcinek i punkt dają strategie (0,1) i $(1,q): q\in [0,\frac{\beta}{\alpha+\beta}]$. Jest to efekt przypadku: $\alpha<0$, $\beta<0$, $\gamma=0$, $\delta<0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre205.png}

Przedostatnim zbiorem równowag Nasha postaci odcinek i punkt są strategie (0,0) i $(1,q): q\in [\frac{\beta}{\alpha+\beta},1]$. Powstaje on w przypadku: $\alpha>0$, $\beta>0$, $\gamma=0$, $\delta>0$,.
%wykres

\includegraphics [width=0.33\textwidth] {wykre206.png}

Ostatnim zbiorem równowag Nasha  jest zbiór strategii postaci \\(1,0) i $(0,q):q\in [\frac{\beta}{\alpha+\beta},1]$, jest tak w przypadku: $\alpha<0$, $\beta<0$, $\gamma<0$, $\delta=0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre207.png}

\begin{ex}
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
$\alpha<0$, $\beta=0$, $\gamma<0$, $\delta<0$.
Więc jego rozwiązaniem jest zbiór równowag Nasha postaci: 
strategie (0,1) i wypłaty \\$\overrightarrow{\pi}=(4,1)$ oraz kombinacja strategii $(p,0): p\in [\frac{1}{2},1]$ i daje ona wypłatę \\$\overrightarrow{\pi}=(4,p+1),p\in [\frac{1}{2},1]$.
\end{ex}

Drugą grupą gier są gry, w których równowagi Nasha tworzą odcinek. Otrzymamy kilka rodzajów odcinków. Pierwym rodzajem są odcinki postaci \\$(p,1):p\in [0,\frac{\delta}{\gamma+\delta}]$. Powstają one w dwóch przypadkach: $\alpha=0$, $\beta>0$, $\gamma<0$, $\delta<0$, lub $\alpha=0$, $\beta<0$, $\gamma<0$, $\delta<0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre208.png}

Następnym rodzajem są odcinki postaci $(1,q):q\in [0,\frac{\beta}{\alpha+\beta}]$ i jest tak w przypadku 
 $\alpha<0$, $\beta<0$, $\gamma=0$, $\delta>0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre209.png}

Kolejnym są odcinki postaci $(p,0):p\in [\frac{\delta}{\gamma+\delta},1]$ i osiągamy je w dwóch przypadkach:
 $\alpha<0$, $\beta>0$, $\gamma<0$, $\delta<0$, lub $\alpha>0$, $\beta=0$, $\gamma<0$, $\delta<0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre210.png}

Inne odcinki równowag Nasha uzyskamy ze strategii $(0,q): q\in [\frac{\beta}{\alpha+\beta},1]$. Dzieje się tak w przypadku: $\alpha<0$, $\beta<0$, $\gamma>0$, $\delta=0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre211.png}

Kolejne odcinki powstają ze strategii $(1,q):q\in [\frac{\beta}{\alpha+\beta},1]$ i osiągamy je w przypadku: 
$\alpha>0$, $\beta>0$, $\gamma=0$, $\delta<0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre212.png}

Następny rodzaj równowag Nasha powstaje ze strategii $(p,0):p\in [0,\frac{\delta}{\gamma+\delta}]$. Powstają one w przypadku: $\alpha<0$, $\beta=0$, $\gamma>0$, $\delta>0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre213.png}

Jeszcze inny rodzaj odcinków tworzą strategie $(p,1):p\in [\frac{\delta}{\gamma+\delta},1]$ i jest tak w przypadku:
 $\alpha=0$, $\beta<0$, $\gamma>0$, $\delta>0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre214.png}

Kolejne odcinki uzyskamy ze strategii $(0,q):q\in [0,\frac{\beta}{\alpha+\beta}]$. Zbiór tych strategii możemy otrzymać w przypadku:  $\alpha>0$, $\beta>0$, $\gamma<0$, $\delta=0$.
%wykres

\includegraphics [width=0.33\textwidth] {wykre215.png}

Następne odcinki powstają ze strategii $(p,0:p\in [0,1]$ i jest tak w przypadkach:
\begin {enumerate}
\item $\alpha>0$, $\beta=0$, $\gamma<0$, $\delta>0$,
\item $\alpha>0$, $\beta=0$, $\gamma<0$, $\delta=0$,
\item $\alpha<0$, $\beta=0$, $\gamma<0$, $\delta>0$,
\item $\alpha<0$, $\beta=0$, $\gamma=0$, $\delta>0$,
\item $\alpha=0$, $\beta=0$, $\gamma<0$, $\delta>0$.
\end {enumerate}
%wykres

\includegraphics [width=0.33\textwidth] {wykre216.png}

Inny rodzaj odcinków jest efektem zagrania strategii postaci: $(0,q):q\in [0,1]$ i uzyskamy je w poniższych przypadkach:
\begin {enumerate}
\item $\alpha<0$, $\beta>0$, $\gamma>0$, $\delta=0$,
\item $\alpha<0$, $\beta>0$, $\gamma<0$, $\delta=0$,
\item $\alpha<0$, $\beta>0$, $\gamma=0$, $\delta=0$,
\item $\alpha<0$, $\beta=0$, $\gamma>0$, $\delta=0$,
\item $\alpha=0$, $\beta>0$, $\gamma<0$, $\delta>0$,
\item $\alpha=0$, $\beta>0$, $\gamma<0$, $\delta=0$.
\end {enumerate}
%wykres

\includegraphics [width=0.33\textwidth] {wykre217.png}

Przedostatni rodzaj odcinków tworzą strategie $(1,q)):q\in [0,1]$ i uzyskamy je w przypadkach:
\begin {enumerate}
\item $\alpha>0$, $\beta<0$, $\gamma=0$, $\delta>0$,
\item $\alpha>0$, $\beta<0$, $\gamma=0$, $\delta<0$,
\item $\alpha>0$, $\beta<0$, $\gamma=0$, $\delta=0$,
\item $\alpha>0$, $\beta=0$, $\gamma=0$, $\delta<0$,
\item $\alpha=0$, $\beta<0$, $\gamma=0$, $\delta>0$.
\end {enumerate}
%wykres

\includegraphics [width=0.33\textwidth] {wykre218.png}

Ostatni zbiór równowag Nasha uzyskamy jako zbiór strategii $(p,1):p\in[0,1]$. Jest to efekt rozwiązania przypadków postaci: 
\begin {enumerate}
\item $\alpha=0$, $\beta>0$, $\gamma>0$, $\delta<0$,
\item $\alpha=0$, $\beta<0$, $\gamma>0$, $\delta<0$,
\item $\alpha=0$, $\beta<0$, $\gamma>0$, $\delta=0$,
\item $\alpha=0$, $\beta>0$, $\gamma=0$, $\delta<0$,
\item $\alpha=0$, $\beta=0$, $\gamma>0$, $\delta<0$.
\end {enumerate}
%wykres

\includegraphics [width=0.33\textwidth] {wykre219.png}
\begin{ex}
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
$\alpha<0$, $\beta=0$, $\gamma=0$, $\delta>0$.
Więc jego rozwiązaniem jest zbiór równowag Nasha postaci: 
strategie $(p,0):p\in [0,1]$ i wypłaty $\overrightarrow{\pi}=(1,p+2), p\in [0,1]$.
\end{ex}

Zbiory rozwiązań w postaci łamanej możemy podzielić na osiem rodzajów. Pierwszy zbiór składa się ze strategii $(p,1):p\in [0,1]$ i $(1,q)):q\in [0,1]$ i jest to wynik rozwiązania przypadków:
\begin {enumerate}
\item $\alpha=0$, $\beta<0$, $\gamma=0$, $\delta<0$,
\item $\alpha=0$, $\beta<0$, $\gamma=0$, $\delta=0$,
\item $\alpha=0$, $\beta=0$, $\gamma=0$, $\delta<0$.
\end {enumerate}
%wykres

\includegraphics [width=0.3\textwidth] {wykre220.png}

Drugim zbiorem postaci łamanej jest zbiór strategii $(p,0):p\in [0,1]$ i \\$(1,q):q\in[0,1]$. Jest to wynik przypadków:
\begin {enumerate}
\item $\alpha>0$, $\beta=0$, $\gamma=0$, $\delta>0$,
\item $\alpha>0$, $\beta=0$, $\gamma=0$, $\delta=0$,
\item $\alpha=0$, $\beta=0$, $\gamma=0$, $\delta>0$.
\end {enumerate}
%wykres

\includegraphics [width=0.3\textwidth] {wykre221.png}

Trzecim zbiorem równowag Nasha jest zbiór strategii postaci $(0,q):q\in[0,1]$ i \\$(p,0):p\in[0,1]$, który powstaje w rezultacie przypadków:
\begin {enumerate}
\item $\alpha<0$, $\beta=0$, $\gamma=0$, $\delta=0$,
\item $\alpha<0$, $\beta=0$, $\gamma<0$, $\delta=0$,
\item $\alpha=0$, $\beta=0$, $\gamma<0$, $\delta=0$.
\end {enumerate}
%wykres

\includegraphics [width=0.3\textwidth] {wykre222.png}

Czwartym rodzajem łamamnej są zbiory strategii $(p,1)):p\in[0,1]$ i \\$(0,q):q\in[0,1]$, które są rezultatem przypadków:
\begin {enumerate}
\item $\alpha=0$, $\beta>0$, $\gamma>0$, $\delta=0$,
\item $\alpha=0$, $\beta>0$, $\gamma=0$, $\delta=0$,
\item $\alpha=0$, $\beta=0$, $\gamma>0$, $\delta=0$.
\end {enumerate}
%wykres

\includegraphics [width=0.3\textwidth] {wykre223.png}

Kolejnym zbiorem rozwiązań opisanym łamaną tworzą strategie postaci \\$(0,q):q\in[\frac{\beta}{\alpha+\beta},1]$, $(p,\frac{\beta}{\alpha+\beta}):p\in[0,1]$ i $(1,q):q\in[0,\frac{\beta}{\alpha+\beta}]$. Dzieje się tak w dwóch przypadkach: $\alpha<0$, $\beta<0$, $\gamma=0$, $\delta=0$, lub $\alpha>0$, $\beta<0$, $\gamma=0$, $\delta=0$ i $|\alpha|<|\beta|$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre224.png}

Następnym zbiorem rozwiązań tworzących łamaną tworzą strategie postaci \\$(0,q):q\in[0,\frac{\beta}{\alpha+\beta}]$, $(p,\frac{\beta}{\alpha+\beta}):p\in[0,1]$ i $(1,q):q\in[\frac{\beta}{\alpha+\beta},1]$. Jest to efekt przypadku: $\alpha>0$, $\beta>0$, $\gamma=0$, $\delta=0$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre225.png}

Innym zbiorem rozwiązań opisanym łamaną tworzą strategie postaci \\$(p,0):p\in[0,\frac{\delta}{\gamma+\delta}]$, $(\frac{\delta}{\gamma+\delta},q):q\in[0,1]$ i $(p,1):p\in[\frac{\delta}{\gamma+\delta},1]$. Dzieje się tak w przypadku: $\alpha=0$, $\beta=0$, $\gamma>0$, $\delta>0$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre226.png}

Ostatnim zbiorem rozwiązań opisanym łamaną tworzą strategie postaci \\$(p,1):p\in[0,\frac{\delta}{\gamma+\delta}]$, $(\frac{\delta}{\gamma+\delta},q):q\in[0,1]$ i $(p,0):p\in[\frac{\delta}{\gamma+\delta},1]$. Jest ona uzyskiwana w przypadku:
 $\alpha=0$, $\beta=0$, $\gamma<0$, $\delta<0$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre227.png}
\begin{ex}
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
$\alpha=0$, $\beta<0$, $\gamma=0$, $\delta=0$.
Więc jego rozwiązaniem jest zbiór równowag Nasha postaci: strategie $(p,0):p\in [0,1]$ i wypłaty $\overrightarrow{\pi}=(1,1+p), p\in[0,1]$ oraz kombinacja strategii $(1,q):q\in [0,1]$ i daje ona wypłatę $\overrightarrow{\pi}=(q,2),q\in [0,1]$.
\end{ex}

Ostatnia grupa rozwiązań to wszystkie możliwe strategie mieszane i czyste jakie mogą zastosować gracze w grze. Ogólnie możemy je zapisać jako \\$(p,q):p\in [0,1], q\in[0,1]$ i są one rezultatem przypadku: $\alpha=0$, $\beta=0$, $\gamma=0$, $\delta=0$.
%wykres

\includegraphics [width=0.3\textwidth] {wykre228.png}
\begin{ex}
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
$\alpha=0$, $\beta=0$, $\gamma=0$, $\delta=0$.
Więc każda możliwa para strategii graczy $(p,q)$, $p,q \in [0,1]$ jest równowagą Nasha tej gry i daje ona wypłaty wysokości $\overrightarrow{\pi}=(8-q,-3+4p):p\in[0,1],q\in[0,1]$.
\end{ex}

Uzyskane wyniki przedstawiamy zbiorczo w tabeli pokazującej zaleźność ilości rownówag Nasha gry 2x2 od wartości parametrów charakteryzujacych daną grę. W tabeli został zastosowany symbol $|NE|$ oznaczający ilość równowag Nasha. Symbol ,,+"~oznacza, iż parametr jest większy od 0, ,,-", że mniejszy od 0, a ,,0'' oznacza, iż wartość parametru jest równa 0. Ostatnia kolumna w tabeli podaje, jaki to przypadek z rodziału drugiego pracy. ,,N'' oznacza przypadek niezdegenerowany, a ,,Z'' oznacza zdegenerowany.
\\
\\
\begin{tabular}{cc}
\begin{tabular}{|c|c|c|c|c|c|}
\hline
$\alpha$ & $\beta$ & $\gamma$ & $\delta$ & $|NE|$ & Lp.\\
\hline
\hline
+&+&+&+&3 & N1\\
\hline
+&+&+&-&1 & N2\\
\hline
+&+&-&+&1 & N3\\
\hline
+&+&-&-&1 & N4\\
\hline
+&-&+&+&1 & N5\\
\hline
+&-&+&-&1 & N6\\
\hline
+&-&-&+&1 & N7\\
\hline
+&-&-&-&1 & N8\\
\hline
-&+&+&+&1 & N9\\
\hline
-&+&+&-&1 & N10\\
\hline
-&+&-&+&1 & N11\\
\hline
-&+&-&-&$\infty$ & N12\\
\hline
-&-&+&+&1 & N13\\
\hline
-&-&+&-&1 & N14\\
\hline
-&-&-&+&1 & N15\\
\hline
-&-&-&-&3 & N16\\
\hline
%-----
\end{tabular}

&

\begin{tabular}{|c|c|c|c|c|c|}
\hline
$\alpha$ & $\beta$ & $\gamma$ & $\delta$ & $|NE|$ & Lp.\\
\hline
\hline
+&+&+&0&$\infty$ & Z1\\
\hline
+&+&-&0&$\infty$ & Z2\\
\hline
+&+&0&+&$\infty$ & Z3\\
\hline
+&+&0&-&$\infty$ & Z4\\
\hline
+&+&0&0&$\infty$ & Z5\\
\hline
+&-&+&0&1 & Z6\\
\hline
+&-&-&0&1 & Z7\\
\hline
+&-&0&+&$\infty$ & Z8\\
\hline
+&-&0&-&$\infty$ & Z9\\
\hline
+&-&0&0&$\infty$ & Z10\\
\hline
+&0&+&+&$\infty$ & Z11\\
\hline
+&0&+&-&$\infty$ & Z12\\
\hline
+&0&+&0&2 & Z13\\
\hline
+&0&-&+&$\infty$ & Z14\\
\hline
+&0&-&-&$\infty$ & Z15\\
\hline
+&0&-&0&$\infty$ & Z16\\
\hline
\end{tabular}
\\
\end{tabular}
%----

\begin{tabular}{cc}
\begin{tabular}{|c|c|c|c|c|c|}
\hline
$\alpha$ & $\beta$ & $\gamma$ & $\delta$ & $|NE|$ & Lp.\\
\hline
\hline
+&0&0&+&$\infty$ & Z17\\
\hline
+&0&0&-&$\infty$ & Z18\\
\hline
+&0&0&0&$\infty$ & Z19\\
\hline
-&+&+&0&$\infty$ & Z20\\
\hline
-&+&-&0&$\infty$ & Z21\\
\hline
-&+&0&+&1 & Z22\\
\hline
-&+&0&-&1 & Z23\\
\hline
-&+&0&0&$\infty$ & Z24\\
\hline
-&-&+&0&$\infty$ & Z25\\
\hline
-&-&-&0&$\infty$ & Z26\\
\hline
-&-&0&+&$\infty$ & Z27\\
\hline
-&-&0&-&$\infty$ & Z28\\
\hline
-&-&0&0&$\infty$ & Z29\\
\hline
-&0&+&+&$\infty$ & Z30\\
\hline
-&0&+&-&1 & Z31\\
\hline
-&0&+&0&$\infty$ & Z32\\
\hline
-&0&-&+&$\infty$ & Z33\\
\hline
-&0&-&-&$\infty$ & Z34\\
\hline
-&0&-&0&$\infty$ & Z35\\
\hline
-&0&0&+&$\infty$ & Z36\\
\hline
-&0&0&-&2 & Z37\\
\hline
-&0&0&0&$\infty$ & Z38\\
\hline
0&+&+&+&$\infty$ & Z39\\
\hline
0&+&+&-&$\infty$ & Z40\\
\hline
0&+&+&0&$\infty$ & Z41\\
\hline





\end{tabular}
%-----
&
%----
\begin{tabular}{|c|c|c|c|c|c|}
\hline
$\alpha$ & $\beta$ & $\gamma$ & $\delta$ & $|NE|$ & Lp.\\
\hline
\hline
0&+&-&+&$\infty$ & Z42\\
\hline
0&+&-&-&$\infty$ & Z43\\
\hline
0&+&-&0&$\infty$ & Z44\\
\hline
0&+&0&+&2 & Z45\\
\hline
0&+&+&0&$\infty$ & Z46\\
\hline
0&+&0&0&$\infty$ & Z47\\
\hline
0&-&+&+&$\infty$ & Z48\\
\hline
0&-&+&-&$\infty$ & Z49\\
\hline
0&-&+&0&$\infty$ & Z50\\
\hline
0&-&-&+&1 & Z51\\
\hline
0&-&-&-&$\infty$ & Z52\\
\hline
0&-&-&0&2 & Z53\\
\hline
0&-&0&+&$\infty$ & Z54\\
\hline
0&-&0&-&$\infty$ & Z55\\
\hline
0&-&0&0&$\infty$ & Z56\\
\hline
0&0&+&+&$\infty$ & Z57\\
\hline
0&0&+&-&$\infty$ & Z58\\
\hline
0&0&+&0&$\infty$ & Z59\\
\hline
0&0&-&+&$\infty$ & Z60\\
\hline
0&0&-&-&$\infty$ & Z61\\
\hline
0&0&-&0&$\infty$ & Z62\\
\hline
0&0&0&+&$\infty$ & Z63\\
\hline
0&0&0&-&$\infty$ & Z64\\
\hline
0&0&0&0&$\infty$ & Z65\\
\hline
\end{tabular}
\\
\end{tabular}
		



##Zakończenie



Celem niniejszej pracy było systematyczne przebadanie wszystkich możliwych typów gier 2x2 pod kątem ilości i rozmieszczenia równowag Nasha. Problem ten nie był dotychczas poruszany w literaturze.

W pierwszym rozdziale przybliżona została historia teorii gier oraz życiorys Johna Nasha. Pokazano także definicję gry i pojęć z nią powiązanych. Zostały w nim zdefiniowane równowagi Nasha i pokazano sposób ich poszukiwania metodą graficzną. Zostały wprowadzone definicje i twierdzenia związane z innwariantnością równowag Nasha względem loklnych przesunięć.

W drugim rozdziale pokazano jak sprowadzić dowolną grę 2x2 do postaci bimacierzy diagonalnej. Otrzymane gry podzielono ze względu na wartości parametrów na przypadki zdegenerowane i niezdegenerowane oraz zbadano ile równowag posiadają gry tworzące poszczególne przypadki. 

Na podstawie wcześniejszego rozdziału w trzecim rozdziale pogrupowano wcześniesze przypadki ze względu na ilość równowag Nasha w bimacierzy wypłat.

Na końcu zaprezentowano tabelę przedstawiającą zależność ilość równowag Nasha gry 2x2 od wartości parametrów charakteryzujących daną grę.



##thebibliography

\bibitem{Kaluski} 
Kałuski J., \textit{Teoria gier}, Wydawnictwo Politechniki Śląskiej, Gliwice 2002. 
\bibitem{Peters}
Peters H., \textit{Game Theory. A Multi-Leveled Approach}, Springer-Verlag, Berlin 2008. 
\bibitem{Plonka} 
Płonka E., \textit{Wykłady z teorii gier}, Wydawnictwo Politechniki Śląskiej, Gliwice 2001.
\bibitem{Watson} 
Watson J., \textit{Strategia. Wprowadzenie do teorii gier}, Wydwnictwo Naukowo-Techniczne, Warszawa 2002.


 
\end{document} 
