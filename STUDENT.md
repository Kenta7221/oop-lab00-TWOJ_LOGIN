# Moje wykonanie Lab00

- Login GitHub / pseudonim: Antoni
- System i terminal (np. Windows + WSL Ubuntu): Ubuntu
- Edytor / IDE: Emacs
- Wersja Git: 2.43.0
- Wersja kompilatora C++: 13.3.0
- Wersje java i javac: 17.0.20.1 i 17.0.20.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): 

## Uruchomienie lokalne
Wynik programu C++:
```text
Hello from C++, Antoni!
...
```
Wynik programu Java:
```text
Hello from Java, Antoni!
...
```



## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: 
  cpp/main.cpp: In function ‘int main()’:
  cpp/main.cpp:5:51: error: expected ‘;’ before ‘return’
5 |     std::cout << "Hello from C++, Antoni!" << '\n'
|                                                   ^
|                                                   ;
        6 |     return 0;
|     ~~~~~~                                         
    Error: Process completed with exit code 1.
- Przyczyna oraz sposób naprawy: Brak średnika
- Commit z błędem (SHA lub link): https://github.com/Kenta7221/oop-lab00-TWOJ_LOGIN/pull/2
- Czy Actions pokazały błąd, a po naprawie sukces? Tak

## Krótkie odpowiedzi
1. Co różni commit od push? Commit zapisuje lokalne zmiany, a push wysyła commity do repozytorium
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Scalenie PR odbywa się tylko ze strony repozytorium i trzeba zrobić pull aby ją zsynchronizować
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Ci tylko potwierdza, że dany kod da się skompilować. Nie potwierdza jednak, jakości kodu, czy działa w różnych środowiskach.

## Ewentualne problemy środowiska
Brak
