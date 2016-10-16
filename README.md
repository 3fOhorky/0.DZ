# JMBAG
{}

#Pitanje {1}:
{Nakon builda, u Bin/debug folder konzolne aplikacije je dodan ClassLibrary1.dll. Ako maknemo dotični .dll i 
 pokrenemo .exe, aplikacija se sruši (baca unhandled exception) pošto smo time maknuli library koji koristimo 
 u aplikaciji - njegovu MyConsole klasu i pripadnu PrintHelloWorld metodu. Za upotrebljivu aplikaciju su 
 potrebne datoteke KonzolnaAplikacija.exe i ClassLibrary1.dll}
 
#Pitanje {2}:
{Pokretanjem aplikacije bez prethodnog build-a, koristi se stara verzija class library asemblija, pošto nije
 izvršeno povezivanje tj. prevođenje novog asemblija.}

#Pitanje {3}:
{Pero: Hello World}

#Pitanje {4}:
{Bin/debug folder sadrži PeroClassLibrary.dll}

#Pitanje {5}:
{Aplikacija i build projekta rade pošto bin/debug folder sadrži PeroClassLibrary.dll - program se referencira
 na tu kopiju originalne datoteke asemblija, dok build solutiona ne radi.}

#Pitanje {6}:
{Build proces je uspješno prošao, automatski je generiran novi NodaTime direktorij unutar packages direktorija
 s pripadnim .dll asemblijem}