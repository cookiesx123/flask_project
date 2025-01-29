# Stronka - blog z kotkami
### Z użyciem Flaska - w ramach projektu na przemiot "Python w praktyce - web & deep learning"
### Autorzy:
- Jagoda Radomska
- Wiktor Trzaskowski - [@VicT0000R](https://github.com/VicT0000R)
- Szymon Urbala - [@urbull](https://github.com/urbull)
## O projekcie:
Prosta strona internetowa stworzona z użyciem frameworka Flask. Jest to blog o kotkach, na którym użytkownicy mogą tworzyć konta, logować się, dodawać posty oraz je przeglądać.

## Funkcjonalności:
1. Rejestracja użytkownika (zakładanie nowego konta)
2. Logowanie i wylogowywanie
3. Tworzenie i wyświetlanie postów

## Strukrtura projektu:
|Plik/Folder| Opis|
|:----------|:----|
|📁 .venv/ |Środowisko wirtualne projektu|
|📁 db/ |Baza danych SQLite obsługiwana przez SQLAlchemy|
|📁 functions/ |Dodatkowe funkcje pomocnicze|
|📁 instance/ |Przechowywanie tabeli users z bazy danych|
|📁 static/ |Pliki statyczne (style CSS, przesłane zdjęcia, grafiki)|
|📁 templates/ |Pliki HTML (base.html, login.html, register.html itp.)|
|📄 app.py |Główny plik aplikacji Flask|
|📄 requirements.txt |Lista wymaganych pakietów do uruchomienia aplikacji|


## Jak uruchomić projekt:
1. Sklonuj repozytorium:

git clone https://github.com/cookiesx123/flask_project.git

cd flask_project

2. Utwórz i aktywuj wirtualne środowisko:

python -m venv .venv

source .venv/bin/activate  # Dla macOS/Linux

.venv\Scripts\activate     # Dla Windows

3. Zainstaluj wymagane rozszerzenia:

pip install -r requirements.txt

4. Uruchom aplikację:

python app.py

5. Otwórz w przeglądarce:

Strona będzie dostępna pod adresem:

http://127.0.0.1:5000/
