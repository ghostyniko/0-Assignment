# JMBAG
{0036491398}

# Pitanje {1.}
{Nakon što se doda referenca, pojavi se datoteka "ClassLibrary1.dll". Kada se makne ta datoteka i pokrene .exe
datoteka, pojavi se poruka da se ne može učitati "ClassLibrary1.dll" i program se sruši. To se dogodi jer postoji
ovisnost pokrenutog asemblija (.exe) o asembliju (.dll) jer smo koristili klasu koja je
definirana u drugom projektu. Datoteke koje treba imati da bi se uporabljiva 
aplikacija pokrenula su .exe datoteka i.dll datoteke.}

# Pitanje {2.}

{Nakon promjene stringa u metodi MyConsole.PrintHelloWorld(), konzolna aplikacija koristi novi string jer CLR prepoznaje 
zahvaljujući metapodacima da je došlo do promjene u kodu.}

# Pitanje {3.}
{Ispisalo se "Pero: Hello World"}

# Pitanje {4.}
{ Nakon dodavanja nove biblioteke i pokretanja aplikacije, stvoren je asemblij "PeroClassLibrary.dll"}

# Pitanje {5.}
{Nakon brisanja originalnog .dll asemblija, program i dalje radi jer postoji kopija asemblija u direktoriju bin/debug. Sada se 
PeroClassLibrary traži u tom direktoriju.}

# Pitanje {6.}
{Nakon brisanja NodaTime direktorija, aplikacija se uspješno builda jer se direktorij koji smo pobrisali automatski
natrag instalira.}
