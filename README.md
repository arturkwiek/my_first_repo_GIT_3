# my_first_repo_GIT_3 — podstawy Gita

Ćwiczenie z systemu kontroli wersji: praca z gałęziami i **rozwiązywanie konfliktów
scalania**. Repozytorium jest samo w sobie zapisem przebiegu ćwiczenia — commity i konflikty
są tu treścią, nie efektem ubocznym.

- Repozytorium: `my_first_repo_GIT`
- Autor: Artur Kwiek, nr albumu 5216

## Zawartość

| Plik | Etap ćwiczenia |
|---|---|
| `GIT_1_idea.txt` | Założenie repozytorium i pierwszy commit |
| `GIT_2_version.txt` | Wersjonowanie zmian |
| `GIT_4_restore.txt` | Przywracanie wcześniejszego stanu |
| `GIT_4_status1.txt`, `…status2.txt`, `…status3.txt` | Kolejne odczyty `git status` — ilustracja, jak zmienia się stan drzewa roboczego |
| `.github/` | Workflow GitHub Actions (super-linter) |

## Sens ćwiczenia

Trzy pliki `GIT_4_status*.txt` pokazują ten sam mechanizm w trzech momentach: plik
nieśledzony → dodany do poczekalni → zacommitowany. To najprostszy sposób, żeby zobaczyć
różnicę między **working tree**, **index** i **HEAD** — trzema stanami, wokół których kręci
się cała reszta Gita.

Oryginalna treść README zawierała zdanie *„Tym wpisem chcemy spowodować konflikt"* —
było ono częścią ćwiczenia ze scalania, celowo wprowadzającą sprzeczną zmianę.
Przebieg konfliktu został w historii commitów.

## Status

⚪ **Zamknięty** — ćwiczenie zaliczone, ostatni commit październik 2025. Jedyny przedmiot
w `PJWSTK`, który był podpięty jako submoduł od początku; reszta doszła w sierpniu 2026.
