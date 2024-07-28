# "Uber Eats"

---

1. Zapoznaj się ze strukturą HTML w `index.html`.

2. Ostylizuj `body > header`:
   -> ustaw obramowanie dolne na 1px solid
   -> ustaw, aby dziecko tego elementu zostało wyśrodkowane na osi głównej

3. Ostylizuj `body > header > div`:
   -> ustaw za pomocą właściwości `flex`, aby element na osi głównej:
   a) nie mógł się rozciągać,
   b) mógł się kurczyć,
   c) jego domyślny rozmiar wynosił `700px`
   -> ustaw, aby jego dzieci zostały wyśrodkowane na osi poprzecznej
   -> ustaw, aby odstęp między jego dziećmi wynosił `40px`
   -> ustaw marginesy wewnętrzne góra-dół na `12px` i lewo-prawo na `40px`
   -> ustaw, aby na rozmiar całkowity pudełka nie wpływał border i padding (`box-sizing`).

4. Ostylizuj `.text-field`:
   -> ustaw wysokość elementu na `48px`
   -> ustaw zaokrąglenie brzegów na `48px`
   -> ustaw tło na `#eeeeee`
   -> ustaw marginesy wewnętrzne góra dół na `0`, lewo-prawo na `16px`
   -> ustaw za pomocą właściwości `flex-grow`, aby element mógł się rozciągać.
   -> ustaw, aby dzieci elementu były wyśrodkowane na osi poprzecznej.
   -> ustaw, aby odstęp między jego dziećmi wynosił `8px`.

5. Ostylizuj `.text-field > input`:
   -> ustaw za pomocą właściwości `flex-grow`, aby element mógł się rozciągać.
   -> ustaw tło na przezroczyste (`transparent`).
   -> usuń obramowanie (`none`).

6. Kliknij na inputa. Powinieneś zauważyć, ze powstaje obramowanie. Ostylizuj `.text-field > input:focus`
   -> ustaw `outline` na `none`

7. Ostylizuj `.text-field:has(input:focus)`
   -> ustaw `outline` na `1px solid rgb(215, 215, 215)`.

8. Ponownie kliknij na inputa, aby zobaczyc zmiany. W punkcie 8. poznaliśmy nowy selektor `:has()`, w tym przypadku pozwala nam ostylizować rodzica (`.text-field`), pod warunkiem, że ma w środku inputa z pseudo-klasą `:focus`.

---

Rozwiązanie: https://stackblitz.com/edit/ts-si-s02-e01-cw2-solved
