Vaja 1 posamična ADC pretvorba

1. Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to?

PIN PC0.

2. V Pinout zavihku ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica?

Razvojna ploščica ima 1 pretvornik.

3. Izbrani ADC pretvornik ima oznako s trikotnikom. Kaj to pomeni?

Pretvornik ima oznako s trikotnikom, ker je delno v konfliktu z drugim pinom.

4. Kaj morate storiti, da razrešite to omejitev? Opišite in jo odpravite.

Izbrani pin (PIN PC0) nastavimo na Analog ADC_IN10 in izberemo pretvornik IN10. Ostale oine, ki jih ne bomo uporabljali pa nastavimo na reset_state.

5. Razširite razdelek ADC. Koliko je vseh vhodnih kanalov?

Razvojna plošča ima 16 pretvornikov (IN0 - IN15).

6. Glede na potenciometer na vaši ploščici  izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora ustrezno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina?

Poleg pina se izpiše ADC_IN10.

7. V configuration kliknemo ADC gumb. V parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0÷255. Kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?

a) 8 bit, od 0 do 255
b) 10 bit, od 0 do 1024
c) 12 bit od 0 do 4096

Komentar:
Razvojna ploščica deluje tako, da pošilja podatke stanja potenciometra preko ADC pina v spremenljivko, ki se nato izpiše v programu STM studio z zakasnitvijo 100ms.

Domen Zidar in Tim Tušek
