# lgbtpl
Lista do dodatku foxreplace, która ukrywa twój deadname oraz obraźliwe dla mniejszości słowa. Zasada jest prosta - jeżeli nie chcesz to nie używaj, poradnik jest kierowany tylko do osób, które widocznie tego potrzebują i chcą.


Jak zacząć korzystać? 

1. Zainstaluj dodatek foxreplace (https://addons.mozilla.org/pl/firefox/addon/foxreplace/). Powinien być dostępny również na innych przeglądarkach (opartych na chromium) nie ręczę jednak za nie, szczególnie mając na uwadze wprowadzany w nich manifest v3, który uniemożliwi blokowanie reklam.
2. Kliknij prawym przyciskiem myszy na ikonę nowo zainstalowanego dodatku, wybierz zarządzaj rozszerzeniem.
3. W wyświetlonych informacjach o dodatku wybierz "..." a następnie "Preferencje".
4. Pod "Periodically update from URL" zaznacz opję enable.
![skryptmoj](https://user-images.githubusercontent.com/112720004/206889469-a1c82b5c-146f-4f2e-bc88-73ee95df8e15.png)
5. W pole URL wklej link: https://raw.githubusercontent.com/unicornsandcandies/lgbtpl/main/lista.json
6. Możesz ustalić Period, czyli czas co jaki lista obraźliwych słów ma się aktualizować (mogę dodać nowe słowo), niech będzie to przykładowo 30 minut.
7. Zaznacz opcję "Apply automatic substitutions on page load", bez niej żadne ze słów nie zmieni się automatycznie.
8. Reszta opcji jest dowolna, jeżeli obawiasz się o obrażliwe słowa na stronie, której zawartość regularnie się zmienia (np pokazywane są nowe komentarze bez konieczności odświeżania strony), mozesz zaznaczyć opcję "Apply automatic substitutions every" i z pola obok wybrać liczbę sekund. Dodatek będzie wtedy regularnie co określony przez ciebie czas od nowa szukał obraźliwych słów na stronie i je zamieniał. Opcja z poprzedniego punktu zapewnia szukanie i zamianę słów tylko przy ładowaniu strony. Nowe słowa nie będą zauważane dopóki strona nie zostanie odświeżona.
