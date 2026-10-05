# Moje wykonanie Lab00

- Login GitHub / pseudonim: JerzT / M_Sz / Marcin_Szablak
- System i terminal (np. Windows + WSL Ubuntu): Qubes os / debian 13 as qube / fedora 42 as qube
- Edytor / IDE: CLion / mousepad (check xfce txt editor)
- Wersja Git: 2.47.3
- Wersja kompilatora C++: 14.2.0
- Wersje java i javac: 17.0.20.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/JerzT/oop-lab00-M_S/pull/1

## Uruchomienie lokalne
Wynik programu C++:
```
Hello from C++! M_SZ sdfadsf
```
Wynik programu Java:
```
Hello from Java! M_Sz
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: 

cpp/main.cpp: In function ‘int main()’:
cpp/main.cpp:5:56: error: expected ‘;’ before ‘return’
    5 |     std::cout << "Hello from C++! M_SZ sdfadsf" << '\n'
      |                                                        ^
      |                                                        ;
    6 |     return 0;
      |     ~~~~~~                                              
Error: Process completed with exit code 1.

- Przyczyna oraz sposób naprawy: No semicolon on end of the line. 
Fix: ending line with semicolon
- Commit z błędem (SHA lub link): https://github.com/JerzT/oop-lab00-M_S/commit/16ad9df50d734186d230537f3f690428f02a28e2
- Czy Actions pokazały błąd, a po naprawie sukces? Tak

## Krótkie odpowiedzi
1. Co różni commit od push?
Commit is saving on local device on which commit was made,
push send all the changed to location of remote (could be local or in the cloude).
2. Dlaczego po scaleniu PR wykonuję lokalnie pull?
To be 100% sure that we have everythink up to date on or local machine
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? 
green result indicates us that: 
code was properly build up,
 autotests go without error.
But from that we don't know:
if in program are bugs,
program is working properly,
code is secured,
if it will work on other devices without error.

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: brak
