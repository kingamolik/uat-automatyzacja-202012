# Pesel

Projekt został wygenerowany przy użyciu [Angular CLI](https://github.com/angular/angular-cli).

## Warunki wstępne do uruchomienia aplikacji
- Zainstaluj [NodeJS](https://nodejs.org/en/)
- Zainstaluj Angualar CLI `npm install -g @angular/cli`

## Lokalny serwer developerski
Wykonaj `npm install` aby zainstalować potrzebne biblioteki
Wykonaj `ng serve` aby uruchomić aplikację lokalną.
Otwórz `http://localhost:4200/`. Aplikacja automatycznie się odświeży po zmianie plików.
Możesz też wykonać komendę `ng serve --open` aby aplikacja otworzyła się automatycznie w oknie przeglądarki

## Build

Komenda `ng build` buduje projekt. Artefakty build'u przechowywane są w `dist/`. Flaga `--prod` powinna być wykorzystana aby wykonać build produkcyjny.

## Uruchomienie lintera

Uruchom `ng lint` aby uruchomić linter TypeScriptu [TSLint](https://palantir.github.io/tslint/)

## Uruchomienie testów jednostkowych

Uruchom `ng test` aby wykonać testy jednostkowe z wykorzystaniem [Karma](https://karma-runner.github.io).
Kod testów jednostkowych znajduje się w `/src/app/app.component.spec.ts`.

## Uruchomienie testów end-to-end

Uruchom `ng e2e` aby wykonać testy end to end z wykorzystaniem [Protractor](http://www.protractortest.org/).
Kod testów e2e znajduje się w `/e2e/src/app.e2e-spec.ts`

## Zadanie 1 - setup
- [ ] Stwórz forka repozytorium
- [ ] Sklonuj sforkowane repozytorium (pracujemy na swoich repozytoriach)
- [ ] Uruchom aplikację lokalnie

## Zadanie 2 - naprawa testów
- [ ] Uruchom linter
- [ ] Napraw wszystkie błędy lintera (plik `/src/app/app.component.ts` )
- [ ] Uruchom testy jednostkowe
- [ ] Napraw testy jednostkowe
- [ ] Uruchom testy End-to-End
- [ ] Napraw test End-to-End

## Zadanie 3 - rozszerzenie unit testów
- [ ] Uruchom testy jednostkowe z flagą --code-coverage
- [ ] Zweryfikuj raport html pokrycia kodu w pliku .coverage\pesel\index.html
dopisz przypadki testowe, które zwiększa pokrycie - zignoruj przypadki dla funkcji onSubmit()

## Mail do prowadzącego
- [ ] Wyślij mail na adres bruno.manczak@gmail.com
- [ ] W mailu podaj link do swojego repozytorium
- [ ] W mailu wyślij screenshot z konsoli pokazującej, że linter nie wykrywa żadnych błędów
- [ ] W mailu wyślij screenshot z konsoli pokazującej, że testy jednostkowe przeszły
- [ ] W mailu wyślij screenshot z konsoli pokazującej, że testy e2e przeszły