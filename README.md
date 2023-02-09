# TestiranjeProjektFerit
Projekt je napravljen pomoću JMetera za testiranje performansi po uzoru na LV5. Testirana je demo stranica: https://www.demoblaze.com/index.html
Uz JMeter je tekođer korišten i BlazeMeter za snimanje kako bi bilo moguće testirati i Sign Up, Log in i dodavanje proizvoda u košaricu. 
Test je proveden za 10, 50 i 100 korisnika, a nakon toga je generiran izvještaj koji prikazuje da je broj errora vrlo mali, najviše 3.32% kod 100 korisnika.
Korišten je View Result Tree Listener i rezultati su spremani u .csv datoteku iz koje je kasnije generiran izvještaj. Korišten je još i Graph Results Listener koji čiji rezultati su također prikazani. 
