File Calculator.java-LOC(107 code lines)
Calculator.java – 8-23 – Klasa `Operations` se nalazi unutar klase `Calculator` Ova struktura nije potrebna i može se izbegavati.
Calculator.java – 12 – Konstante `ADDITION_SYMBOL`, `SUBTRACTION_SYMBOL`, `MULTIPLICATION_SYMBOL` i `DIVISION_SYMBOL` se deklarišu kao `static final`, što je u redu, ali mogu biti deklarisane direktno unutar glavne klase `Calculator`, umesto unutar unutrašnje statičke klase `Operations`.
Calculator.java – 14-17 – Metoda `ToString()` u unutrašnjoj klasi `Operations` je napisana s malim slovima, što nije u skladu s konvencijom imenovanja u Javi. Trebalo bi koristiti  `toString()`.
Calculator.java – 26 – Metoda `Run()` nema potrebu da bude `static`. Trebalo bi razmotriti da li je potrebno da bude `static` ili ne, u zavisnosti od toga kako se koristi u aplikaciji.
Calculator.java – 34-47 – U metodi `evaluateExpression()` postoji kompleksna logika za parsiranje izraza. Ova logika može biti nepregledna i teška za održavanje. Razmotrite izdvajanje dela logike u manje metode radi poboljšanja čitljivosti i održavanja.
Calculator.java – 49-107 – Metoda `Calculate()` sadrži dugačku i složenu logiku koja izvršava operacije nad brojevima. Ova metoda može biti nepregledna i teška za održavanje. Razmotrite razbijanje ove metode na manje metode radi poboljšanja čitljivosti i održavanja.

