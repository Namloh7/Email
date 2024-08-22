# Email
### Čus, chci abys mi udělal apku na získání co možné nejvíc informací z emailu a poté je vypsal. 
**INPUT:**: email -> ve formátu: jmeno.prijmeniCISLO@mailserver.domena. možné jsou i varianty kde . mezi jmenem a prijmenim nahradíme buď "_" nebo "-". Další možné formáty: jmeno(. nebo - nebo _ )prijmeniCISLO@mailserver.domena. CISLO může být jakkoliv dlouhé, ale pokud obsahuje 4 znaky a je větší než momentální rok -125 a zároveň menší než momentální rok - 5 (momentální rozsah je 1899 až 2019), tak se jedná o rok narození osoby... ze kterého jseš schopný zjistit i momentální věk osoby.

**OUTPUT:**  Jmeno, Prijmeni, potencionálně RokNarození a Věk, Mailserver a Domenu. To vše vypíšeš do konzole. To je celý


------------



**CO BUDEŠ POTŘEBOVAT:**  bude to primárně o práci se stringem, takže budeš potřebovat metody na čtení a úpravu stringů jako** .Split()** a .**Substring()**. A poté něco málo z DateTime classy... pravděpodobně **DateTime.Now** + nezapomínej, že samotné typy jako string a char mají taky svoje metody... stačí když zadáš **char**.A tady ti vyjede tuna metod... Ty by se mohli hodit
