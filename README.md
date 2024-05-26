Assignment 1.
LOC (Calculator.java) = 134
LOC (Start.java) = 19
LOC (Total) = 153

calculator.java - 34 - expression = 0 + expression; // Problem: Ovo dodavanje nule može poremetiti rezultat, ako nije unesen matematički ispravan izraz. 
calculator.java - 46 - operationList.add(String.valueOf(expression.charAt(i))); // Problem: Operacije se dodaju u listu bez provjere, može doći do neočekivanog ponašanja.
calculator.java - 62 - numberList.add(Float.parseFloat(numbers[i])); // Problem: Nema provjere ispravnosti unosa, može doći do grešaka prilikom parsiranja.
calculator.java - 64 - return "ERROR"; // Problem: Ovdje bi trebalo biti konkretnije rukovanje greškama, a ne samo vraćanje stringa "ERROR"
