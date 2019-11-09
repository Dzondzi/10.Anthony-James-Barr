# 10_Anthony_James_Barr
TNP
% !TEX encoding = UTF-8 Unicode

\documentclass[a4paper]{article}

\usepackage{color}
\usepackage{url}
\usepackage[T2A]{fontenc} % enable Cyrillic fonts
\usepackage[utf8]{inputenc} % make weird characters work
\usepackage{graphicx}

\usepackage[english,serbian]{babel}
%\usepackage[english,serbianc]{babel} %ukljuciti babel sa ovim opcijama, umesto gornjim, ukoliko se koristi cirilica

\usepackage[unicode]{hyperref}
\hypersetup{colorlinks,citecolor=green,filecolor=green,linkcolor=blue,urlcolor=blue}

%\newtheorem{primer}{Пример}[section] %ćirilični primer
\newtheorem{primer}{Primer}[section]

\begin{document}

\title{Entoni Dzejms Bar\\ \small{Seminarski rad u okviru kursa\\Tehničko i naučno pisanje\\ Matematički fakultet}}

\author{Nikola Borjan, Lucija Kecic, Divna Micic, Milica Golubovic\\ kontakt email prvog, drugog (...) autora}
\date{1. novembar 2019.}
\maketitle

\abstract{
U ovom tekstu je ukratko prikazana osnovna forma seminarskog rada. Obratite pažnju da je pored ove .pdf datoteke, u prilogu i odgovarajuća .tex datoteka, kao i .bib datoteka korišćena za generisanje literature. Na prvoj strani seminarskog rada su naslov, apstrakt i sadržaj, i to sve mora da stane na prvu stranu! Kako bi Vaš seminarski zadovoljio standarde i očekivanja, koristite uputstva i materijale sa predavanja na temu pisanja seminarskih radova. Ovo je samo šablon koji se odnosi na fizički izgled seminarskog rada (šablon koji \emph{morate} da ispoštujete!) kao i par tehničkih pomoćnih uputstava. 

\tableofcontents

\newpage

\section{Entoni Dzejms Bar}
\label{sec:uvod}

Entoni Dzejms Bar, poznatiji kao Toni Bar ili Dzim Bar, rodjend je 24. septembra 1940. godine. Americki je dizajner programskih jezika, inzenjer softvera i izumitelj. Znacajno je doprineo Sistemom statisticke analize (SAS) (eng. Statistical Analysis System), automatizovao je optimizovanu potrosnju resursa drveta, kao i klasifikaociju medicinskih subjekata.

%Kada budete predavali seminarski rad, imenujete datoteke tako da sadrže temu seminarskog rada, kao i prezimena članova grupe. Predaja seminarskih radova biće isključivo preko veb forme, a NE slanjem mejla. Link na formu će biti dat u okviru obaveštenja na strani kursa. Vodite računa da prilikom predavanja seminarskog rada predate samo one fajlove koji su neophodni za ponovno generisanje pdf datoteke. To znači da pomoćne fajlove, kao što su .log, .out, .blg, .toc, .aux i slično, \textbf{ne treba predavati}.

%\section{Osnovna uputstva}
%Vaš seminarski rad mora da sadrži najmanje jednu sliku, najmanje jednu tabelu i najmanje tri reference u spisku literature. \textbf{Dužina seminarskog rada treba da bude:}
%\begin{itemize}
%\item Ukoliko tim ima tri člana, tada od 4 do 6 strana
%\end{itemize} 

%Ко жели, може да пише рад ћирилицом. У том случају, неопходно је да су инсталирани одговарајући пакети: texlive-fonts-extra, texlive-latex-extra, texlive-lang-cyrillic, texlive-lang-other. 

%Nemojte koristiti stari način pisanja slova, tj ovo:
%\begin{verbatim}
%\v{s} i \v{c} i \'c ...
%\end{verbatim}
%Koristite direknto naša slova:	
%\begin{verbatim}
%š i č i ć ... 
%\end{verbatim}


%\section{Engleski termini i citiranje}	
%\label{sec:termini_i_citiranje}

%Na svakom mestu u tekstu naglasiti odakle tačno potiču informacije. Uz sve novouvedene termine u zagradi naglasiti od koje engleske reči termin potiče. 

%Naredni primeri ilustruju način uvođenja enlegskih termina kao i citiranje.

%\begin{primer}
%Problem zaustavljanja (eng.~{\em halting problem}) je neodlučiv \cite{haltingproblem}.
%\end{primer}

%\begin{primer}
%Za prevođenje programa napisanih u programskom jeziku C može se koristiti GCC kompajler \cite{gcc}.
%\end{primer}

%\begin{primer}
 %Da bi se ispitivala ispravost softvera, najpre je potrebno precizno definisati njegovo ponašanje \cite{laski2009software}. 
%\end{primer}

%Reference koje se koriste u ovom tekstu zadate su u datoteci {\em seminarski.bib}. Prevođenje u pdf format u Linux okruženju može se uraditi na sledeći način:
%\begin{verbatim}
%pdflatex TemaImePrezime.tex 
%bibtex TemaImePrezime.aux 
%pdflatex TemaImePrezime.tex 
%pdflatex TemaImePrezime.tex 
%\end{verbatim}
%Prvo latexovanje je neophodno da bi se generisao {\em .aux} fajl. {\em bibtex} proizvodi odgovarajući {\em .bbl} fajl koji se koristi za generisanje literature. 
%Potrebna su dva prolaza (dva puta pdflatex) da bi se reference ubacile u tekst (tj da ne bi ostali znakovi pitanja umesto referenci). Dodavanjem novih referenci potrebno je ponoviti ceo postupak.  


%Broj naslova i podnaslova je proizvoljan. Neophodni su samo Uvod i Zaključak. Na poglavlja unutar teksta referisati se po potrebi. 
%\begin{primer}
%U odeljku \ref{sec:naslov1} precizirani su osnovni pojmovi, dok su zaključci dati u odeljku \ref{sec:zakljucak}.
%\end{primer}




%\section{Slike i tabele}
%\label{slike_i_tabele}

%Slike i tabele treba da budu u svom okruženju, sa odgovarajućim naslovima, obeležene labelom da koje omogućava referenciranje. 

%\begin{primer} Ovako se ubacuje slika. Obratiti pažnju da je dodato i 
%\begin{verbatim}
%\usepackage{graphicx}
%\end{verbatim}

%\begin{figure}[h!]
%\begin{center}
%\includegraphics[scale=0.75]{pande.jpg}
%\end{center}
%\caption{Pande}
%\label{fig:pande}
%\end{figure}

%Na svaku sliku neophodno je referisati se negde u tekstu. Na primer, na slici \ref{fig:pande} prikazane su pande. 
%\end{primer}

%\begin{primer} I tabele treba da budu u svom okruženju, i na njih je neophodno referisati se u tekstu. Na primer, u tabeli \ref{tab:tabela1} su prikazana različita poravnanja u tabelama.

%\begin{table}[h!]
%\begin{center}
%\caption{Razlčita poravnanja u okviru iste tabele ne treba koristiti jer su nepregledna.}
%\begin{tabular}{|c|l|r|} \hline
%centralno poravnanje& levo poravnanje& desno poravnanje\\ \hline
%a &b&c\\ \hline
%d &e&f\\ \hline
%\end{tabular}
%\label{tab:tabela1}
%\end{center}
%\end{table}

%\end{primer}







\section{Doprinos}
\label{sec:naslov1}

\subsection{Sistem statisticke analize}
\label{subsec:podnaslov1}

Sistem statisticke analize (SAS), osmisljen od strane Bara 1966. godine, naisao je na siroku primenu u nauci, upravi, industriji i akademskom razvitku. Septembra 1966. u gradu Atensu u Dzorziji, prezentovao je koncept njegove ideje clanovima Odbora za Statisticki Softver Univerzitetskih Statisticara Juznih Eksperimentalnih Stanica (USJES).\break

Bar je prethodno kreirao jezik za modelovanje analize slucaja, inspirisan notacijom statisticara Morisa Kendala (eng. Maurice Kendall). Razvijao ga je u asemblerskom jeziku, na racunaru IBM 1410, kao apsolvent drzavnog fakulteta Severne Karoline od 1962. do 1963. godine. Dr A. Grandedz, autor programa za analizu slucaja IBM 650, davao mu je savete o statistickim proracunima. Nakon toga je usledio visesruki regresijski program sa fleksibilnim ulaznim formatom i algebarskom transformacijom promenljivih, od 1963. do 1964. godine. Na osnovu tih programa, zajedno sa svojim iskustvom sa struktuiranim datotekama podataka, kreirao je SAS, ostavljajuci statisticke procedure u formatirani okvir datoteka.\break

Bar je stekao iskustvo sa struktuiranim datotekama podataka dok je radio na formatiranom sistemu datoteka. Od 1966. do 1968., Bar je razvio osnovnu strukturu i jezik SAS-a.\break

Bar je zapoceo saradnju sa drugima 1968. godine. Dizajnirao je i implementirao programski jezik, upravljanje podacima, pisanje izvestaja, i sistemska podrucja sistema koji se razvija. Entoni Dz. Bar, Dzejms H. Gudnajt, Dzon P. Sal i Dzejn T. Helvig su 1976. godine osnovali Institut SAS, a Bar je imao najveci udeo (40\%). Svoje akcije je prodao 1979.




\subsection{Drugi podnaslov}
\label{subsec:podnaslov2}

Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 

\section{Drugi naslov}
\label{sec:naslov2}

Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 

\subsection{... podnaslov}
\label{subsec:podnaslovN}

Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 

\section{n-ti naslov}
\label{sec:naslovN}

Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 

\subsection{... podnaslov}
\label{subsec:podnaslovK}

Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 

\subsection{... podnaslov}
\label{subsec:podnaslovM}

Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 

\section{Poslednji naslov}
\label{sec:naslovM}

Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 
Ovde pišem tekst. 

\section{Zaključak}
\label{sec:zakljucak}

Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 
Ovde pišem zaključak. 


\addcontentsline{toc}{section}{Literatura}
\appendix
\bibliography{seminarski} 
\bibliographystyle{plain}

\appendix
\section{Dodatak}
Ovde pišem dodatne stvari, ukoliko za time ima potrebe.
Ovde pišem dodatne stvari, ukoliko za time ima potrebe.
Ovde pišem dodatne stvari, ukoliko za time ima potrebe.
Ovde pišem dodatne stvari, ukoliko za time ima potrebe.
Ovde pišem dodatne stvari, ukoliko za time ima potrebe.


\end{document}
