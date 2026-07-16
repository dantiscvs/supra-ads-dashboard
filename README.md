# Supra Ads Dashboard — publikacja na GitHub Pages

Ten folder zawiera gotowy, samodzielny plik `index.html` (dashboard z hasłem,
zakładkami Dent/Med, statusem wdrożenia i planem restrukturyzacji konta
Google Ads dla supradent.pl).

Hasło do dashboardu: **supra2026** (to jest tylko prosta blokada po stronie
przeglądarki — plik HTML jest publiczny, więc nie traktuj tego jak
prawdziwego zabezpieczenia danych wrażliwych).

## Jak opublikować na GitHub Pages

1. Utwórz nowe repozytorium na GitHubie (np. `supra-ads-dashboard`) — może
   być publiczne lub prywatne (Pages działa w obu, ale w prywatnym repo
   Pages wymaga planu GitHub Pro/Team/Enterprise).
2. Wrzuć do niego plik `index.html` z tego folderu (na root repozytorium).
3. W ustawieniach repo: **Settings → Pages**.
4. W sekcji "Build and deployment" wybierz **Source: Deploy from a branch**,
   branch: `main` (lub `master`), folder: `/ (root)`.
5. Zapisz — GitHub Pages pokaże URL w stylu
   `https://<twoja-nazwa-uzytkownika>.github.io/supra-ads-dashboard/`
   (może zająć do minuty, zanim strona się pojawi).
6. Wyślij ten link webmasterowi razem z hasłem.

## Aktualizacje

Gdy dashboard trzeba będzie zaktualizować (np. po nowym snapshocie Quality
Score albo zmianach w planie), wystarczy podmienić `index.html` w
repozytorium (nowy commit/push) — Pages przebuduje się automatycznie.
