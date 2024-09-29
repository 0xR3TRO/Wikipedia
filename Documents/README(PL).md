## Opis projektu

### Cel:

Projekt "Wikipedia Mini" ma na celu dostarczenie użytkownikom uproszczonej wersji popularnego serwisu do wyszukiwania informacji. Aplikacja umożliwia przeglądanie i edytowanie treści encyklopedycznych, dzięki czemu użytkownicy mogą uzyskać szybki dostęp do podstawowych informacji na interesujące ich tematy.

### Opis funkcji:

- **Wyszukiwanie artykułów:** Użytkownicy mogą wyszukiwać informacje poprzez wpisanie fraz w pasek wyszukiwania.
- **Przeglądanie artykułów:** Dostęp do różnych kategorii i artykułów związanych z tematami nauki, kultury, historii itp.
- **Edycja treści:** Możliwość edycji treści artykułów, aby użytkownicy mogli dodawać lub modyfikować informacje.
- **Historia edycji:** Przegląd i zarządzanie historią edycji artykułów, aby zapewnić transparentność i wiarygodność danych.

## Analiza wymagań:

### Wymagania funkcjonalne:

- **Wyszukiwanie artykułów:** Użytkownik może wyszukiwać tematy poprzez wpisanie słów kluczowych.
- **Przeglądanie kategorii:** Użytkownik ma dostęp do różnych kategorii artykułów, aby łatwiej nawigować po serwisie.
- **Edycja treści artykułów:** Użytkownicy mogą edytować istniejące artykuły, z zachowaniem historii zmian.
- **Historia edycji:** Możliwość przeglądania wcześniejszych wersji artykułów i cofania zmian.

### Wymagania niefunkcjonalne:

- **Szybkość działania:** System powinien być responsywny, z natychmiastowym dostępem do wyszukiwanych treści.
- **Skalowalność:** Aplikacja musi być skalowalna, aby obsłużyć rosnącą liczbę użytkowników i artykułów.
- **Interfejs użytkownika:** Przejrzysty i intuicyjny interfejs, z prostą nawigacją między artykułami i kategoriami.

## Projekt interfejsu:

### Szkice/wizualizacje interfejsu:

- _Strona główna:_ Pasek wyszukiwania, lista popularnych kategorii oraz wyróżnione artykuły.
- _Strona artykułu:_ Zawiera treść artykułu, opcję edycji oraz sekcję "Historia edycji".
- _Strona edycji:_ Formularz do modyfikacji artykułu z podglądem zmian.

### Mapa strony:

- _Strona główna_
  - Pasek wyszukiwania
  - Lista kategorii
- _Strona artykułu_
  - Treść artykułu
  - Opcja edycji
  - Historia edycji
- _Strona edycji_
  - Formularz edycji artykułu
  - Podgląd zmian

## Architektura systemu:

### Opis struktury danych:

Aplikacja przechowuje dane związane z artykułami, w tym:

- **Artykuły:** Zawiera informacje o treści, kategorii oraz historii zmian.
- **Historia edycji:** Dane dotyczące wcześniejszych wersji artykułów, w tym kto i kiedy dokonał zmian.

### Diagramy architektury:

Architektura systemu opiera się na podejściu Model-Widok-Kontroler (MVC):

- **Model:** Odpowiada za logikę przechowywania danych i ich przetwarzanie.
- **Widok (View):** Prezentuje treści encyklopedyczne użytkownikom.
- **Kontroler (Controller):** Obsługuje interakcje użytkownika, takie jak wyszukiwanie i edycja artykułów.

## Implementacja:

### Opis technologii:

- **Frontend:** HTML, CSS, JavaScript (React.js) dla interfejsu użytkownika.
- **Backend:** Django (Python) jako framework obsługujący logikę serwera.
- **Baza danych:** PostgreSQL do przechowywania artykułów, użytkowników i historii edycji.

### Struktura kodu:

- _Katalogi/pliki:_ Oddzielne pliki dla widoków, logiki edycji, oraz zarządzania bazą danych.
- _Style pisania kodu:_ Używanie wzorców modularności, czytelności kodu oraz dokładnych komentarzy.

## Testowanie:

### Plan testów:

- **Testy jednostkowe:** Sprawdzenie poprawności wyszukiwania, edycji artykułów oraz innych podstawowych funkcji.
- **Testy integracyjne:** Weryfikacja współpracy komponentów frontendowych i backendowych.
- **Testy interfejsu użytkownika:** Testy związane z interakcją użytkowników na różnych urządzeniach.
- **Testy wydajnościowe:** Ocena szybkości działania aplikacji, szczególnie w kontekście wyszukiwania i przeglądania artykułów.

### Procedury testowania:

- Opracowanie przypadków testowych dla każdej funkcji aplikacji.
- Zgłaszanie i dokumentowanie błędów, wraz z procedurami ich naprawy.

## Wdrożenie i konserwacja:

### Plan wdrożenia:

- **Etapy wdrażania:** Testowanie beta, poprawki błędów, publikacja na platformach dla użytkowników.
- **Terminy:** Określenie terminów wdrożenia poszczególnych etapów rozwoju.

### Procedury konserwacji:

- **Wsparcie techniczne:** Utworzenie kanału kontaktu dla użytkowników zgłaszających problemy.
- **Aktualizacje:** Regularne aktualizacje na podstawie zgłoszeń użytkowników i pojawiających się potrzeb.

## Harmonogram:

---

### Plan projektu:

- **Etapy realizacji:** Podział projektu na fazy, takie jak implementacja wyszukiwania, tworzenie stron artykułów, testowanie.
- **Terminy:** Przewidywany czas realizacji dla każdego z etapów.

## Kosztorys:

### Szacunkowe koszty:

- **Rozwój aplikacji:** Koszt oparty na ilości godzin pracy zespołu programistycznego.
- **Koszty utrzymania:** Koszty serwerów, bazy danych, aktualizacje, oraz wsparcie techniczne dla użytkowników.
