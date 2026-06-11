# Moduł 7 — Bezpieczeństwo

MFA, zarządzanie uprawnieniami i ochrona danych w Microsoft Teams.

## Uwierzytelnianie wieloskładnikowe (MFA)

MFA wymaga potwierdzenia tożsamości dwoma metodami: hasłem i kodem z aplikacji Microsoft Authenticator lub SMS-em.

1. **Zainstaluj Microsoft Authenticator** — dostępny na iOS i Android, skanuje kody QR przy rejestracji.
2. **Zarejestruj konto** — przejdź na `aka.ms/mfasetup` i postępuj zgodnie z instrukcją.
3. **Loguj się z potwierdzeniem** — przy każdym nowym logowaniu aplikacja wyświetli prośbę o zatwierdzenie.

## Zarządzanie uprawnieniami

=== "Role w zespole"

    - Właściciel — pełna kontrola
    - Członek — edytowanie i komunikacja
    - Gość — ograniczony dostęp

=== "Uprawnienia do plików"

    - Tylko do odczytu
    - Edycja z powiadomieniami
    - Pełna kontrola

## Ochrona danych

**Szyfrowanie**
: Wszystkie dane w Teams są szyfrowane w tranzycie (TLS) i w spoczynku (AES-256).

**RODO**
: Microsoft Teams jest zgodny z RODO. Administratorzy mogą eksportować i usuwać dane użytkowników.

**Prywatność**
: Nie udostępniaj poufnych danych przez czat. Dla dokumentów wrażliwych używaj zaszyfrowanych kanałów prywatnych.

**Aktualizacje**
: Teams aktualizuje się automatycznie. Zawsze korzystaj z najnowszej wersji — łaty bezpieczeństwa są krytyczne.

!!! Uwaga: 
    Nigdy nie udostępniaj swojego hasła ani kodów MFA innym osobom — nawet administratorowi IT. Prawdziwy administrator nigdy o to nie poprosi.

---

⬅️ [Moduł 6 — Współpraca na plikach](modul6.md) | ➡️ [Moduł 8 — Przykładowy scenariusz](modul8.md)
