Projekat ima ukupno 212 linija koda.
Napisan je Java jezikom, sastoji se od 2 fajla: Calculator.java i Start.java.
Calculator.java ima jednu unutrasnju klasu koja cuva znakove za racunavanje (+, -, *, /).
Projekat sluzi da racuna matematicke izraze, racunavanje se radi korak po korak, po pravilima matematike. 
Kod je pregledan i lako se moze razumeti. 
Start.java – linija 6 – promenljiva 'Expression' počinje velikim slovom (nije u skladu sa Java konvencijama)
Start.java – linija 7 – naziv promenljive 'active' nije dovoljno opisno ime
Start.java – linija 8 – System.out.println poruka u originalnoj verziji nije bila pravilno zatvorena navodnicima
Start.java – linija 9 – promenljiva 'scanIn' je deklarisana bez inicijalizacije
Start.java – linija 11 – Scanner se kreira unutar petlje, što nije preporučljivo
Start.java – linija 13 – poređenje stringa koristi equals, ali nema provere null vrednosti
Start.java – linija 14 – Scanner se zatvara unutar petlje, što može izazvati grešku
Start.java – linija 17 – metoda Calculator.Run se poziva bez validacije korisničkog unosa
Calculator.java – linija 1 – nedostaje JavaDoc komentar za klasu
Calculator.java – linija 3 – promenljiva finalResult je statička i globalna, što nije dobra praksa
Calculator.java – linija 5 – ugnježdena klasa Operations mogla bi biti izdvojena u poseban fajl
Calculator.java – linija 9 – konstante su dobro imenovane, što je pozitivno
Calculator.java – linija 16 – metoda ToString ne prati Java konvenciju imenovanja (treba toString)
Calculator.java – linija 16 – sastavljanje stringa je nepregledno
Calculator.java – linija 25 – nema provere neispravnih operatora
Calculator.java – linija 40 – nema obrade greške za deljenje nulom
Calculator.java – linija 55 – metoda Run ima previše odgovornosti (parse + računanje)
Calculator.java – linija 60 – nema komentara koji objašnjavaju logiku
