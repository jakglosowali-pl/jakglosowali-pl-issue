# 🗳️ JakGłosowali.pl — Zgłaszanie błędów / Issue Tracker

> **Publiczne miejsce do zgłaszania błędów, sugestii i problemów z platformą [jakglosowali.pl](https://jakglosowali.pl)**

---

## 📌 Czym jest to repozytorium?

To repozytorium służy **wyłącznie do zgłaszania błędów i sugestii** dotyczących platformy JakGłosowali.pl.  
Kod źródłowy aplikacji nie jest tutaj publikowany.

JakGłosowali.pl to obywatelska platforma umożliwiająca porównanie własnych preferencji z **rzeczywistymi głosowaniami posłów Sejmu RP** — dane pochodzą bezpośrednio z `api.sejm.pl`, nie z deklaracji partii.

---

## 🐛 Jak zgłosić błąd?

### 1. Sprawdź czy błąd nie był już zgłoszony

Przed dodaniem nowego zgłoszenia przeszukaj [istniejące Issues](../../issues) — być może ktoś już to zgłosił.

### 2. Otwórz nowe zgłoszenie

Kliknij **[New Issue](../../issues/new/choose)** i wybierz odpowiedni szablon:

| Szablon | Kiedy użyć |
|---|---|
| 🐛 **Błąd / Bug** | Coś nie działa tak jak powinno |
| 💡 **Sugestia / Feature Request** | Masz pomysł na nową funkcję |
| 📊 **Problem z danymi** | Dane głosowań wyglądają niepoprawnie |
| ❓ **Pytanie / Question** | Chcesz zapytać jak coś działa |

### 3. Wypełnij szablon dokładnie

Im więcej informacji podasz, tym szybciej możemy pomóc. Patrz sekcja poniżej.

---

## 📋 Co powinno zawierać dobre zgłoszenie błędu?

```
Tytuł: Krótki, konkretny opis problemu
Przykład: "Strona posła X nie ładuje głosowań z posiedzenia 12"
```

**Wymagane informacje:**

- **Opis błędu** — co się dzieje, a co powinno się dziać
- **Kroki do odtworzenia** — jak krok po kroku wywołać błąd
- **Oczekiwane zachowanie** — co powinno się stać
- **Zrzuty ekranu** — jeśli to możliwe, bardzo ułatwiają diagnozę
- **Środowisko** — przeglądarka (Chrome/Firefox/Safari), urządzenie (komputer/telefon), system operacyjny

**Opcjonalnie:**

- Logi z konsoli przeglądarki (F12 → Console)
- Adres URL strony, na której wystąpił błąd

---

## 🏷️ Etykiety / Labels

Zgłoszenia są kategoryzowane etykietami:

| Etykieta | Znaczenie |
|---|---|
| `bug` | Potwierdzony błąd w działaniu |
| `enhancement` | Sugestia nowej funkcji |
| `data-issue` | Problem z danymi głosowań |
| `ui` | Problem z interfejsem użytkownika |
| `performance` | Problem z wydajnością / ładowaniem |
| `duplicate` | Zgłoszenie już istnieje |
| `wontfix` | Znane ograniczenie, nie będzie naprawiane |
| `in-progress` | Trwa naprawa |
| `fixed` | Naprawione, czeka na wdrożenie |

---

## ⏱️ Czas reakcji

To projekt prowadzony przez jedną osobę. Staram się odpowiadać na zgłoszenia w ciągu **3–7 dni roboczych**.

Zgłoszenia dotyczące **błędów krytycznych** (brak dostępu do serwisu, błędne dane głosowań) są traktowane priorytetowo.

---

## 🚫 Czego tu nie zgłaszać

- **Błędów bezpieczeństwa** — skontaktuj się prywatnie: [bartosz@jakglosowali.pl] zamiast tworzyć publiczne Issue
- **Pytań o dane z API Sejmu** — to zewnętrzne API, problemy z nim zgłaszaj na [api.sejm.gov.pl](https://api.sejm.gov.pl)
- **Spamu i treści politycznych** — to narzędzie neutralne, nie forum debaty politycznej

---

## 📬 Kontakt

- **E-mail:** bartosz@jakglosowali.pl  
- **LinkedIn:** [JakGlosowaliPL](https://www.linkedin.com/company/jakglosowalipl)  
- **Strona:** [jakglosowali.pl](https://jakglosowali.pl)

---

## 🔒 Prywatność

Zgłaszając Issue, nie podawaj danych osobowych innych osób ani wrażliwych danych swojego konta. Jeśli błąd dotyczy Twoich prywatnych danych — napisz na adres e-mail zamiast tworzyć publiczne zgłoszenie.

---

## 📄 O projekcie

JakGłosowali.pl to niezależna, apolityczna platforma obywatelska.  
Dane głosowań pochodzą wyłącznie z oficjalnego API Sejmu RP (`api.sejm.pl`).  
Projekt powstał jako praca inżynierska w Warszawskiej Wyższej Szkole Informatyki (WWSI, 2026).

> *„Po owocach ich poznacie"* — Mt 7:20

---

*Dziękujemy za każde zgłoszenie — pomagasz budować lepsze narzędzie dla świadomej demokracji* 🇵🇱
