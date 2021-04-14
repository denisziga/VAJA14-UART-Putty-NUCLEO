# VAJA14-UART-Putty-NUCLEO
c) Privzeto je UART2 vmesnik povezan na USB priključek razvojne ploščice. Katere dva mostička bi morali odspajkati in kateri dve povezavi pospajkati, da bi lahko uporabili pina Tx/D1 in Rx/D0? odspajkati SB13 in SB14, prispajkati SB62 in SB63.

e) V področju Connectivity aktivirajte protokol USART2 kot asinhroni. Katera dva pina sta se pobarvala zeleno oz. se aktivirala? PA2 in PA3.

f) V polju Configuration izbranega serijskega vmesnika pustimo privzeto hitrost, ki znaša 115200 Bit/s.

IDE:

e) Za to funkcijo zapišite ukaz za vklop/izklop zelene LED (pomagajte si z metodo toggle, glej vaja0a). HAL_GPIO_TogglePin(GPIOA,GPIO_PIN_5);

f) Dodajte še ukaz za zakasnitev s funkcijo Delay iz knjižnice HAL, in sicer 2 sekunde (glej vaja0a): HAL_Delay(2000);.

Komentar: NALOGE NISMA USPELA NAREDITI, SAJ NAM NI ŽELELO NALOŽITI NA NUCLEO. 
