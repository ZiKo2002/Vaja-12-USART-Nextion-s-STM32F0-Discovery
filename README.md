# Vaja-12-USART-Nextion-s-STM32F0-Discovery
2.
  d) Kako je Nextion poimenoval gauge objekt (objname)? z0
  g) Gumb ima objname b0.
3. 
  b) LED diodi imata vrednost PC9 (zelena LED) in PC8 (modra LED).
  c) Aktivirana sta pina PA10 (Rx) in PA9 (Tx). Kako? Utemeljite: Tx pin Nextiona se poveže z Rx STM32 in obratno.
  d) Kateri kanal morate izbrati? ADC_IN10
4. 
  e) V zgornjih vrsticah smo aktivirali ADC pretvorbo – katera vrsta pretvorba je to? enkratna ADC pretvorba
     ASCII znak  Binarno (dvojiško) Hexadecimalno (šestnajstiško)	Decimalno (desetiško)
         0           00110000                    30                        48
         1           00110001                    31                        49
         2           00110010                    32                        50
         3           00110011                    33                        51
         4           00110100                    34                        52
         5           00110101                    35                        53
         6           00110110                    36                        54
         7           00110111                    37                        55  
         8           00111000                    38                        56  
         9           00111001                    39                        57
     Kaj pa pomeni 3x zapis 0xff? To je so trije polni byti 3 * 11111111
     Kakšen ASCII znak prejme Nextion? ÿÿÿ
     
KOMENTAR:
Z zaslonom nextion upravljamo Zeleno LED na STM, ta pa upravlja gauge na Nextionu. Uporabljen komunikacijski protokol je USART.
     

