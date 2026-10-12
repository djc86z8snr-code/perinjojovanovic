Git uputstvo za početnike
1. Svrha projekta

Ovaj repozitorijum služi za zajednički rad svih 8 članova tima. Svaki član radi na svom delu projekta i redovno šalje izmene na GitHub.

2. Struktura projekta

Projekat je organizovan u sledeće foldere:

app/ – korisnički interfejs aplikacije
backend/ – serverska logika aplikacije
database/ – fajlovi i skripte vezane za bazu podataka
design/ – dizajn, skice i prototipi
docs/ – dokumentacija projekta
devops/ – konfiguracija i alati za pokretanje i održavanje projekta
3. Osnovna Git pravila
Glavna grana projekta je main.
Direktne izmene na grani main nisu dozvoljene.
Svaki član treba da napravi posebnu granu za svoj zadatak.
Izmene se šalju putem Pull Request-a (PR).
Svaki Pull Request mora da pregleda najmanje jedan drugi član tima.
U main se spajaju samo pregledane i odobrene izmene.
4. Kako započeti rad

Preuzimanje repozitorijuma:

git clone URL_REPOZITORIJUMA
cd IME_REPOZITORIJUMA


Pre početka rada preuzmi najnovije izmene:

git checkout main
git pull origin main


Napravi novu granu za svoj zadatak:

git checkout -b feature/opis-zadatka

5. Čuvanje i slanje izmena

Proveri koje su datoteke promenjene:

git status


Dodaj izmene i napravi commit:

git add .
git commit -m "Opis napravljenih izmena"


Pošalji granu na GitHub:

git push -u origin feature/opis-zadatka

6. Pull Request (PR)
Otvori repozitorijum na GitHub-u.
Izaberi opciju za kreiranje Pull Request-a.
Kao ciljnu granu izaberi main.
Ukratko opiši šta je promenjeno.
Pozovi člana tima da pregleda izmene.
Nakon odobrenja spoji PR u main.
7. Pravila za commit poruke

Commit poruke treba da budu kratke i jasne.

Primeri:

Add login page
Fix database connection
Update project documentation
Add initial backend structure
8. Važne napomene
Ne šaljite lozinke, API ključeve ili druge tajne podatke na GitHub.
Ne menjajte tuđe izmene bez dogovora.
Redovno preuzimajte najnovije izmene sa grane main.
Pre slanja Pull Request-a proverite da li vaš kod radi.
Ako dođe do konflikta, rešite ga pre spajanja grana.
9. Cilj tima

Cilj je da svih 8 članova uspešno sarađuje preko GitHub-a, da svaka izmena bude pregledana i da glavna grana main ostane stabilna.
