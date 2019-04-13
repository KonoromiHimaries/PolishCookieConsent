# Polska Ciasteczkowa Zgoda

Rozszerzenie automatycznie akceptujące politykę ciasteczek/RODO na stronach dostępnych w języku polskim. Stanowi ono uzupełnienie **Polskich Filtrów Rodo-Ciasteczkowych**.

[![GitHub Releases](https://img.shields.io/github/downloads/PolishFiltersTeam/PolishCookieConsent/latest/total.svg)](https://github.com/PolishFiltersTeam/PolishCookieConsent/releases/latest)

[![GitHub All Releases](https://img.shields.io/github/downloads/PolishFiltersTeam/PolishCookieConsent/total.svg?colorB=blue)](https://github.com/PolishFiltersTeam/PolishCookieConsent/releases)


## **Jak zainstalować?**
### **I. ![Firefox][Firefox]Firefox/![Waterfox][Waterfox]Waterfox**
1. Pobierz najnowszą wersję rozszerzenia z [AMO](https://addons.mozilla.org/pl/firefox/addon/polish-cookie-consent/) i kliknij **dodaj**, by zainstalować.
2. Gotowe!

### **II. ![Chrome][Chrome]Chrome/![Chromium][Chromium]Chromium/![Vivaldi][Vivaldi]Vivaldi/![Opera][Opera](Chr)Opera/![Cent][Cent]Cent /![Yandex][Yandex]Yandex**
#### a) ![Windows][Windows] Windows
1. Pobierz najnowszego Konserwatora Polskiej Ciasteczkowej Zgody z [github.com/PolishFiltersTeam/PolishCookieConsentMaintenance/releases/download/v1.3/PolishCookieConsentMaintenance.win64.exe](https://github.com/PolishFiltersTeam/PolishCookieConsentMaintenance/releases/download/v1.3/PolishCookieConsentMaintenance.win64.exe) i uruchom instalator.
2. Po zakończeniu instalacji uruchom Konserwatora.
3. Wybierz ścieżkę, gdzie chcesz zainstalować rozszerzenie i kliknij **pobierz i wypakuj**.
4. Otwórz swoją przeglądarkę, a następnie wpisz do paska adresu `chrome://extensions` i potwierdź <kbd>Enterem</kbd>.
5. Włącz tryb programisty.
6. Kliknij **załaduj rozpakowane**, potem wskaż katalog, w którym wypakowałeś(aś) rozszerzenie i kliknij **OK**.
7. Wyłącz tryb programisty.
8. Gotowe! Aktualizacje powinny być automatycznie instalowane co tydzień.

#### b) ![Linux][Linux] Linux
1. Pobierz najnowszego Konserwatora Polskiej Ciasteczkowej Zgody z [github.com/PolishFiltersTeam/PolishCookieConsentMaintenance/releases/download/v1.3/PolishCookieConsentMaintenance.linux-x86_64.xz.run](https://github.com/PolishFiltersTeam/PolishCookieConsentMaintenance/releases/download/v1.3/PolishCookieConsentMaintenance.linux-x86_64.xz.run), zrób ten plik wykonywalnym i uruchom go w terminalu z ścieżki, w której chcesz mieć Konserwatora (zostanie tam utworzony katalog **PolishCookieConsentMaintenance**).
2. Jeśli chcesz przewinąć licencję do końca, naciśnij <kbd>q</kbd>, a jesli chcesz dalej przeczytać, to wciśnij <kbd>Enter</kbd>, a następnie <kbd>y</kbd>, by zaakceptować licencję.
3. Wciśnij <kbd>1</kbd>, jesli chcesz mieć automatyczne cotygodniowe aktualizacje. Jednakże aby to działało poprawnie, cron powinien być zainstalowany i włączony (np. w Manjaro Linux należy zainstalować pakiet **cronie**, a następnie wpisać do konsoli `systemctl enable --now cronie.service` i wykonać punkty 2-3 z [forum.manjaro.org/t/how-to-create-a-cron-job-in-manjaro/105](https://forum.manjaro.org/t/how-to-create-a-cron-job-in-manjaro/105)).
4. Po zakończeniu instalacji uruchom Konserwatora.
5. Wybierz ścieżkę, gdzie chcesz zainstalować rozszerzenie i kliknij **pobierz i wypakuj**.
6. Otwórz swoją przeglądarkę, a następnie wpisz do paska adresu `chrome://extensions` i potwierdź <kbd>Enterem</kbd>.
7. Włącz tryb programisty.
8. Kliknij **załaduj rozpakowane**, potem wskaż katalog, w którym wypakowałeś(aś) rozszerzenie i kliknij **OK**.
9. Wyłącz tryb programisty.
10. Gotowe!

#### c) Inne systemy
1. Pobierz najnowszy plik zip z [github.com/PolishFiltersTeam/PolishCookieConsent/releases/latest](https://github.com/PolishFiltersTeam/PolishCookieConsent/releases/latest).
2. Utwórz nowy katalog **Rozszerzenia**, a w nim katalog **PolishCookieConsent**.
3. Wypakuj archiwum zip do katalogu **PolishCookieConsent**.
4. Wpisz do paska adresu `chrome://extensions` i potwierdź <kbd>Enterem</kbd>.
5. Włącz tryb programisty.
6. Kliknij **załaduj rozpakowane**, potem wskaż katalog, w którym wypakowałeś(aś) rozszerzenie i kliknij **OK**.
7. Gotowe!

**Uwaga! W tym przypadku niestety aktualizacje muszą być przeprowadzane ręcznie (pobierz, wypakuj, nadpisz pliki i zrestartuj przeglądarkę).**


[Firefox]: https://cdnjs.cloudflare.com/ajax/libs/browser-logos/46.1.0/firefox/firefox_24x24.png "Mozilla Firefox"
[Waterfox]: https://cdnjs.cloudflare.com/ajax/libs/browser-logos/46.1.0/waterfox/waterfox_24x24.png "Waterfox"
[Chrome]: https://cdnjs.cloudflare.com/ajax/libs/browser-logos/46.1.0/chrome/chrome_24x24.png "Google Chrome"
[Chromium]: https://cdnjs.cloudflare.com/ajax/libs/browser-logos/46.1.0/chromium/chromium_24x24.png "Chromium"
[Vivaldi]: https://cdnjs.cloudflare.com/ajax/libs/browser-logos/46.1.0/vivaldi/vivaldi_24x24.png "Vivaldi"
[Opera]: https://cdnjs.cloudflare.com/ajax/libs/browser-logos/46.1.0/opera/opera_24x24.png "Opera"
[Cent]: https://cdnjs.cloudflare.com/ajax/libs/browser-logos/46.1.0/cent/cent_24x24.png "Cent Browser"
[Yandex]: https://cdnjs.cloudflare.com/ajax/libs/browser-logos/46.1.0/yandex/yandex_24x24.png "Yandex Browser"
[Windows]: https://img.icons8.com/color/24/000000/windows8.png "Windows"
[Linux]: https://img.icons8.com/color/24/000000/linux.png "Linux"

## **Podziękowania**

Polska Ciasteczkowa Zgoda korzysta z otwartoźródłowego kodu następujących projektów (wg. kolejności alfabetycznej):

* [erosman/HTML-Internationalization](https://github.com/erosman/HTML-Internationalization)

* [primer/octicons](https://github.com/primer/octicons/)


Natomiast paczka ikon systemów operacyjnych została stworzona przez [Icons8](https://icons8.com/).
