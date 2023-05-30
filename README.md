•	Kreirati bazu sa tabelom Student sa poljima ime, prezime, brIndexa i ručno popuniti nekoliko Klijenata u bazu, 
•	Kreirati DAO klasu sa metodama:
o	studentExist (int id): proverava da li postoji klijent u bazi sa ovim parametrima 
o	update (int id, Student s): radi update studenta u bazi
•	Kreirati index  sa formom za prosleđivanje parametra id, ime i prezime na Controller.
•	 Kreirati Controller koji u :
o	post metodi radi update klijenta u bazi ako postoji student sa tim id-om u bazi. U slučaju uspešnog unosa prosleđuje studenta preko sesije na prikaz , u suprotnom vraća odgovarajuće poruke na index 
o	get metodi poništava sesiju i vraća korisnika na index 
•	Kreirati prikaz  prikazuje studenta ako postoji sesija, u suprotnom radi se se redirekcija na index 
