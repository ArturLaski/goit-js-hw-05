# goit-js-hw-05

## Struktura projektu
Projekt składa się z następujących plików i folderów:
- `/js`
  - `task-1.js` - Rozwiązanie zadania 1: User Names
  - `task-2.js` - Rozwiązanie zadania 2: Users with Friend
  - `task-3.js` - Rozwiązanie zadania 3: Sorting by Number of Friends
  - `task-4.js` - Rozwiązanie zadania 4: Total Balance by Gender
- `.gitignore` - Plik ignorujący niepotrzebne pliki w repozytorium
- `.prettierrc` - Plik konfiguracyjny dla Prettier
- `index.html` - Strona główna projektu, wyświetlająca wyniki zadań w przeglądarce
- `README.md` - Dokumentacja projektu

## Opis zadań

### Task 1: User Names
Celem tego zadania jest stworzenie funkcji `getUserNames(users)`, która zwraca tablicę z nazwami użytkowników z obiektu `users`. Wyniki są wyświetlane w sekcji "Task 1 Results" w pliku `index.html`.

### Task 2: Users with Friend
Zadanie polega na stworzeniu funkcji `getUsersWithFriend(users, friendName)`, która zwraca tablicę użytkowników, którzy mają przyjaciela o danej nazwie. Wyniki są wyświetlane w sekcji "Task 2 Results" w pliku `index.html`.

### Task 3: Sorting by Number of Friends
Zadanie polega na stworzeniu funkcji `sortByDescendingFriendCount(users)`, która sortuje użytkowników malejąco według liczby ich przyjaciół. Wyniki są wyświetlane w sekcji "Task 3 Results" w pliku `index.html`.

### Task 4: Total Balance by Gender
Zadanie polega na stworzeniu funkcji `getTotalBalanceByGender(users, gender)`, która oblicza łączny bilans dla użytkowników o określonej płci. Wyniki są wyświetlane w sekcji "Task 4 Results" w pliku `index.html`.

## Wymagania
- Kod musi być sformatowany za pomocą Prettier.
- Nie mogą występować żadne błędy ani ostrzeżenia w konsoli po uruchomieniu zadań.
- Taski 1, 2, 3 i 4 muszą zostać wykonane i poprawnie wyświetlać wyniki w odpowiednich sekcjach strony `index.html`.

## Wyświetlanie wyników
Wyniki zadań są automatycznie wyświetlane w przeglądarce w odpowiednich sekcjach pliku `index.html`:
- Wyniki zadania 1 są wyświetlane w sekcji `#task-1-results`.
- Wyniki zadania 2 są wyświetlane w sekcji `#task-2-results`.
- Wyniki zadania 3 są wyświetlane w sekcji `#task-3-results`.
- Wyniki zadania 4 są wyświetlane w sekcji `#task-4-results`.

## Sformatowanie kodu za pomocą Prettier:

* Aby użyć Prettier, musisz zainstalować go w swoim projekcie. Można to zrobić, jeśli masz zainstalowany Node.js, za pomocą polecenia:
  
```bash
npm install --save-dev prettier
```

* Następnie możesz uruchomić Prettier na swoim kodzie za pomocą:

```bash
npx prettier --write .
```

To polecenie sformatuje wszystkie pliki w projekcie.
