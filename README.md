# SI_2022_lab2_163081

Камелија Ангелова 163081

Control Flow Graph

https://prnt.sc/AR-3gQmDy0wH
(бројките во јазлите се според бројот на линиите на кодот)

Цикломатска комплексност

Цикломатската комплексност на овој код е 9, истата ја добив преку формулата P+1, каде што P е бројот на предикатни јазли. Во случајoв P=8, па цикломатската комплексност изнесува 9. (Истото може да се добие со броење на регионите или број на рабови(31) - број на јазли(24) + 2 = 9)

Тест случаи според критериумот Every statement

https://prnt.sc/dhSY3XgAjvmk
Во првиот тест случај влегува во првиот Exception, вториот случај влегува во вториот Exception, и третиот случај влегува во циклусот и ги задоволува сите услови/statements. Минимален број за Every statement e 3.

Тест случаи според критериумот Every Branch

https://prnt.sc/dG93GP0PFR8m
Овде се искористени истите тест случаеви, и ги задоволуваат сите исходи на јазлите на одлука.

Објаснување на напишаните unit tests

Една функција за 2-та случаеви

За да се тестира првиот тест случај е искористено assertThrows каде што прима празна листа.
За да се тестира вториот тест случај е искористено исто така assertThrows каде што прима функцијата која што ја прима листата со 2 елемента.
За да се тестира третиот случај е искористено assertEquals кој што за прв аргумент прима очекувана листа а за втор прима функцијата која што ја прима листата со 9 елементи.
