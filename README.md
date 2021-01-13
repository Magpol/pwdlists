# pwdlists
Misc useful passwordlists

Ex:

hashcat --stdout -a 1 swehack.txt 4digits_year_1950-2020.txt > word_numbers.txt
hashcat --stdout -a 1 swehack.txt 6digits_year_1970-2020.txt| ./hashcat -a 0 -m TYPE HASH -r rule_smallset.txt
hashcat -a 0 -m TYPE HASH name_numbers_4-8.txt -r rule_smallset.txt
